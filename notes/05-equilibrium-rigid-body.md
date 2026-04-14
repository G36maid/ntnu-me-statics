# Ch05 - Equilibrium of a Rigid Body

> Engineering Mechanics: Statics, 14th Edition (SI Units)

### Section Boundaries

| Section | Title | Start Slide | End Slide |
|:-------:|:------|:-----------:|:---------:|
| — | Title / Objectives / Outline | 001 | 003 |
| 5.1 | Conditions for Rigid-Body Equilibrium | 004 | 007 |
| 5.2 | Free-Body Diagrams | 008 | 039 |
| 5.3 | Equations of Equilibrium | 040 | 067 |
| 5.4 | Two- and Three-Force Members | 068 | 077 |
| 5.5 | Free-Body Diagrams (3D) | 078 | 091 |
| 5.6 | Equations of Equilibrium (3D) | 092 | 094 |
| 5.7 | Constraints and Statical Determinacy | 095 | 117 |

---

![ch05-Equilibrium-of-a-Rigid-Body Slide 01](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-001.png)

---

## Chapter Objectives

![ch05-Equilibrium-of-a-Rigid-Body Slide 02](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-002.png)

- To develop the equations of equilibrium for a rigid body.
- To introduce the concept of the free-body diagram for a rigid body.
- To show how to solve rigid-body equilibrium problems using the equations of equilibrium.

## Chapter Outline

![ch05-Equilibrium-of-a-Rigid-Body Slide 03](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-003.png)

5.1 Conditions for Rigid-Body Equilibrium
5.2 Free-Body Diagrams
5.3 Equations of Equilibrium
5.4 Two- and Three-Force Members
5.5 Free-Body Diagrams
5.6 Equations of Equilibrium
5.7 Constraints and Statical Determinacy

---

## 5.1 Conditions for Rigid-Body Equilibrium

![ch05-Equilibrium-of-a-Rigid-Body Slide 04](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-004.png)

The equilibrium of a rigid body is determined by the **external forces and couple moments** acting upon it, including:

- Gravitational forces
- Electrical forces
- Magnetic forces
- Contact forces

**Internal forces** act between particles within the body. By Newton's third law, these internal forces occur in equal and opposite collinear pairs and therefore cancel out when considering the entire rigid body.

![ch05-Equilibrium-of-a-Rigid-Body Slide 05](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-005.png)

For a rigid body to be in equilibrium, the resultant force and the resultant couple moment must both be zero:

$$\mathbf{F}_R = \sum \mathbf{F} = 0$$

$$(\mathbf{M}_R)_O = \sum \mathbf{M}_O = 0$$

![ch05-Equilibrium-of-a-Rigid-Body Slide 06](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-006.png)

Consider summing moments about some other point, such as point $A$:

$$\sum \mathbf{M}_A = \mathbf{r} \times \mathbf{F}_R + (\mathbf{M}_R)_O = 0$$

Since $\mathbf{F}_R = 0$ and $(\mathbf{M}_R)_O = 0$, it follows that $\sum \mathbf{M}_A = 0$.

![ch05-Equilibrium-of-a-Rigid-Body Slide 07](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-007.png)

### Equilibrium in Two Dimensions

When the force system acting on a body is coplanar (2D), the equilibrium conditions simplify. Any couple moments acting on the body are perpendicular to the plane of the forces.

---

## 5.2 Free-Body Diagrams

![ch05-Equilibrium-of-a-Rigid-Body Slide 08](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-008.png)

A **free-body diagram (FBD)** is a sketch of the outlined shape of the body, which represents it being isolated from its surroundings. It is necessary to show all the forces and couple moments that the surroundings exert on the body so that these effects can be accounted for when the equations of equilibrium are applied.

### Support Reactions

![ch05-Equilibrium-of-a-Rigid-Body Slide 09](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-009.png)

- A support prevents the **translation** of a body in a given direction by exerting a **force** on the body in the opposite direction.
- A support prevents the **rotation** of a body in a given direction by exerting a **couple moment** on the body in the opposite direction.

Consider the three ways a horizontal member (beam) is supported at the end: roller/cylinder, pin, and fixed support.

![ch05-Equilibrium-of-a-Rigid-Body Slide 10](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-010.png)

