# Ch03 - Equilibrium of a Particle

> Engineering Mechanics: Statics, 14th Edition (SI Units)

![ch03-Equilibrium-of-a-Particle Slide 01](assets/ch03-Equilibrium-of-a-Particle/slide-01.png)

---

## Chapter Objectives

![ch03-Equilibrium-of-a-Particle Slide 02](assets/ch03-Equilibrium-of-a-Particle/slide-02.png)

- To introduce the concept of the free-body diagram for a particle.
- To show how to solve particle equilibrium problems using the equations of equilibrium.

## Chapter Outline

![ch03-Equilibrium-of-a-Particle Slide 03](assets/ch03-Equilibrium-of-a-Particle/slide-03.png)

3.1 Condition for the Equilibrium of a Particle
3.2 The Free-Body Diagram
3.3 Coplanar Force Systems
3.4 Three-Dimensional Force Systems

---

## 3.1 Condition for the Equilibrium of a Particle

![ch03-Equilibrium-of-a-Particle Slide 04](assets/ch03-Equilibrium-of-a-Particle/slide-04.png)

A particle is at equilibrium if:

- At rest, **or**
- Moving at a constant velocity

### Newton's First Law of Motion

$$\sum \mathbf{F} = \mathbf{0}$$

where $\sum \mathbf{F}$ is the vector sum of all the forces acting on the particle.

### Newton's Second Law of Motion

![ch03-Equilibrium-of-a-Particle Slide 05](assets/ch03-Equilibrium-of-a-Particle/slide-05.png)

$$\sum \mathbf{F} = m\mathbf{a}$$

When forces fulfill Newton's first law:

$$m\mathbf{a} = \mathbf{0} \implies \mathbf{a} = \mathbf{0}$$

Therefore, the particle is moving at constant velocity or at rest.

---

## 3.2 The Free-Body Diagram

![ch03-Equilibrium-of-a-Particle Slide 06](assets/ch03-Equilibrium-of-a-Particle/slide-06.png)

A free-body diagram (FBD) is the best representation of all the unknown forces ($\sum \mathbf{F}$) acting on a particle. It is a drawing showing the particle with all the forces acting on it.

Consider two common connections:

### Springs

![ch03-Equilibrium-of-a-Particle Slide 07](assets/ch03-Equilibrium-of-a-Particle/slide-07.png)

- **Linearly elastic spring:** change in length is directly proportional to the force acting on it
- **Spring constant (stiffness) $k$:** defines the elasticity of the spring
- Magnitude of force when spring is elongated or compressed:

$$F = ks$$

where $s = l - l_o$

![ch03-Equilibrium-of-a-Particle Slide 08](assets/ch03-Equilibrium-of-a-Particle/slide-08.png)

| Variable | Meaning |
|----------|---------|
| $l$ | deformed length |
| $l_o$ | undeformed length |
| $s > 0$ | elongation -- F "pulls" on the spring |
| $s < 0$ | shortening -- F "pushes" on the spring |

### Cables and Pulleys

![ch03-Equilibrium-of-a-Particle Slide 09](assets/ch03-Equilibrium-of-a-Particle/slide-09.png)

- All cables (or cords) are assumed to have **negligible weight** and they **cannot stretch** (except Sec 7.4)
- A cable only supports **tension** (pulling force), and this force always acts in the **direction of the cable**
- Tension force in a continuous cable must have a **constant magnitude** for equilibrium (Ch 5)

![ch03-Equilibrium-of-a-Particle Slide 10](assets/ch03-Equilibrium-of-a-Particle/slide-10.png)

- For any angle $\theta$, the cable is subjected to a constant tension $T$

### Smooth Contact

![ch03-Equilibrium-of-a-Particle Slide 11](assets/ch03-Equilibrium-of-a-Particle/slide-11.png)

If an object rests on a smooth surface, then the surface will exert a force on the object that is **normal** to the surface at the point of contact.

### Procedure for Drawing a FBD

![ch03-Equilibrium-of-a-Particle Slide 12](assets/ch03-Equilibrium-of-a-Particle/slide-12.png)

1. **Draw outlined shape** -- Isolate the particle from its surroundings
2. **Show all the forces**
   - **Active forces:** set the particle in motion
   - **Reactive forces:** result of constraints and supports that tend to prevent motion

![ch03-Equilibrium-of-a-Particle Slide 13](assets/ch03-Equilibrium-of-a-Particle/slide-13.png)

3. **Identify each force**
   - Known forces should be labeled with proper magnitude and direction
   - Letters are used to represent magnitude and directions of unknown forces

![ch03-Equilibrium-of-a-Particle Slide 14](assets/ch03-Equilibrium-of-a-Particle/slide-14.png)

![ch03-Equilibrium-of-a-Particle Slide 15](assets/ch03-Equilibrium-of-a-Particle/slide-15.png)

---

![ch03-Equilibrium-of-a-Particle Slide 16](assets/ch03-Equilibrium-of-a-Particle/slide-16.png)

![ch03-Equilibrium-of-a-Particle Slide 17](assets/ch03-Equilibrium-of-a-Particle/slide-17.png)

---

## 3.3 Coplanar Force Systems

![ch03-Equilibrium-of-a-Particle Slide 18](assets/ch03-Equilibrium-of-a-Particle/slide-18.png)

