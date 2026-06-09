# Ch06 - Structural Analysis

> Engineering Mechanics: Statics, 14th Edition (SI Units)

### Section Boundaries

| Section | Title | Start Slide | End Slide |
|:-------:|:------|:-----------:|:---------:|
| — | Title / Objectives / Outline | 001 | 003 |
| 6.1 | Simple Trusses | 004 | 012 |
| 6.2 | The Method of Joints | 013 | 020 |
| — | Examples 6.1–6.3 | 021 | 030 |
| 6.3 | Zero-Force Members | 031 | 039 |
| — | Example 6.4 | 040 | 042 |
| 6.4 | The Method of Sections | 043 | 050 |
| — | Examples 6.5–6.7 | 051 | 058 |
| 6.5 | Space Trusses | 059 | 063 |
| — | Example 6.8 | 064 | 066 |
| 6.6 | Frames and Machines | 067 | 071 |
| — | Examples 6.9 -- 6.13 + Procedure | 072 | 086 |
| — | Examples 6.14 -- 6.22 | 087 | 107 |

**Example Locations (Slide Index):**

| Example | Slides |
|---------|--------|
| Ex 6.1 | 021 -- 023 |
| Ex 6.2 | 024 -- 026 |
| Ex 6.3 | 027 -- 030 |
| Ex 6.4 | 040 -- 042 |
| Ex 6.5 | 051 -- 052 |
| Ex 6.6 | 053 -- 055 |
| Ex 6.7 | 056 -- 058 |
| Ex 6.8 | 064 -- 066 |
| Ex 6.9 | 072 -- 074 |
| Ex 6.10 | 075 -- 076 |
| Ex 6.11 | 077 -- 078 |
| Ex 6.12 | 079 -- 081 |
| Ex 6.13 | 082 -- 083 |
| Ex 6.14 | 087 -- 088 |
| Ex 6.15 | 089 -- 090 |
| Ex 6.16 | 091 -- 093 |
| Ex 6.17 | 094 -- 095 |
| Ex 6.18 | 096 -- 097 |
| Ex 6.19 | 098 -- 099 |
| Ex 6.20 | 100 -- 101 |
| Ex 6.21 | 102 -- 103 |
| Ex 6.22 | 104 -- 107 |

---

![ch06N-Structural-Analysis Slide 01](assets/ch06N-Structural-Analysis/slide-001.png)

---

## Chapter Objectives

![ch06N-Structural-Analysis Slide 02](assets/ch06N-Structural-Analysis/slide-002.png)

- To show how to determine the forces in the members of a truss using the method of joints and the method of sections.
- To analyze the forces acting on the members of frames and machines composed of pin-connected members.

## Chapter Outline

![ch06N-Structural-Analysis Slide 03](assets/ch06N-Structural-Analysis/slide-003.png)

6.1 Simple Trusses
6.2 The Method of Joints
6.3 Zero-Force Members
6.4 The Method of Sections
6.5 Space Trusses
6.6 Frames and Machines

---

## 6.1 Simple Trusses

![ch06N-Structural-Analysis Slide 04](assets/ch06N-Structural-Analysis/slide-004.png)

A **truss** is a structure composed of slender members joined together at their end points.

Planar trusses are used to support roofs and bridges. The roof load is transmitted to the truss at the joints by means of a series of **purlins**.

![ch06N-Structural-Analysis Slide 05](assets/ch06N-Structural-Analysis/slide-005.png)

The analysis of the forces developed in the truss members is two-dimensional (2D).

![ch06N-Structural-Analysis Slide 06](assets/ch06N-Structural-Analysis/slide-006.png)

For a bridge, the load on the deck is first transmitted to **stringers**, then to **floor beams**, and finally to the joints of the two supporting side trusses. Like the roof truss, the bridge truss loading is also coplanar.

![ch06N-Structural-Analysis Slide 07](assets/ch06N-Structural-Analysis/slide-007.png)

When bridge or roof trusses extend over large distances, a rocker or roller is commonly used for supporting one end (e.g., joint $A$). This type of support allows freedom for expansion or contraction of the members due to a change in temperature or application of loads.

![ch06N-Structural-Analysis Slide 08](assets/ch06N-Structural-Analysis/slide-008.png)

