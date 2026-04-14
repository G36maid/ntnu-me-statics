# Ch04 - Force System Resultants

> Engineering Mechanics: Statics, 14th Edition (SI Units)

**Section Boundaries (Slide Index):**

| Section | Start Slide |
|---------|-------------|
| Cover / Objectives / Outline | 001 -- 004 |
| 4.1 Moment of a Force -- Scalar Formulation | 005 |
| 4.2 Cross Product | 018 |
| 4.3 Moment of a Force -- Vector Formulation | 027 |
| 4.4 Principle of Moments | 038 |
| 4.5 Moment of a Force about a Specified Axis | 046 |
| 4.6 Moment of a Couple | 058 |
| 4.7 Simplification of a Force and Couple System | 076 |
| 4.8 Further Simplification of a Force and Couple System | 094 |
| 4.9 Reduction of a Simple Distributed Loading | 114 |

**Example Locations (Slide Index):**

| Example | Slides |
|---------|--------|
| Ex 4.1 | 013 -- 014 |
| Ex 4.2 | 015 |
| Ex 4.3 | 034 -- 035 |
| Ex 4.4 | 036 -- 037 |
| Ex 4.5 | 041 -- 042 |
| Ex 4.6 | 043 -- 045 |
| Ex 4.7 | 053 |
| Ex 4.8 | 054 -- 055 |
| Ex 4.9 | 056 -- 057 |
| Ex 4.10 | 067 |
| Ex 4.11 | 068 -- 070 |
| Ex 4.12 | 071 -- 073 |
| Ex 4.13 | 074 -- 075 |
| Ex 4.14 | 086 -- 088 |
| Ex 4.15 | 089 -- 091 |
| Ex 4.16 | 092 -- 093 |
| Ex 4.17 | 104 -- 106 |
| Ex 4.18 | 107 -- 108 |
| Ex 4.19 | 109 -- 110 |
| Ex 4.20 | 111 -- 113 |
| Ex 4.21 | 120 -- 122 |
| Ex 4.22 | 123 -- 124 |
| Ex 4.23 | 125 -- 126 |

---

![ch04N-Force-System-Resultants Slide 001](assets/ch04N-Force-System-Resultants/slide-001.png)

---

## Chapter Objectives

![ch04N-Force-System-Resultants Slide 002](assets/ch04N-Force-System-Resultants/slide-002.png)

- To discuss the concept of the moment of a force and show how to calculate it in two and three dimensions.
- To provide a method for finding the moment of a force about a specified axis.
- To define the moment of a couple.
- To show how to find the resultant effect of a nonconcurrent force system.
- To indicate how to reduce a simple distributed loading to a resultant force acting at a specified location.

## Chapter Outline

![ch04N-Force-System-Resultants Slide 003](assets/ch04N-Force-System-Resultants/slide-003.png)

4.1 Moment of a Force -- Scalar Formulation
4.2 Cross Product
4.3 Moment of a Force -- Vector Formulation
4.4 Principle of Moments
4.5 Moment of a Force about a Specified Axis

![ch04N-Force-System-Resultants Slide 004](assets/ch04N-Force-System-Resultants/slide-004.png)

4.6 Moment of a Couple
4.7 Simplification of a Force and Couple System
4.8 Further Simplification of a Force and Couple System
4.9 Reduction of a Simple Distributed Loading

---

## 4.1 Moment of a Force -- Scalar Formulation

![ch04N-Force-System-Resultants Slide 005](assets/ch04N-Force-System-Resultants/slide-005.png)

The tendency to rotate is called the **moment of a force** (or simply the **moment**, sometimes called a **torque**).

![ch04N-Force-System-Resultants Slide 006](assets/ch04N-Force-System-Resultants/slide-006.png)

The magnitude of the moment is directly proportional to:
- The magnitude of $F$
- The perpendicular distance (**moment arm**) $d$

$$\boxed{M_O = Fd}$$

The larger the force or the longer the moment arm, the greater the moment or turning effect.

![ch04N-Force-System-Resultants Slide 007](assets/ch04N-Force-System-Resultants/slide-007.png)

- If $\theta = 90^\circ$: $d' = d\sin\theta$ which is smaller than $d$, making it harder to turn.

![ch04N-Force-System-Resultants Slide 008](assets/ch04N-Force-System-Resultants/slide-008.png)

- If the force passes through point $O$: no turning can occur.

### General Case

![ch04N-Force-System-Resultants Slide 009](assets/ch04N-Force-System-Resultants/slide-009.png)

- Consider the force $F$ and the point $O$ which lies in the shaded plane.
- The moment $M_O$ about point $O$, or about an axis passing through $O$ and perpendicular to the plane, is a vector quantity.
- Moment $M_O$ has its specified magnitude and direction.

### Magnitude and Direction

![ch04N-Force-System-Resultants Slide 010](assets/ch04N-Force-System-Resultants/slide-010.png)

**Magnitude:**
- $d$ = the moment arm or perpendicular distance
- Units: N$\cdot$m

**Direction:**
- Defined by its moment axis, which is perpendicular to the plane containing force $F$ and its moment arm $d$

![ch04N-Force-System-Resultants Slide 011](assets/ch04N-Force-System-Resultants/slide-011.png)

- Determined by the **right-hand rule**

### Resultant Moment

![ch04N-Force-System-Resultants Slide 012](assets/ch04N-Force-System-Resultants/slide-012.png)

$$\circlearrowleft + \;(M_R)_O = \Sigma\,Fd$$

Resultant moment $(M_R)_O$ = the algebraic sum of the moments caused by all the forces.

- **Positive** moments: counterclockwise (out of the page)
- **Negative** moments: clockwise (into the page)

### Example 4.1

![ch04N-Force-System-Resultants Slide 013](assets/ch04N-Force-System-Resultants/slide-013.png)

For each case illustrated in Fig. 4-4, determine the moment of the force about point $O$.

The line of action of each force is extended as a dashed line to establish the moment arm $d$. The tendency of rotation is shown, and the orbit of the force about $O$ is indicated.

$$(M_R)_O = F_1 d_1 - F_2 d_2 + F_3 d_3$$

**Results for each case (Fig. 4-4a--e):**

| Case | Force | Moment Arm $d$ | Moment $M_O$ |
|------|-------|-----------------|---------------|
| (a) | $100 \text{ N}$ | $2 \text{ m}$ | $M_O = 200 \text{ N}\cdot\text{m} \circlearrowright$ |
| (b) | $50 \text{ N}$ | $0.75 \text{ m}$ | $M_O = 37.5 \text{ N}\cdot\text{m} \circlearrowright$ |
| (c) | $400 \text{ N}$ | $4 \text{ m} + 2\cos 30^\circ \text{ m}$ | $M_O = 2292.8 \text{ N}\cdot\text{m} \circlearrowright$ |
| (d) | $600 \text{ N}$ | $1\sin 45^\circ \text{ m}$ | $M_O = 424.3 \text{ N}\cdot\text{m} \circlearrowleft$ |
| (e) | $7 \text{ kN}$ | $4 \text{ m} - 1 \text{ m} = 3 \text{ m}$ | $M_O = 21.0 \text{ kN}\cdot\text{m} \circlearrowleft$ |

![ch04N-Force-System-Resultants Slide 014](assets/ch04N-Force-System-Resultants/slide-014.png)

### Example 4.2

![ch04N-Force-System-Resultants Slide 015](assets/ch04N-Force-System-Resultants/slide-015.png)

Determine the resultant moment of the four forces acting on the rod shown in Fig. 4-5 about point $O$.

**Given forces:** $F_1 = 50 \text{ N}$ (downward), $F_2 = 60 \text{ N}$ (horizontal), $F_3 = 20 \text{ N}$ (horizontal), $F_4 = 40 \text{ N}$ (downward).

Assuming counterclockwise moments as positive:

$$\circlearrowleft + (M_R)_O = \Sigma Fd$$

$$\begin{aligned}
(M_R)_O &= -50(2) + 60(0) + 20(3\sin 30^\circ) - 40(4 + 3\cos 30^\circ) \\
&= -334 \text{ N}\cdot\text{m}
\end{aligned}$$