**Roller / Cylinder** -- Prevents the beam from translating in the vertical direction. The reaction is a single force vector acting perpendicular to the surface at the point of contact.

![ch05-Equilibrium-of-a-Rigid-Body Slide 11](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-011.png)

**Pin** -- Prevents translation of the beam in any direction $\phi$ but allows rotation. The reaction can be represented as:
1. A single force $\mathbf{F}$ with unknown magnitude and unknown angle $\phi$, or
2. Two rectangular force components: horizontal $\mathbf{F}_x$ and vertical $\mathbf{F}_y$

![ch05-Equilibrium-of-a-Rigid-Body Slide 12](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-012.png)

**Fixed Support** -- Prevents both translation and rotation. The support exerts three reactions on the member:
- Two force components: $F_x$ (horizontal) and $F_y$ (vertical)
- A couple moment: $M$

### Table 5-1: Supports for Rigid Bodies Subjected to Two-Dimensional Force Systems

![ch05-Equilibrium-of-a-Rigid-Body Slide 13](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-013.png)

| Type of Connection | Reaction | Number of Unknowns |
|:---|:---|:---|
| (1) Cable | Force $\mathbf{F}$ acts away from the member in the direction of the cable | 1 |
| (2) Weightless link | Force $\mathbf{F}$ acts along the axis of the link | 1 |
| (3) Roller | Force $\mathbf{F}$ acts perpendicular to the surface at the point of contact | 1 |

![ch05-Equilibrium-of-a-Rigid-Body Slide 14](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-014.png)

| Type of Connection | Reaction | Number of Unknowns |
|:---|:---|:---|
| (4) Rocker | Force $\mathbf{F}$ acts perpendicular to the surface at the point of contact | 1 |
| (5) Smooth contacting surface | Force $\mathbf{F}$ acts perpendicular to the surface at the point of contact | 1 |

![ch05-Equilibrium-of-a-Rigid-Body Slide 15](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-015.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 16](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-016.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 17](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-017.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 18](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-018.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 19](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-019.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 20](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-020.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 21](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-021.png)

### Internal Forces

Internal forces act between particles within the body. By Newton's third law, these internal forces occur in equal and opposite collinear pairs and therefore cancel each other. Internal forces should **not** be included on the FBD. Only external forces (e.g., $T_1$, $T_2$, and $W$) appear on the FBD.

### Weight and the Center of Gravity

![ch05-Equilibrium-of-a-Rigid-Body Slide 22](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-022.png)

- Each particle within a body has a specified weight.
- The system of individual particle weights can be reduced to a single resultant force -- the total weight $W$ of the body.
- The location where this resultant weight force is applied is known as the **center of gravity**.

![ch05-Equilibrium-of-a-Rigid-Body Slide 23](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-023.png)

- When the body is uniform or made from the same material, the center of gravity will be located at the body's **geometric center** or **centroid**.
- For non-homogeneous bodies and unusual shapes, the center of gravity $G$ will be given.

![ch05-Equilibrium-of-a-Rigid-Body Slide 24](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-024.png)

### Idealized Models

![ch05-Equilibrium-of-a-Rigid-Body Slide 25](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-025.png)

- Needed to perform a correct force analysis of any object.
- Careful selection of supports, material, behavior, and dimensions is required for reliable results.
- Complex cases may require developing several different models for analysis.

![ch05-Equilibrium-of-a-Rigid-Body Slide 26](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-026.png)

**Case 1 -- Steel beam supporting roof joists:**

- For force analysis, it is reasonable to assume the beam is a rigid body since only small deflections occur when the beam is loaded.
- A bolted connection at $A$ that allows for slight rotation is modeled as a **pin**.
- The support at $B$ offers no resistance to horizontal movement, so it is modeled as a **roller**.

![ch05-Equilibrium-of-a-Rigid-Body Slide 27](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-027.png)

Additional modeling considerations:
- Building code requirements are used to specify the roof loading (calculations of the joist forces).
- Large roof loading forces account for extreme loading cases and dynamic or vibration effects.
- The weight of the body is neglected when it is small compared to the loads the member supports.

![ch05-Equilibrium-of-a-Rigid-Body Slide 28](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-028.png)

**Case 2 -- Lift boom:**

