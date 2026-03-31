# Ch01 - General Principles

> Engineering Mechanics: Statics, 14th Edition (SI Units)

## Chapter Objectives

- To provide an introduction to the basic quantities and idealizations of mechanics.
- To give a statement of Newton's Laws of Motion and Gravitation.
- To review the principles for applying the SI system of units.
- To examine the standard procedures for performing numerical calculations.
- To present a general guide for solving problems.

## Chapter Outline

1.1 Mechanics
1.2 Fundamental Concepts
1.3 The International System of Units
1.4 Numerical Calculations
1.5 General Procedure for Analysis

---

## 1.1 Mechanics

Mechanics can be divided into 3 branches:

- Rigid-body Mechanics
- Deformable-body Mechanics
- Fluid Mechanics

Rigid-body Mechanics is divided into:

- **Statics** — Equilibrium of bodies (at rest or moving with constant velocity)
- **Dynamics** — Accelerated motion of bodies

### Historical Development

| Earlier | Later |
|---------|-------|
| **Statics** | **Dynamics** |
| Principles can be formulated simply from measurements of geometry and force | Depend on an accurate measurement of time |

---

## 1.2 Fundamental Concepts

### Basic Quantities

- **Length** — locate the position of a point in space
- **Time** — conceive as succession of events
- **Mass** — measure of a quantity of matter
- **Force** — "push" or "pull" exerted by one body on another
  - Occur due to direct contact between bodies (e.g., person pushing against a wall)
  - Occur through a distance without direct contact (e.g., gravitational, electrical, and magnetic forces)

### Idealizations

**Particles**

- Consider mass but neglect size
- Example: Size of Earth insignificant compared to the size of its orbit

**Rigid Body**

- Combination of a large number of particles
- Neglect material properties
- Example: Deformations in structures, machines, and mechanisms

**Concentrated Force**

- Effect of loading, assumed to act at a point on a body
- Represented by a concentrated force, provided the loading area is small compared to overall size
- Example: Contact force between wheel and ground

### Newton's Three Laws of Motion

**First Law**

> "A particle originally at rest, or moving in a straight line with constant velocity, will remain in this state provided that the particle is not subjected to an unbalanced force."

**Second Law**

> "A particle acted upon by an unbalanced force **F** experiences an acceleration **a** that has the same direction as the force and a magnitude that is directly proportional to the force."

$$F = ma$$

**Third Law**

> "The mutual forces of action and reaction between two particles are equal, opposite, and collinear."

### Newton's Law of Gravitational Attraction

$$F = G \frac{m_1 m_2}{r^2}$$

Where:
- $F$ = force of gravitation between the two particles
- $G$ = universal constant of gravitation
- $m_1, m_2$ = mass of each of the two particles
- $r$ = distance between the two particles

### Weight

Letting $g = \frac{GM}{r^2}$ yields:

$$W = mg$$

Comparing $F = mg$ with $F = ma$:

- $g$ is the acceleration due to gravity
- Since $g$ is dependent on $r$, weight of a body is **not** an absolute quantity
- Magnitude is determined from where the measurement is taken
- For most engineering calculations, $g$ is determined at sea level and at a latitude of 45°

---

## 1.3 The International System of Units

Length, time, mass, and force are not all independent from one another — they are related by Newton's second law of motion.

- Three of the units, called **base units**, are defined
- The fourth unit is **derived** from the equation $F = ma$

### SI Units

- Stands for **Système International d'Unités**
- SI system specifies length in **meters (m)**, time in **seconds (s)**, and mass in **kilograms (kg)**
- Unit of force, called **Newton (N)**, is derived from $F = ma$

At the standard location: $g = 9.80665 \text{ m/s}^2$

For calculations, we use $g = 9.81 \text{ m/s}^2$. Hence, a body of mass 1 kg has a weight of 9.81 N, a 2 kg body weighs 19.62 N.

### Prefixes

For very large or very small numerical quantities, units can be modified using a prefix. Each represents a multiple or sub-multiple of a unit.

| Example | Conversion |
|---------|-----------|
| 4,000,000 N | = 4000 kN (kilo-newton) = 4 MN (mega-newton) |
| 0.005 m | = 5 mm (milli-meter) |

### Rules for Use

1. Quantities defined by several units which are multiples are separated by a dot
   - Example: $\text{N} = \text{kg} \cdot \text{m/s}^2 = \text{kg} \cdot \text{m} \cdot \text{s}^{-2}$

2. The exponential power represented for a unit having a prefix refers to both the unit and its prefix
   - Example: $\mu\text{N}^2 = (\mu\text{N})^2 = \mu\text{N} \cdot \mu\text{N}$

3. With the exception of the base unit the kilogram, in general avoid the use of a prefix in the denominator of composite units
   - Example: N/mm → kN/m; m/mg → Mm/kg

4. In calculations, represent numbers in terms of their base or derived units by converting all prefixes to powers of 10
   - Example: $(50\text{ kN})(60\text{ nm}) = [50(10^3)\text{N}][60(10^{-9})\text{m}] = 3\text{ mN}\cdot\text{m}$

5. The final result should be expressed using a single prefix

---

## 1.4 Numerical Calculations

### Dimensional Homogeneity

- Each term must be expressed in the same units
- All the terms of an equation can be combined if numerical values are substituted for the variables
- Example: $s = vt + \frac{1}{2}at^2$ where $s$ is position (m), $t$ is time (s), $v$ is velocity (m/s), $a$ is acceleration (m/s²)
- Regardless of how the equation is evaluated, it maintains its dimensional homogeneity

> Problems in mechanics always involve the solution of dimensionally homogeneous equations, and so this fact can be used as a partial check for algebraic manipulations of an equation.

### Significant Figures

- The number of significant figures contained in any number determines the accuracy of the number
- If zeros occur at the beginning of a number less than one, the zeros are **not** significant
  - Example: 0.00821 → 3 significant figures → $8.21 \times 10^{-3}$
- If zeros occur at the end of a whole number, it is unclear
  - Example: 23,400 → unclear (3, 4, or 5 significant figures?)
  - **Solution**: Use engineering notation → $23.4 \times 10^3$

### Rounding Off Numbers

Rules for three significant figures:

| Number | Result |
|--------|--------|
| 3.5587 | 3.56 |
| 0.5896 | 0.590 |
| 9.3866 | 9.39 |
| 1.341 | 1.34 |
| 0.3762 | 0.376 |

**Special case: end in "5"**

| Type | Example | Result |
|------|---------|--------|
| Even number | 75.25 | 75.2 |
| Odd number | 0.1275 | 0.128 |

### Calculations

- Do **not** round off calculations until expressing the final result
- In this book, answers are rounded off to **three significant figures**

---

## 1.5 General Procedure for Analysis

1. **Read** the problem carefully and try to correlate the actual physical situation with the theory studied.

2. **Tabulate** the problem data and draw to a large scale any necessary diagrams.

3. **Apply** the relevant principles, generally in mathematical form. When writing any equations, be sure they are dimensionally homogeneous.

4. **Solve** the necessary equations, and report the answer with no more than three significant figures.

5. **Study** the answer with technical judgment and common sense to determine whether or not it seems reasonable.

---

*Source: [ch01 General Principles.pdf](../course-materials/ch01%20General%20Principles.pdf)*
