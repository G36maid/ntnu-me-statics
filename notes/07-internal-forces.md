# Ch07 - Internal Forces

> Engineering Mechanics: Statics, 14th Edition (SI Units)

### Section Boundaries

| Section | Title | Start Slide | End Slide |
|:-------:|:------|:-----------:|:---------:|
| — | Title / Objectives / Outline | 01 | 03 |
| 7.1 | Internal Forces Developed in Structural Members | 04 | 11 |
| — | Examples 7.1–7.3 | 12 | 24 |
| 7.2 | Shear and Moment Equations and Diagrams | 25 | 32 |
| — | Examples 7.4–7.6 | 33 | 37 |
| 7.3 | Relations between Distributed Load, Shear and Moment | 38 | 45 |
| — | Examples 7.7–7.9 | 46 | 53 |
| 7.4 | Cables — Concentrated Loads | 54 | 57 |
| — | Examples | 58 | 62 |
| 7.4 | Cables — Distributed Load | 63 | 70 |
| — | Examples | 71 | 74 |
| 7.4 | Cables — Own Weight | 75 | 80 |
| — | Examples / End | 81 | 85 |

**Example Locations (Slide Index):**

| Example | Slides |
|---------|--------|
| Ex 7.1 | 12 -- 13 |
| Ex 7.2 | 14 -- 16 |
| Ex 7.3 | 17 -- 18 |
| Ex 7.4 | 19 -- 21 |
| Ex 7.5 | 22 -- 24 |
| Ex 7.6 | 33 -- 34 |
| Ex 7.7 | 35 -- 37 |
| Ex 7.8 | 46 -- 47 |
| Ex 7.9 | 48 -- 50 |
| Ex 7.10 | 51 -- 53 |
| Ex 7.11 | 58 -- 62 |
| Ex 7.12 | 71 -- 74 |
| Ex 7.13 | 81 -- 85 |

---

![ch07-Internal-Forces Slide 01](assets/ch07-Internal-Forces/slide-01.png)

---

## Chapter Objectives

![ch07-Internal-Forces Slide 02](assets/ch07-Internal-Forces/slide-02.png)

- To use the method of sections to determine the internal loadings in a member at a specific point.
- To show how to obtain the internal shear and moment throughout a member and express the result graphically in the form of shear and moment diagrams.
- To analyze the forces and the shape of cables supporting various types of loadings.

## Chapter Outline

![ch07-Internal-Forces Slide 03](assets/ch07-Internal-Forces/slide-03.png)

7.1 Internal Forces Developed in Structural Members
7.2 Shear and Moment Equations and Diagrams
7.3 Relations between Distributed Load, Shear and Moment
7.4 Cables

---

## 7.1 Internal Forces Developed in Structural Members

![ch07-Internal-Forces Slide 04](assets/ch07-Internal-Forces/slide-04.png)

Knowing the internal loading is necessary to ensure the material can resist the loading. Internal loadings can be determined by using the **method of sections**.

![ch07-Internal-Forces Slide 05](assets/ch07-Internal-Forces/slide-05.png)

### Internal Loadings at a Section

![ch07-Internal-Forces Slide 06](assets/ch07-Internal-Forces/slide-06.png)

At any section through the member, three internal resultants act:

- **$N_B$** — Normal force (perpendicular to the cross section)
- **$V_B$** — Shear force (tangent to the cross section)
- **$M_B$** — Bending moment

For 3D problems, a general internal force and couple moment resultant acts at the section:

| Component | Type |
|:---------:|:----:|
| $N_y$ | Normal force |
| $V_x$, $V_z$ | Shear components |
| $M_y$ | Torsional (twisting) moment |
| $M_x$, $M_z$ | Bending moment components |

The resultant loadings act at the **geometric center (centroid)** of the cross section.

![ch07-Internal-Forces Slide 07](assets/ch07-Internal-Forces/slide-07.png)

