# Ch03 - Equilibrium of a Particle

> Engineering Mechanics: Statics, 14th Edition (SI Units)

## Chapter Objectives

- To introduce the concept of the free-body diagram for a particle.
- To show how to solve particle equilibrium problems using the equations of equilibrium.

## Chapter Outline

3.1 Condition for the Equilibrium of a Particle
3.2 The Free-Body Diagram
3.3 Coplanar Force Systems
3.4 Three-Dimensional Force Systems

---

## 3.1 Condition for the Equilibrium of a Particle

A particle is at equilibrium if:

- At rest, **or**
- Moving at a constant velocity

### Newton's First Law of Motion

$$\sum \mathbf{F} = \mathbf{0}$$

where $\sum \mathbf{F}$ is the vector sum of all the forces acting on the particle.

### Newton's Second Law of Motion

$$\sum \mathbf{F} = m\mathbf{a}$$

When forces fulfill Newton's first law:

$$m\mathbf{a} = \mathbf{0} \implies \mathbf{a} = \mathbf{0}$$

Therefore, the particle is moving at constant velocity or at rest.

---

## 3.2 The Free-Body Diagram

A free-body diagram (FBD) is the best representation of all the unknown forces ($\sum \mathbf{F}$) acting on a particle. It is a drawing showing the particle with all the forces acting on it.

Consider two common connections:

### Springs

- **Linearly elastic spring:** change in length is directly proportional to the force acting on it
- **Spring constant (stiffness) $k$**: defines the elasticity of the spring
- Magnitude of force when spring is elongated or compressed:

$$F = ks$$

where $s = l - l_o$

| Variable | Meaning |
|----------|---------|
| $l$ | deformed length |
| $l_o$ | undeformed length |
| $s > 0$ | elongation — F "pulls" on the spring |
| $s < 0$ | shortening — F "pushes" on the spring |

### Cables and Pulleys

- All cables (or cords) are assumed to have **negligible weight** and they **cannot stretch** (except Sec 7.4)
- A cable only supports **tension** (pulling force), and this force always acts in the **direction of the cable**
- Tension force in a continuous cable must have a **constant magnitude** for equilibrium (Ch 5)
- For any angle $\theta$, the cable is subjected to a constant tension $T$

### Smooth Contact

If an object rests on a smooth surface, then the surface will exert a force on the object that is **normal** to the surface at the point of contact.

### Procedure for Drawing a FBD

1. **Draw outlined shape** — Isolate the particle from its surroundings
2. **Show all the forces**
   - **Active forces**: set the particle in motion
   - **Reactive forces**: result of constraints and supports that tend to prevent motion
3. **Identify each force**
   - Known forces should be labeled with proper magnitude and direction
   - Letters are used to represent magnitude and directions of unknown forces

---

## 3.3 Coplanar Force Systems

A particle is subjected to coplanar forces in the x-y plane. Each force is resolved into $\mathbf{i}$ and $\mathbf{j}$ components for equilibrium.

$$\sum \mathbf{F} = \mathbf{0} \implies \sum F_x\,\mathbf{i} + \sum F_y\,\mathbf{j} = \mathbf{0}$$

For this vector equation, the resultant force's x and y components must equal zero:

$$\boxed{\sum F_x = 0, \quad \sum F_y = 0}$$

> These two equations can be used to solve for up to **two unknowns**.

### Direction Sense

- Sense of direction = an algebraic sign which corresponds to the arrowhead direction of the component along the x or y axis
- For unknown magnitude, **assume** an arrowhead sense of the force
- If the solution yields a **negative scalar**, this indicates the sense of the force is **opposite**

### Example

Consider the free-body diagram of a particle subjected to two forces. Assume unknown force $F$ acts to the right for equilibrium:

$$\sum F_x = 0: \quad +F + 10\text{N} = 0 \implies F = -10\text{N}$$

→ Force $F$ acts towards the **left** for equilibrium.

### Procedure for Analysis

**Free-Body Diagram:**
- Establish the x, y axes in any suitable orientation
- Label all the unknown and known force magnitudes and directions on the diagram
- The sense of a force having an unknown magnitude can be assumed
- Since the magnitude of a force is always a positive quantity, then if the solution for a force yields a negative result, this indicates that its sense is the reverse of that shown on the free-body diagram

**Equations of Equilibrium:**
- Apply $\sum F_x = 0$ and $\sum F_y = 0$
- Components are positive if directed along a positive axis, and negative if directed along a negative axis
- If more than two unknowns exist and the problem involves a spring, apply $F = ks$ to relate the spring force to the deformation $s$ of the spring

---

## 3.4 Three-Dimensional Force Systems

For particle equilibrium: $\sum \mathbf{F} = \mathbf{0}$

In three-dimensional force systems, resolve into $\mathbf{i, j, k}$ components:

$$\sum F_x\,\mathbf{i} + \sum F_y\,\mathbf{j} + \sum F_z\,\mathbf{k} = \mathbf{0}$$

Three scalar equations representing algebraic sums of the x, y, z forces:

$$\boxed{\sum F_x = 0, \quad \sum F_y = 0, \quad \sum F_z = 0}$$

> These three equations can be used to solve for up to **three unknowns**.

### Procedure for Analysis

**Free-Body Diagram:**

- Establish the x, y, z axes in any suitable orientation
- Label all the known and unknown force magnitudes and directions on the diagram
- The sense of a force having an unknown magnitude can be assumed

**Equations of Equilibrium:**

- Apply $\sum F_x = 0$, $\sum F_y = 0$, and $\sum F_z = 0$ when forces can be easily resolved into x, y, z components
- If the three-dimensional geometry appears difficult, express each force as a Cartesian vector. Substitute vectors into $\sum \mathbf{F} = \mathbf{0}$ and set $\mathbf{i, j, k}$ components = 0
- Negative results indicate the sense of the force is opposite to that shown on the FBD

---

*Source: [ch03 Equilibrium of a Particle_N.pdf](../course-materials/ch03%20Equilibrium%20of%20a%20Particle_N.pdf)*
