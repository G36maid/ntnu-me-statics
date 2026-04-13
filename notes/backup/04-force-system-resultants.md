# Ch04 - Force System Resultants

> Engineering Mechanics: Statics, 14th Edition (SI Units)

## Chapter Objectives

- To discuss the concept of the moment of a force and show how to calculate it in two and three dimensions.
- To provide a method for finding the moment of a force about a specified axis.
- To define the moment of a couple.
- To show how to find the resultant effect of a nonconcurrent force system.
- To indicate how to reduce a simple distributed loading to a resultant force acting at a specified location.

## Chapter Outline

4.1 Moment of a Force – Scalar Formulation
4.2 Cross Product
4.3 Moment of a Force – Vector Formulation
4.4 Principle of Moments
4.5 Moment of a Force about a Specified Axis
4.6 Moment of a Couple
4.7 Simplification of a Force and Couple System
4.8 Further Simplification of a Force and Couple System
4.9 Reduction of a Simple Distributed Loading

---

## 4.1 Moment of a Force – Scalar Formulation

The tendency to rotate is called the **moment of a force** (or simply the **moment**, sometimes called a **torque**).

The magnitude of the moment is directly proportional to:
- The magnitude of $F$
- The perpendicular distance (**moment arm**) $d$

$$\boxed{M_O = Fd}$$

- The larger the force or the longer the moment arm, the greater the moment or turning effect
- If $\theta = 90°$: $d' = d\sin\theta$ → smaller than $d$ → harder to turn
- If force passes through point O: no turning can occur

### Magnitude and Direction

**Magnitude:**
- $d$ = the moment arm or perpendicular distance
- Units: N·m

**Direction:**
- Defined by its moment axis, which is perpendicular to the plane containing force $F$ and moment arm $d$
- Determined by the **right-hand rule**

### Resultant Moment

$$(M_R)_O = \text{algebraic sum of the moments caused by all the forces}$$

- **Positive** moments: counterclockwise (out of the page)
- **Negative** moments: clockwise (into the page)

---

## 4.2 Cross Product

$$\mathbf{C} = \mathbf{A} \times \mathbf{B}$$

(read as "C equals A cross B")

### Magnitude and Direction

$$C = AB\sin\theta$$

**Direction:** Right-hand rule — curling the fingers from $\mathbf{A}$ to $\mathbf{B}$, the thumb points in the direction of $\mathbf{C}$.

$$\mathbf{C} = (AB\sin\theta)\,\mathbf{u_C}$$

### Laws of Operations

1. **Commutative law is NOT valid:**

$$\mathbf{A} \times \mathbf{B} \neq \mathbf{B} \times \mathbf{A}$$

Rather: $\mathbf{A} \times \mathbf{B} = -\mathbf{B} \times \mathbf{A}$

2. **Multiplied by a scalar (associative law):**

$$a(\mathbf{A} \times \mathbf{B}) = (a\mathbf{A}) \times \mathbf{B} = \mathbf{A} \times (a\mathbf{B})$$

3. **Distributive law:**

$$\mathbf{A} \times (\mathbf{B} + \mathbf{D}) = (\mathbf{A} \times \mathbf{B}) + (\mathbf{A} \times \mathbf{D})$$

### Cartesian Vector Formulation

Using $C = AB\sin\theta$ on pairs of Cartesian unit vectors:

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

**Cross product of vectors $\mathbf{A}$ and $\mathbf{B}$:**

$$\mathbf{A} \times \mathbf{B} = (A_yB_z - A_zB_y)\,\mathbf{i} - (A_xB_z - A_zB_x)\,\mathbf{j} + (A_xB_y - A_yB_x)\,\mathbf{k}$$

**Determinant form:**

$$\mathbf{A} \times \mathbf{B} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ A_x & A_y & A_z \\ B_x & B_y & B_z \end{vmatrix}$$

---

## 4.3 Moment of a Force – Vector Formulation

Moment of force $\mathbf{F}$ about point $O$ can be expressed using the cross product:

$$\boxed{\mathbf{M_O} = \mathbf{r} \times \mathbf{F}}$$

where $\mathbf{r}$ represents a position vector from $O$ to any point on the line of action of $\mathbf{F}$.

### Magnitude

$$M_O = rF\sin\theta$$

where $\theta$ is the angle measured between tails of $\mathbf{r}$ and $\mathbf{F}$.

Since $d = r\sin\theta$:

$$M_O = rF\sin\theta = F(r\sin\theta) = Fd$$

### Direction

Direction and sense of $\mathbf{M_O}$ are determined by the right-hand rule:
- Extend $\mathbf{r}$ to the dashed position
- Curl fingers from $\mathbf{r}$ towards $\mathbf{F}$
- Direction of $\mathbf{M_O}$ is the same as the direction of the thumb