### Sign Convention

![ch07-Internal-Forces Slide 08](assets/ch07-Internal-Forces/slide-08.png)

- **Positive normal force** — creates tension.
- **Positive shear force** — causes the beam segment to rotate clockwise.
- **Positive bending moment** — bends the segment concave upward.
- Loadings opposite to these are considered negative.

![ch07-Internal-Forces Slide 09](assets/ch07-Internal-Forces/slide-09.png)

### Procedure for Analysis

![ch07-Internal-Forces Slide 10](assets/ch07-Internal-Forces/slide-10.png)

1. **Support Reactions** — Determine support reactions by considering the equilibrium of the entire body.
2. **Make an Imaginary Cut** — Section the body perpendicular to its axis at the point where the internal loading is to be determined. Draw a FBD of one of the resulting segments.
3. **Apply Equilibrium** — Apply the equations of equilibrium to obtain the internal forces and moment.

![ch07-Internal-Forces Slide 11](assets/ch07-Internal-Forces/slide-11.png)

### Examples 7.1 -- 7.3

![ch07-Internal-Forces Slide 12](assets/ch07-Internal-Forces/slide-12.png)

![ch07-Internal-Forces Slide 13](assets/ch07-Internal-Forces/slide-13.png)

![ch07-Internal-Forces Slide 14](assets/ch07-Internal-Forces/slide-14.png)

![ch07-Internal-Forces Slide 15](assets/ch07-Internal-Forces/slide-15.png)

![ch07-Internal-Forces Slide 16](assets/ch07-Internal-Forces/slide-16.png)

![ch07-Internal-Forces Slide 17](assets/ch07-Internal-Forces/slide-17.png)

![ch07-Internal-Forces Slide 18](assets/ch07-Internal-Forces/slide-18.png)

![ch07-Internal-Forces Slide 19](assets/ch07-Internal-Forces/slide-19.png)

![ch07-Internal-Forces Slide 20](assets/ch07-Internal-Forces/slide-20.png)

![ch07-Internal-Forces Slide 21](assets/ch07-Internal-Forces/slide-21.png)

---

## 7.2 Shear and Moment Equations and Diagrams

![ch07-Internal-Forces Slide 22](assets/ch07-Internal-Forces/slide-22.png)

**Beams** are structural members designed to support loadings applied perpendicular to their axes.

- A **simply supported beam** is pinned at one end and roller-supported at the other.
- A **cantilevered beam** is fixed at one end and free at the other.

![ch07-Internal-Forces Slide 23](assets/ch07-Internal-Forces/slide-23.png)

### Discontinuity of Loading

![ch07-Internal-Forces Slide 24](assets/ch07-Internal-Forces/slide-24.png)

Internal shear and bending-moment functions will be **discontinuous**, or their slopes will be discontinuous, at points where:

- A distributed load changes
- Concentrated forces or couple moments are applied

Functions must be determined for **each segment** of the beam located between any two discontinuities of loading.

### Shear and Moment Diagrams

![ch07-Internal-Forces Slide 25](assets/ch07-Internal-Forces/slide-25.png)

The **shear diagram** is a plot of the shear force $V$ versus position $x$ along the beam.

The **bending-moment diagram** is a plot of the bending moment $M$ versus position $x$ along the beam.

The internal normal force will not be considered in this 2D analysis.

### Procedure for Analysis

![ch07-Internal-Forces Slide 26](assets/ch07-Internal-Forces/slide-26.png)

1. **Support Reactions** — Determine all reactive forces and couple moments acting on the beam, and resolve all forces into components in the $x$ and $y$ directions.
2. **Shear and Moment Functions** — Section the beam perpendicular to its axis at each region where the loading changes. Draw the FBD of the segment, and obtain $V$ and $M$ as functions of $x$.
3. **Shear and Moment Diagrams** — Plot the shear and moment functions.