$$(M_R)_O = 334 \text{ N}\cdot\text{m} \circlearrowright$$

![ch04N-Force-System-Resultants Slide 016](assets/ch04N-Force-System-Resultants/slide-016.png)

![ch04N-Force-System-Resultants Slide 017](assets/ch04N-Force-System-Resultants/slide-017.png)

---

## 4.2 Cross Product

![ch04N-Force-System-Resultants Slide 018](assets/ch04N-Force-System-Resultants/slide-018.png)

![ch04N-Force-System-Resultants Slide 019](assets/ch04N-Force-System-Resultants/slide-019.png)

![ch04N-Force-System-Resultants Slide 020](assets/ch04N-Force-System-Resultants/slide-020.png)

$$\mathbf{C} = \mathbf{A} \times \mathbf{B}$$

(read as "C equals A cross B")

### Magnitude and Direction

![ch04N-Force-System-Resultants Slide 021](assets/ch04N-Force-System-Resultants/slide-021.png)

$$C = AB\sin\theta$$

**Direction:** Right-hand rule -- curling the fingers from $\mathbf{A}$ to $\mathbf{B}$, the thumb points in the direction of $\mathbf{C}$.

$$\mathbf{C} = (AB\sin\theta)\,\mathbf{u_C}$$

where $\mathbf{u_C}$ is the unit vector in the direction of $\mathbf{C}$.

### Laws of Operations

![ch04N-Force-System-Resultants Slide 022](assets/ch04N-Force-System-Resultants/slide-022.png)

1. **Commutative law is NOT valid:**

$$\mathbf{A} \times \mathbf{B} \neq \mathbf{B} \times \mathbf{A}$$

Rather: $\mathbf{A} \times \mathbf{B} = -\mathbf{B} \times \mathbf{A}$

The cross product $\mathbf{A} \times \mathbf{B}$ yields a vector opposite in direction to $\mathbf{B} \times \mathbf{A}$, i.e., $\mathbf{B} \times \mathbf{A} = -\mathbf{C}$.

![ch04N-Force-System-Resultants Slide 023](assets/ch04N-Force-System-Resultants/slide-023.png)

2. **Multiplied by a scalar (associative law):**

$$a(\mathbf{A} \times \mathbf{B}) = (a\mathbf{A}) \times \mathbf{B} = \mathbf{A} \times (a\mathbf{B})$$

3. **Distributive law:**

$$\mathbf{A} \times (\mathbf{B} + \mathbf{D}) = (\mathbf{A} \times \mathbf{B}) + (\mathbf{A} \times \mathbf{D})$$

> Proper order of the cross product must be maintained, since cross products are not commutative.

### Cartesian Vector Formulation

![ch04N-Force-System-Resultants Slide 024](assets/ch04N-Force-System-Resultants/slide-024.png)

Using $C = AB\sin\theta$ on pairs of Cartesian unit vectors. For example:

$$\mathbf{i} \times \mathbf{j} = (1)(1)(\sin 90^\circ)\,\mathbf{k} = (1)(1)(1)\,\mathbf{k} = \mathbf{k}$$

![ch04N-Force-System-Resultants Slide 025](assets/ch04N-Force-System-Resultants/slide-025.png)

| Product | Result |
|---------|--------|
| $\mathbf{i} \times \mathbf{i}$ | $\mathbf{0}$ |
| $\mathbf{i} \times \mathbf{j}$ | $\mathbf{k}$ |
| $\mathbf{i} \times \mathbf{k}$ | $-\mathbf{j}$ |
| $\mathbf{j} \times \mathbf{j}$ | $\mathbf{0}$ |
| $\mathbf{j} \times \mathbf{k}$ | $\mathbf{i}$ |
| $\mathbf{j} \times \mathbf{i}$ | $-\mathbf{k}$ |
| $\mathbf{k} \times \mathbf{i}$ | $\mathbf{j}$ |
| $\mathbf{k} \times \mathbf{j}$ | $-\mathbf{i}$ |
| $\mathbf{k} \times \mathbf{k}$ | $\mathbf{0}$ |

> Use the circle: crossing counterclockwise yields positive, clockwise yields negative.

![ch04N-Force-System-Resultants Slide 026](assets/ch04N-Force-System-Resultants/slide-026.png)

**Cross product of vectors $\mathbf{A}$ and $\mathbf{B}$:**

$$\mathbf{A} \times \mathbf{B} = (A_yB_z - A_zB_y)\,\mathbf{i} - (A_xB_z - A_zB_x)\,\mathbf{j} + (A_xB_y - A_yB_x)\,\mathbf{k}$$

---

## 4.3 Moment of a Force -- Vector Formulation

![ch04N-Force-System-Resultants Slide 027](assets/ch04N-Force-System-Resultants/slide-027.png)

**Determinant form:**

$$\mathbf{A} \times \mathbf{B} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ A_x & A_y & A_z \\ B_x & B_y & B_z \end{vmatrix}$$

![ch04N-Force-System-Resultants Slide 028](assets/ch04N-Force-System-Resultants/slide-028.png)

**Expanding the determinant:**

- For element $\mathbf{i}$: $\mathbf{i}(A_yB_z - A_zB_y)$
- For element $\mathbf{j}$: $-\mathbf{j}(A_xB_z - A_zB_x)$ -- remember the negative sign
- For element $\mathbf{k}$: $\mathbf{k}(A_xB_y - A_yB_x)$

![ch04N-Force-System-Resultants Slide 029](assets/ch04N-Force-System-Resultants/slide-029.png)

Moment of force $\mathbf{F}$ about point $O$ can be expressed using the cross product:

$$\boxed{\mathbf{M_O} = \mathbf{r} \times \mathbf{F}}$$

where $\mathbf{r}$ represents a position vector from $O$ to any point on the line of action of $\mathbf{F}$.

### Magnitude

![ch04N-Force-System-Resultants Slide 030](assets/ch04N-Force-System-Resultants/slide-030.png)

$$M_O = rF\sin\theta$$

where $\theta$ is the angle measured between tails of $\mathbf{r}$ and $\mathbf{F}$.

Since $d = r\sin\theta$:

$$M_O = rF\sin\theta = F(r\sin\theta) = Fd$$

### Direction

![ch04N-Force-System-Resultants Slide 031](assets/ch04N-Force-System-Resultants/slide-031.png)

Direction and sense of $\mathbf{M_O}$ are determined by the right-hand rule:
- Extend $\mathbf{r}$ to the dashed position
- Curl fingers from $\mathbf{r}$ towards $\mathbf{F}$
- Direction of $\mathbf{M_O}$ is the same as the direction of the thumb

> Maintain proper order of $\mathbf{r} \times \mathbf{F}$ since cross product is not commutative.

### Principle of Transmissibility

![ch04N-Force-System-Resultants Slide 032](assets/ch04N-Force-System-Resultants/slide-032.png)

$\mathbf{F}$ can be applied at any point along its line of action, creating the same moment about $O$. $\mathbf{F}$ can be considered a **sliding vector**.

$$\mathbf{M_O} = \mathbf{r_1} \times \mathbf{F} = \mathbf{r_2} \times \mathbf{F} = \mathbf{r_3} \times \mathbf{F}$$

### Cartesian Vector Formulation

![ch04N-Force-System-Resultants Slide 033](assets/ch04N-Force-System-Resultants/slide-033.png)

$$\mathbf{M_O} = \mathbf{r} \times \mathbf{F} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ r_x & r_y & r_z \\ F_x & F_y & F_z \end{vmatrix}$$

where $r_x, r_y, r_z$ represent the components of the position vector, and $F_x, F_y, F_z$ represent those of the force vector.

$$= (r_yF_z - r_zF_y)\,\mathbf{i} - (r_xF_z - r_zF_x)\,\mathbf{j} + (r_xF_y - r_yF_x)\,\mathbf{k}$$

Once $\mathbf{M_O}$ is determined, it is always **perpendicular** to the plane containing $\mathbf{r}$ and $\mathbf{F}$.

### Resultant Moment of a System of Forces

Resultant moment of the forces about point $O$ can be determined by vector addition of the moment of each force:

$$(\mathbf{M_R})_O = \sum (\mathbf{r} \times \mathbf{F})$$