### Assumptions for Design

- All loadings are applied at the joints. The weight of the members is neglected.
- The members are joined together by smooth pins. Assume connections provided the center lines of the joining members are concurrent.

![ch06N-Structural-Analysis Slide 09](assets/ch06N-Structural-Analysis/slide-009.png)

Because of these two assumptions, each truss member will act as a **two-force member**.

- If the force tends to elongate the member, it is a **tensile force** ($T$).
- If the force tends to shorten the member, it is a **compressive force** ($C$).

![ch06N-Structural-Analysis Slide 10](assets/ch06N-Structural-Analysis/slide-010.png)

### Simple Truss

- A triangular truss is rigid.
- A **simple truss** is a truss that can be constructed by expanding the basic triangular truss. This is done by repeatedly adding two new members and one new joint.

![ch06N-Structural-Analysis Slide 11](assets/ch06N-Structural-Analysis/slide-011.png)

---

## 6.2 The Method of Joints

![ch06N-Structural-Analysis Slide 12](assets/ch06N-Structural-Analysis/slide-012.png)

For a truss, we need to know the force in each member. The **method of joints** uses the fact that the entire truss and each of its joints are in equilibrium.

- Force equilibrium equations can be used to obtain the member forces.
- The force system acting at each joint is coplanar and concurrent.
- $\sum F_x = 0$ and $\sum F_y = 0$.

![ch06N-Structural-Analysis Slide 13](assets/ch06N-Structural-Analysis/slide-013.png)

At least one known force and at most two unknown forces must act at the joint, so that $\sum F_x = 0$ and $\sum F_y = 0$ can be applied.

Two methods to determine the correct sense of an unknown member force:

1. The correct sense of a direction of an unknown force can be determined **"by inspection"**.

![ch06N-Structural-Analysis Slide 14](assets/ch06N-Structural-Analysis/slide-014.png)

- $F_{BC}$ must push on the pin (compression) since its horizontal component must balance the $500\text{ N}$ force.
- $F_{BA}$ is a tensile force since it balances the vertical component of $F_{BC}$.

In more complicated problems, the sense of the member can be assumed. A positive answer indicates that the sense is correct, whereas a negative answer indicates that the sense must be reversed.

![ch06N-Structural-Analysis Slide 15](assets/ch06N-Structural-Analysis/slide-015.png)

2. Always assume the unknown member forces acting on the joint's FBD to be in tension (pull).

- Positive scalars indicate members in tension.
- Negative scalars indicate members in compression.

![ch06N-Structural-Analysis Slide 16](assets/ch06N-Structural-Analysis/slide-016.png)

![ch06N-Structural-Analysis Slide 17](assets/ch06N-Structural-Analysis/slide-017.png)

### Procedure for Analysis

![ch06N-Structural-Analysis Slide 18](assets/ch06N-Structural-Analysis/slide-018.png)

**Free-Body Diagram:**

- Orient the $x$ and $y$ axes such that the forces on the free-body diagram can be easily resolved into their $x$ and $y$ components.
- Apply the two force equilibrium equations $\sum F_x = 0$ and $\sum F_y = 0$.
- Solve for the two unknown member forces and verify their correct sense.
- Using the calculated results, continue to analyze each of the other joints.
- Remember that a member in compression "pushes" on the joint and a member in tension "pulls" on the joint.
- Choose a joint having at most two unknowns and at least one known force.

![ch06N-Structural-Analysis Slide 19](assets/ch06N-Structural-Analysis/slide-019.png)

---

### Example 6.1

![ch06N-Structural-Analysis Slide 20](assets/ch06N-Structural-Analysis/slide-020.png)

Determine the force in each member of the truss shown and indicate whether the members are in tension or compression.

**Solution:**

Begin the analysis at joint $B$ since there should be no more than two unknown forces at the joint and at least one known force acting there.

![ch06N-Structural-Analysis Slide 21](assets/ch06N-Structural-Analysis/slide-021.png)

**Joint B.** The free-body diagram of joint $B$ is shown. Applying the equations of equilibrium:

$$\xrightarrow{+} \sum F_x = 0; \quad 500\text{ N} - F_{BC} \sin 45^\circ = 0$$

$$F_{BC} = 707.1\text{ N (C)}$$