A particle is subjected to coplanar forces in the x-y plane. Each force is resolved into $\mathbf{i}$ and $\mathbf{j}$ components for equilibrium.

$$\sum \mathbf{F} = \mathbf{0} \implies \sum F_x\,\mathbf{i} + \sum F_y\,\mathbf{j} = \mathbf{0}$$

![ch03-Equilibrium-of-a-Particle Slide 19](assets/ch03-Equilibrium-of-a-Particle/slide-19.png)

For this vector equation, the resultant force's x and y components must equal zero:

$$\boxed{\sum F_x = 0, \quad \sum F_y = 0}$$

> These two equations can be used to solve for up to **two unknowns**.

### Direction Sense

![ch03-Equilibrium-of-a-Particle Slide 20](assets/ch03-Equilibrium-of-a-Particle/slide-20.png)

- Sense of direction = an algebraic sign which corresponds to the arrowhead direction of the component along the x or y axis
- For unknown magnitude, **assume** an arrowhead sense of the force
- If the solution yields a **negative scalar**, this indicates the sense of the force is **opposite**

### Example

![ch03-Equilibrium-of-a-Particle Slide 21](assets/ch03-Equilibrium-of-a-Particle/slide-21.png)

Consider the free-body diagram of a particle subjected to two forces. Assume unknown force $F$ acts to the right for equilibrium:

$$\sum F_x = 0: \quad +F + 10\text{N} = 0 \implies F = -10\text{N}$$

Force $F$ acts towards the **left** for equilibrium.

![ch03-Equilibrium-of-a-Particle Slide 22](assets/ch03-Equilibrium-of-a-Particle/slide-22.png)

### Procedure for Analysis

![ch03-Equilibrium-of-a-Particle Slide 23](assets/ch03-Equilibrium-of-a-Particle/slide-23.png)

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

![ch03-Equilibrium-of-a-Particle Slide 24](assets/ch03-Equilibrium-of-a-Particle/slide-24.png)

---

![ch03-Equilibrium-of-a-Particle Slide 25](assets/ch03-Equilibrium-of-a-Particle/slide-25.png)

---

![ch03-Equilibrium-of-a-Particle Slide 26](assets/ch03-Equilibrium-of-a-Particle/slide-26.png)

---

![ch03-Equilibrium-of-a-Particle Slide 27](assets/ch03-Equilibrium-of-a-Particle/slide-27.png)

---

![ch03-Equilibrium-of-a-Particle Slide 28](assets/ch03-Equilibrium-of-a-Particle/slide-28.png)

---

![ch03-Equilibrium-of-a-Particle Slide 29](assets/ch03-Equilibrium-of-a-Particle/slide-29.png)

---

![ch03-Equilibrium-of-a-Particle Slide 30](assets/ch03-Equilibrium-of-a-Particle/slide-30.png)

---

![ch03-Equilibrium-of-a-Particle Slide 31](assets/ch03-Equilibrium-of-a-Particle/slide-31.png)

---

![ch03-Equilibrium-of-a-Particle Slide 32](assets/ch03-Equilibrium-of-a-Particle/slide-32.png)

---

## 3.4 Three-Dimensional Force Systems

![ch03-Equilibrium-of-a-Particle Slide 33](assets/ch03-Equilibrium-of-a-Particle/slide-33.png)

For particle equilibrium: $\sum \mathbf{F} = \mathbf{0}$

In three-dimensional force systems, resolve into $\mathbf{i, j, k}$ components:

$$\sum F_x\,\mathbf{i} + \sum F_y\,\mathbf{j} + \sum F_z\,\mathbf{k} = \mathbf{0}$$

Three scalar equations representing algebraic sums of the x, y, z forces:

$$\boxed{\sum F_x = 0, \quad \sum F_y = 0, \quad \sum F_z = 0}$$

> These three equations can be used to solve for up to **three unknowns**.

![ch03-Equilibrium-of-a-Particle Slide 34](assets/ch03-Equilibrium-of-a-Particle/slide-34.png)

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

![ch03-Equilibrium-of-a-Particle Slide 35](assets/ch03-Equilibrium-of-a-Particle/slide-35.png)

![ch03-Equilibrium-of-a-Particle Slide 36](assets/ch03-Equilibrium-of-a-Particle/slide-36.png)

![ch03-Equilibrium-of-a-Particle Slide 37](assets/ch03-Equilibrium-of-a-Particle/slide-37.png)

![ch03-Equilibrium-of-a-Particle Slide 38](assets/ch03-Equilibrium-of-a-Particle/slide-38.png)

![ch03-Equilibrium-of-a-Particle Slide 39](assets/ch03-Equilibrium-of-a-Particle/slide-39.png)

![ch03-Equilibrium-of-a-Particle Slide 40](assets/ch03-Equilibrium-of-a-Particle/slide-40.png)

![ch03-Equilibrium-of-a-Particle Slide 41](assets/ch03-Equilibrium-of-a-Particle/slide-41.png)

![ch03-Equilibrium-of-a-Particle Slide 42](assets/ch03-Equilibrium-of-a-Particle/slide-42.png)

---

*Source: [ch03 Equilibrium of a Particle_N.pdf](../course-materials/ch03%20Equilibrium%20of%20a%20Particle_N.pdf)*