- Consider a lift boom supported by a pin at $A$ and a hydraulic cylinder at $BC$ (treat as weightless link).
- Assume rigid material with density known.
- For design loading $P$, the idealized model is used for force analysis.
- Average dimensions are used to specify the location of the loads and supports.

![ch05-Equilibrium-of-a-Rigid-Body Slide 29](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-029.png)

### Procedure for Drawing a Free-Body Diagram

1. **Draw Outlined Shape** -- Isolate the body from its surroundings and draw its outlined shape.
2. **Show All Forces and Couple Moments** -- Indicate all external forces and couple moments acting on the body.
3. **Label Known Forces** -- Identify magnitudes and directions of all known forces.
4. **Represent Unknown Forces** -- Use letters to represent unknown magnitudes and direction angles.
5. **Establish Coordinate System** -- Set up $x$, $y$ axes and indicate necessary dimensions.

---

![ch05-Equilibrium-of-a-Rigid-Body Slide 30](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-030.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 31](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-031.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 32](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-032.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 33](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-033.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 34](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-034.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 35](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-035.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 36](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-036.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 37](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-037.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 38](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-038.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 39](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-039.png)

---

## 5.3 Equations of Equilibrium

![ch05-Equilibrium-of-a-Rigid-Body Slide 40](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-040.png)

For equilibrium of a rigid body in two dimensions (coplanar force system), the following three independent equations must be satisfied:

$$\sum F_x = 0$$

$$\sum F_y = 0$$

$$\sum M_O = 0$$

- $\sum F_x$ and $\sum F_y$ represent the algebraic sums of the $x$ and $y$ components of all the forces acting on the body.
- $\sum M_O$ represents the algebraic sum of the couple moments and the moments of all the force components about an axis perpendicular to the $x$-$y$ plane and passing through arbitrary point $O$ (located either on or off the body).

### Alternative Sets of Equilibrium Equations

![ch05-Equilibrium-of-a-Rigid-Body Slide 41](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-041.png)

Two alternative sets of three independent equilibrium equations can be used:

**Set 1:**

$$\sum F_x = 0; \quad \sum M_A = 0; \quad \sum M_B = 0$$

> Requirement: The line passing through points $A$ and $B$ must not be parallel to the $y$-axis (or perpendicular to the direction of the force summation).

![ch05-Equilibrium-of-a-Rigid-Body Slide 42](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-042.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 43](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-043.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 44](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-044.png)

**Set 2:**

$$\sum M_A = 0; \quad \sum M_B = 0; \quad \sum M_C = 0$$

> Requirement: Points $A$, $B$, and $C$ must not lie on the same straight line.

![ch05-Equilibrium-of-a-Rigid-Body Slide 45](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-045.png)

### Procedure for Analysis

![ch05-Equilibrium-of-a-Rigid-Body Slide 46](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-046.png)

**Free-Body Diagram:**

1. Establish the $x$, $y$ coordinate axes.
2. Draw the outlined shape of the body.
3. Show all forces and couple moments acting on the body.
4. Label the magnitudes and directions of known forces/moments.
5. Show unknown components (e.g., $A_x$, $A_y$) with assumed senses.
6. Indicate dimensions necessary for calculating moments of forces.

![ch05-Equilibrium-of-a-Rigid-Body Slide 47](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-047.png)

**Equations of Equilibrium:**

1. Apply $\sum M_O = 0$ about a point $O$ that intersects the lines of action of as many unknown forces as possible.
2. Orient $x$ and $y$ axes to simplify force equilibrium equations.
3. If the solution for a force yields a negative scalar, the sense is opposite to that assumed on the FBD.

### Examples

![ch05-Equilibrium-of-a-Rigid-Body Slide 48](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-048.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 49](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-049.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 50](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-050.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 51](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-051.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 52](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-052.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 53](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-053.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 54](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-054.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 55](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-055.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 56](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-056.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 57](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-057.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 58](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-058.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 59](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-059.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 60](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-060.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 61](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-061.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 62](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-062.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 63](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-063.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 64](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-064.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 65](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-065.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 66](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-066.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 67](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-067.png)

---

## 5.4 Two- and Three-Force Members


![ch05-Equilibrium-of-a-Rigid-Body Slide 68](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-068.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 69](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-069.png)


Simplify some equilibrium problems by recognizing members that are subjected to only 2 or 3 forces.

![ch05-Equilibrium-of-a-Rigid-Body Slide 70](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-070.png)

