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

![ch04N-Force-System-Resultants Slide 013](assets/ch04N-Force-System-Resultants/slide-013.png)

**Example:**

$$(M_R)_O = F_1 d_1 - F_2 d_2 + F_3 d_3$$

![ch04N-Force-System-Resultants Slide 014](assets/ch04N-Force-System-Resultants/slide-014.png)

![ch04N-Force-System-Resultants Slide 015](assets/ch04N-Force-System-Resultants/slide-015.png)

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

![ch04N-Force-System-Resultants Slide 034](assets/ch04N-Force-System-Resultants/slide-034.png)

$$= (r_yF_z - r_zF_y)\,\mathbf{i} - (r_xF_z - r_zF_x)\,\mathbf{j} + (r_xF_y - r_yF_x)\,\mathbf{k}$$

Once $\mathbf{M_O}$ is determined, it is always **perpendicular** to the plane containing $\mathbf{r}$ and $\mathbf{F}$.

### Resultant Moment of a System of Forces

![ch04N-Force-System-Resultants Slide 035](assets/ch04N-Force-System-Resultants/slide-035.png)

Resultant moment of the forces about point $O$ can be determined by vector addition of the moment of each force:

$$(\mathbf{M_R})_O = \sum (\mathbf{r} \times \mathbf{F})$$

![ch04N-Force-System-Resultants Slide 036](assets/ch04N-Force-System-Resultants/slide-036.png)

![ch04N-Force-System-Resultants Slide 037](assets/ch04N-Force-System-Resultants/slide-037.png)

---

## 4.4 Principle of Moments

### Varignon's Theorem

![ch04N-Force-System-Resultants Slide 038](assets/ch04N-Force-System-Resultants/slide-038.png)

![ch04N-Force-System-Resultants Slide 039](assets/ch04N-Force-System-Resultants/slide-039.png)

![ch04N-Force-System-Resultants Slide 040](assets/ch04N-Force-System-Resultants/slide-040.png)

![ch04N-Force-System-Resultants Slide 041](assets/ch04N-Force-System-Resultants/slide-041.png)

![ch04N-Force-System-Resultants Slide 042](assets/ch04N-Force-System-Resultants/slide-042.png)

> "The moment of a force about a point is equal to the sum of the moments of the components of the force about the point."

For $\mathbf{F} = \mathbf{F_1} + \mathbf{F_2}$:

$$\mathbf{M_O} = \mathbf{r} \times \mathbf{F} = \mathbf{r} \times (\mathbf{F_1} + \mathbf{F_2}) = \mathbf{r} \times \mathbf{F_1} + \mathbf{r} \times \mathbf{F_2}$$

![ch04N-Force-System-Resultants Slide 043](assets/ch04N-Force-System-Resultants/slide-043.png)

For two-dimensional problems:

$$M_O = F_x y - F_y x$$

> This method is often easier than $M_O = Fd$.

![ch04N-Force-System-Resultants Slide 044](assets/ch04N-Force-System-Resultants/slide-044.png)

![ch04N-Force-System-Resultants Slide 045](assets/ch04N-Force-System-Resultants/slide-045.png)

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

![ch04N-Force-System-Resultants Slide 053](assets/ch04N-Force-System-Resultants/slide-053.png)

To find the moment of force $\mathbf{F}$: use $\mathbf{M_O} = \mathbf{r} \times \mathbf{F}$

$M_y$ along the $y$ axis is the projection of $\mathbf{M_O}$, using the dot product:

$$M_y = \mathbf{j} \cdot \mathbf{M_O} = \mathbf{j} \cdot (\mathbf{r} \times \mathbf{F})$$

where $\mathbf{j}$ is the unit vector for the $y$ axis.

![ch04N-Force-System-Resultants Slide 054](assets/ch04N-Force-System-Resultants/slide-054.png)

Let $\mathbf{u_a}$ be the unit vector defining the direction of the $a$ axis. The projection of the moment onto the $a$ axis (scalar triple product):

$$\boxed{M_a = \mathbf{u_a} \cdot (\mathbf{r} \times \mathbf{F}) = \begin{vmatrix} u_{a_x} & u_{a_y} & u_{a_z} \\ r_x & r_y & r_z \\ F_x & F_y & F_z \end{vmatrix}}$$