![ch07-Internal-Forces Slide 27](assets/ch07-Internal-Forces/slide-27.png)

![ch07-Internal-Forces Slide 28](assets/ch07-Internal-Forces/slide-28.png)

![ch07-Internal-Forces Slide 29](assets/ch07-Internal-Forces/slide-29.png)

### Examples 7.4 -- 7.7

![ch07-Internal-Forces Slide 30](assets/ch07-Internal-Forces/slide-30.png)

![ch07-Internal-Forces Slide 31](assets/ch07-Internal-Forces/slide-31.png)

![ch07-Internal-Forces Slide 32](assets/ch07-Internal-Forces/slide-32.png)

![ch07-Internal-Forces Slide 33](assets/ch07-Internal-Forces/slide-33.png)

![ch07-Internal-Forces Slide 34](assets/ch07-Internal-Forces/slide-34.png)

![ch07-Internal-Forces Slide 35](assets/ch07-Internal-Forces/slide-35.png)

![ch07-Internal-Forces Slide 36](assets/ch07-Internal-Forces/slide-36.png)

![ch07-Internal-Forces Slide 37](assets/ch07-Internal-Forces/slide-37.png)

![ch07-Internal-Forces Slide 38](assets/ch07-Internal-Forces/slide-38.png)

![ch07-Internal-Forces Slide 39](assets/ch07-Internal-Forces/slide-39.png)

![ch07-Internal-Forces Slide 40](assets/ch07-Internal-Forces/slide-40.png)

![ch07-Internal-Forces Slide 41](assets/ch07-Internal-Forces/slide-41.png)

![ch07-Internal-Forces Slide 42](assets/ch07-Internal-Forces/slide-42.png)

![ch07-Internal-Forces Slide 43](assets/ch07-Internal-Forces/slide-43.png)

---

## 7.3 Relations between Distributed Load, Shear and Moment

![ch07-Internal-Forces Slide 44](assets/ch07-Internal-Forces/slide-44.png)

Consider a beam $AD$ subjected to an arbitrary distributed load $w = w(x)$ and a series of concentrated forces and couple moments. Distributed load is considered **positive** when the loading acts **upwards**.

![ch07-Internal-Forces Slide 45](assets/ch07-Internal-Forces/slide-45.png)

### Differential Element Analysis

![ch07-Internal-Forces Slide 46](assets/ch07-Internal-Forces/slide-46.png)

A FBD for a small segment of the beam having length $\Delta x$ is chosen at point $x$ where there is no concentrated force or couple moment. The internal shear and bending moments are assumed in the positive sense.

![ch07-Internal-Forces Slide 47](assets/ch07-Internal-Forces/slide-47.png)

The distributed loading is replaced by a resultant force $\Delta F = w(x)\,\Delta x$ acting at a fractional distance $k(\Delta x)$ from the right end, where $0 < k < 1$.

### Relation between Distributed Load and Shear

![ch07-Internal-Forces Slide 48](assets/ch07-Internal-Forces/slide-48.png)

From vertical force equilibrium ($\sum F_y = 0$):

$$V + \Delta V - w(x)\,\Delta x - V = 0$$

Dividing by $\Delta x$ and letting $\Delta x \to 0$:

$$\boxed{\frac{dV}{dx} = w(x)}$$

> The **slope of the shear diagram** at a point equals the intensity of the distributed loading at that point.

Integrating:

$$\Delta V = \int w(x)\,dx$$

> The **change in shear** between any two points equals the area under the distributed loading curve between those points.

### Relation between Shear and Moment

![ch07-Internal-Forces Slide 49](assets/ch07-Internal-Forces/slide-49.png)

From moment equilibrium ($\sum M_O = 0$):

$$M + \Delta M - w(x)\,k(\Delta x)^2 - V\,\Delta x - M = 0$$

Dividing by $\Delta x$ and letting $\Delta x \to 0$:

$$\boxed{\frac{dM}{dx} = V}$$