> Maintain proper order of $\mathbf{r} \times \mathbf{F}$ since cross product is not commutative.

### Principle of Transmissibility

$\mathbf{F}$ can be applied at any point along its line of action, creating the same moment about $O$. $\mathbf{F}$ can be considered a **sliding vector**.

$$\mathbf{M_O} = \mathbf{r_1} \times \mathbf{F} = \mathbf{r_2} \times \mathbf{F} = \mathbf{r_3} \times \mathbf{F}$$

### Cartesian Vector Formulation

$$\mathbf{M_O} = \mathbf{r} \times \mathbf{F} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ r_x & r_y & r_z \\ F_x & F_y & F_z \end{vmatrix}$$

$$= (r_yF_z - r_zF_y)\,\mathbf{i} - (r_xF_z - r_zF_x)\,\mathbf{j} + (r_xF_y - r_yF_x)\,\mathbf{k}$$

Once $\mathbf{M_O}$ is determined, it is always **perpendicular** to the plane containing $\mathbf{r}$ and $\mathbf{F}$.

### Resultant Moment of a System of Forces

$$(\mathbf{M_R})_O = \sum (\mathbf{r} \times \mathbf{F})$$

---

## 4.4 Principle of Moments

### Varignon's Theorem

> "The moment of a force about a point is equal to the sum of the moments of the components of the force about the point."

For $\mathbf{F} = \mathbf{F_1} + \mathbf{F_2}$:

$$\mathbf{M_O} = \mathbf{r} \times \mathbf{F} = \mathbf{r} \times (\mathbf{F_1} + \mathbf{F_2}) = \mathbf{r} \times \mathbf{F_1} + \mathbf{r} \times \mathbf{F_2}$$

For two-dimensional problems:

$$M_O = F_x y - F_y x$$

> This method is often easier than $M_O = Fd$.

---

## 4.5 Moment of a Force about a Specified Axis

Sometimes, a specified axis must be determined. For example, loosening a car tire: the nut can only rotate about the y axis — only the y component of the moment is needed.

### Scalar Analysis

$$M_y = Fd_y = F(d\cos\theta)$$

In general:

$$\boxed{M_a = Fd_a}$$

### Vector Analysis

To find the moment of force $\mathbf{F}$: use $\mathbf{M_O} = \mathbf{r} \times \mathbf{F}$

The projection of $\mathbf{M_O}$ onto the $a$ axis (scalar triple product):

$$\boxed{M_a = \mathbf{u_a} \cdot (\mathbf{r} \times \mathbf{F}) = \begin{vmatrix} u_{a_x} & u_{a_y} & u_{a_z} \\ r_x & r_y & r_z \\ F_x & F_y & F_z \end{vmatrix}}$$

where $\mathbf{u_a}$ is the unit vector defining the direction of the $a$ axis.

**Sign interpretation:**
- $M_a$ positive → same sense as $\mathbf{u_a}$
- $M_a$ negative → opposite sense to $\mathbf{u_a}$

Express $M_a$ as a Cartesian vector:

$$\mathbf{M_a} = M_a\,\mathbf{u_a} = [\mathbf{u_a} \cdot (\mathbf{r} \times \mathbf{F})]\,\mathbf{u_a}$$

---

## 4.6 Moment of a Couple

### Definition

A **couple** consists of:
- Two parallel forces
- Same magnitude but opposite direction
- Separated by perpendicular distance $d$

Properties:
- Resultant force = 0
- Tendency to rotate in a specified direction
- Couple moment = sum of moments of both couple forces about any arbitrary point

$$\mathbf{M} = \mathbf{r} \times \mathbf{F}$$

where $\mathbf{r}$ is directed between the forces.

> A couple moment is a **free vector** — it can act at any point since $\mathbf{M}$ depends only on the position vector $\mathbf{r}$ directed between forces.

### Scalar Formulation

$$M = Fd$$

- Direction and sense determined by right-hand rule
- In all cases, $\mathbf{M}$ acts perpendicular to the plane containing the forces

### Vector Formulation

$$\mathbf{M} = \mathbf{r} \times \mathbf{F}$$

If moments are taken about point $A$, the moment of $-\mathbf{F}$ is zero about this point.

### Equivalent Couples

If two couples produce a moment with the same magnitude and direction, they are **equivalent**.

Example:
- $M = 30\text{N}(0.4\text{m}) = 12\text{ N·m}$
- $M = 40\text{N}(0.3\text{m}) = 12\text{ N·m}$

→ Equivalent couples.

### Resultant Couple Moment

Since couple moments are free vectors, their resultant can be determined by vector addition:

$$\mathbf{M_R} = \mathbf{M_1} + \mathbf{M_2}$$