![ch04N-Force-System-Resultants Slide 055](assets/ch04N-Force-System-Resultants/slide-055.png)

$$M_a = \mathbf{u_a} \cdot (\mathbf{r} \times \mathbf{F}) = u_{a_x}(r_yF_z - r_zF_y) - u_{a_y}(r_xF_z - r_zF_x) + u_{a_z}(r_xF_y - r_yF_x)$$

**Sign interpretation:**
- $M_a$ positive -- same sense as $\mathbf{u_a}$
- $M_a$ negative -- opposite sense to $\mathbf{u_a}$

![ch04N-Force-System-Resultants Slide 056](assets/ch04N-Force-System-Resultants/slide-056.png)

Express $M_a$ as a Cartesian vector:

$$\mathbf{M_a} = M_a\,\mathbf{u_a} = [\mathbf{u_a} \cdot (\mathbf{r} \times \mathbf{F})]\,\mathbf{u_a}$$

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

![ch04N-Force-System-Resultants Slide 067](assets/ch04N-Force-System-Resultants/slide-067.png)

If two couples produce a moment with the same magnitude and direction, they are **equivalent**.

![ch04N-Force-System-Resultants Slide 068](assets/ch04N-Force-System-Resultants/slide-068.png)

Example:
- $M = 30\text{ N}(0.4\text{ m}) = 12\text{ N}\cdot\text{m}$
- $M = 40\text{ N}(0.3\text{ m}) = 12\text{ N}\cdot\text{m}$

Equivalent couples.

### Resultant Couple Moment

![ch04N-Force-System-Resultants Slide 069](assets/ch04N-Force-System-Resultants/slide-069.png)

Since couple moments are free vectors, their resultant can be determined by vector addition:

$$\mathbf{M_R} = \mathbf{M_1} + \mathbf{M_2}$$

For more than two couple moments:

$$\mathbf{M_R} = \sum (\mathbf{r} \times \mathbf{F})$$

![ch04N-Force-System-Resultants Slide 070](assets/ch04N-Force-System-Resultants/slide-070.png)

![ch04N-Force-System-Resultants Slide 071](assets/ch04N-Force-System-Resultants/slide-071.png)

![ch04N-Force-System-Resultants Slide 072](assets/ch04N-Force-System-Resultants/slide-072.png)

![ch04N-Force-System-Resultants Slide 073](assets/ch04N-Force-System-Resultants/slide-073.png)

![ch04N-Force-System-Resultants Slide 074](assets/ch04N-Force-System-Resultants/slide-074.png)

![ch04N-Force-System-Resultants Slide 075](assets/ch04N-Force-System-Resultants/slide-075.png)

---

## 4.7 Simplification of a Force and Couple System

![ch04N-Force-System-Resultants Slide 076](assets/ch04N-Force-System-Resultants/slide-076.png)

![ch04N-Force-System-Resultants Slide 077](assets/ch04N-Force-System-Resultants/slide-077.png)

![ch04N-Force-System-Resultants Slide 078](assets/ch04N-Force-System-Resultants/slide-078.png)

![ch04N-Force-System-Resultants Slide 079](assets/ch04N-Force-System-Resultants/slide-079.png)

![ch04N-Force-System-Resultants Slide 080](assets/ch04N-Force-System-Resultants/slide-080.png)

![ch04N-Force-System-Resultants Slide 081](assets/ch04N-Force-System-Resultants/slide-081.png)

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

![ch04N-Force-System-Resultants Slide 086](assets/ch04N-Force-System-Resultants/slide-086.png)

$$(\mathbf{M_R})_O = \sum \mathbf{M} + \sum (\mathbf{M_O})_i$$

![ch04N-Force-System-Resultants Slide 087](assets/ch04N-Force-System-Resultants/slide-087.png)

**Key properties:**
- $\mathbf{F_R}$ is **independent** of the location of point $O$
- $(\mathbf{M_R})_O$ **depends** on the location of point $O$ since $M_1$ and $M_2$ are determined using position vectors $\mathbf{r_1}$ and $\mathbf{r_2}$
- $(\mathbf{M_R})_O$ is a **free vector** and can act at any point on the body