### Example 4.3

Determine the moment produced by the force $\mathbf{F}$ about point $O$. Express the result as a Cartesian vector.

**Given:** A cable is attached to a tree at point $A(0, 0, 12)$ m and pulled by a tractor at point $B(4, 12, 0)$ m. The force along the cable has magnitude $F = 2$ kN.

![ch04N-Force-System-Resultants Slide 034](assets/ch04N-Force-System-Resultants/slide-034.png)

**Solution:** The force vector is $\mathbf{F} = F\,\mathbf{u}_{AB} = \{0.4588\mathbf{i} + 1.376\mathbf{j} - 1.376\mathbf{k}\}$ kN. Using either position vector $\mathbf{r}_A = \{12\mathbf{k}\}$ m or $\mathbf{r}_B = \{4\mathbf{i} + 12\mathbf{j}\}$ m:

$$\mathbf{M}_O = \mathbf{r}_A \times \mathbf{F} = \{-16.5\mathbf{i} + 5.51\mathbf{j}\} \text{ kN}\cdot\text{m}$$

![ch04N-Force-System-Resultants Slide 035](assets/ch04N-Force-System-Resultants/slide-035.png)

### Example 4.4

Two forces act on the rod shown in Fig. 4-15a. Determine the resultant moment they create about the flange at $O$. Express the result as a Cartesian vector.

**Given:** $\mathbf{F}_1 = \{-6\mathbf{i} + 4\mathbf{j} + 2\mathbf{k}\}$ kN applied at $A(0, 5, 0)$ m, and $\mathbf{F}_2 = \{8\mathbf{i} + 4\mathbf{j} - 3\mathbf{k}\}$ kN applied at $B(4, 5, -2)$ m.

![ch04N-Force-System-Resultants Slide 036](assets/ch04N-Force-System-Resultants/slide-036.png)

**Solution:** Using position vectors $\mathbf{r}_A = \{5\mathbf{j}\}$ m and $\mathbf{r}_B = \{4\mathbf{i} + 5\mathbf{j} - 2\mathbf{k}\}$ m:

$$(\mathbf{M_R})_O = \mathbf{r}_A \times \mathbf{F}_1 + \mathbf{r}_B \times \mathbf{F}_2 = \{3\mathbf{i} - 4\mathbf{j} + 6\mathbf{k}\} \text{ kN}\cdot\text{m}$$

![ch04N-Force-System-Resultants Slide 037](assets/ch04N-Force-System-Resultants/slide-037.png)

---

## 4.4 Principle of Moments

### Varignon's Theorem

![ch04N-Force-System-Resultants Slide 038](assets/ch04N-Force-System-Resultants/slide-038.png)

![ch04N-Force-System-Resultants Slide 039](assets/ch04N-Force-System-Resultants/slide-039.png)

![ch04N-Force-System-Resultants Slide 040](assets/ch04N-Force-System-Resultants/slide-040.png)

### Example 4.5

Determine the moment of the force in Fig. 4-18a about point $O$. A force of $F = 5\text{ kN}$ acts at $45^\circ$ below the horizontal at the end of a $3\text{ m}$ rod inclined at $30^\circ$ above the horizontal.

![ch04N-Force-System-Resultants Slide 041](assets/ch04N-Force-System-Resultants/slide-041.png)

**Solution I** -- Using the moment arm (perpendicular distance from $O$ to the line of action of $\mathbf{F}$):

$$d = (3\text{ m})\sin 75^\circ = 2.898\text{ m}$$

$$M_O = Fd = (5\text{ kN})(2.898\text{ m}) = 14.5\text{ kN}\cdot\text{m} \circlearrowright$$

![ch04N-Force-System-Resultants Slide 042](assets/ch04N-Force-System-Resultants/slide-042.png)

**Solution II** -- Resolve $\mathbf{F}$ into components and apply the principle of moments:

$$\circlearrowleft + M_O = -(5\cos 45^\circ)(3\sin 30^\circ) - (5\sin 45^\circ)(3\cos 30^\circ) = -14.5\text{ kN}\cdot\text{m}$$

**Solution III** -- Use axes parallel/perpendicular to the rod. Only the perpendicular component produces a moment about $O$:

$$\circlearrowleft + M_O = -(5\sin 75^\circ)(3) = -14.5\text{ kN}\cdot\text{m}$$

> "The moment of a force about a point is equal to the sum of the moments of the components of the force about the point."

For $\mathbf{F} = \mathbf{F_1} + \mathbf{F_2}$:

$$\mathbf{M_O} = \mathbf{r} \times \mathbf{F} = \mathbf{r} \times (\mathbf{F_1} + \mathbf{F_2}) = \mathbf{r} \times \mathbf{F_1} + \mathbf{r} \times \mathbf{F_2}$$

### Example 4.6

Force $\mathbf{F}$ ($F = 400\text{ N}$ at $30^\circ$ from the vertical) acts at the end of the angle bracket in Fig. 4-19a. Determine the moment of the force about point $O$. The application point is at $(0.4\text{ m}, -0.2\text{ m})$ relative to $O$.

![ch04N-Force-System-Resultants Slide 043](assets/ch04N-Force-System-Resultants/slide-043.png)

**Solution I (Scalar Analysis)** -- Resolve $\mathbf{F}$ into components:

$$\circlearrowleft + M_O = (400\sin 30^\circ\text{ N})(0.2\text{ m}) - (400\cos 30^\circ\text{ N})(0.4\text{ m}) = -98.6\text{ N}\cdot\text{m}$$

$$\mathbf{M}_O = \{-98.6\mathbf{k}\}\text{ N}\cdot\text{m}$$

For two-dimensional problems:

$$M_O = F_x y - F_y x$$

> This method is often easier than $M_O = Fd$.

![ch04N-Force-System-Resultants Slide 044](assets/ch04N-Force-System-Resultants/slide-044.png)

**Solution II (Vector Analysis)** -- Express position and force as Cartesian vectors:

$$\mathbf{r} = \{0.4\mathbf{i} - 0.2\mathbf{j}\}\text{ m}, \quad \mathbf{F} = \{200.0\mathbf{i} - 346.4\mathbf{j}\}\text{ N}$$

![ch04N-Force-System-Resultants Slide 045](assets/ch04N-Force-System-Resultants/slide-045.png)

Compute the cross product determinant:

$$\mathbf{M}_O = \mathbf{r} \times \mathbf{F} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 0.4 & -0.2 & 0 \\ 200.0 & -346.4 & 0 \end{vmatrix} = \{-98.6\mathbf{k}\}\text{ N}\cdot\text{m}$$

> Scalar analysis (Solution I) is generally recommended for two-dimensional problems; Cartesian vector analysis is recommended for three-dimensional problems.

---

## 4.5 Moment of a Force about a Specified Axis

![ch04N-Force-System-Resultants Slide 046](assets/ch04N-Force-System-Resultants/slide-046.png)

![ch04N-Force-System-Resultants Slide 047](assets/ch04N-Force-System-Resultants/slide-047.png)

![ch04N-Force-System-Resultants Slide 048](assets/ch04N-Force-System-Resultants/slide-048.png)

![ch04N-Force-System-Resultants Slide 049](assets/ch04N-Force-System-Resultants/slide-049.png)

![ch04N-Force-System-Resultants Slide 050](assets/ch04N-Force-System-Resultants/slide-050.png)

Sometimes, a specified axis must be determined. For example, loosening a car tire: the nut can only rotate about the $y$ axis -- only the $y$ component of the moment is needed. The total moment produced is not important.

![ch04N-Force-System-Resultants Slide 051](assets/ch04N-Force-System-Resultants/slide-051.png)

### Scalar Analysis

![ch04N-Force-System-Resultants Slide 052](assets/ch04N-Force-System-Resultants/slide-052.png)

$$M_y = Fd_y = F(d\cos\theta)$$

In general:

$$\boxed{M_a = Fd_a}$$

### Vector Analysis

To find the moment of force $\mathbf{F}$ about a specified axis, use $\mathbf{M_O} = \mathbf{r} \times \mathbf{F}$.

$M_y$ along the $y$ axis is the projection of $\mathbf{M_O}$, using the dot product:

$$M_y = \mathbf{j} \cdot \mathbf{M_O} = \mathbf{j} \cdot (\mathbf{r} \times \mathbf{F})$$

where $\mathbf{j}$ is the unit vector for the $y$ axis.

Let $\mathbf{u_a}$ be the unit vector defining the direction of the $a$ axis. The projection of the moment onto the $a$ axis (scalar triple product):

$$\boxed{M_a = \mathbf{u_a} \cdot (\mathbf{r} \times \mathbf{F}) = \begin{vmatrix} u_{a_x} & u_{a_y} & u_{a_z} \\ r_x & r_y & r_z \\ F_x & F_y & F_z \end{vmatrix}}$$

$$M_a = \mathbf{u_a} \cdot (\mathbf{r} \times \mathbf{F}) = u_{a_x}(r_yF_z - r_zF_y) - u_{a_y}(r_xF_z - r_zF_x) + u_{a_z}(r_xF_y - r_yF_x)$$

**Sign interpretation:**
- $M_a$ positive -- same sense as $\mathbf{u_a}$
- $M_a$ negative -- opposite sense to $\mathbf{u_a}$

Express $M_a$ as a Cartesian vector:

$$\mathbf{M_a} = M_a\,\mathbf{u_a} = [\mathbf{u_a} \cdot (\mathbf{r} \times \mathbf{F})]\,\mathbf{u_a}$$

### Example 4.7

> Determine the resultant moment of the three forces about the $x$, $y$, and $z$ axes.

Given: $F_1 = 60\text{ N}$, $F_2 = 50\text{ N}$, $F_3 = 40\text{ N}$ acting on a rectangular structure with dimensions $0.6\text{ m}$ and $0.9\text{ m}$.

Method: Scalar analysis using $M = Fd$ and the right-hand rule.

![ch04N-Force-System-Resultants Slide 053](assets/ch04N-Force-System-Resultants/slide-053.png)

### Example 4.8

> Determine the moment $M_{AB}$ produced by force $\mathbf{F}$ that tends to rotate the rod about the $AB$ axis.

Given: $F = 300\text{ N}$ acting vertically downward at point $C$. Points $A(0, 0, 0)$, $B(0.4, 0.2, 0)$ m, $C(0.6, 0, 0.3)$ m.

Method: Vector analysis using the scalar triple product $M_{AB} = \mathbf{u}_B \cdot (\mathbf{r} \times \mathbf{F})$.

- Unit vector: $\mathbf{u}_B = \dfrac{0.4\mathbf{i} + 0.2\mathbf{j}}{\sqrt{0.4^2 + 0.2^2}} = 0.8944\mathbf{i} + 0.4472\mathbf{j}$
- Position vector: $\mathbf{r}_D = \{0.6\mathbf{i}\}\text{ m}$
- Force vector: $\mathbf{F} = \{-300\mathbf{k}\}\text{ N}$

![ch04N-Force-System-Resultants Slide 054](assets/ch04N-Force-System-Resultants/slide-054.png)

$$M_{AB} = \mathbf{u}_B \cdot (\mathbf{r}_D \times \mathbf{F}) = \begin{vmatrix} 0.8944 & 0.4472 & 0 \\ 0.6 & 0 & 0 \\ 0 & 0 & -300 \end{vmatrix} = 80.50\text{ N}\cdot\text{m}$$

$$\mathbf{M}_{AB} = M_{AB}\,\mathbf{u}_B = (80.50)(0.8944\mathbf{i} + 0.4472\mathbf{j}) = \{72.0\mathbf{i} + 36.0\mathbf{j}\}\text{ N}\cdot\text{m}$$

> The positive result indicates $\mathbf{M}_{AB}$ has the same sense as $\mathbf{u}_B$. If the axis were defined from $B$ toward $A$ ($-\mathbf{u}_B$), the scalar would be $-80.50\text{ N}\cdot\text{m}$, but the vector result $\mathbf{M}_{AB}$ remains the same.

![ch04N-Force-System-Resultants Slide 055](assets/ch04N-Force-System-Resultants/slide-055.png)

### Example 4.9

> Determine the magnitude of the moment of force $\mathbf{F}$ about segment $OA$ of the pipe assembly.

Given: $F = 300\text{ N}$ acting at point $C$ directed toward point $D$.

Coordinates: $O(0, 0, 0)$, $A(0.3, 0.4, 0)$ m, $C(0.5, 0.5, 0)$ m, $D(0.5, 0, 0.5)$ m.

Force vector:

$$\mathbf{F} = (300\text{ N})\left[\frac{0.4\mathbf{i} - 0.4\mathbf{j} + 0.2\mathbf{k}}{\sqrt{0.4^2 + (-0.4)^2 + 0.2^2}}\right] = \{200\mathbf{i} - 200\mathbf{j} + 100\mathbf{k}\}\text{ N}$$

![ch04N-Force-System-Resultants Slide 056](assets/ch04N-Force-System-Resultants/slide-056.png)

$$M_{OA} = \mathbf{u}_{OA} \cdot (\mathbf{r}_{OD} \times \mathbf{F}) = \begin{vmatrix} 0.6 & 0.8 & 0 \\ 0.5 & 0 & 0.5 \\ 200 & -200 & 100 \end{vmatrix} = 100\text{ N}\cdot\text{m}$$

![ch04N-Force-System-Resultants Slide 057](assets/ch04N-Force-System-Resultants/slide-057.png)

---

## 4.6 Moment of a Couple

### Definition

![ch04N-Force-System-Resultants Slide 058](assets/ch04N-Force-System-Resultants/slide-058.png)

![ch04N-Force-System-Resultants Slide 059](assets/ch04N-Force-System-Resultants/slide-059.png)

![ch04N-Force-System-Resultants Slide 060](assets/ch04N-Force-System-Resultants/slide-060.png)

![ch04N-Force-System-Resultants Slide 061](assets/ch04N-Force-System-Resultants/slide-061.png)

![ch04N-Force-System-Resultants Slide 062](assets/ch04N-Force-System-Resultants/slide-062.png)

A **couple** consists of:
- Two parallel forces
- Same magnitude but opposite direction
- Separated by perpendicular distance $d$

Properties:
- Resultant force = 0
- Tendency to rotate in a specified direction
- Couple moment = sum of moments of both couple forces about any arbitrary point

![ch04N-Force-System-Resultants Slide 063](assets/ch04N-Force-System-Resultants/slide-063.png)

Position vectors $\mathbf{r_A}$ and $\mathbf{r_B}$ are directed from $O$ to $A$ and $B$, lying on the line of action of $\mathbf{F}$ and $-\mathbf{F}$.

Couple moment about $O$:

$$\mathbf{M} = \mathbf{r_A} \times \mathbf{F} + \mathbf{r_B} \times (-\mathbf{F}) = (\mathbf{r_B} - \mathbf{r_A}) \times \mathbf{F} = \mathbf{r} \times \mathbf{F}$$

where $\mathbf{r}$ is directed between the forces.

> A couple moment is a **free vector** -- it can act at any point since $\mathbf{M}$ depends only on the position vector $\mathbf{r}$ directed between forces and not on position vectors $\mathbf{r_A}$ and $\mathbf{r_B}$ directed from $O$ to the forces. Unlike the moment of a force, which requires a definite point or axis.

![ch04N-Force-System-Resultants Slide 064](assets/ch04N-Force-System-Resultants/slide-064.png)

### Scalar Formulation

![ch04N-Force-System-Resultants Slide 065](assets/ch04N-Force-System-Resultants/slide-065.png)

$$M = Fd$$

- Direction and sense determined by right-hand rule
- In all cases, $\mathbf{M}$ acts perpendicular to the plane containing the forces

### Vector Formulation

![ch04N-Force-System-Resultants Slide 066](assets/ch04N-Force-System-Resultants/slide-066.png)

$$\mathbf{M} = \mathbf{r} \times \mathbf{F}$$

If moments are taken about point $A$, the moment of $-\mathbf{F}$ is zero about this point. $\mathbf{r}$ is crossed with the force $\mathbf{F}$ to which it is directed.

### Equivalent Couples

If two couples produce a moment with the same magnitude and direction, they are **equivalent**.