$$+\uparrow \sum F_y = 0; \quad F_{BC} \cos 45^\circ - F_{BA} = 0$$

$$F_{BA} = 500\text{ N (T)}$$

Since the force in member $BC$ has been calculated, proceed to analyze joint $C$ to determine the force in member $CA$ and the support reaction at the rocker.

![ch06N-Structural-Analysis Slide 22](assets/ch06N-Structural-Analysis/slide-022.png)

**Joint C.** From the free-body diagram of joint $C$:

$$\xrightarrow{+} \sum F_x = 0; \quad -F_{CA} + 707.1 \cos 45^\circ\text{ N} = 0$$

$$F_{CA} = 500\text{ N (T)}$$

$$+\uparrow \sum F_y = 0; \quad C_y - 707.1 \sin 45^\circ\text{ N} = 0$$

$$C_y = 500\text{ N}$$

**Joint A.** Although it is not necessary, the components of the support reactions at joint $A$ can be determined using the results of $F_{CA}$ and $F_{BA}$.

$$\xrightarrow{+} \sum F_x = 0; \quad 500\text{ N} - A_x = 0 \quad A_x = 500\text{ N}$$

$$+\uparrow \sum F_y = 0; \quad 500\text{ N} - A_y = 0 \quad A_y = 500\text{ N}$$

![ch06N-Structural-Analysis Slide 23](assets/ch06N-Structural-Analysis/slide-023.png)

> **Note:** The results of the analysis are summarized in the figure. The free-body diagram of each joint (or pin) shows the effects of all the connected members and external forces applied to the joint, whereas the free-body diagram of each member shows only the effects of the end joints on the member.

---

### Example 6.2

![ch06N-Structural-Analysis Slide 24](assets/ch06N-Structural-Analysis/slide-024.png)

Determine the forces acting in all the members of the truss shown.

**Solution:**

By inspection, there are more than two unknowns at each joint. Consequently, the support reactions on the truss must first be determined.

![ch06N-Structural-Analysis Slide 25](assets/ch06N-Structural-Analysis/slide-025.png)

**Joint C.** From the free-body diagram:

$$\xrightarrow{+} \sum F_x = 0; \quad -F_{CD} \cos 30^\circ + F_{CB} \sin 45^\circ = 0$$

$$+\uparrow \sum F_y = 0; \quad 1.5\text{ kN} + F_{CD} \sin 30^\circ - F_{CB} \cos 45^\circ = 0$$

These two equations must be solved simultaneously for each of the two unknowns. A direct solution for one of the unknown forces may be obtained by applying a force summation along an axis that is perpendicular to the direction of the other unknown force.