### Coplanar Force and Couple System

![ch04N-Force-System-Resultants Slide 088](assets/ch04N-Force-System-Resultants/slide-088.png)

If the force system lies on the $x$-$y$ plane and any couple moments are perpendicular to this plane:

$$(F_R)_x = \sum F_x, \quad (F_R)_y = \sum F_y$$

$$(M_R)_O = \sum M_O + \sum M$$

### Procedure for Analysis

![ch04N-Force-System-Resultants Slide 089](assets/ch04N-Force-System-Resultants/slide-089.png)

![ch04N-Force-System-Resultants Slide 090](assets/ch04N-Force-System-Resultants/slide-090.png)

![ch04N-Force-System-Resultants Slide 091](assets/ch04N-Force-System-Resultants/slide-091.png)

![ch04N-Force-System-Resultants Slide 092](assets/ch04N-Force-System-Resultants/slide-092.png)

![ch04N-Force-System-Resultants Slide 093](assets/ch04N-Force-System-Resultants/slide-093.png)

---

## 4.8 Further Simplification of a Force and Couple System

![ch04N-Force-System-Resultants Slide 094](assets/ch04N-Force-System-Resultants/slide-094.png)

![ch04N-Force-System-Resultants Slide 095](assets/ch04N-Force-System-Resultants/slide-095.png)

![ch04N-Force-System-Resultants Slide 096](assets/ch04N-Force-System-Resultants/slide-096.png)

![ch04N-Force-System-Resultants Slide 097](assets/ch04N-Force-System-Resultants/slide-097.png)

![ch04N-Force-System-Resultants Slide 098](assets/ch04N-Force-System-Resultants/slide-098.png)

![ch04N-Force-System-Resultants Slide 099](assets/ch04N-Force-System-Resultants/slide-099.png)

![ch04N-Force-System-Resultants Slide 100](assets/ch04N-Force-System-Resultants/slide-100.png)

If $\mathbf{F_R}$ and $(\mathbf{M_R})_O$ are **perpendicular**: the force system can be further reduced to an equivalent force.

Because of this condition, only **concurrent**, **coplanar**, and **parallel** force systems can be further simplified.

### Concurrent Force System

![ch04N-Force-System-Resultants Slide 101](assets/ch04N-Force-System-Resultants/slide-101.png)

Lines of action of all the forces intersect at a common point $O$.

$$\mathbf{F_R} = \sum \mathbf{F}$$

### Coplanar Force System

![ch04N-Force-System-Resultants Slide 102](assets/ch04N-Force-System-Resultants/slide-102.png)

Lines of action of all the forces and the resultant force $\mathbf{F_R} = \sum \mathbf{F}$ lie in the same plane.

$(\mathbf{M_R})_O$ and $\mathbf{F_R}$ are mutually perpendicular.

$$(M_R)_O = F_R d = \sum M_O$$

$$d = \frac{(M_R)_O}{F_R}$$

### Parallel Force System

![ch04N-Force-System-Resultants Slide 103](assets/ch04N-Force-System-Resultants/slide-103.png)

Forces and the resultant force $\mathbf{F_R} = \sum \mathbf{F}$ at point $O$ are all parallel.

$$(M_R)_O = F_R d = \sum M_O$$

$$d = \frac{(M_R)_O}{F_R}$$

### Procedure for Analysis

![ch04N-Force-System-Resultants Slide 104](assets/ch04N-Force-System-Resultants/slide-104.png)

![ch04N-Force-System-Resultants Slide 105](assets/ch04N-Force-System-Resultants/slide-105.png)

### Reduction to a Wrench

![ch04N-Force-System-Resultants Slide 106](assets/ch04N-Force-System-Resultants/slide-106.png)

For 3-D force and couple moment systems where $(\mathbf{M_R})_O$ is **not perpendicular** to $\mathbf{F_R}$:

1. Resolve $(\mathbf{M_R})_O$ into $\mathbf{M_\perp}$ and $\mathbf{M_\parallel}$
2. Move $\mathbf{F_R}$ to point $P$ where $\mathbf{M_\perp}$ can be replaced
3. $\mathbf{M_\parallel}$ is a free vector, it can be moved to $P$