Example:
- $M = 30\text{ N}(0.4\text{ m}) = 12\text{ N}\cdot\text{m}$
- $M = 40\text{ N}(0.3\text{ m}) = 12\text{ N}\cdot\text{m}$

Equivalent couples.

### Resultant Couple Moment

Since couple moments are free vectors, their resultant can be determined by vector addition:

$$\mathbf{M_R} = \mathbf{M_1} + \mathbf{M_2}$$

For more than two couple moments:

$$\mathbf{M_R} = \sum (\mathbf{r} \times \mathbf{F})$$

### Example 4.10

![ch04N-Force-System-Resultants Slide 067](assets/ch04N-Force-System-Resultants/slide-067.png)

Determine the resultant couple moment of the three couples acting on the plate.

Given: $F_1 = 200\text{ N}$, $F_2 = 450\text{ N}$, $F_3 = 300\text{ N}$; perpendicular distances $d_1 = 1.2\text{ m}$, $d_2 = 0.9\text{ m}$, $d_3 = 1.5\text{ m}$.

$$\circlearrowleft + M_R = \sum M = -F_1 d_1 + F_2 d_2 - F_3 d_3 = -(200)(1.2) + (450)(0.9) - (300)(1.5) = -285\text{ N}\cdot\text{m}$$

The negative sign indicates $M_R = 285\text{ N}\cdot\text{m}$ clockwise.

### Example 4.11

![ch04N-Force-System-Resultants Slide 068](assets/ch04N-Force-System-Resultants/slide-068.png)

![ch04N-Force-System-Resultants Slide 069](assets/ch04N-Force-System-Resultants/slide-069.png)

![ch04N-Force-System-Resultants Slide 070](assets/ch04N-Force-System-Resultants/slide-070.png)

Determine the magnitude and direction of the couple moment acting on the gear.

Given: $F = 600\text{ N}$, gear radius $r = 0.2\text{ m}$, angle $\theta = 30^\circ$.

**Solution:** Resolve forces into components and sum moments about center $O$:

$$\circlearrowleft + M = (600 \cos 30^\circ)(0.2) - (600 \sin 30^\circ)(0.2) = 43.9\text{ N}\cdot\text{m} \circlearrowleft$$

The positive result indicates counterclockwise direction. The same result can be obtained using $M = Fd$, but calculating the perpendicular distance $d$ is more involved. The couple moment is a free vector producing the same turning effect about any point.

### Example 4.12

![ch04N-Force-System-Resultants Slide 071](assets/ch04N-Force-System-Resultants/slide-071.png)

![ch04N-Force-System-Resultants Slide 072](assets/ch04N-Force-System-Resultants/slide-072.png)

![ch04N-Force-System-Resultants Slide 073](assets/ch04N-Force-System-Resultants/slide-073.png)

Determine the couple moment acting on the pipe. Segment $AB$ is directed $30^\circ$ below the $x$-$y$ plane.

Given: Two $25\text{ N}$ forces forming a couple; $OA = 0.8\text{ m}$ along $y$-axis, $AB = 0.6\text{ m}$ at $30^\circ$ below $x$-$y$ plane.

**Solution I (Vector Analysis):**

$$\mathbf{M} = \mathbf{r}_{AB} \times (25\mathbf{k}) = (0.6\cos 30^\circ\,\mathbf{i} - 0.6\sin 30^\circ\,\mathbf{k}) \times (25\mathbf{k}) = \{-13.0\mathbf{j}\}\text{ N}\cdot\text{m}$$

**Solution II (Scalar Analysis):**

$$d = 0.6\cos 30^\circ = 0.5196\text{ m}, \quad M = Fd = 25(0.5196) = 13.0\text{ N}\cdot\text{m}$$

By right-hand rule: $\mathbf{M} = \{-13.0\mathbf{j}\}\text{ N}\cdot\text{m}$

### Example 4.13

![ch04N-Force-System-Resultants Slide 074](assets/ch04N-Force-System-Resultants/slide-074.png)

![ch04N-Force-System-Resultants Slide 075](assets/ch04N-Force-System-Resultants/slide-075.png)

Replace the two couples acting on the pipe column by a resultant couple moment.

Given: Couple 1 -- $F_1 = 150\text{ N}$, $d_1 = 0.4\text{ m}$; Couple 2 -- $F_2 = 125\text{ N}$, $\mathbf{r}_{DC} = 0.3\mathbf{i}$, $\mathbf{F}_C = [100\mathbf{j} - 75\mathbf{k}]\text{ N}$.

**Solution:**

$$\mathbf{M_1} = Fd = 150(0.4) = 60\text{ N}\cdot\text{m}, \quad \mathbf{M_1} = \{60\mathbf{i}\}\text{ N}\cdot\text{m}$$

$$\mathbf{M_2} = \mathbf{r}_{DC} \times \mathbf{F}_C = (0.3\mathbf{i}) \times (100\mathbf{j} - 75\mathbf{k}) = \{22.5\mathbf{j} + 30\mathbf{k}\}\text{ N}\cdot\text{m}$$

$$\mathbf{M_R} = \mathbf{M_1} + \mathbf{M_2} = \{60\mathbf{i} + 22.5\mathbf{j} + 30\mathbf{k}\}\text{ N}\cdot\text{m}$$

---

## 4.7 Simplification of a Force and Couple System

![ch04N-Force-System-Resultants Slide 076](assets/ch04N-Force-System-Resultants/slide-076.png)

![ch04N-Force-System-Resultants Slide 077](assets/ch04N-Force-System-Resultants/slide-077.png)

The equivalent system at point $O$ consists of a resultant force $\mathbf{F}_R$ and a resultant couple moment $(\mathbf{M}_R)_O$.

![ch04N-Force-System-Resultants Slide 078](assets/ch04N-Force-System-Resultants/slide-078.png)

Several forces and couple moments acting on a body can be replaced by an equivalent single resultant force at point $O$. Each force produces a moment about $O$:

$$(\mathbf{M}_O)_1 = \mathbf{r}_1 \times \mathbf{F}_1, \quad (\mathbf{M}_O)_2 = \mathbf{r}_2 \times \mathbf{F}_2$$

![ch04N-Force-System-Resultants Slide 079](assets/ch04N-Force-System-Resultants/slide-079.png)

**Application:** The weights of traffic lights can be replaced by an equivalent resultant force $W_R = W_1 + W_2$ and a couple moment $(M_R)_O = W_1 d_1 + W_2 d_2$ at the support $O$. In both cases the support must provide the same resistance to translation and rotation.

![ch04N-Force-System-Resultants Slide 080](assets/ch04N-Force-System-Resultants/slide-080.png)

**General system simplification:**

$$\mathbf{F}_R = \sum \mathbf{F}, \quad (\mathbf{M}_R)_O = \sum \mathbf{M}_O + \sum \mathbf{M}$$

**Planar (2D) system simplification:**

$$(F_R)_x = \sum F_x, \quad (F_R)_y = \sum F_y$$

$$(M_R)_O = \sum M_O + \sum M$$

![ch04N-Force-System-Resultants Slide 081](assets/ch04N-Force-System-Resultants/slide-081.png)

**Key properties:**

- $\mathbf{F}_R = \mathbf{F}_1 + \mathbf{F}_2$ is **independent** of the location of point $O$
- $(\mathbf{M}_R)_O = \mathbf{M} + (\mathbf{M}_O)_1 + (\mathbf{M}_O)_2$ **depends** on the location of point $O$ since moments are determined using position vectors $\mathbf{r}_1$ and $\mathbf{r}_2$
- $(\mathbf{M}_R)_O$ is a **free vector** and can act at any point on the body

![ch04N-Force-System-Resultants Slide 082](assets/ch04N-Force-System-Resultants/slide-082.png)

To reduce a system of forces and couple moments to a simpler form by replacing it with an **equivalent system**.

An equivalent system has the same **external effects** (translating and rotating motion of the body, or reactive forces at supports if the body is held fixed) as the original.

### Principle of Transmissibility

![ch04N-Force-System-Resultants Slide 083](assets/ch04N-Force-System-Resultants/slide-083.png)

