# Ch02 - Force Vectors

> Engineering Mechanics: Statics, 14th Edition (SI Units)

## Chapter Objectives

- To show how to add forces and resolve them into components using the Parallelogram Law.
- To express force and position in Cartesian vector form and explain how to determine the vector's magnitude and direction.
- To introduce the dot product in order to use it to find the angle between two vectors or the projection of one vector onto another.

## Chapter Outline

2.1 Scalars and Vectors
2.2 Vector Operations
2.3 Vector Addition of Forces
2.4 Addition of a System of Coplanar Forces
2.5 Cartesian Vectors
2.6 Addition of Cartesian Vectors
2.7 Position Vectors
2.8 Force Vector Directed along a Line
2.9 Dot Product

---

## 2.1 Scalars and Vectors

### Scalar

Any positive or negative physical quantity that can be completely specified by its magnitude.

- Example: Length, Mass, Time

### Vector

Described by:

- **Magnitude** — e.g., 4 units
- **Direction** — e.g., 20° measured counterclockwise from the horizontal axis
- **Sense** — e.g., upward and to the right

The point O is called the **tail** of the vector and the point P is called the **tip** or **head**.

---

## 2.2 Vector Operations

### Multiplication and Division of a Vector by a Scalar

- If a vector is multiplied by a **positive** scalar, its magnitude is increased by that amount.
- Multiplying by a **negative** scalar will also change the directional sense of the vector.

### Vector Addition

**Parallelogram Law:**

$$\mathbf{R} = \mathbf{A} + \mathbf{B}$$

**Triangle Rule:**

Special case: Vectors A and B are collinear (both have the same line of action).

$$\mathbf{R} = \mathbf{A} + \mathbf{B} = \mathbf{B} + \mathbf{A}$$

### Vector Subtraction

A special case of addition:

$$\mathbf{R'} = \mathbf{A} - \mathbf{B} = \mathbf{A} + (-\mathbf{B})$$

Rules of vector addition apply.

---

## 2.3 Vector Addition of Forces

### Finding a Resultant Force

$$\mathbf{F_R} = \mathbf{F_1} + \mathbf{F_2}$$

### Finding the Components of a Force

Resolve a force into two components.

### Addition of Several Forces

If more than two forces are added, successive applications of the parallelogram law is carried out to find the resultant force.

Example: Forces $\mathbf{F_1}$, $\mathbf{F_2}$, and $\mathbf{F_3}$ act at a point O:

1. Find resultant $\mathbf{F_1} + \mathbf{F_2}$
2. Find resultant $\mathbf{F_R} = (\mathbf{F_1} + \mathbf{F_2}) + \mathbf{F_3}$

### Procedure for Analysis

1. Draw a sketch of the problem
2. Establish coordinate system
3. Resolve forces into components
4. Apply parallelogram law or triangle rule
5. Solve for unknowns using trigonometry

---

## 2.4 Addition of a System of Coplanar Forces

### Rectangular Components

When a force is resolved into two components along the x and y axes:

- **Scalar notation**: $F = F_x + F_y$
- **Cartesian vector notation**: $\mathbf{F} = F_x \mathbf{i} + F_y \mathbf{j}$

### Scalar Notation

Using a right triangle with sides $a$, $b$, $c$:

$$F_x = F \cos\theta, \quad F_y = F \sin\theta$$

The y component is a negative scalar if $\mathbf{F_y}$ is directed along the negative y axis.

### Notation Conventions

- **Head** of a vector arrow = sense of the vector graphically (algebraic signs not used)
- **Vectors** are designated using **boldface** notations
- **Magnitudes** (always a positive quantity) are designated using *italic* symbols

### Cartesian Vector Notation

Unit vectors $\mathbf{i}$ and $\mathbf{j}$ have dimensionless magnitude of unity (= 1) and designate the x and y directions (positive quantity).

$$\mathbf{F} = F_x \mathbf{i} + F_y \mathbf{j}$$

### Coplanar Force Resultants

**Step 1:** Resolve each force into its components.

**Step 2:** Add all the x-components together, followed by adding all the y-components together. These two totals are the x and y components of the resultant vector.

**Step 3:** Find the magnitude and angle of the resultant vector.

$$\mathbf{F_R} = \mathbf{F_1} + \mathbf{F_2} + \mathbf{F_3}$$

$$= (F_{1x} - F_{2x} + F_{3x})\mathbf{i} + (F_{1y} + F_{2y} - F_{3y})\mathbf{j}$$

$$= (F_{Rx})\mathbf{i} + (F_{Ry})\mathbf{j}$$

In all cases:

$$(F_R)_x = \sum F_x, \quad (F_R)_y = \sum F_y$$

You can also represent a 2-D vector with a magnitude and angle:

$$F_R = \sqrt{(F_R)_x^2 + (F_R)_y^2}$$

$$\theta = \tan^{-1}\left|\frac{(F_R)_y}{(F_R)_x}\right|$$

---

## 2.5 Cartesian Vectors

### Right-Handed Coordinate System

The x, y, z axes follow the right-hand rule.

### Rectangular Components of a Vector

By two successive applications of the parallelogram law:

$$\mathbf{A} = \mathbf{A'} + \mathbf{A_z}$$

$$\mathbf{A'} = \mathbf{A_x} + \mathbf{A_y}$$

Combining: $\mathbf{A} = \mathbf{A_x} + \mathbf{A_y} + \mathbf{A_z}$

### Cartesian Unit Vectors

The set of Cartesian unit vectors $\mathbf{i, j, k}$: the directions of the x, y, z axes (positive/negative).

### Cartesian Vector Representation

$$\mathbf{A} = A_x \mathbf{i} + A_y \mathbf{j} + A_z \mathbf{k}$$

### Magnitude of a Cartesian Vector

$$A = \sqrt{A_x^2 + A_y^2 + A_z^2}$$

### Coordinate Direction Angles

The direction or orientation of vector $\mathbf{A}$ is defined by the angles $\alpha$, $\beta$, and $\gamma$ — measured between the vector and the positive x, y, z axes respectively. Range: 0° to 180°.

**Direction cosines of A:**

$$\cos\alpha = \frac{A_x}{A}, \quad \cos\beta = \frac{A_y}{A}, \quad \cos\gamma = \frac{A_z}{A}$$

**Unit vector form:**

$$\mathbf{u_A} = \frac{\mathbf{A}}{A} = \frac{A_x}{A}\mathbf{i} + \frac{A_y}{A}\mathbf{j} + \frac{A_z}{A}\mathbf{k}$$

$$\mathbf{u_A} = \cos\alpha\,\mathbf{i} + \cos\beta\,\mathbf{j} + \cos\gamma\,\mathbf{k}$$

Since magnitude of $\mathbf{u_A} = 1$:

$$\cos^2\alpha + \cos^2\beta + \cos^2\gamma = 1$$

**A in Cartesian vector form:**

$$\mathbf{A} = A\,\mathbf{u_A} = A\cos\alpha\,\mathbf{i} + A\cos\beta\,\mathbf{j} + A\cos\gamma\,\mathbf{k}$$

### Transverse and Azimuth Angles

$$A_z = A\cos\phi, \quad A' = A\sin\phi$$

$$A_x = A'\cos\theta = A\sin\phi\cos\theta, \quad A_y = A'\sin\theta = A\sin\phi\sin\theta$$

Cartesian vector $\mathbf{A}$:

$$\mathbf{A} = A\cos\phi\,\mathbf{k} + A\sin\phi\cos\theta\,\mathbf{i} + A\sin\phi\sin\theta\,\mathbf{j}$$

---

## 2.6 Addition of Cartesian Vectors

Given:

$$\mathbf{A} = A_x\mathbf{i} + A_y\mathbf{j} + A_z\mathbf{k}$$

$$\mathbf{B} = B_x\mathbf{i} + B_y\mathbf{j} + B_z\mathbf{k}$$

**Vector Addition:**

$$\mathbf{R} = \mathbf{A} + \mathbf{B} = (A_x + B_x)\mathbf{i} + (A_y + B_y)\mathbf{j} + (A_z + B_z)\mathbf{k}$$

For several concurrent force systems:

$$\mathbf{F_R} = \sum \mathbf{F}$$

---

## 2.7 Position Vectors

### x, y, z Coordinates

Each point in space can be located by its coordinates (x, y, z).

### Position Vector

Position vector $\mathbf{r}$ is defined as a fixed vector which locates a point in space relative to another point.

$$\mathbf{r} = x\,\mathbf{i} + y\,\mathbf{j} + z\,\mathbf{k}$$

### Position Vector from A to B

Vector addition gives $\mathbf{r_A} + \mathbf{r} = \mathbf{r_B}$, therefore:

$$\mathbf{r} = \mathbf{r_B} - \mathbf{r_A}$$

$$\mathbf{r} = (x_B - x_A)\mathbf{i} + (y_B - y_A)\mathbf{j} + (z_B - z_A)\mathbf{k}$$

---

## 2.8 Force Vector Directed along a Line

In 3D problems, the direction of $\mathbf{F}$ is specified by 2 points through which its line of action passes. $\mathbf{F}$ can be formulated as a Cartesian vector.

$$\mathbf{F} = F\,\mathbf{u} = F\frac{\mathbf{r}}{r}$$

$$= \frac{F}{\sqrt{(x_B - x_A)^2 + (y_B - y_A)^2 + (z_B - z_A)^2}} \left[(x_B - x_A)\mathbf{i} + (y_B - y_A)\mathbf{j} + (z_B - z_A)\mathbf{k}\right]$$

$\mathbf{F}$ has units of forces, unlike $\mathbf{r}$ which has units of length.

---

## 2.9 Dot Product

The dot product of vectors $\mathbf{A}$ and $\mathbf{B}$ is written as $\mathbf{A} \cdot \mathbf{B}$ (read "A dot B").

$$\mathbf{A} \cdot \mathbf{B} = AB\cos\theta$$

where $0° \leq \theta \leq 180°$.

Referred to as the **scalar product** of vectors as the result is a scalar and not a vector.

### Laws of Operation

1. **Commutative law:** $\mathbf{A} \cdot \mathbf{B} = \mathbf{B} \cdot \mathbf{A}$
2. **Multiplication by a scalar:** $a(\mathbf{A} \cdot \mathbf{B}) = (a\mathbf{A}) \cdot \mathbf{B} = \mathbf{A} \cdot (a\mathbf{B})$
3. **Distributive law:** $\mathbf{A} \cdot (\mathbf{B} + \mathbf{D}) = (\mathbf{A} \cdot \mathbf{B}) + (\mathbf{A} \cdot \mathbf{D})$

### Cartesian Vector Formulation

$$\mathbf{i} \cdot \mathbf{i} = 1, \quad \mathbf{i} \cdot \mathbf{j} = 0, \quad \text{etc.}$$

$$\mathbf{A} \cdot \mathbf{B} = A_x B_x + A_y B_y + A_z B_z$$

### Applications

**1. Angle between two vectors:**

$$\theta = \cos^{-1}\left(\frac{\mathbf{A} \cdot \mathbf{B}}{AB}\right), \quad 0° \leq \theta \leq 180°$$

> If $\mathbf{A} \cdot \mathbf{B} = 0$, then $\theta = 90°$ — A is perpendicular to B.

**2. Components of a vector parallel and perpendicular to a line:**

Component of $\mathbf{A}$ parallel or collinear with line $aa$ (projection of $\mathbf{A}$ onto the line):

$$A_a = A\cos\theta = \mathbf{A} \cdot \mathbf{u_a}$$

Expressed as a vector:

$$\mathbf{A_a} = A_a\,\mathbf{u_a} = (\mathbf{A} \cdot \mathbf{u_a})\mathbf{u_a}$$

- If $A_a$ is positive → same sense as $\mathbf{u_a}$
- If $A_a$ is negative → opposite sense to $\mathbf{u_a}$

**Component perpendicular to line $aa$:**

$$\mathbf{A_\perp} = \mathbf{A} - \mathbf{A_a}$$

Or by Pythagorean theorem:

$$A_\perp = \sqrt{A^2 - A_a^2}$$

---

*Source: [ch02 Force Vectors(modified).pdf](../course-materials/ch02%20Force%20Vectors(modified).pdf)*