> The **slope of the moment diagram** at a point equals the shear at that point.

Integrating:

$$\Delta M = \int V\,dx$$

> The **change in moment** between any two points equals the area under the shear diagram between those points.

### Concentrated Force

![ch07-Internal-Forces Slide 50](assets/ch07-Internal-Forces/slide-50.png)

Since the change in shear is positive, the shear diagram will **jump upward** when $F$ acts upward on the beam. Likewise, the jump $\Delta V$ is downward when $F$ acts downward.

$$\Delta V = F$$

### Couple Moment

![ch07-Internal-Forces Slide 51](assets/ch07-Internal-Forces/slide-51.png)

The change in moment is positive, or the moment diagram will **jump upward** if $M_0$ is clockwise. The jump $\Delta M$ is downward when $M_0$ is counterclockwise.

$$\Delta M = M_0$$

### Examples 7.8 -- 7.10

![ch07-Internal-Forces Slide 52](assets/ch07-Internal-Forces/slide-52.png)

![ch07-Internal-Forces Slide 53](assets/ch07-Internal-Forces/slide-53.png)

![ch07-Internal-Forces Slide 54](assets/ch07-Internal-Forces/slide-54.png)

![ch07-Internal-Forces Slide 55](assets/ch07-Internal-Forces/slide-55.png)

![ch07-Internal-Forces Slide 56](assets/ch07-Internal-Forces/slide-56.png)

![ch07-Internal-Forces Slide 57](assets/ch07-Internal-Forces/slide-57.png)

![ch07-Internal-Forces Slide 58](assets/ch07-Internal-Forces/slide-58.png)

![ch07-Internal-Forces Slide 59](assets/ch07-Internal-Forces/slide-59.png)

![ch07-Internal-Forces Slide 60](assets/ch07-Internal-Forces/slide-60.png)

![ch07-Internal-Forces Slide 61](assets/ch07-Internal-Forces/slide-61.png)

![ch07-Internal-Forces Slide 62](assets/ch07-Internal-Forces/slide-62.png)

---

## 7.4 Cables

![ch07-Internal-Forces Slide 63](assets/ch07-Internal-Forces/slide-63.png)

Cables and chains are used to support and transmit loads from one member to another. In the force analysis:

- The weight of cables is neglected.
- The cable is assumed to be perfectly **flexible** (offers no resistance to bending) and **inextensible** (length remains constant before and after loading).

![ch07-Internal-Forces Slide 64](assets/ch07-Internal-Forces/slide-64.png)

### Cable Subjected to Concentrated Loads

![ch07-Internal-Forces Slide 65](assets/ch07-Internal-Forces/slide-65.png)

For a cable of negligible weight supporting several concentrated loads, the cable takes the form of several straight-line segments, each subjected to a **constant tensile force**.

Given: $h$, $L_1$, $L_2$, $L_3$ and loads $P_1$ and $P_2$:

1. Form 2 equations of force equilibrium at each point $A$, $B$, $C$, $D$.
2. If the total length $L$ is specified, use the Pythagorean theorem to relate the three segmental lengths.
3. If not, specify one of the sags ($y_C$ or $y_D$), and from the answer determine the other sag and hence the total length $L$.

![ch07-Internal-Forces Slide 66](assets/ch07-Internal-Forces/slide-66.png)

### Examples

![ch07-Internal-Forces Slide 67](assets/ch07-Internal-Forces/slide-67.png)

![ch07-Internal-Forces Slide 68](assets/ch07-Internal-Forces/slide-68.png)

![ch07-Internal-Forces Slide 69](assets/ch07-Internal-Forces/slide-69.png)

![ch07-Internal-Forces Slide 70](assets/ch07-Internal-Forces/slide-70.png)

![ch07-Internal-Forces Slide 71](assets/ch07-Internal-Forces/slide-71.png)

### Cable Subjected to a Distributed Load