A force acting on a body is a **sliding vector** since it can be applied at any point along its line of action.

### Moving a Force Off Its Line of Action

![ch04N-Force-System-Resultants Slide 084](assets/ch04N-Force-System-Resultants/slide-084.png)

If $\mathbf{F}$ is not on the line of action (perpendicular):
- Attach $\mathbf{F}$ and $-\mathbf{F}$ at the new point $B$
- The couple moment: $M = Fd$
- Result: A downward force $\mathbf{F}$ and a clockwise couple moment $M$

### Equivalent System at Point O

![ch04N-Force-System-Resultants Slide 085](assets/ch04N-Force-System-Resultants/slide-085.png)

For several forces and couple moments, an equivalent single resultant force at point $O$:

$$\mathbf{F_R} = \sum \mathbf{F} = \mathbf{F_1} + \mathbf{F_2}$$

### Example 4.14

> Replace the force and couple system shown in Fig. 4-37a by an equivalent resultant force and couple moment acting at point $O$.

Given: a $3\text{ kN}$ force at $30^\circ$, a $4\text{ kN}$ vertical force, and a $5\text{ kN}$ force on a 3-4-5 slope acting on a structural member.

![ch04N-Force-System-Resultants Slide 086](assets/ch04N-Force-System-Resultants/slide-086.png)

**Force Summation:** Resolve all forces into $x$ and $y$ components.

$$\xrightarrow{+}\;(F_R)_x = \sum F_x;\quad (F_R)_x = (3\;\text{kN})\cos 30^\circ + \tfrac{3}{5}(5\;\text{kN}) = 5.598\;\text{kN}\;\rightarrow$$

$$+\uparrow\;(F_R)_y = \sum F_y;\quad (F_R)_y = (3\;\text{kN})\sin 30^\circ - \tfrac{4}{5}(5\;\text{kN}) - 4\;\text{kN} = -6.50\;\text{kN} = 6.50\;\text{kN}\;\downarrow$$

$$F_R = \sqrt{(5.598)^2 + (6.50)^2} = 8.58\;\text{kN}, \quad \theta = \tan^{-1}\!\left(\frac{6.50}{5.598}\right) = 49.3^\circ$$

![ch04N-Force-System-Resultants Slide 087](assets/ch04N-Force-System-Resultants/slide-087.png)

**Moment Summation:**

$$\circlearrowleft +\;(M_R)_O = \sum M_O$$

$$(M_R)_O = (3\;\text{kN})\sin 30^\circ(0.2\;\text{m}) - (3\;\text{kN})\cos 30^\circ(0.1\;\text{m}) + \tfrac{3}{5}(5\;\text{kN})(0.1\;\text{m}) - \tfrac{4}{5}(5\;\text{kN})(0.5\;\text{m}) - (4\;\text{kN})(0.2\;\text{m})$$

$$(M_R)_O = -2.46\;\text{kN}\cdot\text{m} = 2.46\;\text{kN}\cdot\text{m}\;\circlearrowright \quad\text{(Ans.)}$$

> The resultant force and couple moment produce the same external effects at the supports as the original force system.

![ch04N-Force-System-Resultants Slide 088](assets/ch04N-Force-System-Resultants/slide-088.png)

### Example 4.15

> Replace the force and couple system acting on the member in Fig. 4-38a by an equivalent resultant force and couple moment acting at point $O$.

Given: a $750\text{ N}$ downward force, a $500\text{ N}$ force on a 3-4-5 slope, and a couple of two $200\text{ N}$ forces.

![ch04N-Force-System-Resultants Slide 089](assets/ch04N-Force-System-Resultants/slide-089.png)

**Force Summation:** The $200\text{ N}$ couple forces are equal and opposite (zero resultant). Resolve the $500\text{ N}$ force into components.

$$\xrightarrow{+}\;(F_R)_x = \sum F_x;\quad (F_R)_x = \tfrac{3}{5}(500\;\text{N}) = 300\;\text{N}\;\rightarrow$$

$$+\uparrow\;(F_R)_y = \sum F_y;\quad (F_R)_y = \tfrac{4}{5}(500\;\text{N}) - 750\;\text{N} = -350\;\text{N} = 350\;\text{N}\;\downarrow$$

$$F_R = \sqrt{(300)^2 + (350)^2} = 461\;\text{N}, \quad \theta = \tan^{-1}\!\left(\frac{350}{300}\right) = 49.4^\circ$$

![ch04N-Force-System-Resultants Slide 090](assets/ch04N-Force-System-Resultants/slide-090.png)

**Moment Summation:** The couple moment is a free vector and can act at any point.

$$\circlearrowleft +\;(M_R)_O = \sum M_O + \sum M$$

$$(M_R)_O = (500\;\text{N})\tfrac{4}{5}(2.5\;\text{m}) - (500\;\text{N})\tfrac{3}{5}(1\;\text{m}) - (750\;\text{N})(1.25\;\text{m}) + 200\;\text{N}\cdot\text{m}$$

$$(M_R)_O = -37.5\;\text{N}\cdot\text{m} = 37.5\;\text{N}\cdot\text{m}\;\circlearrowright \quad\text{(Ans.)}$$

![ch04N-Force-System-Resultants Slide 091](assets/ch04N-Force-System-Resultants/slide-091.png)

### Example 4.16

> Replace the system of a couple moment $\mathbf{M}$ and forces $\mathbf{F}_1$ and $\mathbf{F}_2$ acting on an I-beam by an equivalent resultant force and couple moment at its base, point $O$.

Given: $\mathbf{F}_1 = 800\text{ N}$ (downward), $\mathbf{F}_2 = 300\text{ N}$ (from $C$ to $B$), $\mathbf{M} = 500\text{ N}\cdot\text{m}$ (3-4-5 slope in $y$-$z$ plane). Member height $= 1\text{ m}$, point $B$ at $(-0.15, 0.1, 1)\text{ m}$.

![ch04N-Force-System-Resultants Slide 092](assets/ch04N-Force-System-Resultants/slide-092.png)

**Vector Analysis:**

$$\mathbf{F}_1 = \{-800\mathbf{k}\}\;\text{N}$$

$$\mathbf{F}_2 = 300\left[\frac{-0.15\mathbf{i} + 0.1\mathbf{j}}{\sqrt{(-0.15)^2 + (0.1)^2}}\right] = \{-249.6\mathbf{i} + 166.4\mathbf{j}\}\;\text{N}$$

$$\mathbf{M} = -500\!\left(\tfrac{4}{5}\right)\mathbf{j} + 500\!\left(\tfrac{3}{5}\right)\mathbf{k} = \{-400\mathbf{j} + 300\mathbf{k}\}\;\text{N}\cdot\text{m}$$

**Force Summation:**

$$\mathbf{F}_R = \mathbf{F}_1 + \mathbf{F}_2 = \{-250\mathbf{i} + 166\mathbf{j} - 800\mathbf{k}\}\;\text{N}$$

**Moment Summation:**

$$(\mathbf{M}_R)_O = \mathbf{M} + \mathbf{r}_C \times \mathbf{F}_1 + \mathbf{r}_B \times \mathbf{F}_2$$

$$(\mathbf{M}_R)_O = (-400\mathbf{j} + 300\mathbf{k}) + (\mathbf{k}) \times (-800\mathbf{k}) + \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ -0.15 & 0.1 & 1 \\ -249.6 & 166.4 & 0 \end{vmatrix}$$

$$(\mathbf{M}_R)_O = \{-166\mathbf{i} - 650\mathbf{j} + 300\mathbf{k}\}\;\text{N}\cdot\text{m}$$

![ch04N-Force-System-Resultants Slide 093](assets/ch04N-Force-System-Resultants/slide-093.png)

---

## 4.8 Further Simplification of a Force and Couple System

![ch04N-Force-System-Resultants Slide 094](assets/ch04N-Force-System-Resultants/slide-094.png)

If $\mathbf{F_R}$ and $(\mathbf{M_R})_O$ are **perpendicular**: the force system can be further reduced to an equivalent force.

Because of this condition, only **concurrent**, **coplanar**, and **parallel** force systems can be further simplified.

![ch04N-Force-System-Resultants Slide 095](assets/ch04N-Force-System-Resultants/slide-095.png)