### Two-Force Members

![ch05-Equilibrium-of-a-Rigid-Body Slide 71](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-071.png)

A **two-force member** has forces applied at only two points on a member. For equilibrium:

- The two forces must have the **same magnitude**.
- They must act in **opposite directions**.
- They must have the **same line of action**, directed along the line joining the two points where these forces act.

![ch05-Equilibrium-of-a-Rigid-Body Slide 72](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-072.png)

> A hydraulic cylinder $AB$ is a typical example of a two-force member since it is pin connected at its ends and, provided its weight is neglected, only the pin forces act on this member.

### Three-Force Members

![ch05-Equilibrium-of-a-Rigid-Body Slide 73](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-073.png)

If a member is subjected to only three forces, it is called a **three-force member**. When subjected to three forces, the forces must be either:

- **Concurrent** -- the lines of action of the three forces intersect at a single common point $O$, or
- **Parallel** -- the lines of action of the three forces are all parallel to one another.

![ch05-Equilibrium-of-a-Rigid-Body Slide 74](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-074.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 75](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-075.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 76](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-076.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 77](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-077.png)

---

## 5.5 Free-Body Diagrams (3D)

![ch05-Equilibrium-of-a-Rigid-Body Slide 78](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-078.png)

To solve three-dimensional equilibrium problems, a free-body diagram must be drawn. Consider the types of reactions that can occur at the supports.

### Support Reactions

![ch05-Equilibrium-of-a-Rigid-Body Slide 79](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-079.png)

As in the two-dimensional case:

- A **force** is developed by a support that restricts the translation of its attached member.
- A **couple moment** is developed when rotation of the attached member is prevented.

It is important to recognize the symbols used to represent each of these supports and to clearly understand how the forces and couple moments are developed.

![ch05-Equilibrium-of-a-Rigid-Body Slide 80](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-080.png)

**Ball-and-Socket Joint** -- The ball-and-socket joint prevents any translation of the connecting member; therefore, a force must act on the member at the point of connection. This force has unknown components $F_x$, $F_y$, and $F_z$. The magnitude of the force is:

$$F = \sqrt{F_x^2 + F_y^2 + F_z^2}$$

Since the connecting member is allowed to rotate freely about any axis, no couple moment is resisted by a ball-and-socket joint.

![ch05-Equilibrium-of-a-Rigid-Body Slide 81](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-081.png)

The force's orientation is defined by the coordinate angles $\alpha$, $\beta$, and $\gamma$. Single bearing supports, single pin, and single hinge are shown to resist both force and couple-moment components.

![ch05-Equilibrium-of-a-Rigid-Body Slide 82](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-082.png)

However, when these supports are used with other properly aligned bearings, pins, or hinges to hold a rigid body in equilibrium, the force reactions at these supports alone are adequate for supporting the body. Couple moments become redundant and are not shown on the FBD.

### Table 5-2: Supports for Rigid Bodies Subjected to Three-Dimensional Force Systems

![ch05-Equilibrium-of-a-Rigid-Body Slide 83](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-083.png)

| Type of Connection | Reaction | Number of Unknowns |
|:---|:---|:---|
| (1) Cable | Force $\mathbf{F}$ acts away from the member in the known direction of the cable | 1 |
| (2) Smooth surface support | Force $\mathbf{F}$ acts perpendicular to the surface at the point of contact | 1 |

![ch05-Equilibrium-of-a-Rigid-Body Slide 84](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-084.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 85](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-085.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 86](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-086.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 87](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-087.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 88](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-088.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 89](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-089.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 90](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-090.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 91](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-091.png)

---

## 5.6 Equations of Equilibrium (3D)

![ch05-Equilibrium-of-a-Rigid-Body Slide 92](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-092.png)

The resultant force and resultant couple moment must both be zero.

### Vector Equations of Equilibrium

Two conditions for equilibrium of a rigid body in vector form:

$$\sum \mathbf{F} = 0$$

$$\sum \mathbf{M}_O = 0$$

where $\sum \mathbf{F}$ is the vector sum of all the external forces acting on the body, and $\sum \mathbf{M}_O$ is the sum of the couple moments and the moments of all the forces about any point $O$ located either on or off the body.

![ch05-Equilibrium-of-a-Rigid-Body Slide 93](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-093.png)