![ch07-Internal-Forces Slide 72](assets/ch07-Internal-Forces/slide-72.png)

Consider a weightless cable subjected to a distributed loading $w = w(x)$ measured in the $x$ direction.

![ch07-Internal-Forces Slide 73](assets/ch07-Internal-Forces/slide-73.png)

![ch07-Internal-Forces Slide 74](assets/ch07-Internal-Forces/slide-74.png)

The FBD of a small cable segment of length $\Delta s$. The tensile force changes in both magnitude and direction along the cable's length (denoted by $\Delta T$). The distributed load is represented by its resultant $w(x)(\Delta x)$.

From equilibrium of the segment:

$$T\cos\theta + \Delta(T\cos\theta) - T\cos\theta = 0$$

$$T\sin\theta + \Delta(T\sin\theta) + w(x)\,\Delta x - T\sin\theta = 0$$

$$\Delta M = 0$$

Dividing by $\Delta x$ and taking the limit as $\Delta x \to 0$:

$$\frac{d}{dx}(T\cos\theta) = 0 \quad (7{-}7)$$

$$\frac{d}{dx}(T\sin\theta) = -w(x) \quad (7{-}8)$$

$$\tan\theta = \frac{dy}{dx} \quad (7{-}9)$$

![ch07-Internal-Forces Slide 75](assets/ch07-Internal-Forces/slide-75.png)

Integrating Eq. 7-7:

$$T\cos\theta = F_H = \text{constant} \quad (7{-}10)$$

> The **horizontal component** of cable tension is constant throughout the cable.

Integrating Eq. 7-8:

$$T\sin\theta = -\int w(x)\,dx \quad (7{-}11)$$

Dividing Eq. 7-11 by Eq. 7-10 eliminates $T$:

$$\tan\theta = \frac{dy}{dx} = \frac{1}{F_H} \int w(x)\,dx$$

Performing a second integration:

$$y = \frac{1}{F_H} \int \left(\int w(x)\,dx\right) dx$$

![ch07-Internal-Forces Slide 76](assets/ch07-Internal-Forces/slide-76.png)

![ch07-Internal-Forces Slide 77](assets/ch07-Internal-Forces/slide-77.png)

### Examples

![ch07-Internal-Forces Slide 78](assets/ch07-Internal-Forces/slide-78.png)

![ch07-Internal-Forces Slide 79](assets/ch07-Internal-Forces/slide-79.png)

### Cable Subjected to its Own Weight

![ch07-Internal-Forces Slide 80](assets/ch07-Internal-Forces/slide-80.png)

When the weight of the cable is considered, the loading function becomes a function of the arc length $s$ rather than length $x$. Consider $w = w(s)$.

![ch07-Internal-Forces Slide 81](assets/ch07-Internal-Forces/slide-81.png)

![ch07-Internal-Forces Slide 82](assets/ch07-Internal-Forces/slide-82.png)

From equilibrium and using $ds^2 = dx^2 + dy^2$, replace $\frac{dy}{dx}$ by $\frac{ds}{dx}$:

$$\frac{T\sin\theta}{T\cos\theta} = \frac{dy}{dx} = \frac{1}{F_H} \int w(s)\,ds$$

Since $ds = \sqrt{1 + \left(\frac{dy}{dx}\right)^2}\,dx$:

$$x = \int \frac{ds}{\sqrt{1 + \frac{1}{F_H^2}\left(\int w(s)\,ds\right)^2}}$$

![ch07-Internal-Forces Slide 83](assets/ch07-Internal-Forces/slide-83.png)

![ch07-Internal-Forces Slide 84](assets/ch07-Internal-Forces/slide-84.png)

![ch07-Internal-Forces Slide 85](assets/ch07-Internal-Forces/slide-85.png)

---

*Source: [ch07 Internal Forces.pdf](../course-materials/ch07%20Internal%20Forces.pdf)*