### Concurrent Force System

Lines of action of all the forces intersect at a common point $O$.

$$\mathbf{F_R} = \sum \mathbf{F}$$

![ch04N-Force-System-Resultants Slide 096](assets/ch04N-Force-System-Resultants/slide-096.png)

### Coplanar Force System

Lines of action of all the forces and the resultant force $\mathbf{F_R} = \sum \mathbf{F}$ lie in the same plane.

$(\mathbf{M_R})_O$ and $\mathbf{F_R}$ are mutually perpendicular.

$$(M_R)_O = F_R d = \sum M_O$$

$$d = \frac{(M_R)_O}{F_R}$$

![ch04N-Force-System-Resultants Slide 097](assets/ch04N-Force-System-Resultants/slide-097.png)

### Parallel Force System

Forces and the resultant force $\mathbf{F_R} = \sum \mathbf{F}$ at point $O$ are all parallel.

$$(M_R)_O = F_R d = \sum M_O$$

$$d = \frac{(M_R)_O}{F_R}$$

![ch04N-Force-System-Resultants Slide 098](assets/ch04N-Force-System-Resultants/slide-098.png)

The four cable forces on this bridge tower are all concurrent at point $O$, producing no resultant moment there -- only a resultant force $\mathbf{F_R}$ directed along the tower to the support, avoiding any bending.

![ch04N-Force-System-Resultants Slide 099](assets/ch04N-Force-System-Resultants/slide-099.png)

The weights of the traffic lights are replaced by their resultant force $W_R = W_1 + W_2$ acting at a distance $d = (W_1 d_1 + W_2 d_2) / W_R$ from $O$. Both systems are equivalent.

### Procedure for Analysis

![ch04N-Force-System-Resultants Slide 100](assets/ch04N-Force-System-Resultants/slide-100.png)

The technique used to reduce a coplanar or parallel force system to a single resultant force follows a similar procedure:

- Establish the $x, y, z$ axes and locate the resultant force $\mathbf{F_R}$ an arbitrary distance away from the origin of the coordinates.
- **Force Summation**: The resultant force equals the sum of all forces. For coplanar systems, resolve each force into $x$ and $y$ components.
- **Moment Summation**: The moment of $\mathbf{F_R}$ about point $O$ equals the sum of the moments about $O$ of all the forces in the system.

### Concurrent Force System (Detailed)

![ch04N-Force-System-Resultants Slide 101](assets/ch04N-Force-System-Resultants/slide-101.png)

Lines of action of all the forces intersect at a common point $O$.

$$\mathbf{F_R} = \sum \mathbf{F}$$

### Coplanar Force System (Detailed)

![ch04N-Force-System-Resultants Slide 102](assets/ch04N-Force-System-Resultants/slide-102.png)

Lines of action of all the forces and the resultant force $\mathbf{F_R} = \sum \mathbf{F}$ lie in the same plane.

$(\mathbf{M_R})_O$ and $\mathbf{F_R}$ are mutually perpendicular.

$$(M_R)_O = F_R d = \sum M_O$$

$$d = \frac{(M_R)_O}{F_R}$$

### Parallel Force System (Detailed)

![ch04N-Force-System-Resultants Slide 103](assets/ch04N-Force-System-Resultants/slide-103.png)

Forces and the resultant force $\mathbf{F_R} = \sum \mathbf{F}$ at point $O$ are all parallel.

$$(M_R)_O = F_R d = \sum M_O$$

$$d = \frac{(M_R)_O}{F_R}$$

### Reduction to a Wrench

For 3-D force and couple moment systems where $(\mathbf{M_R})_O$ is **not perpendicular** to $\mathbf{F_R}$:

1. Resolve $(\mathbf{M_R})_O$ into $\mathbf{M_\perp}$ and $\mathbf{M_\parallel}$
2. Move $\mathbf{F_R}$ to point $P$ where $\mathbf{M_\perp}$ can be replaced
3. $\mathbf{M_\parallel}$ is a free vector, it can be moved to $P$
4. The combination of $\mathbf{F_R}$ and $\mathbf{M_\parallel}$ tends to translate and rotate the body about its axis -- acts as a **wrench** (or screw)

### Example 4.17

![ch04N-Force-System-Resultants Slide 104](assets/ch04N-Force-System-Resultants/slide-104.png)

Replace the force and couple moment system acting on the beam in Fig. 4-44 by an equivalent resultant force, and find its point of application $d$ from point $O$.

![ch04N-Force-System-Resultants Slide 105](assets/ch04N-Force-System-Resultants/slide-105.png)

**Force Summation:**

$$(F_R)_x = \sum F_x = 8\,\text{kN}\left(\frac{3}{5}\right) = 4.80\,\text{kN} \rightarrow$$

$$(F_R)_y = \sum F_y = -4\,\text{kN} + 8\,\text{kN}\left(\frac{4}{5}\right) = 2.40\,\text{kN} \uparrow$$

$$F_R = \sqrt{(4.80\,\text{kN})^2 + (2.40\,\text{kN})^2} = 5.37\,\text{kN}$$

$$\theta = \tan^{-1}\left(\frac{2.40}{4.80}\right) = 26.6^\circ$$

![ch04N-Force-System-Resultants Slide 106](assets/ch04N-Force-System-Resultants/slide-106.png)

**Moment Summation:**

$$2.40\,\text{kN}(d) = -(4\,\text{kN})(1.5\,\text{m}) - 15\,\text{kN}\!\cdot\!\text{m} - \left[8\,\text{kN}\left(\tfrac{3}{5}\right)\right](0.5\,\text{m}) + \left[8\,\text{kN}\left(\tfrac{4}{5}\right)\right](4.5\,\text{m})$$

$$d = 2.25\,\text{m}$$

### Example 4.18

![ch04N-Force-System-Resultants Slide 107](assets/ch04N-Force-System-Resultants/slide-107.png)

The jib crane in Fig. 4-45a is subjected to three coplanar forces. Replace this loading by an equivalent resultant force and specify where the resultant's line of action intersects the column $AB$ and the boom $BC$.

**Force Summation:**

$$(F_R)_x = \sum F_x = -9\,\text{kN} \quad (9\,\text{kN} \leftarrow)$$

$$(F_R)_y = \sum F_y = -6\,\text{kN} \quad (6\,\text{kN} \downarrow)$$

$$F_R = \sqrt{(9\,\text{kN})^2 + (6\,\text{kN})^2} = 10.8\,\text{kN}$$

$$\theta = \tan^{-1}\left(\frac{6}{9}\right) = 33.7^\circ$$

![ch04N-Force-System-Resultants Slide 108](assets/ch04N-Force-System-Resultants/slide-108.png)

**Moment Summation** (about point $A$):

- Intersection with column $AB$: $y = 1.11\,\text{m}$
- Intersection with boom $BC$: $x = 4.33\,\text{m}$

### Example 4.19

![ch04N-Force-System-Resultants Slide 109](assets/ch04N-Force-System-Resultants/slide-109.png)

The slab in Fig. 4-46a is subjected to four parallel forces. Determine the magnitude and direction of a resultant force equivalent to the given force system, and locate its point of application on the slab.

**Force Summation (scalar analysis):**

$$+\uparrow \quad F_R = \sum F_z = -600\,\text{N} + 100\,\text{N} - 400\,\text{N} - 500\,\text{N} = -1400\,\text{N}$$

$$F_R = 1400\,\text{N} \downarrow$$

![ch04N-Force-System-Resultants Slide 110](assets/ch04N-Force-System-Resultants/slide-110.png)

**Moment Summation:**

Moment about the $x$-axis:

$$(M_R)_x = \sum M_x; \quad -(1400\,\text{N})\,y = 600\,\text{N}(0) + 100\,\text{N}(5\,\text{m}) - 400\,\text{N}(10\,\text{m}) + 500\,\text{N}(0)$$

$$y = 2.50\,\text{m}$$

Moment about the $y$-axis:

$$(M_R)_y = \sum M_y; \quad (1400\,\text{N})\,x = 600\,\text{N}(8\,\text{m}) - 100\,\text{N}(6\,\text{m}) + 400\,\text{N}(0) + 500\,\text{N}(0)$$