![ch04N-Force-System-Resultants Slide 107](assets/ch04N-Force-System-Resultants/slide-107.png)

4. The combination of $\mathbf{F_R}$ and $\mathbf{M_\parallel}$ tends to translate and rotate the body about its axis -- acts as a **wrench** (or screw)

![ch04N-Force-System-Resultants Slide 108](assets/ch04N-Force-System-Resultants/slide-108.png)

![ch04N-Force-System-Resultants Slide 109](assets/ch04N-Force-System-Resultants/slide-109.png)

![ch04N-Force-System-Resultants Slide 110](assets/ch04N-Force-System-Resultants/slide-110.png)

![ch04N-Force-System-Resultants Slide 111](assets/ch04N-Force-System-Resultants/slide-111.png)

![ch04N-Force-System-Resultants Slide 112](assets/ch04N-Force-System-Resultants/slide-112.png)

![ch04N-Force-System-Resultants Slide 113](assets/ch04N-Force-System-Resultants/slide-113.png)

---

## 4.9 Reduction of a Simple Distributed Loading

![ch04N-Force-System-Resultants Slide 114](assets/ch04N-Force-System-Resultants/slide-114.png)

![ch04N-Force-System-Resultants Slide 115](assets/ch04N-Force-System-Resultants/slide-115.png)

![ch04N-Force-System-Resultants Slide 116](assets/ch04N-Force-System-Resultants/slide-116.png)

![ch04N-Force-System-Resultants Slide 117](assets/ch04N-Force-System-Resultants/slide-117.png)

![ch04N-Force-System-Resultants Slide 118](assets/ch04N-Force-System-Resultants/slide-118.png)

A body may be subjected to a loading that is distributed over its surface. The pressure exerted at each point on the surface indicates the **intensity** of the loading.

- Units: pascals (Pa) or N/m$^2$

### Loading Along a Single Axis

![ch04N-Force-System-Resultants Slide 119](assets/ch04N-Force-System-Resultants/slide-119.png)

Most common type of distributed loading -- along a single axis.
- Constant width $b$, pressure loading varies only along the $x$ axis: $p = p(x)$ N/m$^2$
- Only one variable $x$

![ch04N-Force-System-Resultants Slide 120](assets/ch04N-Force-System-Resultants/slide-120.png)

- Coplanar distributed load: $w(x) = p(x) \cdot b$ N/m
- Replace coplanar parallel force system with a single equivalent resultant force $\mathbf{F_R}$

### Magnitude of Resultant Force

![ch04N-Force-System-Resultants Slide 121](assets/ch04N-Force-System-Resultants/slide-121.png)

Magnitude of $d\mathbf{F}$ is determined from differential area $dA$ under the loading curve. For length $L$:

$$\boxed{F_R = \sum F = \int_L dA = \int_0^L w(x)\,dx = A}$$

> The magnitude of the resultant force is equal to the total **area $A$** under the loading diagram.

### Location of Resultant Force

![ch04N-Force-System-Resultants Slide 122](assets/ch04N-Force-System-Resultants/slide-122.png)

$$\bar{x} = \frac{\int_0^L x\,w(x)\,dx}{\int_0^L w(x)\,dx} = \frac{\int_A x\,dA}{\int_A dA}$$

> The resultant force acts through the **centroid** of the loading diagram area.

![ch04N-Force-System-Resultants Slide 123](assets/ch04N-Force-System-Resultants/slide-123.png)

![ch04N-Force-System-Resultants Slide 124](assets/ch04N-Force-System-Resultants/slide-124.png)

![ch04N-Force-System-Resultants Slide 125](assets/ch04N-Force-System-Resultants/slide-125.png)

![ch04N-Force-System-Resultants Slide 126](assets/ch04N-Force-System-Resultants/slide-126.png)

![ch04N-Force-System-Resultants Slide 127](assets/ch04N-Force-System-Resultants/slide-127.png)

---

*Source: [ch04N Force System Resultants.pdf](../course-materials/ch04N%20Force%20System%20Resultants.pdf)*