### Scalar Equations of Equilibrium

If all the applied external forces and couple moments are expressed in Cartesian vector form, the $\mathbf{i}$, $\mathbf{j}$, and $\mathbf{k}$ components are independent from one another. This yields six scalar equations of equilibrium:

**Force components** (the sum of the external force components acting in the $x$, $y$, and $z$ directions must be zero):

$$\sum F_x = 0, \quad \sum F_y = 0, \quad \sum F_z = 0$$

**Moment components** (the sum of the moment components about the $x$, $y$, and $z$ axes must be zero):

$$\sum M_x = 0, \quad \sum M_y = 0, \quad \sum M_z = 0$$

![ch05-Equilibrium-of-a-Rigid-Body Slide 94](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-094.png)

---

## 5.7 Constraints and Statical Determinacy

![ch05-Equilibrium-of-a-Rigid-Body Slide 95](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-095.png)

To ensure the equilibrium of a rigid body, it is necessary to satisfy the equations of equilibrium and have the body properly held or **constrained** by its supports.

### Redundant Constraints

- More supports than needed for equilibrium.
- **Statically indeterminate**: more unknown loadings on the body than equations of equilibrium available for their solution.

![ch05-Equilibrium-of-a-Rigid-Body Slide 96](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-096.png)

**Example (2D):** A beam with a fixed support at $A$ and roller supports at $B$ and $C$ has 5 unknowns ($M_A$, $A_x$, $A_y$, $B_y$, $C_y$) but only 3 equilibrium equations ($\sum F_x = 0$, $\sum F_y = 0$, $\sum M_O = 0$). This system is statically indeterminate.

![ch05-Equilibrium-of-a-Rigid-Body Slide 97](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-097.png)

**Example (3D):** In 3D, there can be 8 unknowns but only 6 equilibrium equations. Additional equations involving the physical properties of the body are needed to solve indeterminate problems.

### Improper Constraints

![ch05-Equilibrium-of-a-Rigid-Body Slide 98](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-098.png)

Having the same number of unknown reactive forces as available equations of equilibrium does **not** always guarantee that a body will be stable when subjected to a particular loading.

**Concurrent Forces:** If the lines of action of all reactive forces are concurrent at a single point $A$, a loading $P$ will cause the beam to rotate about that point ($\sum M_A \neq 0$), leading to instability. The beam is **improperly constrained**.

![ch05-Equilibrium-of-a-Rigid-Body Slide 99](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-099.png)

In 3D, a body will be improperly constrained if the lines of action of all the reactive forces intersect a common axis.

![ch05-Equilibrium-of-a-Rigid-Body Slide 100](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-100.png)

**Example:** The reactive forces at ball-and-socket supports at $A$ and $B$ all intersect the axis passing through $A$ and $B$. Since the moments of these forces about $A$ and $B$ are all zero, the loading $P$ will rotate the member about the $AB$ axis ($\sum M_{AB} \neq 0$).

![ch05-Equilibrium-of-a-Rigid-Body Slide 101](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-101.png)

**Parallel Forces:** If the reactive forces are all parallel, the summation of forces along a perpendicular axis will not equal zero. This also results in improper constraint.

![ch05-Equilibrium-of-a-Rigid-Body Slide 102](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-102.png)

### Partially Constrained

![ch05-Equilibrium-of-a-Rigid-Body Slide 103](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-103.png)

When there are **fewer** reactive forces than equations of equilibrium, the body is **partially constrained**. For example, if $\sum F_y = 0$ cannot be satisfied for the given loading conditions, equilibrium will not be maintained.

### Procedure for Analysis and Examples

![ch05-Equilibrium-of-a-Rigid-Body Slide 104](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-104.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 105](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-105.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 106](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-106.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 107](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-107.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 108](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-108.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 109](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-109.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 110](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-110.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 111](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-111.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 112](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-112.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 113](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-113.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 114](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-114.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 115](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-115.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 116](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-116.png)

![ch05-Equilibrium-of-a-Rigid-Body Slide 117](assets/ch05-Equilibrium-of-a-Rigid-Body/slide-117.png)

---

*Source: [ch05 Equilibrium of a Rigid Body.pdf](../course-materials/ch05%20Equilibrium%20of%20a%20Rigid%20Body.pdf)*