$$+\nearrow \sum F_{y'} = 0; \quad 1.5 \cos 30^\circ\text{ kN} - F_{CB} \sin 15^\circ = 0$$

$$F_{CB} = 5.019\text{ kN} = 5.02\text{ kN (C)}$$

![ch06N-Structural-Analysis Slide 26](assets/ch06N-Structural-Analysis/slide-026.png)

---

### Example 6.3

![ch06N-Structural-Analysis Slide 27](assets/ch06N-Structural-Analysis/slide-027.png)

![ch06N-Structural-Analysis Slide 28](assets/ch06N-Structural-Analysis/slide-028.png)

![ch06N-Structural-Analysis Slide 29](assets/ch06N-Structural-Analysis/slide-029.png)

> **Note:** The analysis is summarized in the figure, which shows the free-body diagram for each joint and member.

---

## 6.3 Zero-Force Members

![ch06N-Structural-Analysis Slide 30](assets/ch06N-Structural-Analysis/slide-030.png)

Truss analysis using the method of joints is greatly simplified if we can first identify those members which support no loading.

- These **zero-force members** are used to increase the stability of the truss during construction and to provide added support if the loading is changed.
- The zero-force members are found by inspection of each of the joints.

![ch06N-Structural-Analysis Slide 31](assets/ch06N-Structural-Analysis/slide-031.png)

From the FBD of the pin at joint $A$:

$$\xrightarrow{+} \sum F_x = 0; \quad F_{AB} = 0$$

$$+\uparrow \sum F_y = 0; \quad F_{AF} = 0$$

Members $AB$ and $AF$ are zero-force members.

![ch06N-Structural-Analysis Slide 32](assets/ch06N-Structural-Analysis/slide-032.png)

From the FBD of the pin at joint $D$, members $DC$ and $DE$ are zero-force members.

![ch06N-Structural-Analysis Slide 33](assets/ch06N-Structural-Analysis/slide-033.png)

![ch06N-Structural-Analysis Slide 34](assets/ch06N-Structural-Analysis/slide-034.png)

### Conclusion

> If only two non-collinear members form a truss joint and no external load or support reaction is applied to the joint, the two members must be zero-force members.

![ch06N-Structural-Analysis Slide 35](assets/ch06N-Structural-Analysis/slide-035.png)

> In general, if three members form a truss joint for which two of the members are collinear, the third member is a zero-force member provided no external force or support reaction is applied to the joint.

---

### Example 6.4

![ch06N-Structural-Analysis Slide 36](assets/ch06N-Structural-Analysis/slide-036.png)

Using the method of joints, determine all the zero-force members of the Fink roof truss shown. Assume all joints are pin connected.

**Solution:**

Look for joint geometries that have three members for which two are collinear.

![ch06N-Structural-Analysis Slide 37](assets/ch06N-Structural-Analysis/slide-037.png)

**Joint G.**

$$+\uparrow \sum F_y = 0; \quad F_{GC} = 0$$

Realize that we could not conclude that $GC$ is a zero-force member by considering joint $C$, where there are five unknowns. The fact that $GC$ is a zero-force member means that the $5\text{-kN}$ load at $C$ must be supported by members $CB$, $CH$, $CF$, and $CD$.

![ch06N-Structural-Analysis Slide 38](assets/ch06N-Structural-Analysis/slide-038.png)

**Joint D.**

$$+\swarrow \sum F_x = 0; \quad F_{DF} = 0$$

**Joint F.**

$$+\uparrow \sum F_y = 0; \quad F_{FC} \cos \theta = 0$$

Since $\theta \neq 90^\circ$, $F_{FC} = 0$.

![ch06N-Structural-Analysis Slide 39](assets/ch06N-Structural-Analysis/slide-039.png)

> **Note:** If joint $B$ is analyzed, $F_{BH} = 2\text{ kN (C)}$. Also, $F_{HC}$ must satisfy $\sum F_y = 0$, and therefore $HC$ is not a zero-force member.

---

## 6.4 The Method of Sections

![ch06N-Structural-Analysis Slide 40](assets/ch06N-Structural-Analysis/slide-040.png)

The **method of sections** is used to find forces within members.

- If the truss is in equilibrium, any segment of the truss is also in equilibrium.
- An imaginary section is used to cut each member into two parts and "expose" each internal force as "external" to the FBD.

![ch06N-Structural-Analysis Slide 41](assets/ch06N-Structural-Analysis/slide-041.png)

The method of sections can also be used to "cut" or section the members of an entire truss.

- Only three independent equilibrium equations ($\sum F_x = 0$; $\sum F_y = 0$; $\sum M_O = 0$) are available.
- Select a section that cuts through no more than three members in which the forces are unknown.

![ch06N-Structural-Analysis Slide 42](assets/ch06N-Structural-Analysis/slide-042.png)

> **Note:**
> 1. The force in a member is along its axis.
> 2. Member forces are equal and opposite to those acting on the other part — Newton's Law.

![ch06N-Structural-Analysis Slide 43](assets/ch06N-Structural-Analysis/slide-043.png)

![ch06N-Structural-Analysis Slide 44](assets/ch06N-Structural-Analysis/slide-044.png)

Two ways to determine the correct sense of an unknown member force:

1. **"By inspection."**
2. Always assume that the unknown member forces at the cut section are tensile forces, i.e., "pulling" on the member. By doing this, the numerical solution of the equilibrium equations will yield positive scalars for members in tension and negative scalars for members in compression.

![ch06N-Structural-Analysis Slide 45](assets/ch06N-Structural-Analysis/slide-045.png)

### Procedure for Analysis

![ch06N-Structural-Analysis Slide 46](assets/ch06N-Structural-Analysis/slide-046.png)

**Equations of Equilibrium:**

- Moments should be summed about a point that lies at the intersection of the lines of action of two unknown forces, so that the third unknown force can be determined directly from the moment equation.
- If two of the unknown forces are parallel, forces may be summed perpendicular to the direction of these unknowns to determine directly the third unknown force.

![ch06N-Structural-Analysis Slide 47](assets/ch06N-Structural-Analysis/slide-047.png)

![ch06N-Structural-Analysis Slide 48](assets/ch06N-Structural-Analysis/slide-048.png)

![ch06N-Structural-Analysis Slide 49](assets/ch06N-Structural-Analysis/slide-049.png)

---

### Example 6.5

![ch06N-Structural-Analysis Slide 50](assets/ch06N-Structural-Analysis/slide-050.png)

Determine the force in members $GE$, $GC$, and $BC$ of the truss shown. Indicate whether the members are in tension or compression.

**Solution:**

Section $aa$ has been chosen since it cuts through the three members whose forces are to be determined. It is first necessary to determine the external reactions at $A$ or $D$.

$$\xrightarrow{+} \sum F_x = 0; \quad 400\text{ N} - A_x = 0 \quad A_x = 400\text{ N}$$

$$\circlearrowleft + \sum M_A = 0; \quad -1200\text{ N}(8\text{ m}) - 400\text{ N}(3\text{ m}) + D_y(12\text{ m}) = 0$$

$$D_y = 900\text{ N}$$

$$+\uparrow \sum F_y = 0; \quad A_y - 1200\text{ N} + 900\text{ N} = 0 \quad A_y = 300\text{ N}$$

![ch06N-Structural-Analysis Slide 51](assets/ch06N-Structural-Analysis/slide-051.png)

For the analysis, the free-body diagram of the left portion of the sectioned truss will be used, since it involves the least number of forces.

![ch06N-Structural-Analysis Slide 52](assets/ch06N-Structural-Analysis/slide-052.png)

**Equations of Equilibrium.** Summing moments about point $G$ eliminates $F_{GE}$ and $F_{GC}$ and yields a direct solution for $F_{BC}$.

$$\circlearrowleft + \sum M_G = 0; \quad -300\text{ N}(4\text{ m}) - 400\text{ N}(3\text{ m}) + F_{BC}(3\text{ m}) = 0$$

$$F_{BC} = 800\text{ N (T)}$$

Summing moments about point $C$:

$$\circlearrowleft + \sum M_C = 0; \quad -300\text{ N}(8\text{ m}) + F_{GE}(3\text{ m}) = 0$$

$$F_{GE} = 800\text{ N (C)}$$

Since $F_{BC}$ and $F_{GE}$ have no vertical components, summing forces in the $y$ direction directly yields $F_{GC}$:

$$+\uparrow \sum F_y = 0; \quad 300\text{ N} - \frac{3}{5}F_{GC} = 0$$

$$F_{GC} = 500\text{ N (T)}$$

---

### Example 6.6

![ch06N-Structural-Analysis Slide 53](assets/ch06N-Structural-Analysis/slide-053.png)

Determine the force in member $CF$ of the truss shown. Indicate whether the member is in tension or compression. Assume each member is pin connected.

**Solution:**

Section $aa$ will be used since this section will "expose" the internal force in member $CF$ as "external" on the free-body diagram of either the right or left portion of the truss. It is first necessary to determine the support reactions.

![ch06N-Structural-Analysis Slide 54](assets/ch06N-Structural-Analysis/slide-054.png)

The free-body diagram of the right portion of the truss is shown. There are three unknowns: $F_{FG}$, $F_{CF}$, and $F_{CD}$.

![ch06N-Structural-Analysis Slide 55](assets/ch06N-Structural-Analysis/slide-055.png)

**Equations of Equilibrium.** Apply the moment equation about point $O$ in order to eliminate the two unknowns $F_{FG}$ and $F_{CD}$. The location of point $O$ measured from $E$ can be determined from proportional triangles:

$$\frac{4}{4 + x} = \frac{6}{8 + x}, \quad x = 4\text{ m}$$

An easy way to determine the moment of $F_{CF}$ about point $O$ is to use the principle of transmissibility and slide $F_{CF}$ to point $C$, and then resolve $F_{CF}$ into its two rectangular components.

$$\circlearrowleft + \sum M_O = 0;$$

$$-F_{CF} \sin 45^\circ (12\text{ m}) + (3\text{ kN})(8\text{ m}) - (4.75\text{ kN})(4\text{ m}) = 0$$

$$F_{CF} = 0.589\text{ kN (C)}$$

---

### Example 6.7

![ch06N-Structural-Analysis Slide 56](assets/ch06N-Structural-Analysis/slide-056.png)

Determine the force in member $EB$ of the roof truss shown. Indicate whether the member is in tension or compression.

**Solution:**

By the method of sections, any imaginary section that cuts through $EB$ will also have to cut through three other members for which the forces are unknown. For example, section $aa$ cuts through $ED$, $EB$, $FB$, and $AB$. If a free-body diagram of the left side of this section is considered, it is possible to obtain $F_{ED}$ by summing moments about $B$ to eliminate the other three unknowns; however, $F_{EB}$ cannot be determined from the remaining two equilibrium equations. One possible way of obtaining $F_{EB}$ is first to determine $F_{ED}$ from section $aa$, then use this result on section $bb$, which is shown in the figure. Here the force system is concurrent and our sectioned free-body diagram is the same as the free-body diagram for the joint at $E$.

![ch06N-Structural-Analysis Slide 57](assets/ch06N-Structural-Analysis/slide-057.png)

![ch06N-Structural-Analysis Slide 58](assets/ch06N-Structural-Analysis/slide-058.png)

![ch06N-Structural-Analysis Slide 59](assets/ch06N-Structural-Analysis/slide-059.png)

---

## 6.5 Space Trusses

![ch06N-Structural-Analysis Slide 60](assets/ch06N-Structural-Analysis/slide-060.png)

A **space truss** consists of members joined together at their ends to form a 3D structure.

- The simplest space truss is a **tetrahedron**, formed by connecting six members.
- Additional members would be redundant in supporting force $P$.

![ch06N-Structural-Analysis Slide 61](assets/ch06N-Structural-Analysis/slide-061.png)

### Assumptions for Design

- Members of a space truss are treated as two-force members provided the external loading is applied at the joints and the joints consist of ball-and-socket connections.
- When the weight of the member is considered, apply it as a vertical force, half of its magnitude applied at each end of the member.

![ch06N-Structural-Analysis Slide 62](assets/ch06N-Structural-Analysis/slide-062.png)

![ch06N-Structural-Analysis Slide 63](assets/ch06N-Structural-Analysis/slide-063.png)

### Procedure for Analysis

![ch06N-Structural-Analysis Slide 64](assets/ch06N-Structural-Analysis/slide-064.png)

![ch06N-Structural-Analysis Slide 65](assets/ch06N-Structural-Analysis/slide-065.png)

---

### Example 6.8

![ch06N-Structural-Analysis Slide 66](assets/ch06N-Structural-Analysis/slide-066.png)

![ch06N-Structural-Analysis Slide 67](assets/ch06N-Structural-Analysis/slide-067.png)

![ch06N-Structural-Analysis Slide 68](assets/ch06N-Structural-Analysis/slide-068.png)

![ch06N-Structural-Analysis Slide 69](assets/ch06N-Structural-Analysis/slide-069.png)

---

## 6.6 Frames and Machines

![ch06N-Structural-Analysis Slide 70](assets/ch06N-Structural-Analysis/slide-070.png)

**Frames and Machines** are composed of pin-connected multi-force members.

- **Frames** are stationary and used to support loads.
- **Machines** have moving parts.
- Apply equations of equilibrium to each member to determine the unknown forces.

![ch06N-Structural-Analysis Slide 71](assets/ch06N-Structural-Analysis/slide-071.png)

### Free-Body Diagrams

- Isolate each part by drawing its outlined shape.
- Show all forces and/or couple moments acting on the part.
- Identify each known and unknown force and couple moment.
- Indicate any dimensions.
- Apply equations of equilibrium.
- Assume a sense for unknown force or couple moment.

### Example 6.9

![ch06N-Structural-Analysis Slide 72](assets/ch06N-Structural-Analysis/slide-072.png)

![ch06N-Structural-Analysis Slide 73](assets/ch06N-Structural-Analysis/slide-073.png)

![ch06N-Structural-Analysis Slide 74](assets/ch06N-Structural-Analysis/slide-074.png)

---

### Example 6.10

![ch06N-Structural-Analysis Slide 75](assets/ch06N-Structural-Analysis/slide-075.png)

![ch06N-Structural-Analysis Slide 76](assets/ch06N-Structural-Analysis/slide-076.png)

---

### Example 6.11

![ch06N-Structural-Analysis Slide 77](assets/ch06N-Structural-Analysis/slide-077.png)

![ch06N-Structural-Analysis Slide 78](assets/ch06N-Structural-Analysis/slide-078.png)

---

### Example 6.12

![ch06N-Structural-Analysis Slide 79](assets/ch06N-Structural-Analysis/slide-079.png)

![ch06N-Structural-Analysis Slide 80](assets/ch06N-Structural-Analysis/slide-080.png)

![ch06N-Structural-Analysis Slide 81](assets/ch06N-Structural-Analysis/slide-081.png)

---

### Example 6.13

![ch06N-Structural-Analysis Slide 82](assets/ch06N-Structural-Analysis/slide-082.png)

![ch06N-Structural-Analysis Slide 83](assets/ch06N-Structural-Analysis/slide-083.png)

---

### Procedure for Analysis

![ch06N-Structural-Analysis Slide 84](assets/ch06N-Structural-Analysis/slide-084.png)

![ch06N-Structural-Analysis Slide 85](assets/ch06N-Structural-Analysis/slide-085.png)

![ch06N-Structural-Analysis Slide 86](assets/ch06N-Structural-Analysis/slide-086.png)

---

### Example 6.14

![ch06N-Structural-Analysis Slide 87](assets/ch06N-Structural-Analysis/slide-087.png)

![ch06N-Structural-Analysis Slide 88](assets/ch06N-Structural-Analysis/slide-088.png)

---

### Example 6.15

![ch06N-Structural-Analysis Slide 89](assets/ch06N-Structural-Analysis/slide-089.png)

![ch06N-Structural-Analysis Slide 90](assets/ch06N-Structural-Analysis/slide-090.png)

---

### Example 6.16

![ch06N-Structural-Analysis Slide 91](assets/ch06N-Structural-Analysis/slide-091.png)

![ch06N-Structural-Analysis Slide 92](assets/ch06N-Structural-Analysis/slide-092.png)

![ch06N-Structural-Analysis Slide 93](assets/ch06N-Structural-Analysis/slide-093.png)

---

### Example 6.17

![ch06N-Structural-Analysis Slide 94](assets/ch06N-Structural-Analysis/slide-094.png)

![ch06N-Structural-Analysis Slide 95](assets/ch06N-Structural-Analysis/slide-095.png)

---

### Example 6.18

![ch06N-Structural-Analysis Slide 96](assets/ch06N-Structural-Analysis/slide-096.png)

![ch06N-Structural-Analysis Slide 97](assets/ch06N-Structural-Analysis/slide-097.png)

---

### Example 6.19

![ch06N-Structural-Analysis Slide 98](assets/ch06N-Structural-Analysis/slide-098.png)

![ch06N-Structural-Analysis Slide 99](assets/ch06N-Structural-Analysis/slide-099.png)

---

### Example 6.20

![ch06N-Structural-Analysis Slide 100](assets/ch06N-Structural-Analysis/slide-100.png)

![ch06N-Structural-Analysis Slide 101](assets/ch06N-Structural-Analysis/slide-101.png)

---

### Example 6.21

![ch06N-Structural-Analysis Slide 102](assets/ch06N-Structural-Analysis/slide-102.png)

![ch06N-Structural-Analysis Slide 103](assets/ch06N-Structural-Analysis/slide-103.png)

---

### Example 6.22

![ch06N-Structural-Analysis Slide 104](assets/ch06N-Structural-Analysis/slide-104.png)

![ch06N-Structural-Analysis Slide 105](assets/ch06N-Structural-Analysis/slide-105.png)

![ch06N-Structural-Analysis Slide 106](assets/ch06N-Structural-Analysis/slide-106.png)

![ch06N-Structural-Analysis Slide 107](assets/ch06N-Structural-Analysis/slide-107.png)

---

*Source: [ch06N Structural Analysis.pdf](../course-materials/ch06N%20Structural%20Analysis.pdf)*