$$x = 3.00\,\text{m}$$

A resultant force of $F_R = 1400\,\text{N}$ placed at point $P(3.00\,\text{m},\; 2.50\,\text{m})$ is equivalent to the original parallel force system.

### Example 4.20

![ch04N-Force-System-Resultants Slide 111](assets/ch04N-Force-System-Resultants/slide-111.png)

Replace the force system in Fig. 4-47a by an equivalent resultant force and specify its point of application on the pedestal. Three vertical forces act: $F_A = 30\,\text{kN}$ downward at $A$, $F_B = 50\,\text{kN}$ downward at $B$, $F_C = 10\,\text{kN}$ upward at $C$.

**Force Summation (vector analysis):**

$$\mathbf{F_R} = \sum \mathbf{F} = \{-30\mathbf{k}\}\,\text{kN} + \{-50\mathbf{k}\}\,\text{kN} + \{10\mathbf{k}\}\,\text{kN} = \{-70\mathbf{k}\}\,\text{kN}$$

![ch04N-Force-System-Resultants Slide 112](assets/ch04N-Force-System-Resultants/slide-112.png)

**Moment Summation** about point $O$:

$$\mathbf{r}_P \times \mathbf{F_R} = (\mathbf{r}_A \times \mathbf{F_A}) + (\mathbf{r}_B \times \mathbf{F_B}) + (\mathbf{r}_C \times \mathbf{F_C})$$

$$(x\mathbf{i} + y\mathbf{j}) \times (-70\mathbf{k}) = [(0.4\mathbf{i}) \times (-30\mathbf{k})] + [(-0.4\mathbf{i} + 0.2\mathbf{j}) \times (-50\mathbf{k})] + [(-0.4\mathbf{j}) \times (10\mathbf{k})]$$

$$70x\,\mathbf{j} - 70y\,\mathbf{i} = 12\mathbf{j} - 20\mathbf{j} - 10\mathbf{i} - 4\mathbf{i}$$

![ch04N-Force-System-Resultants Slide 113](assets/ch04N-Force-System-Resultants/slide-113.png)

**Equating components:**

$$-70y = -14 \implies y = 0.2\,\text{m}$$

$$70x = -8 \implies x = -0.114\,\text{m}$$

The negative $x$ indicates the resultant acts to the left of the $y$-axis.

---

## 4.9 Reduction of a Simple Distributed Loading

![ch04N-Force-System-Resultants Slide 114](assets/ch04N-Force-System-Resultants/slide-114.png)

A body may be subjected to a loading that is distributed over its surface. The pressure exerted at each point on the surface indicates the **intensity** of the loading.

- Units: pascals (Pa) or N/m$^2$

![ch04N-Force-System-Resultants Slide 115](assets/ch04N-Force-System-Resultants/slide-115.png)

The most common type of distributed loading acts along a single axis. With constant width $b$, the pressure loading varies only along the $x$ axis: $p = p(x)$ N/m$^2$.

![ch04N-Force-System-Resultants Slide 116](assets/ch04N-Force-System-Resultants/slide-116.png)

The coplanar distributed load intensity is $w(x) = p(x) \cdot b$ N/m. This parallel force system can be replaced with a single equivalent resultant force $\mathbf{F_R}$ acting through the centroid $C$ of the loading area at distance $\bar{x}$ from the origin.

![ch04N-Force-System-Resultants Slide 117](assets/ch04N-Force-System-Resultants/slide-117.png)

### Magnitude of Resultant Force

The magnitude of $d\mathbf{F}$ is determined from the differential area $dA$ under the loading curve. For length $L$:

$$\boxed{F_R = \sum F = \int_L dA = \int_0^L w(x)\,dx = A}$$

> The magnitude of the resultant force is equal to the total **area $A$** under the loading diagram.

![ch04N-Force-System-Resultants Slide 118](assets/ch04N-Force-System-Resultants/slide-118.png)

### Location of Resultant Force

The resultant's location is found by equating moments about point $O$:

$$\bar{x} = \frac{\int_0^L x\,w(x)\,dx}{\int_0^L w(x)\,dx} = \frac{\int_A x\,dA}{\int_A dA}$$

> The resultant force acts through the **centroid** of the loading diagram area.

![ch04N-Force-System-Resultants Slide 119](assets/ch04N-Force-System-Resultants/slide-119.png)

A real-world example of distributed loading: a pile of bricks creates an approximate triangular distributed loading on a board.

---

### Example 4.21

Determine the magnitude and location of the equivalent resultant force acting on the shaft. The shaft is subjected to a distributed load $w = 60x^2$ N/m over a length of 2 m (maximum intensity 240 N/m at $x = 2$ m).

![ch04N-Force-System-Resultants Slide 120](assets/ch04N-Force-System-Resultants/slide-120.png)

![ch04N-Force-System-Resultants Slide 121](assets/ch04N-Force-System-Resultants/slide-121.png)

**Solution -- Magnitude:**

$$F_R = \int_0^{2} 60x^2\,dx = 60\left[\frac{x^3}{3}\right]_0^{2} = 160 \text{ N}$$

![ch04N-Force-System-Resultants Slide 122](assets/ch04N-Force-System-Resultants/slide-122.png)

**Solution -- Location:**

$$\bar{x} = \frac{\int_0^{2} x(60x^2)\,dx}{160} = \frac{60\left[\frac{x^4}{4}\right]_0^{2}}{160} = 1.5 \text{ m}$$

This can be verified using the exparabolic area formula: $A = \frac{ab}{3} = \frac{2(240)}{3} = 160$ N, and $\bar{x} = \frac{3}{4}a = 1.5$ m.

---

### Example 4.22

A distributed loading of $p = 800x$ Pa acts over the top surface of a beam (width 0.2 m, length 9 m). Determine the magnitude and location of the equivalent resultant force.

The linear load intensity is $w = (800x)(0.2) = 160x$ N/m, with maximum $w = 1440$ N/m at $x = 9$ m.

![ch04N-Force-System-Resultants Slide 123](assets/ch04N-Force-System-Resultants/slide-123.png)

![ch04N-Force-System-Resultants Slide 124](assets/ch04N-Force-System-Resultants/slide-124.png)

**Solution:**

$$F_R = \frac{1}{2}(9)(1440) = 6480 \text{ N} = 6.48 \text{ kN}$$

$$\bar{x} = 9 - \frac{1}{3}(9) = 6 \text{ m}$$

Alternatively, using the volume of the loading diagram: $F_R = V = \frac{1}{2}(7200)(9)(0.2) = 6.48$ kN.

---

### Example 4.23

Granular material exerts a trapezoidal distributed loading on a 3 m beam: $1500$ N/m at point $A$ and $750$ N/m at point $B$. Determine the magnitude and location of the equivalent resultant.

Decompose the trapezoidal load into a triangle and a rectangle:

- $F_1 = \frac{1}{2}(3)(750) = 1125$ N, located $\bar{x}_1 = 1$ m from $A$
- $F_2 = (3)(750) = 2250$ N, located $\bar{x}_2 = 1.5$ m from $A$

![ch04N-Force-System-Resultants Slide 125](assets/ch04N-Force-System-Resultants/slide-125.png)

![ch04N-Force-System-Resultants Slide 126](assets/ch04N-Force-System-Resultants/slide-126.png)

**Solution:**

$$F_R = F_1 + F_2 = 1125 + 2250 = 3375 \text{ N} = 3.375 \text{ kN}$$

$$\bar{x} = \frac{F_1 \bar{x}_1 + F_2 \bar{x}_2}{F_R} = \frac{1125(1) + 2250(1.5)}{3375} = 1.333 \text{ m from } A$$

> **Note**: An alternative method decomposes the trapezoid into two triangles: $F_3 = 2250$ N at $\bar{x}_3 = 1$ m and $F_4 = 1125$ N at $\bar{x}_4 = 2$ m, yielding the same resultant.

![ch04N-Force-System-Resultants Slide 127](assets/ch04N-Force-System-Resultants/slide-127.png)

---

*Source: [ch04N Force System Resultants.pdf](../course-materials/ch04N%20Force%20System%20Resultants.pdf)*