For more than two couple moments:

$$\mathbf{M_R} = \sum (\mathbf{r} \times \mathbf{F})$$

---

## 4.7 Simplification of a Force and Couple System

To reduce a system of forces and couple moments to a simpler form by replacing it with an **equivalent system**.

An equivalent system has the same **external effects** (translating and rotating motion of the body, or reactive forces at supports if the body is held fixed) as the original.

### Principle of Transmissibility

A force acting on a body is a **sliding vector** since it can be applied at any point along its line of action.

### Moving a Force Off Its Line of Action

If $\mathbf{F}$ is not on the line of action (perpendicular):
- Attach $\mathbf{F}$ and $-\mathbf{F}$ at the new point $B$
- The couple moment: $M = Fd$
- Result: A force $\mathbf{F}$ and a clockwise couple moment $M$

### Equivalent System at Point O

For several forces and couple moments → an equivalent single resultant force at point $O$:

$$\mathbf{F_R} = \sum \mathbf{F} = \mathbf{F_1} + \mathbf{F_2}$$

$$(\mathbf{M_R})_O = \sum \mathbf{M} + \sum (\mathbf{M_O})_i$$

**Key properties:**
- $\mathbf{F_R}$ is **independent** of the location of point $O$
- $(\mathbf{M_R})_O$ **depends** on the location of point $O$
- $(\mathbf{M_R})_O$ is a **free vector** and can act at any point on the body

### Coplanar Force and Couple System

If the force system lies on the x-y plane and any couple moments are perpendicular to this plane:

$$(F_R)_x = \sum F_x, \quad (F_R)_y = \sum F_y$$

$$(M_R)_O = \sum M_O + \sum M$$

---

## 4.8 Further Simplification of a Force and Couple System

If $\mathbf{F_R}$ and $(\mathbf{M_R})_O$ are **perpendicular**: the force system can be further reduced to an equivalent force.

Because of this condition, only **concurrent**, **coplanar**, and **parallel** force systems can be further simplified.

### Concurrent Force System

Lines of action of all the forces intersect at a common point $O$.

$$\mathbf{F_R} = \sum \mathbf{F}$$

### Coplanar Force System

Lines of action of all the forces and the resultant force $\mathbf{F_R} = \sum \mathbf{F}$ lie in the same plane.

$(\mathbf{M_R})_O$ and $\mathbf{F_R}$ are mutually perpendicular.

$$(M_R)_O = F_R d = \sum M_O$$

$$d = \frac{(M_R)_O}{F_R}$$

### Parallel Force System

Forces and the resultant force $\mathbf{F_R} = \sum \mathbf{F}$ at point $O$ are all parallel.

$$(M_R)_O = F_R d = \sum M_O$$

$$d = \frac{(M_R)_O}{F_R}$$

### Reduction to a Wrench

For 3-D force and couple moment systems where $(\mathbf{M_R})_O$ is **not perpendicular** to $\mathbf{F_R}$:

1. Resolve $(\mathbf{M_R})_O$ into $\mathbf{M_\perp}$ and $\mathbf{M_\parallel}$
2. Move $\mathbf{F_R}$ to point $P$ where $\mathbf{M_\perp}$ can be replaced
3. $\mathbf{M_\parallel}$ is a free vector, it can be moved to $P$
4. The combination of $\mathbf{F_R}$ and $\mathbf{M_\parallel}$ tends to translate and rotate the body about its axis → acts as a **wrench** (or screw)

---

## 4.9 Reduction of a Simple Distributed Loading

A body may be subjected to a loading that is distributed over its surface. The pressure exerted at each point on the surface indicates the **intensity** of the loading.

- Units: pascals (Pa) or N/m²

### Loading Along a Single Axis

Most common type of distributed loading — along a single axis.

- Constant width $b$, pressure loading varies only along the x axis: $p = p(x)$ N/m²
- Coplanar distributed load: $w(x) = p(x) \cdot b$ N/m
- Replace with a single equivalent resultant force $\mathbf{F_R}$

### Magnitude of Resultant Force

Magnitude of $d\mathbf{F}$ is determined from differential area $dA$ under the loading curve. For length $L$:

$$\boxed{F_R = \sum F = \int_L dA = \int_0^L w(x)\,dx = A}$$

> The magnitude of the resultant force is equal to the total **area $A$** under the loading diagram.

### Location of Resultant Force

$$\bar{x} = \frac{\int_0^L x\,w(x)\,dx}{\int_0^L w(x)\,dx} = \frac{\int_A x\,dA}{\int_A dA}$$

> The resultant force acts through the **centroid** of the loading diagram area.

---

*Source: [ch04N Force System Resultants.pdf](../course-materials/ch04N%20Force%20System%20Resultants.pdf)*
