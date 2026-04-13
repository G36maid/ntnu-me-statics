# Chapter 09 Solutions - Center of Gravity and Centroid

> Source: [Solution_Chpter 09.pdf](../../course-materials/Solution_Chpter%2009.pdf)

---

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–1.
y
Locate the center of mass of the homogeneous rod bent
into the shape of a circular arc.
30(cid:2)
300mm
x
SOLUTION
dL = 300du
' 30(cid:2)
x = 300cos u
'
y = 300sin u
2p
' 3
xdL 300cos u(300du)
L L-2p
x = = 3
2p
dL 3
L
300du
L-2p
3
(300)2 C sin uD2 -3 p 2p
= 3
4
300a pb
3
= 124mm Ans.
y = 0 (By symmetry) Ans.
Ans:
x = 124 mm, y = 0
881

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–2.
y
Locate the centroid (x, y)of the uniform rod.Evaluate the
integrals using a numerical method.
y(cid:2) a cos –
p
– x
a
a
SOLUTION
Differential Element. The length of the element shown shaded in Fig.ais
x
dy 2
–a–
dL = 2dx2 + dy2 = 1 + a b dx 2
C dx
dy p p p
Here, = aa-sin xba b = -p sin x
dx a a a
p 2 p
dL = 1 + a-p sin xb dx = 1 + p2 sin2 x dx
C a C a
p
The centroid of the element is located at x = xand y = y = a cos x. Applying
c c a
Eq.9–5 we have
a>2 p
x~ dL x 1 + p2 sin2 x dx
L L B a 0.3444a2
x = L = 0 = = 0.299a Ans.
a>2 p 1.1524a
dL 1 + p2 sin2 x dx
L L L 0 B a
a>2 p p
y~d L a cos x 1 + p2 sin2 x dx
L L a B a 0.6191a2
y = L = 0 = = 0.537a Ans.
a>2 p 1.1524a
dL 1 + p2 sin2 x dx
L L L 0 B a
Ans:
x = 0.299a
y = 0.537a
882

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–3.
Locate the center of gravity x  of the homogeneous rod. If  y
| the rod has a weight per unit length of 100 N |     |     |     |     |     | m, determine  |     |     |     |
| --------------------------------------------- | --- | --- | --- | --- | --- | ------------- | --- | --- | --- |
1 m
the vertical reaction at A and the x and y components of
>
reaction at the pin B.
B
1 m
y (cid:31) x2
A x
Solution
| Length  |     | And  | Moment  | Arm.  | The  | length  of  | the  differential  | element  | is  |
| ------- | --- | ---- | ------- | ----- | ---- | ----------- | ------------------ | -------- | --- |
dy
|     |     |       |       |     | dy 2 |                         | ~            |     |        |
| --- | --- | ----- | ----- | --- | ---- | ----------------------- | ------------ | --- | ------ |
| dL  | =   | dx2 + | dy2 = | 1 + |      | dx and its centroid is  | x = x. Here  |     | = 2x.  |
|     |     |       |       |     | dx   |                         |              |     | dx     |
2
| Perform the integrationcA |     |     |     |     | a b d |     |     |     |     |
| ------------------------- | --- | --- | --- | --- | ----- | --- | --- | --- | --- |
1 m
|     |     |  L  | dL  |     | 1 4x2 dx |     |     |     |     |
| --- | --- | --- | --- | --- | -------- | --- | --- | --- | --- |
|     |     | =   | =   |     | +        |     |     |     |     |
|     |     | LL  |     | L0  |          |     |     |     |     |
2
1 m
1
|     |     |     |  =  | 2   | x2  |  dx |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|     |     |     |     |     | +   | 4   |     |     |     |
L0
A
|     |     |     |     |     | 1   | 1        | 1 1 m |     |     |
| --- | --- | --- | --- | --- | --- | -------- | ----- | --- | --- |
|     |     |     |     | x2  |     |          | x2    |     |     |
|     |     |     |  =  | x   | + + |  ln  x + | +     |     |     |
|     |     |     |     |     | 4   | 4        | 4     |     |     |
0
|     |     |     |  =  | 1.4789 m c A |     | a A | bd  |     |     |
| --- | --- | --- | --- | ------------ | --- | --- | --- | --- | --- |
1 m
|     |     |     | ~      |     | 4x2 dx |     |     |     |     |
| --- | --- | --- | ------ | --- | ------ | --- | --- | --- | --- |
|     |     |     | x dL = |     | x 1 +  |     |     |     |     |
|     |     | LL  |        | L0  |        |     |     |     |     |
2
1 m
1
|     |     |     |  =  | 2   | x x2 |  dx |     |     |     |
| --- | --- | --- | --- | --- | ---- | --- | --- | --- | --- |
+
|     |     |     |     | L0  |     | 4   |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
A
|     |     |     |     |      | 32  | 1 m |     |     |     |
| --- | --- | --- | --- | ---- | --- | --- | --- | --- | --- |
|     |     |     |     | 2    | 1   |     |     |     |     |
|     |     |     |  =  |   x2 | +   |     |     |     |     |
|     |     |     |     | 3    | 4 > |     |     |     |     |
0
|     |     |     |     | c a       | b   | d   |     |     |     |
| --- | --- | --- | --- | --------- | --- | --- | --- | --- | --- |
|     |     |     |  =  | 0.8484 m2 |     |     |     |     |     |
Centroid.
~
|     |     | 1L  | xdL | 0.8484 m2 |     |          |          |     |      |
| --- | --- | --- | --- | --------- | --- | -------- | -------- | --- | ---- |
|     |     | x   |     |           |     | 0.5736 m | 0.574 m  |     | Ans. |
|     |     | =   |     | =         | =   | =        |          |     |      |
|     |     | 1L  | dL  | 1.4789 m  |     |          |          |     |      |
Equations of Equilibrium. Refering to the FBD of the rod shown in Fig. a
| + ΣF |     | 0;  |                      |                      | B       | 0       |     |     | Ans. |
| ---- | --- | --- | -------------------- | -------------------- | ------- | ------- | --- | --- | ---- |
| S    | x = |     |                      |                      | x       | =       |     |     |      |
| a+ΣM |     | 0;  | 100(1.4789) (0.4264) |                      |         | A (1) 0 |     |     |      |
|      | B   | =   |                      |                      | -       | y =     |     |     |      |
|      |     |     |                      | A                    | 63.06 N | 63.1 N  |     |     | Ans. |
|      |     |     |                      |                      | y =     | =       |     |     |      |
| a+ΣM |     | 0;  | B (1)                | 100(1.4789) (0.5736) |         | 0       |     |     |      |
|      | A   | =   | y                    | -                    |         | =       |     |     |      |
|      |     |     |                      | B                    | 84.84 N | 84.8 N  |     |     | Ans. |
|      |     |     |                      |                      | y =     | =       |     |     |      |
Ans:
x = 0.574 m
B = 0
x
A = 63.1 N
y
B = 84.8 N
y
883

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–4.
Locate the center of gravity y  of the homogeneous rod. y
1 m
B
1 m
y (cid:31) x2
A x
Solution
| Length  | And  | Moment  | Arm.  | The  | length  | of  the  | differential  | element  | is  |
| ------- | ---- | ------- | ----- | ---- | ------- | -------- | ------------- | -------- | --- |
dy
|      |       |       |     | dy 2 |                         |     | ~            |     |        |
| ---- | ----- | ----- | --- | ---- | ----------------------- | --- | ------------ | --- | ------ |
| dL = | dx2 + | dy2 = | 1 + |      | dx and its centroid is  |     | y = y. Here  |     | = 2x.  |
|      |       |       |     | dx   |                         |     |              |     | dx     |
2
| Perform the integrationc,A |     |     | a   | b d |     |     |     |     |     |
| -------------------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
1 m
|     |  L  | dL  |     | 4x2 dx |     |     |     |     |     |
| --- | --- | --- | --- | ------ | --- | --- | --- | --- | --- |
|     | =   | =   |     | 1 +    |     |     |     |     |     |
|     | LL  | L   |     |        |     |     |     |     |     |
0 2
1 m
1
|     |     |  = 2 |     | x2  |  dx |     |     |     |     |
| --- | --- | ---- | --- | --- | --- | --- | --- | --- | --- |
+ 4
L0
A
|     |     |     |     | 1   | 1      |     | 1 1 m |     |     |
| --- | --- | --- | --- | --- | ------ | --- | ----- | --- | --- |
|     |     |     | x2  |     |        | x2  |       |     |     |
|     |     |  =  | x   | + + |  ln  x | +   | +     |     |     |
|     |     |     |     | 4   | 4      |     | 4     |     |     |
0
|     |     |  = 1.4789 m c | A   |     | a   | A   | bd  |     |     |
| --- | --- | ------------- | --- | --- | --- | --- | --- | --- | --- |
1 m
|     | ~    | x2  |     | 4x2 dx |     |     |     |     |     |
| --- | ---- | --- | --- | ------ | --- | --- | --- | --- | --- |
|     | y dL | =   | 1 + |        |     |     |     |     |     |
| LL  |      | L0  |     |        |     |     |     |     |     |
2
1 m
1
|     |     |  = 2 | x2 x2 |  dx |     |     |     |     |     |
| --- | --- | ---- | ----- | --- | --- | --- | --- | --- | --- |
+
|     |     | L0  |     | 4   |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
A
1 m
|     |     | x   |      | 1 3 | 1     | 1   | 1        |     | 1   |
| --- | --- | --- | ---- | --- | ----- | --- | -------- | --- | --- |
|     |     | = 2 | x2 + | -   |  x x2 | + - |  ln  x + | x2  | +   |
|     |     | 4   |      | 4   | 32    | 4   | 128      |     | 4   |
0
|     |     | c Aa |     | b   | A   |     | a   | A   | bd  |
| --- | --- | ---- | --- | --- | --- | --- | --- | --- | --- |
 = 0.6063 m2
Centroid.
|     |     | y~ dL | 0.6063 m2 |     |     |     |     |     |     |
| --- | --- | ----- | --------- | --- | --- | --- | --- | --- | --- |
1 L
|     | y = |   = |          | =   | 0.40998 m | = 0.410 m  |     |     | Ans. |
| --- | --- | --- | -------- | --- | --------- | ---------- | --- | --- | ---- |
|     |     | dL  | 1.4789 m |     |           |            |     |     |      |
1 L
Ans:
y = 0.410 m
884

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–5.
Determine the distance y  to the center of gravity of the  y
homogeneous rod. 1 m
y (cid:31) 2x3
2 m
Solution
x
| Length  | And  Moment  | Arm.  | The  length  | of  the             | differential  element  | is        |
| ------- | ------------ | ----- | ------------ | ------------------- | ---------------------- | --------- |
|         |              | dy    | 2            |                     | ~                      |           |
| dL =    | dx2 + dy2 =  | 1 +   |  dx          | and  its  centroid  | is  at  y =            | y.  Here  |
dx
dy 2
6x2. Evaluate the ainAtegral anumberibcally,
=
dx
1 m
|     |  L dL | 1   | 36x4 dx | 2.4214 m |     |     |
| --- | ----- | --- | ------- | -------- | --- | --- |
|     | =     | =   | +       | =        |     |     |
|     | LL    | L0  |         |          |     |     |
2
1 m
|     |   y~ dL = | 2x3 1 | 36x4 dx | = 2.0747 m2 |     |     |
| --- | --------- | ----- | ------- | ----------- | --- | --- |
+
|     | LL  | L0  |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
2
Centroid. Applying Eq. 9–5,
~
|     | 1L  ydL | 2.0747 m2 |        |          |     |      |
| --- | ------- | --------- | ------ | -------- | --- | ---- |
|     | y       |           | 0.8568 | 0.857 m  |     | Ans. |
|     | =       | =         | =      | =        |     |      |
|     | 1L  dL  | 2.4214 m  |        |          |     |      |
Ans:
y = 0.857 m
885

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–6.
Locate the centroid yof the area. y
y 1––x2 1
4
1m
x
2m
SOLUTION
| Area and Moment Arm: |        | The area of the differential element is |       |           |     |
| -------------------- | ------ | --------------------------------------- | ----- | --------- | --- |
|                      | 1      |                                         | ' y 1 | 1         |     |
| dA = ydx             | = a1 - | x2bdxand its centroid is                | y = = | a1 - x2b. |     |
|                      | 4      |                                         | 2 2   | 4         |     |
Centroid:Due to symmetry
|     |     | x = 0 |     |     | Ans. |
| --- | --- | ----- | --- | --- | ---- |
Applying Eq.9–4 and performing the integration,we have
|     |     | 2m 1 | 1 1    |     |     |
| --- | --- | ---- | ------ | --- | --- |
|     | '   |      | x2 x2  |     |     |
|     | ydA | 1 -  | 1 -    | dx  |     |
|     |     | 2 ¢  | 4 ≤¢ 4 | ≤   |     |
|     | LA  | L-2m |        |     |     |
|     | y = | =    |        |     |     |
2m
|     |     | dA  | 1   |     |     |
| --- | --- | --- | --- | --- | --- |
1 - x2 dx
|     | LA  | ¢   | 4 ≤ |     |     |
| --- | --- | --- | --- | --- | --- |
L-2m
|     |     | x x3 x5 | 2m  |     |     |
| --- | --- | ------- | --- | --- | --- |
`
|     |     | - +        |     |     |     |
| --- | --- | ---------- | --- | --- | --- |
|     |     | ¢2 12 160≤ | 2   |     |     |
-2m
|     |     | =   | = m |     | Ans. |
| --- | --- | --- | --- | --- | ---- |
x3 2m 5
`
x -
|     |     | ¢ 12≤ |     |     |     |
| --- | --- | ----- | --- | --- | --- |
-2m
Ans:
2
y =  m
5
886

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–7.
Locate the centroid xof the shaded area.Solve the problem by y
evaluating the integrals using Simpson’s rule.
y=0.5ex2
SOLUTION
At x = 1m
0.5e12
| y =  | = 1.359m |         |           |          |     |     |
| ---- | -------- | ------- | --------- | -------- | --- | --- |
|      | 1        | 1       |           |          |     | x   |
|      |          | a1.359  | 0.5ex2bdx | 0.6278m2 |     |     |
| dA = | (1.359 - | y)dx  = | =         | =        |     |     |
1m
| LA  | L0  | L0  |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
x = x
1
| xdA | x a1.359 | 0.5ex2b dx |     |     |     |     |
| --- | -------- | ---------- | --- | --- | --- | --- |
|     | =        | -          |     |     |     |     |
| LA  | L0       |            |     |     |     |     |
0.25 m3
=
xdA
0.25
| x LA |     | 0.398m |     |     | Ans. |     |
| ---- | --- | ------ | --- | --- | ---- | --- |
| =    | =   | =      |     |     |      |     |
0.6278
dA
LA
Ans:
x = 0.398 m
887

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–8.
Locate the centroid yof the shaded area.Solve the problem by y
evaluating the integrals using Simpson’s rule.
y=0.5ex2
SOLUTION
|     | 1        |        | 1   |          |                       |     |
| --- | -------- | ------ | --- | -------- | --------------------- | --- |
| dA  | = (1.359 | - y)dx | =   | a1.359 - | 0.5ex2b dx = 0.6278m2 |     |
| LA  | L0       |        | L0  |          |                       |     |
|     | 1.359 y  |        |     |          |                       |     |
+ x
y =
2
1m
|     | 1   | 0.5ex2  |          |         |     |     |
| --- | --- | ------- | -------- | ------- | --- | --- |
|     |     | 1.359 + |          |         |     |     |
| ydA |     | a       | bA 1.359 | 0.5ex2B | dx  |     |
|     | =   |         |          | -       |     |     |
| LA  | L0  | 2       |          |         |     |     |
1
|     | 1   | a1.847 | 0.25e2x2b | 0.6278 m3 |     |     |
| --- | --- | ------ | --------- | --------- | --- | --- |
|     | =   | -      |           | dx =      |     |     |
2
L0
ydA
|     | LA  | 0.6278  |     |     |     |      |
| --- | --- | ------- | --- | --- | --- | ---- |
| y = | =   | = 1.00m |     |     |     | Ans. |
0.6278
dA
LA
Ans:
y = 1.00 m
888

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–9. Locate the centroid x of the parabolic area.
y
h
y (cid:31) ax2
SOLUTION
x
b
Differential Element:The area element parallel to the xaxis shown shaded in Fig.a
will be considered.The area of the element is
a
dA = xdy =
y1>2dy
h1>2
Centroid:The centroid of the element is located at
'
x =
x
=
a y1>2and '
y = y.
2 2h1>2
Area:Integrating,
A = dA =
h a y1>2dy
=
2a A y3>2B h
=
2
ah Ans.
LA L0
h1>2 3h1>2 2
0
3
x =
LA
'
xdA
=
L0
h
¢2h
a
1>2
y1>2
≤¢h
a
1>2
y1>2dy
≤
=
L0
h
2
a
h
2
ydy
=
2
a
h
2
¢
y
2
2
≤
` h
0
=
3
a Ans.
2 2 2 8
dA ah ah ah
3 3 3
LA
Ans:
3
x = a
8
889

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–10.
Locate the centroid of the shaded area. y
px
y (cid:31) a cos
L
a
x
L  L
2 2
Solution
Area And Moment Arm. The area of the differential element shown shaded in
|              |     |        | p                               |     | y a       | p   |
| ------------ | --- | ------ | ------------------------------- | --- | --------- | --- |
| Fig. a is dA | ydx | a cos  |  x dx and its centroid is at y~ |     |           |  x. |
|              | =   | =      |                                 |     | = =  cos  |     |
|              |     |        | L                               |     | 2 2       | 2   |
Centroid. Perform the integration
L2
|     |     |       | a      | p              | p     |     |
| --- | --- | ----- | ------ | -------------- | ----- | --- |
|     |     |       |        |  cos  x a cos  |  x dx |     |
|     |     | ~ ydA | > 2    | L              | L     |     |
|     | 1A  |       | L -L 2 |                |       |     |
|  y  | =   | =     |        |                |       |     |
|     |     |       | a      | L2 ba          | b     |     |
|     | 1A  | dA    | >      |                | p     |     |
|     |     |       |        |  a cos         |  x dx |     |
|     |     |       |        | >              | L     |     |
L -L 2
>
|     |     |     | L2 a2 | 2p       |         |     |
| --- | --- | --- | ----- | -------- | ------- | --- |
|     |     |     |       |   cos  x | + 1  dx |     |
>
|     |     |     | L 4  | L             |     |     |
| --- | --- | --- | ---- | ------------- | --- | --- |
|     |     |  =  | -L 2 |               |     |     |
|     |     |     |      | La2           | b   |     |
|     |     |     | >    | p             |     |     |
|     |     |     |      |  a cos   x dx |     |     |
>
|     |     |     | L   | L   |     |     |
| --- | --- | --- | --- | --- | --- | --- |
-L 2
>
|     |     |     | a2   |            | L2  |     |
| --- | --- | --- | ---- | ---------- | --- | --- |
|     |     |     | L    | 2p         |     |     |
|     |     |     |      |  sin   x + | x   |     |
|     |     |     | 4 2p | L          | >   |     |
-L2
 =
|     |     |     | a aL | p L2b` |     |     |
| --- | --- | --- | ---- | ------ | --- | --- |
>
|     |     |     |     |  sin   x |     |     |
| --- | --- | --- | --- | -------- | --- | --- |
|     |     |     | p   | L        | >   |     |
-L2
|     |     |     | a   | b`  | >   |     |
| --- | --- | --- | --- | --- | --- | --- |
a2 L
|     |     |     | 4     | p     |     |      |
| --- | --- | --- | ----- | ----- | --- | ---- |
|     |     |  =  |       | =  a  |     | Ans. |
|     |     |     | 2aL p | 8     |     |      |
>
>
Due to Symmetry,
|     |     |     |     | x = 0  |     | Ans. |
| --- | --- | --- | --- | ------ | --- | ---- |
Ans:
p
y =  a
8
x = 0
890

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–11.
Locate the centroid x of the shaded area. y
4 m
y (cid:31) 1 x2
4
x
4 m
Solution
Area And Moment Arm. The area of the differential element shown shaded in Fig. a
is dA = x dy and its centroid is at ~ x = 1 x. Here, x = 2y12
2
>
Centroid. Perform the integration
4 m1
~ 2y12 2y12 dy
x =
1A x dA
=
L0 2
> >
1A dA a4 m
2y
b
1
a
2 dy
b
L0
>
3
= m Ans.
2
Ans:
3
x = m
2
891

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–12.
Locate the centroid y of the shaded area. y
4 m
y (cid:31) 1 x2
4
x
4 m
Solution
Area And Moment Arm. The area of the differential element shown shaded in Fig. a
is dA = x dy and its centroid is at ∼y = y. Here, x = 2y12.
>
Centroid. Perform the integration
4 m
~ y 2y12 dy
y =
1A y dA
=
L0
>
1A dA 4 ma
2y12 dy
b
L0
>
4 4 m
y52
5
= > 0
a4 b`4 m
y32
3
> 0
a b`
12
= m Ans.
5
Ans:
12
y = m
5
892

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–13.
y
Locate the centroid xof the area.
h
y (cid:31) —     x2
b2
h
x
b
SOLUTION
dA = y dx
'
 x x
=
|      |          |     | b h     |     | h b      |      |
| ---- | -------- | --- | ------- | --- | -------- | ---- |
|      |   ' x dA |     |   x3 dx |     | x4       |      |
|      |          |     | 2       |     | B4 b2  R |      |
|      | LA       |     | L0 b    |     | 0 3      |      |
|  x = |          | =   |         | =   | = b      | Ans. |
|      |          |     | b       |     | b 4      |      |
|      |          |     | h       |     | h        |      |
|      |  dA      |     |   x2 dx |     | x3       |      |
|      |          |     | b2      |     | B3b2  R  |      |
|      | LA       |     | L0      |     | 0        |      |
Ans:
3
x =  b
4
893

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–14.
y
Locate the centroid yof the shaded area.
h
y (cid:31) —     x2
b2
h
SOLUTION
x
b
 dA = y dx
y
'
 y =
2
|     |        |     | b h 2 |     | h 2    | b    |      |
| --- | ------ | --- | ----- | --- | ------ | ---- | ---- |
|     | '      |     | x4 dx |     | x5     |      |      |
|     |   y dA |     |   4   |     | 4      |      |      |
|     |        |     | 2 b   |     | B1 0 b | R 3  |      |
|  y  | LA     | L0  |       |     |        | 0 h  | Ans. |
| =   |        | =   |       | =   |        | = 0  |      |
|     |        |     | b h   |     | h      | b 1  |      |
|     |  dA    |     | x2 dx |     | x3     |      |      |
|     |        |     |   b2  |     | B3b2   |      |      |
|     | LA     |     |       |     |        | R 0  |      |
L0
Ans:
3
y =  h
10
894

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–15.
Locate the centroid xof the shaded area. y
4 m
y 4 – 1 – x2
16 x
8 m
SOLUTION
1
dA = 14 - y2dx = a
16
x2b dx
'
x = x
' xdA
8
x a
x2
b dx
16
x =
LA
=
L0
8 1
dA a x2b dx
LA L0 16
x = 6 m Ans.
Ans:
x = 6 m
895

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–16.
Locate the centroid yof the shaded area. y
4 m
y 4 – 1 – x2
16 x
8 m
SOLUTION
1
dA = 14 - y2dx = a
16
x2b dx
4 + y
y =
2
1 8 x2 x2
' ydA
2 ¢
8 -
16
ba
16
b dx
y =
LA
=
L0
8 1
dA a x2b dx
LA L0 16
y = 2.8 m Ans.
Ans:
y = 2.8 m
896

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–17.
Locate the centroid yof the shaded area.
y
y – h –xn
an
h
SOLUTION
dA = ydx
x
a
y
y =
2
a
| '    | 1 h2 x2ndx |                 |           |      |
| ---- | ---------- | --------------- | --------- | ---- |
| ydA  |            | h2(a2n+1)       |           |      |
|      | 2 a2n      | 2a2 n( 2 n + 1) | h n + 1   |      |
| y LA | L0         |                 |           | Ans. |
| =    | = a        | = n+ 1)         | = n       |      |
|      |            | h ( a           | 2( 2 + 1) |      |
| dA   | h xndx     | an(n + 1)       |           |      |
a n
| LA  | L0  |     |     |     |
| --- | --- | --- | --- | --- |
Ans:
hn 1
y +
=
2(2n + 1)
897

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–18.
y
Locate the centroid yof the area.
–2
y (cid:2) x –
3
4 m
x
8 m
SOLUTION
Area:Integrating the area of the differential element gives
8 m
|     |      | 8 m | 3                  | 2   |           |     |      |
| --- | ---- | --- | ------------------ | --- | --------- | --- | ---- |
| =   |      | =   | x2>3 dx = c  x5>3d |     | = 19.2 m2 |     |      |
| A   |   dA |     |                    |     |           |     | Ans. |
|     | L    | L0  | 5                  | 0   |           |     |      |
A
|           |                                            |     |     |     |     | '       | 1                  |
| --------- | ------------------------------------------ | --- | --- | --- | --- | ------- | ------------------ |
| Centroid: | The centroid of the element is located at  |     |     |     |     | y = y>2 | =  x2>3. Applying  |
2
Eq.9–4,we have
|     |     |     | 8 m            |     | 8 m       |     |     |
| --- | --- | --- | -------------- | --- | --------- | --- | --- |
|     | '   |     | 1  x2>3A x2>3B |     | 1  x4>3dx |     |     |
|     | y   | dA  |                | dx  |           |     |     |
|     |     | L   |                | L   |           |     |     |
|     | L A |     | 0 2            |     | 0 2       |     |     |
| y   | =   | =   |                | =   |           |     |     |
|     |     |     | 19.2           |     | 19.2      |     |     |
dA
L
A
8 m
|     | c 3 | 7>3d 2 |     |     |     |     |     |
| --- | --- | ------ | --- | --- | --- | --- | --- |
 x
14
0
|     | =   |     | = 1.43 m |     |     |     | Ans. |
| --- | --- | --- | -------- | --- | --- | --- | ---- |
19.2
m
Ans:
19.2 m2, y
A = = 1.43 m
898

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–19.
Locate the centroid x of the shaded area. y
h
y(cid:31) (cid:29)    x2(cid:28)h
a2
h
x
a
Solution
Area And Moment Arm. The area of the differential element shown shaded in Fig. a
h
|              |  x2 |                                | ~      |     |
| ------------ | --- | ------------------------------ | ------ | --- |
| is dA = y dx | = - | + h dx and its centroid is at  | x = x. |     |
a2
Centroid. Performa the integratbion,
a h
|     |              | x   x2 h | dx  |     |
| --- | ------------ | -------- | --- | --- |
|     | ~            | - +      |     |     |
|     | 1 A   x  d A | L0 a2    |     |     |
|     |  x =         | =        |     |     |
|     |              | a a      | b   |     |
|     | 1  d A       | h  x2    |     |     |
|     | A            | - + h    | dx  |     |
L0 a2
|     |     | a           | b   |     |
| --- | --- | ----------- | --- | --- |
|     |     | h h         | a   |     |
|     |     | -  x4 +  x2 |     |     |
|     |     | 4a2 2       |     |     |
0
 =
|     |     | a h ba` |     |     |
| --- | --- | ------- | --- | --- |
|     |     |  x3 hx  |     |     |
- +
|     |     | 3a2  | 0   |     |
| --- | --- | ---- | --- | --- |
|     |     | a b` |     |     |
3
|     |  =  |  a  |     | Ans. |
| --- | --- | --- | --- | ---- |
8
Ans:
3
x =  a
8
899

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–20.
Locate the centroid y of the shaded area. y
h
y(cid:31) (cid:29)    x2(cid:28)h
a2
h
x
a
Solution
Area And Moment Arm. The area of the differential element shown shaded in Fig. a
|         |        |       |                                |     |     | y h2      |       |
| ------- | ------ | ----- | ------------------------------ | --- | --- | --------- | ----- |
|         |        | h     |                                |     | ~   | 1         |       |
| is dA = | y dx = | -  x2 | + h dx and its centroid is at  |     | y = | =   -  x2 | + h . |
|         |        | a2    |                                |     |     | 2 2 a     |       |
Centroid. Performa the integratbion,
|     |        |        |         |     |     | a   | b   |
| --- | ------ | ------ | ------- | --- | --- | --- | --- |
|     |        |        | a 1 h   |     | h   |     |     |
|     |        |        |  x2     |     |  x2 |     |     |
|     | ~      |        |     - + | h - | + h | dx  |     |
|     | 1      | y  d A | L0 2 a2 |     | a2  |     |     |
|     |  y A   |        |         |     |     |     |     |
|     | =      | =      | a a     | ba  |     | b   |     |
|     | 1      |  d A   | h       |  x2 |     |     |     |
|     | A      |        | -       | + h | dx  |     |     |
a2
L0
|     |     |     | a         |     | b   |     |     |
| --- | --- | --- | --------- | --- | --- | --- | --- |
|     |     |     | 1 h2 2h2  |     | a   |     |     |
|     |     |     |    x5  x3 | h2x |     |     |     |
|     |     |     | 5a4 - 3a2 | +   |     |     |     |
|     |     |     | 2         |     | 0   |     |     |
 =
|     |     |     | a h | a   | b`  |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
 x3
|     |     |     | - + | hx  |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
3a2
0
|     |     |     | a   | b`  |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
2
|     |     |  =  |  h  |     |     |     | Ans. |
| --- | --- | --- | --- | --- | --- | --- | ---- |
5
Ans:
2
y =  h
5
900

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–21.
y
Locate the centroid xof the area.
xy(cid:2) c2

SOLUTION
Differential Element:The element parallel to the yaxis shown shaded in Fig.awill
be considered.The area of the element is x
a
c2
|     | =    | =   |     |     |     |     |     |     |
| --- | ---- | --- | --- | --- | --- | --- | --- | --- |
| dA  | y dx |  dx |     |     |     |     |     | b   |
x
'
| Centroid:The centroid of the element is located at x |     |     |     |     |     | = x |     |     |
| ---------------------------------------------------- | --- | --- | --- | --- | --- | --- | --- | --- |
Area:Integrating,
b
|     |     | c2  |       | 2 b     | b        |     |     |     |
| --- | --- | --- | ----- | ------- | -------- | --- | --- | --- |
| A = | dA  | =   |  dx = | c2 ln x | = c2 ln  |     |     |     |
|     |     | x   |       |         | a        |     |     |     |
|     | L A | L a |       | a       |          |     |     |     |
We have
|     |       |     | b c2    |     | b     | b   |       |     |
| --- | ----- | --- | ------- | --- | ----- | --- | ----- | --- |
|     | '     |     |         |     |       | 2   |       |     |
|     |  x dA |     | x a dxb |     | c2 dx | c2x |       |     |
|     | L     | L   | x       | L   |       |     | b - a |     |
| =   | A     | = a |         | =   | a =   | a = |       |     |
 x Ans.
|     |     |     | b      |     | b      | b        | b     |     |
| --- | --- | --- | ------ | --- | ------ | -------- | ----- | --- |
|     |  dA |     | c2 ln  |     | c2 ln  | c2 ln    | ln    |     |
|     |     |     |   a    |     |   a    | a        |       |     |
|     | L A |     |        |     |        |          | a     |     |
Ans:
b - a
x =
b
ln
a
901

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–22.
y
Locate the centroid yof the area.
xy(cid:2) c2

SOLUTION
x
Differential Element:The element parallel to the yaxis shown shaded in Fig.awill
a
be considered.The area of the element is
b
c2
| dA  | = y dx | =  dx |     |     |     |     |
| --- | ------ | ----- | --- | --- | --- | --- |
x
2
|                                                      |     |     |     |     | ' y c |     |
| ---------------------------------------------------- | --- | --- | --- | --- | ----- | --- |
| Centroid:The centroid of the element is located at y |     |     |     |     | = = . |     |
2 2x
Area:Integrating,
|     |      | b   | c2        | b   |          |      |
| --- | ---- | --- | --------- | --- | -------- | ---- |
|     | =    | =   | = c2 ln x | 2 = | c2 ln  b |      |
| A   |   dA |     |  dx       |     |          | Ans. |
|     | L    | L   | x         |     | a        |      |
|     | A    | a   |           | a   |          |      |
We have
|     |       |     | b c2 c2      |     | b c4   |     |
| --- | ----- | --- | ------------ | --- | ------ | --- |
|     |       |     | a   ba   dxb |     |        |     |
|     |  y dA |     |              |     |  dx    |     |
|     | L c   |     | L 2x x       |     | L 2x2  |     |
|  y  | = A   | =   | a            | =   | a      |     |
|     |       |     | b            |     | b      |     |
|     |  dA   |     | c2 ln        |     | c2 ln  |     |
|     | L     |     |   a          |     |   a    |     |
A
b
c4
3
-
2x
c2(b -
|     |        | a         | a)  |     |     |      |
| --- | ------ | --------- | --- | --- | --- | ---- |
|     | =      | =         |     |     |     | Ans. |
|     |        | b         | b   |     |     |      |
|     | c2 ln  |           |     |     |     |      |
|     |        |   2ab ln  |     |     |     |      |
|     |        | a         | a   |     |     |      |
Ans:
b
c2ln
A =
a
c2(b - a)
y
=
b
2ab ln
a
902

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–23.
y
Locate the centroid xof the area.
h
y   h    —    xn
an
h
SOLUTION
x
a
 dA = y dx
'
 x = x
a
h
|   ' x dA |   hx - | xn+1  dx |     |
| -------- | ------ | -------- | --- |
|          | ¢      | an  ≤    |     |
| LA       | L0     |          |     |
|  x =     | =      |          |     |
a
h
|  dA |   h       | xn  dx |     |
| --- | --------- | ------ | --- |
|     | -         | n      |     |
| LA  | L0 ¢      | a ≤    |     |
| h   | h1xn+22 a |        |     |
x2
| B2  - an1n | 22R |     |     |
| ---------- | --- | --- | --- |
+
|  =  | 0   |     |     |
| --- | --- | --- | --- |
h1xn+12 a
| hx -   |       |     |     |
| ------ | ----- | --- | --- |
| B an1n | + 12R |     |     |
0
| a h h | ba2 |     |     |
| ----- | --- | --- | --- |
-
| 2 n + | 2 a(1 | + n) |      |
| ----- | ----- | ---- | ---- |
|  x    |       |      | Ans. |
| =     | =     |      |      |
| h     | 2(2   | + n) |      |
| ah -  | ba    |      |      |
n 1
+
Ans:
a(1 + n)
x =
2(2 + n)
903

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–24.
y
Locate the centroid yof the area.
h
y   h    —    xn
an
h
x
a
SOLUTION
 dA y dx
=
y
'
 y =
2
| 1         | a h2   | h2         |     |
| --------- | ------ | ---------- | --- |
| '         |   h2 2 | xn x2n  dx |     |
|   y dA 2  | -  an  | + a2n      |     |
|           | L0 ¢   | ≤          |     |
 y LA
| = = |       |        |     |
| --- | ----- | ------ | --- |
|     | a     | h      |     |
|  dA |       | xn     |     |
|     |   h - | n   dx |     |
| LA  | ¢     | a ≤    |     |
L0
| 2h21xn+12 | h21x2n+12 | a   |     |
| --------- | --------- | --- | --- |
1
| h2x -     | +         |     |     |
| --------- | --------- | --- | --- |
| 2  B an1n | 12 a2n12n | 12R |     |
|           | +         | + 0 |     |
 =
h1xn+12
a
hx
- an1n 12R
| B   | + 0 |     |     |
| --- | --- | --- | --- |
2n2
12  h
| 21n + 1212n | + hn |     |      |
| ----------- | ---- | --- | ---- |
|  y =        | =    |     | Ans. |
| n           | 2n + | 1   |      |
n 1
+
Ans:
hn
y =
2n 1
+
904

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–25. y
If the density at any point in the quarter circular plate is x2(cid:4) y2 (cid:2) r2
defined by r = r xy,where r is a constant,determine the
0 0
mass and locate the center of mass (x,y) of the plate.The
plate has a thickness t.
r
x
SOLUTION
Differential Element:The element parallel to the y axis shown shaded in Fig.awill
be considered.The mass of this element is
dm = r dV = r xy(ty dx)
0
= r txy2dx
0
= r t(r2x - x3) dx
0
Mass:Integrating,
m = dm = r r t(r2x - x3) dx = r ta r 2x 2 - x 4 b2 r = 1 r r4 t Ans.
L L 0 0 2 4 4 0
m 0 0
Center of Mass:The center of mass of the element is located at x = x.Applying
c
Eq.9–2 we have
r r
x~ dm xcr t(r2x - x3)dxd r tar2x2 - x4bdx
L L
0
L
0
x = m = 0 = 0
1 1
dm r r4 t r r4t
L 4 0 4 0
m
r ta r 2x 3 - x5 b2 r
= 0 3 5 0 = 8 r Ans.
1 15
r r4t
4 0
By considering the element parallel to the x axis shown shaded in Fig. b,
dm = r dV = r xy(tx dy) = r tx2y dy = r t(r2y - y3) dy. In this case, y = y.
0 0 0 c
Applying Eq.9–2,we have
r r
y~ dm ycr t(r2y - y3)dyd r t(r2y2 - y4) dy
L L
0
L
0
8
y = m = 0 = 0 = r Ans.
1 1 15
dm r r4 t r r4t
L 4 0 4 0
m
Ans:
1
m = 4 r 0 r4t
8
x = r
15
8
y = r
15
905

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
y
9–26.
Locate the centroid xof the area.
p
y (cid:2) a cos –   –  x
a
a
SOLUTION
x
Differential Element:The element parallel to the yaxis shown shaded in Fig.awill
be considered.The area of the element is –a–
2
p
|     | =     | =      |        |     |     |     |     |
| --- | ----- | ------ | ------ | --- | --- | --- | --- |
| dA  | ydx   | a cos  |  xdx   |     |     |     |     |
a
'
| Centroid:The centroid of the element is located at x |     |     |     |     | =   | x.  |     |
| ---------------------------------------------------- | --- | --- | --- | --- | --- | --- | --- |
Area:Integrating,
|     |     | a>2 | p   | a2  | p   | a>2 a2 |     |
| --- | --- | --- | --- | --- | --- | ------ | --- |
2
| A   | = dA | = a cos  | x dx | =   |  sin    x | =   | Ans. |
| --- | ---- | -------- | ---- | --- | --------- | --- | ---- |
|     | L    | L        | a    | p   | a         | p   |      |
|     | A    | 0        |      |     |           | 0   |      |
We have
|     | a>2' |     | a>2      |       |     | a>2           |     |
| --- | ---- | --- | -------- | ----- | --- | ------------- | --- |
|     |      |     |          | p     |     | p             |     |
|     |      |     | xaa cos  | x dxb |     |               |     |
|     | x dA |     |          | a     |     | ax cos   x dx |     |
|     | L    | L   |          |       |     | L a           |     |
| x   | = 0  | = 0 |          |       | =   | 0             |     |
|     |      |     |          | a2    |     | a2            |     |
  dA
|     | L   |     |     | p   |     | p   |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
A
|     | a 2 p    | a3      | p          | 2 a>2 |       |     |      |
| --- | -------- | ------- | ---------- | ----- | ----- | --- | ---- |
|     |   x sin  | x +     |    cos  x  |       |       |     |      |
|     | p        | a  p  2 | a          |       |       |     |      |
|     |          |         |            | 0     | p - 2 |     |      |
| =   |          |         |            | = a   |       | ba  | Ans. |
|     |          | a2      |            |       | 2p    |     |      |
p
Ans:
a2 p - 2
A , x a
= =
p 2p
a b
906

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–27. y
Locate the centroid yof the area.
y (cid:2) a cos –
p
– x
a
a
SOLUTION
Differential Element:The element parallel to the yaxis shown shaded in Fig.awill x
be considered.The area of the element is –a–
2
p
dA = ydx = a cos xdx
a
' y a p
Centroid:The centroid of the element is located at y = = cos x.
2 2 a
Area:Integrating,
A = dA =
a>2
a cos
p
x dx =
a2
sin
p
x 2
a>2
=
a2
Ans.
L L a p a p
A 0 0
We have
' a>2 a p p a>2a2 p
y dA a cos xbaa cos x dxb cos2 x dx
L L 2 a a L 2 a
y = A = 0 = 0
a2 a2
dA
L p p
A
=
a
4
2
L 0
a>2 acos 2
a
p x + 1b dx
=
a
4
2 a
2
a
p
sin 2
a
p x + xb2
0
a>2
= p a Ans.
a2 a2 8
p p
Ans:
a2 p
A = , y = a
p 8
907

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–28.
Locate the centroid xof the shaded area. y
y (cid:31) a sin a x
a
x
ap
SOLUTION
Area and Moment Arm:The area of the differential element is
x
dA = ydx = a sin
a
dxand its centroid are x = x
' xdA
pa
xaasin x dxb
a
x =
LA
=
L0
pa
x
dA asin dx
LA L0 a
ca3 sin x - xaa2 cos x bd`
pa
a a
0
=
a -a2 cos x b`
pa
a
0
p
=
2
a Ans.
Ans:
p
x = a
2
908

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–29.
y
Locate the centroid yof the shaded area.
x
y   a sin  a
a
x
ap
SOLUTION
Area and Moment Arm:The area of the differential element is
|     |         | x           |                          |     | y a   | x             |       |      |
| --- | ------- | ----------- | ------------------------ | --- | ----- | ------------- | ----- | ---- |
| dA  | = ydx = | a   sin  a  | dxand its centroid are y |     | = =   |  sin  .       |       |      |
|     |         |             |                          |     | 2 2   | a             |       |      |
|     |         | paa         |                          |     |       |               | pa    |      |
|     |         |             | x x                      |     | 1     | 1 2 x         |       |      |
|     |         |             | a dxb                    | c   | a2a x | a s in        | bd`   |      |
|     |  y d A  |             |  s i n     a   si n   a  |     | 4  -  |               |       |      |
|     |         |             | 2 a                      |     |       | 2 a           | 0 p a |      |
|   y | L A     | L0          |                          |     |       |               |       | Ans. |
| =   |         | =           | p a                      | =   |       |               | = 8   |      |
|     |         |             | x                        |     |       | x p           | a     |      |
|     |  d A    |             | a s in   d x             |     | a -a  | 2 c o s   b ` |       |      |
  a
|     | L A |     | LL 0 |     |     | a 0 |     |     |
| --- | --- | --- | ---- | --- | --- | --- | --- | --- |
Ans:
pa
y =
8
909

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–30.
y
| The         | steel  | plate                                         | is  0.3  | m  thick  | and  | has  a  | density  | of  |     |     |     |
| ----------- | ------ | --------------------------------------------- | -------- | --------- | ---- | ------- | -------- | --- | --- | --- | --- |
| 7850 kg>m3. |        | Determine the location of its center of mass. |          |           |      |         |          |     |     |     |     |
Also compute the reactions at the pin and roller support. y2 (cid:31) 2x
2 m
x
A
SOLUTION
2 m
 y -x
| 1    | = 1 |     |     |     |     |     |     |     |     |     | y (cid:31) (cid:30)x |
| ---- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | -------------------- |
|  y 2 | 2x  |     |     |     |     |     |     |     |     |     | B                    |
2 = 2
|     | 1y  | 2 dx | A22x |     | B   |     |     |     |     |     |     |
| --- | --- | ---- | ---- | --- | --- | --- | --- | --- | --- | --- | --- |
|  dA | =   | - y  | =    | + x |  dx |     |     |     |     |     | 2 m |
|     | 2   | 1    |      |     |     |     |     |     |     |     |     |
'
 x = x
22x
| '   | y 2 + | y 1 | - x |     |     |     |     |     |     |     |     |
| --- | ----- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  y  | =     | =   |     |     |     |     |     |     |     |     |     |
|     | 2     |     | 2   |     |     |     |     |     |     |     |     |
2
|     |          |     |         |        |         | 22 2  | 1    | 2    |                 |      |     |
| --- | -------- | --- | ------- | ------ | ------- | ----- | ---- | ---- | --------------- | ---- | --- |
|     |   ' x dA |     |  x A22x | x      | B  dx   | c     | x5>2 |  x3d |                 |      |     |
|     |          |     |         | +      |         |       | +    |      |                 |      |     |
|     | LA       |     | L0      |        |         | 5     | 3    | 0    |                 |      |     |
|  x  | =        | =   |         |        | =       |       |      | =    | 1.2571 = 1.26 m | Ans. |     |
|     |          |     | 2       |        |         | 222   |      | 2    |                 |      |     |
|     |  dA      |     | A22x    | B      |         |  x3>2 |      | 1    |                 |      |     |
|     |          |     |         | + x    |  dx     | c     | +    |  x2d |                 |      |     |
|     |          |     |         |        |         | 3     |      | 2    |                 |      |     |
|     | LA       |     | L0      |        |         |       |      | 0    |                 |      |     |
|     |          |     | 222x    | x      |         |       | x    | 2 1  | 2               |      |     |
|     | '        |     |         | - A22x |         | B     | c    | x3d  |                 |      |     |
|     |   y dA   |     |         |        | +       | x  dx |      | - 6  |                 |      |     |
|     |          |     | 2       |        |         |       | 2    |      |                 |      |     |
| y   | LA       |     | L0      |        |         |       |      |      | 0 0.143 m       | Ans. |     |
| =   |          | =   | 2       |        |         | =     |      |      | =               |      |     |
|     |          |     |         |        |         |       | 22 2 |      | 1 2             |      |     |
|     |  dA      |     |         |   A22x | x B  dx |       | c    | x3>2 | x2d             |      |     |
|     |          |     |         | +      |         |       |      | +    |                 |      |     |
|     | LA       |     | L0      |        |         |       | 3    |      | 2 0             |      |     |
4.667 m2
 A =
785019.81214.667210.32
|  W    | =    |     |     | = 107.81 kN     |               |         |         |     |     |      |     |
| ----- | ---- | --- | --- | --------------- | ------------- | ------- | ------- | --- | --- | ---- | --- |
| a+ ©M |      | 0;  |     | -1.25711107.812 |               | N       | A 222 B | 0   |     |      |     |
|       | A    | =   |     |                 |               | + B     |         | =   |     |      |     |
|       |      |     |     | N B = 47.92     | =             | 47.9 kN |         |     |     | Ans. |     |
| : +   | ©F = | 0;  |     | -A +            | 47.92 sin 45° | =       | 0       |     |     |      |     |
|       | x    |     |     | x               |               |         |         |     |     |      |     |
|       |      |     |     | A = 33.9 kN     |               |         |         |     |     | Ans. |     |
x
|  + c ©F |     | = 0; |     | A + 47.92 cos 45° |     | -   | 107.81 | = 0 |     |      |     |
| ------- | --- | ---- | --- | ----------------- | --- | --- | ------ | --- | --- | ---- | --- |
|         | y   |      |     | y                 |     |     |        |     |     |      |     |
|         |     |      |     | A 73.9 kN         |     |     |        |     |     | Ans. |     |
y =
Ans:
x 1.26 m
=
y = 0.143 m
N = 47.9 kN
B
A = 33.9 kN
x
A = 73.9 kN
y
910

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–31.
Locate the centroid x of the shaded area. y
y (cid:31) h (cid:30)  — h     xn
an
h
h
y (cid:31) h (cid:30)  — a   x
x
a
Solution
|                                                               |         |               |        |      | h     |                         | h          |             |
| ------------------------------------------------------------- | ------- | ------------- | ------ | ---- | ----- | ----------------------- | ---------- | ----------- |
| Area                                                          | And     | Moment  Arm.  | Here,  | y =  | h -   |  xn  and  y             | = h -  x.  | Thus,  the  |
|                                                               |         |               |        | 2    | an    | 1                       | a          |             |
| area of the differential element shown shaded in Fig. a is dA |         |               |        |      |       |                         | = (y       | - y ) dx    |
|                                                               |         |               |        |      |       |                         | 2          | 1           |
|                                                               | h       | h             |        | h    | h     |                         | ~          |             |
| =                                                             | h -  xn | - h -         |  x dx  | =  x | -  xn | dx and its centroid is  | x =        | x.          |
|                                                               | an      | a             |        | a    | an    |                         |            |             |
| c                                                             |         | a             | bd     | a    |       | b                       |            |             |
Centroid. Perform the integration
a
|     |      |      |     | h    | h      |     |     |     |
| --- | ---- | ---- | --- | ---- | ------ | --- | --- | --- |
|     |      | ~    | x   |  x - |  xn dx |     |     |     |
|     |      | x dA |     | a    | an     |     |     |     |
|     |      | 1A   | L0  |      |        |     |     |     |
|     |  x = | =    |     |      |        |     |     |     |
|     |      |  dA  | a   | ah   | h b    |     |     |     |
|     |      | 1A   |     |  x   |  xn dx |     |     |     |
|     |      |      |     | -    | n      |     |     |     |
L0 a a
|     |     |     |     | a   | b   |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
a
|     |     |     | h   |      | h     |     |     |     |
| --- | --- | --- | --- | ---- | ----- | --- | --- | --- |
|     |     |     |  x3 | -    |  xn+2 |     |     |     |
|     |     |     | 3a  | an(n | 2)    |     |     |     |
|     |     |     |     |      | +     | 0   |     |     |
 =
|     |     |     | c h |     | h     | d `a |     |     |
| --- | --- | --- | --- | --- | ----- | ---- | --- | --- |
|     |     |     |  x2 |     |  xn+1 |      |     |     |
- an(n
|     |     |     | 2a  |     | + 1) | 0   |     |     |
| --- | --- | --- | --- | --- | ---- | --- | --- | --- |
|     |     |     | c   |     |      | b`  |     |     |
ha2 (n
- 1)
3(n 2)
+
 =
|     |     |     | ha(n | - 1) |     |     |     |     |
| --- | --- | --- | ---- | ---- | --- | --- | --- | --- |
2(n + 1)
2(n
+ 1)
|     |     |  =  |     | a   |     |     |     | Ans. |
| --- | --- | --- | --- | --- | --- | --- | --- | ---- |
3(n 2)
+
|     |     |     | c   | d   |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
Ans:
2(n 1)
+
x = a
3(n + 2)
c d
911

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–32.
Locate the centroid y of the shaded area. y
y (cid:31) h (cid:30) — h xn
an
h
h
y (cid:31) h (cid:30) — a x
x
a
Solution
h h
Area And Moment Arm. Here, y 2 = h - an xn and y 1 = h - a x. Thus, the
area of the differential element shown shaded in Fig. a is dA = (y 2 - y 1 ) dx
h h h h
= h - xn - h - x dx = x - xn dx and its centroid is at
an a a an
∼y = c y 1 + y 2 - 2 ya 1 = 1 2 ( b y 2 d + y 1 ) a = 1 2 h - a h n b xn + h - h a x = 1 2 2h - a h n xn - h a x .
a b a b a b
Centroid. Perform the integration
a1 h h h h
y =
1A ~ y dA
=
L0 2 2h - an xn - a x a x - an xn dx
1A dA a L0 a h a x - a h n b x a n dx b
a b
1 h2 h2 2h2 h2 a
x2 - x3 - xn+1 + x2n + 1
2 a 3a2 an(n + 1) a2n(2n + 1) 0
=
c h h a d `
x2 - xn + 1
2a an(n + 1) 0
c b`
(4n + 1) (n - 1)
h2a
6(n + 1)(2n + 1)
=
c n - 1 d
ha
2(n + 1)
c d
(4n + 1)
= h Ans.
3(2n + 1)
c d
Ans:
(4n + 1)
y = h
3(2n + 1)
c d
912

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–33.
Locate the centroid x of the shaded area. y
a
h
y (cid:31) –   –  x
h a h
y (cid:31) (     )(x(cid:29)b)
a(cid:29) b
x
b
Solution
|                                   |                               |     |     | a        | a        | - b    |                        |              |
| --------------------------------- | ----------------------------- | --- | --- | -------- | -------- | ------ | ---------------------- | ------------ |
| Area And Moment Arm. Here x       |                               |     | =   |  y and x | =        |        |  y + b. Thus the area  |              |
|                                   |                               |     | 1   | h        | 2        | h      |                        |              |
|                                   |                               |     |     |          | a        | a -bb  |                        | a            |
| of the differential element is dA |                               |     | =   | (x -     | x ) dy = |        | y +                    | b -  y dy =  |
|                                   |                               |     |     | 2        | 1        | h      |                        | h            |
| b                                 |                               |     |     | x        | x 1      |        | a                      | b db         |
| (b                                |  y)dy and its centroid is at  |     | ~   | 2-       | 1  (c    | a      | )b                     |              |
| -                                 |                               |     | x=  | x 1+     | =        | x 2+ x | 1 =  y-                |  y + .       |
| h                                 |                               |     |     |          | 2 2      |        | h                      | 2 h 2        |
Centroid. Perform the integration,
|     |     |     | h a | b   | b   | b   |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |

|     | ~        |     |  y - |  y + | b   | -  y | dy  |     |
| --- | -------- | --- | ---- | ---- | --- | ---- | --- | --- |
|     | 1A  x dA | L0  | h    | 2h   | 2   | h    |     |     |
 x
|     | =   | =   | a   | h   | bb ca | b   | d   |     |
| --- | --- | --- | --- | --- | ----- | --- | --- | --- |
1A  dA
|     |     |     |     | b   | -  y dy |     |     |     |
| --- | --- | --- | --- | --- | ------- | --- | --- | --- |
h
L0
|     |     |     |          | a     | b         |     |      |     |
| --- | --- | --- | -------- | ----- | --------- | --- | ---- | --- |
|     |     | b   |          |       | b         |     | b2 h |     |
|     |     |     |  (a b)y2 |       |  (b 2a)y3 |     |  y   |     |
|     |     |     | -        | + 6h2 | -         | +   |      |     |
|     |     | 2h  |          |       |           |     | 2 0  |     |
 =
|     |     | c   |     |     | b   | h   | d ` |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
 y2
|     |     |     |     | by  | -   |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
2h
0
|     |     |     |     | a   | b`  |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
bh
 (a + b)
6
 =
bh
2
1
|     |     |  =  (a | + b) |     |     |     |     |   Ans. |
| --- | --- | ------ | ---- | --- | --- | --- | --- | ------ |
3
Ans:
1
x =  (a + b)
3
913

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–34.
Locate the centroid y of the shaded area. y
a
h
y (cid:31) –   –  x
h a h
y (cid:31) (     )(x(cid:29)b)
a(cid:29) b
x
b
Solution
|                                   |     | a    |          | a - b   |                       |              |
| --------------------------------- | --- | ---- | -------- | ------- | --------------------- | ------------ |
| Area And Moment Arm. Here, x      |     | =    |  y and x | =       | y + b. Thus the area  |              |
|                                   |     | 1 h  | 2        | h       |                       |              |
|                                   |     |      |          | a a -bb |                       | a            |
| of the differential element is dA |     | = (x | - x ) dy | =       | y +                   | b -  y dy =  |
|                                   |     |      | 2 1      |         | h                     | h            |
b
~
| b -  y dy and its centroid is at y |     | = y. |     | ca  | b   | d   |
| ---------------------------------- | --- | ---- | --- | --- | --- | --- |
h
Caentroid. bPerform the integration,
|      | h       | b      |     |     |     |     |
| ---- | ------- | ------ | --- | --- | --- | --- |
|      | y       | b  y   | dy  |     |     |     |
| ~    |         | -      |     |     |     |     |
| 1A   | y dA L0 | h      |     |     |     |     |
|  y = | =       |        |     |     |     |     |
|      | h       | a      | b   |     |     |     |
| 1A   |  dA     | b      |     |     |     |     |
|      |         | b -  y | dy  |     |     |     |
|      | L0      | h      |     |     |     |     |
|      |         | a      | b   |     |     |     |
|      | b       | b      | h   |     |     |     |
|      |  y2     |  y3    |     |     |     |     |
-
|     | 2   | 3h  |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
|     |  =  |     | 0   |     |     |     |
|     | a   |     | bh` |     |     |     |
b
|     | by  | -  y2 |     |     |     |     |
| --- | --- | ----- | --- | --- | --- | --- |
2h
0
|     | a   | b`  |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
1
 bh2
|     | 6   | h   |     |     |     |      |
| --- | --- | --- | --- | --- | --- | ---- |
|     |  =  |     |     |     |     | Ans. |
=
|     | 1   | 3   |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
 bh
2
Ans:
h
y =
3
914

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–35.
Locate the centroid x of the shaded area. y
y (cid:31) x
100 mm 1
y (cid:31) x2
100
x
100 mm
Solution
1
| Area And Moment Arm. Here, y |     | = x and y | =  x2. Thus the area of the  |     |
| ---------------------------- | --- | --------- | ---------------------------- | --- |
|                              |     | 2         | 1 100                        |     |
1
| differential element shown shaded in Fig. a is dA |     |     | (y y ) dx | (x  x2)dx  |
| ------------------------------------------------- | --- | --- | --------- | ---------- |
|                                                   |     |     | = 2 - 1   | = -        |
100
~
| and its centroid is at x | = x. |     |     |     |
| ------------------------ | ---- | --- | --- | --- |
Centroid. Perform the integration
100 mm
1
|     | ~    | x  x - |  x2  dx |     |
| --- | ---- | ------ | ------- | --- |
|     | x dA | 100    |         |     |
1A  L0
|  x = | =   |           |        |     |
| ---- | --- | --------- | ------ | --- |
|      |  dA | 100 mma 1 | b      |     |
|      | 1A  | x         |  x2 dx |     |
-
L0 100
|     |     | a        | b   |     |
| --- | --- | -------- | --- | --- |
|     | x3  | 1 100 mm |     |     |
-  x4
3 400
0
 =
|     | ax2 | 1 b`100 mm |     |     |
| --- | --- | ---------- | --- | --- |
 x3
-
2 300 0
|     | a          | b`  |     |      |
| --- | ---------- | --- | --- | ---- |
|     |  = 50.0 mm |     |     | Ans. |
Ans:
x = 50.0 mm
915

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–36.
Locate the centroid y of the shaded area. y
y (cid:31) x
100 mm 1
y (cid:31) x2
100
x
100 mm
Solution
| Area And Moment Arm. Here, x                       |      | = 10y 12 and x | = y. Thus, the area of the  |               |       |
| -------------------------------------------------- | ---- | -------------- | --------------------------- | ------------- | ----- |
|                                                    |      | 2              | 1                           |               |       |
| differential element shown shaded in Fig. a is >dA |      |                | = (x x                      | ) dy = (10y12 | y)dy  |
|                                                    |      |                | 2 - 1                       |               | -     |
| and its centroid is at y                           | ~ y. |                |                             |               |       |
|                                                    | =    |                |                             |               | >     |
Centroid. Perform the integration,
100 mm
|     |     | y  10y12 - y | dy  |     |     |
| --- | --- | ------------ | --- | --- | --- |
~ y dA
1A  L0
|  y = | =      | >     |     |     |     |
| ---- | ------ | ----- | --- | --- | --- |
|      | 100 mm | a     | b   |     |     |
| 1A   |  dA    | 10y12 |     |     |     |
|      |        | - y   | dy  |     |     |
L0
>
a b
y3 100 mm
4y52
-
3 0
 = >
|     | a20        | y2b` 100 mm |     |     |      |
| --- | ---------- | ----------- | --- | --- | ---- |
|     |  y32       | -           |     |     |      |
|     | 3          | 2           |     |     |      |
|     |            | > 0         |     |     |      |
|     | a          | b`          |     |     |      |
|     |  = 40.0 mm |             |     |     | Ans. |
Ans:
y = 40.0 mm
916

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–37.
Locate the centroid x of the circular sector. y
r
a
C
x
a
x
Solution
Area And Moment Arm. The area of the differential element shown in Fig. a is
1 2
|  r2 du and its centroid is at x | ~   |     |     |
| ------------------------------- | --- | --- | --- |
dA = =  r cos u.
2 3
Centroid. Perform the integration
|     | a 2 1 |     |     |
| --- | ----- | --- | --- |
 r2 du
| ~        |    r cos u |     |     |
| -------- | ---------- | --- | --- |
| 1A  x dA | L 3 2      |     |     |
|  x       | -a         |     |     |
| =        | = a a b a  | b   |     |
1A  dA 1
   r 2  du
L 2
-a
| 1   | a   |     |     |
| --- | --- | --- | --- |
 r3 sin u
| 3   | -a  |     |     |
| --- | --- | --- | --- |
   =
| a 1 | ba` |     |     |
| --- | --- | --- | --- |
 r2 u
2
-a
| a   | b`  |     |     |
| --- | --- | --- | --- |
2
 r3 sin a
3
=  r2 a
2 r sin a
| =   |     |     | Ans. |
| --- | --- | --- | ---- |
3  a
| a   | b   |     |     |
| --- | --- | --- | --- |
Ans:
2 r sin a
x =
3  a
a b
917

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–38.
Determine the location rof the centroid Cfor the loop of the
r2=2a2cos 2θ
| lemniscate,r2 | 2a2cos 2u,(-45° |     | u   |       |     |     |
| ------------- | --------------- | --- | --- | ----- | --- | --- |
|               | =               |     | … … | 45°). |     |     |
r
O
θ
C
_
r
SOLUTION
|      | 1 1           |     |     |     |     |     |
| ---- | ------------- | --- | --- | --- | --- | --- |
| dA = | (r)rdu = r2du |     |     |     |     |     |
|      | 2 2           |     |     |     |     |     |
45°1
|       | (2a2 cos 2u)du | a2C | sin 2uD4 | 5° a2 |     |     |
| ----- | -------------- | --- | -------- | ----- | --- | --- |
| A = 2 |                | =   |          | 0 =   |     |     |
2
L0
|     | 45° |     |     | 45° |     |     |
| --- | --- | --- | --- | --- | --- | --- |
A2rcos uBA1r2duB
|     | xdA 2 |     |     | 2 r3cosudu |     |     |
| --- | ----- | --- | --- | ---------- | --- | --- |
|     |       | 3   | 2   | 3          |     |     |
| LA  | L0    |     |     | L0         |     |     |
| x = | =     |     |     | =          |     |     |
|     |       | a2  |     | a2         |     |     |
dA
LA
|     | 45°         |     | 45°           |                |          |     |
| --- | ----------- | --- | ------------- | -------------- | -------- | --- |
|     | 2 r3cos udu | 2   | A 2a2B3/2 cos | u(cos 2u)3/2du | 0.7854a3 |     |
| xdA | =           | =   |               |                | =        |     |
|     | 3           | 3   |               |                |          |     |
| LA  | L0          |     | L0            |                |          |     |
0.7854a3
| x   | 0.785a |     |     |     |     | Ans. |
| --- | ------ | --- | --- | --- | --- | ---- |
| =   | a2 =   |     |     |     |     |      |
Ans:
x = 0.785 a
918

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–39.
Locate the center of gravity of the volume.The material is z
homogeneous.
2m
SOLUTION 2m
y2=2z
| Volume and Moment Arm: |         | The volume of the thin disk differential element is |        |     |
| ---------------------- | ------- | --------------------------------------------------- | ------ | --- |
| py2dz                  | p12z2dz | 2pzdzand its centroid                               | '      | y   |
| dV =                   | =       | =                                                   | z = z. |     |
Centroid:Due to symmetry about zaxis
|     |     | x- y- 0 | Ans. |     |
| --- | --- | ------- | ---- | --- |
= =
Applying Eq.9–3 and performing the integration,we have
2 m
'
|     |     | zdV z12pzdz2 |     |     |
| --- | --- | ------------ | --- | --- |
|     | -z  | Lv L0        |     |     |
|     |     | = =          |     |     |
2 m
|     |     | dV 2pzdz |     |     |
| --- | --- | -------- | --- | --- |
Lv
L0
z3 2 m
2p
3
|     |     | 0 4 |     |     |
| --- | --- | --- | --- | --- |
m Ans.
= =
|     |     | z2 2 m 3 |     |     |
| --- | --- | -------- | --- | --- |
2p
2
0
Ans:
x y
= = 0
4
z =   m
3
919

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–40.
Locate the centroid yof the paraboloid. z
z2=4y
4m
y
SOLUTION
| Volume and Moment Arm: |                           | The volume of the thin disk differential element is  |        |     |
| ---------------------- | ------------------------- | ---------------------------------------------------- | ------ | --- |
| pz2dy                  | p                         |                                                      | '      |     |
|  dV =                  | = 14y2dyand its centroid  |                                                      | y = y. |     |
4m
Centroid:Applying Eq.9–3 and performing the integration,we have
4 m
|     | ' ydV  | y3   | p 14y2dy4 |     |
| --- | ------ | ---- | --------- | --- |
|     | y = LV | = L0 |           |     |
4 m
|     |     | dV p | 14y2dy |     |
| --- | --- | ---- | ------ | --- |
|     | LV  | L0   |        |     |
|     |     | y3   | 4 m    |     |
4p
3
0
|     |     | =   | = 2.67m | Ans. |
| --- | --- | --- | ------- | ---- |
|     |     | y2  | 4 m     |      |
4p
2
0
Ans:
y = 2.67 m
920

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–41.
|     | Locate the centroid z |     |     | of the frustum of the right-circular |     |     |     |     |     |     |     |     |     |     | z   |     |
| --- | --------------------- | --- | --- | ------------------------------------ | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
cone.
r
h
R
SOLUTION
|     |         |      |       |                                                      |      |       |     |      |           |     | y r   |       |     |     |     |     |
| --- | ------- | ---- | ----- | ---------------------------------------------------- | ---- | ----- | --- | ---- | --------- | --- | ----- | ----- | --- | --- | --- | --- |
|     |         |      |       |                                                      |      |       |     |      |           |     | -     | h - z | x   |     |     | y   |
|     | Volume  |      | and   | Moment                                               | Arm: | From  |     | the  | geometry, |     |       | = ,   |     |     |     |     |
|     |         |      |       |                                                      |      |       |     |      |           |     | R - r | h     |     |     |     |     |
|     |         | 1r - | R2z + | Rh                                                   |      |       |     |      |           |     |       |       |     |     |     |     |
|     | y       | =    |       | .The volume of the thin disk differential element is |      |       |     |      |           |     |       |       |     |     |     |     |
h
|     |     |     |         |       | 1r  | R2z | Rh  |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | ------- | ----- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|     |     |     |         |       | -   | +   | 2   |     |     |     |     |     |     |     |     |     |
|     |     | dV  | = py2dz | = pca |     |     | b   | ddz |     |     |     |     |     |     |     |     |
h
p
|     |     |     |     |     | c1r | R22z2 | 2Rh1r | R2z | R2h2ddz |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | ----- | ----- | --- | ------- | --- | --- | --- | --- | --- | --- | --- |
|     |     |     |     | =   | -   |       | +     | -   | +       |     |     |     |     |     |     |     |
h2
|     | and its centroid z |     |     | z.  |     |     |     |     |     |     |     |     |     |     |     |     |
| --- | ------------------ | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
=
Centroid:Applying Eq.9.3 and performing the integration,we have
h p
|     |     | '   |     |     | 31r | R22z2 | 2Rh1r | R2z | R2h24dz |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | ----- | ----- | --- | ------- | --- | --- | --- | --- | --- | --- | --- |
|     |     | zdV |     | z   | -   | +     |       | -   | +       |     |     |     |     |     |     |     |
|     |     |     |     | bh2 |     |       |       |     |         |     | r   |     |     |     |     |     |
|     |     | LV  |     | L0  |     |       |       |     |         |     |     |     |     |     |     |     |
|     | z   | =   | =   |     |     |       |       |     |         |     |     |     |     |     |     |     |
h p
dV
|     |     |     |     |     | 3r - | R22z2 + | 2Rh1r | - R2z | + R2h24dz |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | ---- | ------- | ----- | ----- | --------- | --- | --- | --- | --- | --- | --- | --- |
|     |     | LV  |     | h2  |      |         |       |       |           |     |     |     |     |     |     |     |
L0
p
|     |     |     |     |      |     | z4      |     | z3  |     | z2   | ` h |     |     |     |     |     |
| --- | --- | --- | --- | ---- | --- | ------- | --- | --- | --- | ---- | --- | --- | --- | --- | --- | --- |
|     |     |     |     | 1r - | R22 | + 2Rh1r | -   | R2  | +   | R2h2 |     |     |     |     |     |     |
|     |     |     |     | h2B  | ¢4≤ |         |     | ¢3≤ |     | ¢2≤R |     |     |     |     |     |     |
0
=
|     |     |     |     | p   |     | z3  |       |     | z2  |         | h   |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | ----- | --- | --- | ------- | --- | --- | --- | --- | --- | --- |
|     |     |     |     | 1r  | R22 |     | 2Rh1r | R2  |     | R2h21z2 | `   |     |     |     |     |     |
|     |     |     |     |     | -   | +   |       | -   | +   |         |     |     |     |     |     |     |
|     |     |     |     | h2  |     | 3   |       |     | 2   |         |     |     |     |     |     |     |
0
|     |     |     |     | R2 3r2 |       |     |     |     |     |     |     |      |     |     |     |     |
| --- | --- | --- | --- | ------ | ----- | --- | --- | --- | --- | --- | --- | ---- | --- | --- | --- | --- |
|     |     |     |     | +      | + 2rR |     |     |     |     |     |     |      |     |     |     |     |
|     |     |     | =   |        |       | h   |     |     |     |     |     | Ans. |     |     |     |     |
|     |     |     |     | 4 R2   | r2 rR |     |     |     |     |     |     |      |     |     |     |     |
|     |     |     |     | +      | +     |     |     |     |     |     |     |      |     |     |     |     |
Ans:
|            |     |     |     |     |     |     |     |     |     |     |     |     |     |     | R2 + 3r2 + | 2rR |
| ---------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---------- | --- |
| Ans:       |     |     |     |     |     |     |     |     |     |     |     |     |     | z   |            |  h  |
|            |     |     |     |     |     |     |     |     |     |     |     |     |     | =   | 4(R2 r2    |     |
| y = 2.67 m |     |     |     |     |     |     |     |     |     |     |     |     |     |     | + +        | rR) |
921

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–42.  Locate the centroid of the solid.
z
a
h
h2
z2 =  –   y
a y
Solution
| x y | 0    |   (By symmetry)  |     |     |     |     | Ans. |
| --- | ---- | ---------------- | --- | --- | --- | --- | ---- |
= =
x
|      | h     |     | ha2   |     | pa2 | h pa2h |     |
| ---- | ----- | --- | ----- | --- | --- | ------ | --- |
|      | py2dz |     |  z4dz |     | z5  |        |     |
| dV = |       | =   | p     | =   |     | =      |     |
| L    | L0    |     | L0 h4 |     | 5h4 | 5      |     |
0
|     | h        |     | pa2 | h      | c pa2 | d h pa2h2 |     |
| --- | -------- | --- | --- | ------ | ----- | --------- | --- |
| zdV | = py2zdz |     | =   | z5dz = | z6    | =         |     |
|     |          |     | h4  |        | 6h4   | 6         |     |
| L   | L0       |     | L0  |        |       | 0         |     |
|     |          |     |     |        | c     | d         |     |
pa2h2
zdV
| Lv  |     | 6    | 5    |     |     |     |      |
| --- | --- | ---- | ---- | --- | --- | --- | ---- |
| z = | =   |      | = h  |     |     |     | Ans. |
|     |     | pa2h | 6    |     |     |     |      |
dV
| Lv  |     | 5   |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
Ans:
5
z  h
=
6
922

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–43.
Locate the centroid z of the volume. z
1 m
y2 (cid:31) 0.5z
2 m
Solution
Volume And Moment Arm. The volume of the thin disk differential element shown y
shaded in Fig. a is dV = py2 dz = p(0.5z)dz and its centroid is at ~ z = z.
Centroid. Perform the integration x
2 m
~ z[p(0.5z)dz]
1V zdV L0
z = =
1V dV 2 m
p(0.5z)dz
L0
0.57 2 m
z3
3
0
=
0.5p `2 m
z2
2
0
`
4
= m Ans.
3
Ans:
4
z = m
3
923

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–44.
Locate the centroid of the quarter-cone. z
h
SOLUTION
a
'
z = z y
a x
r = (h - z)
h
p pa2
dV = r2dz = (h - z)2dz
4 4h2
pa2 h pa2 z3 h
dV = (h2 - 2hz + z2)dz = ch2z - hz2 + d
4h2 4h2 3
L L0 0
pa2 h3 pa2h
a b
= =
4h2 3 12
' zdV =
pa2 h
(h2 - 2hz + z2)zdz =
pa2
ch2
z2
- 2h
z3
+
z4
d
h
L
4h2
L0
4h2 2 3 4
0
pa2 h4 pa2h2
a b
= =
4h2 12 48
'
pa2h2
zdV
48 h
z = L = = Ans.
pa2h 4
dV
12
L
' xdV = p 4 a h2 2 h 3 4 p r (h - z)2dz = 4 pa h 2 2 h 3 4 p a h (h3 - 3h2z + 3hz2 - z3)dz
L L0 L0
pa2 4a 3h4 h4
=
ah4
- +
h4
-
b
4h2 3ph 2 4
pa2 ah3 a3h
a b
= 4h2 3p = 12
'
a3h
xdV
12 a
x = y = L = pa2h = p Ans.
dV
12
L
Ans:
h
z =
4
a
x = y =
p
924

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–45.
Locate the centroid of the ellipsoid of revolution. z
y2 z2
(cid:30) (cid:31)1
b2 a2
a
x y
SOLUTION
dV pz2dy b
=
|     |     | b     | y2     |         | y3  | b 2pa2b |     |
| --- | --- | ----- | ------ | ------- | --- | ------- | --- |
| dV  | =   | pa2a1 | - b dy | = pa2cy | -   | d =     |     |
|     |     |       | b2     |         | 3b2 | 3       |     |
| L   | L0  |       |        |         |     | 0       |     |
b
|      |     |        | y2   |         | y2  | y4 b pa2b2 |     |
| ---- | --- | ------ | ---- | ------- | --- | ---------- | --- |
| 'ydV |     | pa2ya1 | b    | dy pa2c |     | d          |     |
|      | =   |        | - b2 | =       | -   | 4b2 =      |     |
|      |     |        |      |         | 2   | 4          |     |
| L    | L0  |        |      |         |     | 0          |     |
pa2b2
'ydV
4 3
| y   | LV  |         | b   |     |     |     |      |
| --- | --- | ------- | --- | --- | --- | --- | ---- |
| =   |     | = 2pa2b | =   |     |     |     | Ans. |
8
dV
3
LV
| x   | z 0 |     |     | (By symmetry) |     |     | Ans. |
| --- | --- | --- | --- | ------------- | --- | --- | ---- |
= =
Ans:
3
y =  b
8
x = z = 0
925

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–46.
z
The hemisphere of radius ris made from a stack of very thin
| plates such that the density varies with height r |     |     | = kz, |     |
| ------------------------------------------------- | --- | --- | ----- | --- |
where kis a constant.Determine its mass and the distance
to the center of mass G.
G
_
r z
SOLUTION
y
x
| Mass and Moment Arm:The density of the material is r |     |     | kz.The mass of the thin |     |
| ---------------------------------------------------- | --- | --- | ----------------------- | --- |
=
|                     |              | rdV rpy2dz | kz3p(r2 z2) dz4 |          |
| ------------------- | ------------ | ---------- | --------------- | -------- |
| disk  differential  | element  is  | dm = =     | = -             | and  its |
'
| centroid z = | z.Evaluating the integrals,we have |     |     |     |
| ------------ | ---------------------------------- | --- | --- | --- |
r
kz3p(r2 z2) dz4
|  m  | =  dm = | -   |     |     |
| --- | ------- | --- | --- | --- |
Lm L0
|     |     | r2z2 z4 r pkr4 |     |      |
| --- | --- | -------------- | --- | ---- |
|     | pk  | `              |     |      |
|     |  =  | - =            |     | Ans. |
|     | ¢   | 2 4≤           | 4   |      |
0
r
|     | ' z5kz3p(r2 | z2) dz46 |     |     |
| --- | ----------- | -------- | --- | --- |
|     |     zdm =   | -        |     |     |
Lm L0
|     |     | r2z3 z5 r 2pkr5 |     |     |
| --- | --- | --------------- | --- | --- |
`
|     |  = pk | - =  |     |     |
| --- | ----- | ---- | --- | --- |
|     | ¢     | 3 5≤ | 15  |     |
0
Centroid:Applying Eq.9–2,we have
'
 zdm 2pkr5>15
8
| z   | Lm       | r     |     | Ans. |
| --- | -------- | ----- | --- | ---- |
| =   | = pkr4>4 | = 15  |     |      |
 dm
Lm
Ans:
pkr4
m =
4
8
z =  r
15
926

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–47.
| Determine  | the  | location  | z of  the  | centroid  |     | for  the |     |
| ---------- | ---- | --------- | ---------- | --------- | --- | -------- | --- |
z
tetrahedron.Hint:Use a triangular “plate”element parallel
to the x–yplane and of thickness dz.
b
a
| SOLUTION |          |       |      |     |     |     | c   |
| -------- | -------- | ----- | ---- | --- | --- | --- | --- |
|          | 1        |       | 1    |     |     |     | y   |
| z =      | ca1 - yb | = ca1 | - xb |     |     |     |     |
|          | b        |       | a    |     |     |     |     |
|          | c1       |       | 1 c  | z   | z   | abc |     |
x
| dV  | = (x)(y)dz |     | = aa1 | - bba1 | - b | dz = |     |
| --- | ---------- | --- | ----- | ------ | --- | ---- | --- |
|     | 2          |     | 2     | c      | c   | 6    |     |
| L   | L0         |     | L0    |        |     |      |     |
c
| '   | 1    |     | z z   | abc2 |     |     |     |
| --- | ---- | --- | ----- | ---- | --- | --- | --- |
| zdV | zaa1 |     | bba1  | bdz  |     |     |     |
|     | =    | -   | c - c | =    |     |     |     |
| L   | 2 L0 |     |       |      | 24  |     |     |
abc2
'
zdV
|     | 24  |     | c   |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
z L Ans.
| =   | =   | =   |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     | abc |     | 4   |     |     |     |     |
dV
6
L
Ans:
c
z =
4
927

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
z
*9–48.
The king’s chamber of the Great Pyramid of Giza is located
at its centroid.Assuming the pyramid to be a solid,prove
| that this point is at z |     |     | = 1h, Suggestion: | Use a rectangular |     |     |     |     |
| ----------------------- | --- | --- | ----------------- | ----------------- | --- | --- | --- | --- |
4
| differential plate element having a thickness dz |     |     |     |     |     | and area |     |     |
| ------------------------------------------------ | --- | --- | --- | --- | --- | -------- | --- | --- |
(2x)(2y).
h
a a
SOLUTION
a a
x y
|     | dV = | 12x212y2dz | = 4xy dz |     |     |     |     |     |
| --- | ---- | ---------- | -------- | --- | --- | --- | --- | --- |
a
|     | x = | y = | 1h - z2 |     |     |     |     |     |
| --- | --- | --- | ------- | --- | --- | --- | --- | --- |
h
|     |     | h4a2 |       | 4a2    |       | z3  | h 4a2h |     |
| --- | --- | ---- | ----- | ------ | ----- | --- | ------ | --- |
|     | =   |      | - 2dz | = Bh2z | - hz2 | +   | R =    |     |
|     | dV  |      | 1h z2 |        |       |     |        |     |
|     | L   | L    | h2    | h2     |       | 3   | 3      |     |
|     |     | 0    |       |        |       |     | 0      |     |
h4a2
|     | '     |     |              | 4a2 | z2    | z3  | z4 h a2h2 |     |
| --- | ----- | --- | ------------ | --- | ----- | --- | --------- | --- |
|     | zdV = |     | 1h - z2 2zdz | =   | Bh2 - | 2h  | + R =     |     |
| L   |       | L   | h2           | h2  |       |     |           |     |
|     |       | 0   |              |     | 2     | 3   | 4 0 3     |     |
'
|     |     | zdV | a2h2 |     |     |     |     |       |
| --- | --- | --- | ---- | --- | --- | --- | --- | ----- |
|     | '   | L   |      | h   |     |     |     |       |
|     | z = |     | = 3  | =   |     |     |     | (QED) |
4a2h
4
|     |     | dV  | 3   |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
L
928

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–49.  Locate the center of gravity z  of the frustum of the
paraboloid. The material is homogeneous.
z
z  6.25 (0.25   y2)
SOLUTION
0.3 m
Given:
1 m
a (cid:2) 1 m
(cid:2)
| b 0.5 | m   |     |
| ----- | --- | --- |
y
| c (cid:2) 0.3 | m   |     |
| ------------- | --- | --- |
0.5 m
x
a
| (cid:16)  | (cid:10) (cid:21)            | (cid:22)(cid:13)      |
| --------- | ---------------------------- | --------------------- |
| (cid:17)  | 2 z 2                        | 2                     |
| V (cid:2) | (cid:20) (cid:11)b (cid:9) b | (cid:9) c (cid:14) dz |
| (cid:17)  | (cid:12)                     | (cid:15)              |
| (cid:18)  | a                            |                       |
0
| (cid:16) a       | (cid:21)                        | (cid:22)           |
| ---------------- | ------------------------------- | ------------------ |
| 1                | (cid:10) z                      | (cid:13)           |
| (cid:2) (cid:17) | z(cid:20) (cid:11)b 2 (cid:9) 2 | (cid:9) 2 (cid:14) |
| z                | b                               | c dz               |
| V (cid:17)       | (cid:12) a                      | (cid:15)           |
(cid:18)
0
z (cid:2) 0.422 m Ans.
Ans:
z = 0.422 m
929

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–50.
Locate the centroid zof the spherical segment.
z
z2 a2 y2
1
C — a
2
a
SOLUTION
z
| dV = py2dz | = p(a2 | - z2)dz |     |     |     |     |     |     |     |
| ---------- | ------ | ------- | --- | --- | --- | --- | --- | --- | --- |
y
z = z
a
| '   | p   | z(a2 | z2)dz |     |     |     |     |     | x   |
| --- | --- | ---- | ----- | --- | --- | --- | --- | --- | --- |
| zdV |     |      | -     |     |     |     |     |     |     |
La
| LV  |     | 2   |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
z = =
a
| dV  | p   | (a2 | z2)dz |     |     |     |     |     |     |
| --- | --- | --- | ----- | --- | --- | --- | --- | --- | --- |
-
| LV  |     | La  |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
2
|     |     | z2  | z4  | a    | a4 a4 a4 | a4  |     | 9a4    |     |
| --- | --- | --- | --- | ---- | -------- | --- | --- | ------ | --- |
|     | p   | a2a | b a | b    | p        |     | p   |        |     |
|     |     |     | -   |      | - -      | +   |     |        |     |
|     | B   | 2   |     | 4 Ra | B 2 4 8  | 64R |     | B 64 R |     |
2
|     | =   |       |     | =   |       |     | =   |        |     |
| --- | --- | ----- | --- | --- | ----- | --- | --- | ------ | --- |
|     |     |       | z3  | a   | a3 a3 | a3  |     | 5a3    |     |
|     | p   | a2(z) | a   | b   | p a3  |     | p   |        |     |
|     |     |       | -   |     | - -   | +   |     |        |     |
|     |     | B     | 3   | Ra  | B 3 2 | 24R |     | B 24 R |     |
2
| z = 0.675 a |     |     |     |     |     |     |     | Ans. |     |
| ----------- | --- | --- | --- | --- | --- | --- | --- | ---- | --- |
Ans:
z = 0.675a
930

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–51.
The steel and aluminum plate assembly is bolted together y
and fastened to the wall.Each plate has a constant width in
the z direction of 200 mm and thickness of 20 mm.If the
density of A and B is r s = 7.85Mg>m3, and for C,
r al = 2.71Mg>m3,determine the location xof the center of 100mm
mass.Neglect the size of the bolts. 200mm
A
x
C
B
300mm
SOLUTION
©m = 2C7.85(10)3(0.3)(0.2)(0.02)D+2.71(10)3(0.3)(0.2)(0.02) = 22.092kg
© ' xm = 150{2C7.85(10)3(0.3)(0.2)(0.02)D}+350C2.71(10)3(0.3)(0.2)(0.02)D
= 3964.2kg.mm
'
©xm 3964.2
x = = = 179mm Ans.
©m 22.092
Ans:
x = 179 mm
931

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–52.
Locate the center of gravity G1x,y2of the streetlight.Neglect 1m 1.5m
the thickness of each segment.The mass per unit length of y
| each segment is as follows:r |     |      |        | 12kg>m, | r 8kg>m, |     |     |     |
| ---------------------------- | --- | ---- | ------ | ------- | -------- | --- | --- | --- |
|                              |     |      | AB =   |         | BC =     |     |     |     |
| r 5kg>m,and r                |     |      | 2kg>m. |         |          |     |     |     |
| CD =                         |     | DE = |        |         |          |     |     |     |
D E
90(cid:31) 1m
1m 1m
C
G(x,y)
3m
B
SOLUTION
|              |     |           |           |      | 2(1) p |      |     |     |
| ------------ | --- | --------- | --------- | ---- | ------ | ---- | --- | --- |
| 'xm          |     |           |           | a1   | ba     | b(5) |     |     |
| © = 0(4)(12) |     |  +0(3)(8) |  +0(1)(5) |  + - | p      |      |     | 4m  |
2
# A
|     | +   | 1.5 (1) (5) |  +2.75(1.5) (2) |     | = 18.604 kg | m   |     |     |
| --- | --- | ----------- | --------------- | --- | ----------- | --- | --- | --- |
x
p
| © m = 4(12)+3(8)+1(5)+ |     |     | (5)+1(5)+1.5(2) |     | = 92.854kg |     |     |     |
| ---------------------- | --- | --- | --------------- | --- | ---------- | --- | --- | --- |
2
| 'x m | 1 8 . 6 | 0 4 |     |     |     |     |     |     |
| ---- | ------- | --- | --- | --- | --- | --- | --- | --- |
x ©
| = m | =       | = 0.200 m |     |     |     |     | Ans. |     |
| --- | ------- | --------- | --- | --- | --- | --- | ---- | --- |
| ©   | 9 2 . 8 | 5 4       |     |     |     |     |      |     |
p
| 'ym           |     |              |              |     | 2(1) |         |     |     |
| ------------- | --- | ------------ | ------------ | --- | ---- | ------- | --- | --- |
| © = 2(4) (12) |     |  +5.5 (3)(8) |  +7.5(1) (5) |  +  | a8+  | ba b(5) |     |     |
p 2
|     |     | 9(1) (5) |  +9(1.5) (2) | 405.332kg |     | # m |     |     |
| --- | --- | -------- | ------------ | --------- | --- | --- | --- | --- |
|     |     | +        |              | =         |     |     |     |     |
'ym
| ©   | 405.332 |     |     |     |     |     |     |     |
| --- | ------- | --- | --- | --- | --- | --- | --- | --- |
y
| = m | =      | = 4.37 m |     |     |     |     | Ans. |     |
| --- | ------ | -------- | --- | --- | --- | --- | ---- | --- |
| ©   | 92.854 |          |     |     |     |     |      |     |
Ans:
x = 0.200 m
y = 4.37 m
932

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–53.
Locate the centroid (x,y) of the metal cross section.Neglect y
the thickness of the material and slight bends at the corners.
50mm
150mm
x
50mm100mm 100mm 50mm
SOLUTION
Centroid:The length of each segment and its respective centroid are tabulated below.
|     | Segment | L (mm) | ' y (mm) | ' yL(mm2) |     |
| --- | ------- | ------ | -------- | --------- | --- |
50p
|                              | 1   |        | 168.17 | 26415.93 |      |
| ---------------------------- | --- | ------ | ------ | -------- | ---- |
|                              | 2   | 180.28 | 75     | 13520.82 |      |
|                              | 3   | 400    | 0      | 0        |      |
|                              | 4   | 180.28 | 75     | 13520.82 |      |
|                              | ©   | 917.63 |        | 53457.56 |      |
| Due to symmetry about yaxis, |     | x- = 0 |        |          | Ans. |
'
|     | ©yL | 53457.56    |          |     |      |
| --- | --- | ----------- | -------- | --- | ---- |
|     | y = | = = 58.26mm | = 58.3mm |     | Ans. |
|     | ©L  | 917.63      |          |     |      |
Ans:
x = 0
y = 58.3 mm
933

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–54.
| Determine the location y |     | of the centroidal axis x-x | of the |     |
| ------------------------ | --- | -------------------------- | ------ | --- |
150mm
beam’s cross-sectional area.Neglect the size of the corner 15mm
welds at Aand Bfor the calculation. B
y
150mm 15mm
C
x x
SOLUTION
A
'
| © yA = 7.5(15) | (150) + 90(150) | (15) + 215(p)(50)2 |     |     |
| -------------- | --------------- | ------------------ | --- | --- |
|                |                 |                    |     |     |
= 1907981.05 mm2 50mm
| ©A = 15(150) | + 150(15) | + p(50)2 |     |     |
| ------------ | --------- | -------- | --- | --- |
= 12353.98 mm2
'
| ©yA | 1907981.05 |         |     |      |
| --- | ---------- | ------- | --- | ---- |
| y = | =          | = 154mm |     | Ans. |
| ©A  | 12353.98   |         |     |      |
Ans:
y = 154 mm
934

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–55.
The truss is made from five members,each having a length y
of4mand a mass of 7kg>m.If the mass of the gusset plates
at the joints and the thickness of the members can be
neglected,determine the distance d to where the hoisting
cable must be attached, so that the truss does not tip d 4m C
B
(rotate) when it is lifted.
4m
4m
4m
60
x
A 4m D
SOLUTION
' #
©xM = 4(7)(1+4+2+3+5) = 420kg m
©M = 4(7)(5) = 140 kg
'
©xM 420
d = x = = = 3m Ans.
©M 140
Ans:
d = 3 m
935

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–56.
A rack is made from roll-formed sheet steel and has the y
| cross section shown.Determine the location 1x,y2 |     |     |     | of the |     |
| ------------------------------------------------ | --- | --- | --- | ------ | --- |
30mm
centroid of the cross section.The dimensions are indicated
at the center thickness of each segment.
80mm
50mm
SOLUTION
x
L
| © = 15 | + 50 + 15 + 30 | + 30 + 80 + | 15 = 235mm |     |     |
| ------ | -------------- | ----------- | ---------- | --- | --- |
15mm 15mm
| 'xL         |            |                    |          |                     | 5737.50mm2 |
| ----------- | ---------- | ------------------ | -------- | ------------------- | ---------- |
| © = 7.5(15) | + 0(50)    | + 7.5(15) + 15(30) | + 30(30) | + 45(80) + 37.5(15) | =          |
| 'yL         |            |                    |          |                     | 9550 mm2   |
| © = 0(15)   | + 25(50) + | 50(15) + 65(30)    | + 80(30) | + 40(80) + 0(15)    | =          |
'x L
| x © | 57 3 7 .50  |     |     |     |      |
| --- | ----------- | --- | --- | --- | ---- |
| =   | = = 24.4 mm |     |     |     | Ans. |
| © L | 2 3 5       |     |     |     |      |
'yL
| ©   | 9550   |     |     |     |      |
| --- | ------ | --- | --- | --- | ---- |
| y   | 40.6mm |     |     |     | Ans. |
| = L | = =    |     |     |     |      |
| ©   | 235    |     |     |     |      |
Ans:
x = 24.4 mm
y = 40.6 mm
936

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–57.
| Determine the location  |     | (x, y, z) of the centroid of the  |     |     |     |     |     | z   |
| ----------------------- | --- | --------------------------------- | --- | --- | --- | --- | --- | --- |
homogeneous rod.
200 mm
x
30(cid:31)
600 mm
100 mm y
Solution
Centroid. Referring to Fig. a, the length of the segments and the locations of their
respective centroids are tabulated below
|         |       |             | y~(mm)      | z~(mm) |             |            |           |     |
| ------- | ----- | ----------- | ----------- | ------ | ----------- | ---------- | --------- | --- |
| Segment | L(mm) | x~(mm)      |             |        | x~L(mm2)    | y~L(mm2)   | z~L(mm2)  |     |
| 1       | 200   | 0           | 0           | 100    | 0           | 0          | 20.0(103) |     |
| 2       | 600   | 300 cos 30° | 300 sin 30° | 0      | 155.88(103) | 90.0(103)  | 0         |     |
| 3       | 100   | 600 cos 30° | 600 sin 30° | –50    | 51.96(103)  | 30.0(103)  | -5.0(103) |     |
|         | 900   |             |             |        | 207.85(103) | 120.0(103) | 15.0(103) |     |
a
Thus,
~xL 207.85(103)mm2
Σ
|   x   |       |               | 230.94 mm   |     | 231 mm    |     | Ans. |     |
| ----- | ----- | ------------- | ----------- | --- | --------- | --- | ---- | --- |
| =     | =     |               | =           |     | =         |     |      |     |
|       | ΣL    | 900 mm        |             |     |           |     |      |     |
|       | Σ ~yL | 120.0(103)mm2 |             |     |           |     |      |     |
|   y = | =     |               | = 133.33 mm |     | = 133 mm  |     | Ans. |     |
|       | ΣL    | 900 mm        |             |     |           |     |      |     |
~zL 15.0(103)mm2
Σ
|   z = | =   |         | = 16.67 mm | =   | 16.7 mm  |     | Ans. |     |
| ----- | --- | ------- | ---------- | --- | -------- | --- | ---- | --- |
|       | ΣL  | 900 mm2 |            |     |          |     |      |     |
Ans:
x = 231 mm
y = 133 mm
z = 16.7 mm
937

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–58.
| Locate the center of gravity 1x,y,z2 |     | of the homogeneous |     |     | z   |
| ------------------------------------ | --- | ------------------ | --- | --- | --- |
wire.
400mm
SOLUTION
p
| 'xL          |          | 2(300)     |             |     |     |
| ------------ | -------- | ---------- | ----------- | --- | --- |
| © = 150(500) | + 0(500) | + a b(300) | = 165000mm2 |     |     |
p 2 y
300mm
p
| L       | a b(300) |             |     |     |     |
| ------- | -------- | ----------- | --- | --- | --- |
| © = 500 | + 500 +  | = 1471.24mm |     |     |     |
2
'x L x
| ©   | 1 6 5  0 0 0 |     |     |      |     |
| --- | ------------ | --- | --- | ---- | --- |
| x = | = = 112mm    |     |     | Ans. |     |
| L   | 1 4 7 1 .2 4 |     |     |      |     |
©
Due to symmetry,
| y = 112mm    |            |             |               | Ans. |     |
| ------------ | ---------- | ----------- | ------------- | ---- | --- |
| 'zL          |            | p           |               |      |     |
| © = 200(500) | + 200(500) | + 0a b(300) | = 200 000 mm2 |      |     |
2
| 'z L | 2 0 0 0 0 0 |     |     |     |     |
| ---- | ----------- | --- | --- | --- | --- |
z ©
| =   | = = 136mm    |     |     | Ans. |     |
| --- | ------------ | --- | --- | ---- | --- |
| © L | 1 4 7 1 .2 4 |     |     |      |     |
Ans:
x = 112 mm
y = 112 mm
z = 136 mm
938

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–59.
To determine the location of the center of gravity of the
– G
automobile it is first placed in a level position,with the two y
wheels on one side resting on the scale platform P.In this
position the scale records a reading of W.Then,one side is
1
elevated  to  a  convenient  height  c as  shown. The  new c P
reading on the scale is W. 2 If the automobile has a total x –
weight of W,determine the location of its center of gravity
G(x,y). W
b 2
SOLUTION
Equation of Equilibrium:First,we will consider the case in which the automobile is
| in a level position. |     | Referring to the free-body diagram in Fig. |     |     |     |     |     | a and writing the |     |     |
| -------------------- | --- | ------------------------------------------ | --- | --- | --- | --- | --- | ----------------- | --- | --- |
moment equation of equilibrium about point A,
| a+©M                             | =   |     |      | -    | =         |     |       | = W 1 |      |     |
| -------------------------------- | --- | --- | ---- | ---- | --------- | --- | ----- | ----- | ---- | --- |
|                                  | 0;  |     | W(b) | W(x) | 0         |     | x     | b     | Ans. |     |
|                                  | A   |     | 1    |      |           |     |       | W     |      |     |
|                                  |     |     |      | c    |           |     | 2b2 - | c2    |      |     |
| From the geometry in Fig.c,sin u |     |     |      | =    | and cos u | =   |       |       |      |     |
.Using the result of x
|     |     |     |     | b   |     |     | b   |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
and referring to the free-body diagram in Fig.b,we can write the moment equation
of equilibrium about point A¿.
|     |       |     |     | 2b2   | - c2  |      | 2b2 | - c2 W    | c     |     |
| --- | ----- | --- | --- | ----- | ----- | ---- | --- | --------- | ----- | --- |
| a   | +©M = |     | Bb¢ |       | ≤R    | - W¢ |     | ≤a 1 bb - | Wa by | =   |
|     | A¿ 0; |     | W 2 |       |       |      |     |           |       | 0   |
|     |       |     |     | b     |       |      | b   | W         | b     |     |
|     |       |     |     | b(W - | W)2b2 | - c2 |     |           |       |     |
|     |       |     | =   | 2     | 1     |      |     |           |       |     |
|     |       |     | y   |       |       |      |     |           | Ans.  |     |
cW
Ans:
W 1
x = b
W
b(W W ) b2 c2
2 - 1 -
y =
cW2
939

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
| *9–60. Locate the centroid yof the cross-sectional area of |     |     |     | y   |
| ---------------------------------------------------------- | --- | --- | --- | --- |
the built-up beam.
200 mm
200 mm
20 mm
50 mm
150 mm
|          |     |     | 10 mm        | 10 mm |
| -------- | --- | --- | ------------ | ----- |
| Solution |     |     | 300 mm 20 mm | 20 mm |
Centroid: The centroid of each composite segment is shown in Fig. a.
x
| ΣyA 225(450)(40) | + 2 400(200)(10) | + 510(400)(20) |     |     |
| ---------------- | ---------------- | -------------- | --- | --- |
y
= =
| ΣA      | 450(40) + 2(200)(10) | + 400(20) |     |     |
| ------- | -------------------- | --------- | --- | --- |
|         | 3                    | 4         |     |     |
| 324 mm  |                      | Ans.      |     |     |
=
Ans:
y = 324mm
940

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–61.
Locate the centroid y of the cross-sectional area of the
beam constructed from a channel and a plate.Assume all
corners are square and neglect the size of the weld at A.
20mm y
350mm
C
10mm
A
70mm
SOLUTION
325mm 325mm
Centroid:The area of each segment and its respective centroid are tabulated below.
|         | A(mm2)  | '      | ' yA(mm3) |     |
| ------- | ------- | ------ | --------- | --- |
| Segment |         | y (mm) |           |     |
| 1       | 350(20) | 175    | 1225000   |     |
| 2       | 630(10) | 355    | 2236500   |     |
| 3       | 70(20)  | 385    | 539000    |     |
|         | 14700   |        | 4000500   |     |
©
Thus,
'
| ©yA | 4000500 |     |     |     |
| --- | ------- | --- | --- | --- |
'
| y = | = = 272.14mm | = 272mm |     | Ans. |
| --- | ------------ | ------- | --- | ---- |
| ©A  | 14700        |         |     |      |
Ans:
y = 272 mm
941

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
| 9–62.                   |                                    |     |     |     |     |     | y   |     |
| ----------------------- | ---------------------------------- | --- | --- | --- | --- | --- | --- | --- |
| Locate the centroid (x, | y) of the member’s cross-sectional |     |     |     |     |     |     |     |
30mm
area.
40mm
SOLUTION
50mm
Centroid:The area of each segment and its respective centroid are tabulated below.
x
|         |        | '     |     | '     | '       | '       |      |       |
| ------- | ------ | ----- | --- | ----- | ------- | ------- | ---- | ----- |
|         | A(mm2) |       |     |       | xA(mm3) | yA(mm3) | 60mm | 100mm |
| Segment |        | x(mm) |     | y(mm) |         |         |      |       |
1
| 1   | 13021902 |     | 20  | 30  | 27 000 | 40500 |     |     |
| --- | -------- | --- | --- | --- | ------ | ----- | --- | --- |
2
| 2   | 30(90)  |     | 45  | 45  | 121 500 | 121500 |     |     |
| --- | ------- | --- | --- | --- | ------- | ------ | --- | --- |
| 3   | 100(50) |     | 110 | 25  | 550 000 | 125000 |     |     |
| ©   | 9050    |     |     |     | 698 500 | 287000 |     |     |
Thus,
'
©xA
698500
|     | x = = |      | = 77.18mm | = 77.2 mm |     | Ans. |     |     |
| --- | ----- | ---- | --------- | --------- | --- | ---- | --- | --- |
|     | ©A    | 9050 |           |           |     |      |     |     |
'
|     | ©yA | 287000 |         |        |     |      |     |     |
| --- | --- | ------ | ------- | ------ | --- | ---- | --- | --- |
|     | = = |        | =       | =      |     |      |     |     |
|     | y   |        | 31.71mm | 31.7mm |     | Ans. |     |     |
|     | ©A  | 9050   |         |        |     |      |     |     |
Ans:
x = 77.2 mm, y = 31.7 mm
942

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–63.
Determine the location y of the centroid C of the beam 150 mm
having the cross-sectional area shown. 15 mm
B
y
C
x x
150 mm
15 mm
15 mm A
100 mm
Solution
Centroid. The locations of the centroids measuring from the x axis for segments 1,
2 and 3 are indicated in Fig. a. Thus
~
ΣyA 7.5(15)(150) + 90(150)(15) + 172.5(15)(100)
y = =
ΣA 15(150) + 150(15) + 15(100)
= 79.6875 mm = 79.7 mm Ans.
Ans:
y = 79.7 mm
943

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–64. y
Locate the centroid yof the beam’s cross-sectional area.
50 mm 50 mm
10 mm
10 mm
10 mm 10 mm 75 mm
10 mm
x
SOLUTION
100 mm 100 mm
Centroid:The centroid of each composite segment is shown in Fig.a.We have
'
© y A 5(180)(10) + 2[37.5(75)(10)] + 2[70(40)(10)]
y = = = 29.6mm Ans.
©A 180(10) + 2(75)(10) + 2(40)(10)
Ans:
y = 29.6mm
944

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–65.
Determine the location yof the centroid of the beam’s cross-
sectional area.Neglect the size of the corner welds at Aand B
for the calculation.
35mm
A
SOLUTION
110mm
| '   |     |     | 35 2 | 35  |     |     |
| --- | --- | --- | ---- | --- | --- | --- |
© yA = p(25)2(25) + 15(110)(50 + 55) + pa b a50 + 110 + b = 393112mm3 C
|     |     |     | 2   | 2   |     |     |
| --- | --- | --- | --- | --- | --- | --- |
15mm
35 2
| p(25)2 |           | pa b 4575.6mm2 |     |     |     | B   |
| ------ | --------- | -------------- | --- | --- | --- | --- |
| ©A =   | + 15(110) | + =            |     |     | y   |     |
2
50mm
'
| ©yA | 393112 |        |     |      |     |     |
| --- | ------ | ------ | --- | ---- | --- | --- |
| y   |        | 85.9mm |     | Ans. |     |     |
| =   | = =    |        |     |      |     |     |
| ©A  | 4575.6 |        |     |      |     |     |
Ans:
y = 85.9 mm
945

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–66.  An aluminum strut has a cross section referred to as
a deep hat. Locate the centroid y of its area. Each segment  30 mm 30 mm
has a thickness of 10 mm.
–y
x'
C 100 mm
80 mm
Solution
Centroid: The area of each segment and its respective centroid are tabulated below.
|     | Segment A(mm2) | y(mm) yA(mm3) |     |     |
| --- | -------------- | ------------- | --- | --- |
|     | 1 40(10)       | 5 2 000       |     |     |
|     | 2 100(20)      | 50 100 000    |     |     |
|     | 3 60(10)       | 95 57 000     |     |     |
|     | Σ 3 000        | 159 000       |     |     |
Thus,
|     | ΣyA 159 000 |             |     |      |
| --- | ----------- | ----------- | --- | ---- |
|     | y = =       | = 53.0 mm   |     | Ans. |
|     | ΣA 3 000    |             |     |      |
Ans:
y = 53.0 mm
946

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–67.
300mm
| Locate the centroid y |     | of the concrete beam having the |     |     |     | 300mm |
| --------------------- | --- | ------------------------------- | --- | --- | --- | ----- |
300mm
tapered cross section shown.
y
C 80mm
x
SOLUTION
360mm
100mm
'
| ©yA | =             | +             | + 2c | 1 (100)(360)(200)d | = 19.44(106)mm3 |     |
| --- | ------------- | ------------- | ---- | ------------------ | --------------- | --- |
|     | 900(80)(40)   | 100(360)(260) |      |                    |                 |     |
2
1
| ©A  | = 900(80) | + 100(360) | + 2c (100)(360)d | = 0.144(106)mm2 |     |     |
| --- | --------- | ---------- | ---------------- | --------------- | --- | --- |

2
'
|     | ©yA   | 19.44(106) |     |     |     |     |
| --- | ----- | ---------- | --- | --- | --- | --- |
|     | y = = |            | =   |     |     |     |
135mm Ans.
©A 0.144(106)
Ans:
y = 135mm
947

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–68.
Locate the centroid y for the beam’s cross-sectional area.
120 mm
240 mm
x
y
Solution
240 mm
Centroid. The locations of the centroids measuring from the x axis for segments 120 mm 240 mm
1 and 2 are indicated in Fig. a. Thus
~
ΣyA 300(120)(600) + 120(240)(120)
y = =
ΣA 120(600) + 240(120)
= 248.57 mm = 249 mm
Ans:
y = 249 mm
948

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–69.  The gravity wall is made of concrete. Determine the  y
location (x, y) of the center of gravity G for the wall. 1.2 m
_
x
3 m
G
_
y

0.4 m
x
2.4 m
Solution
0.6 m 0.6 m
|                   |           | 1            | 1            |     |
| ----------------- | --------- | ------------ | ------------ | --- |
| ΣxA 1.8(3.6)(0.4) | 2.1(3)(3) | 3.4 (3)(0.6) | 1.2 (1.8)(3) |     |
| =                 | +         | -            | -            |     |
|                   |           | 2            | 2            |     |
|                   |           | a b          | a b          |     |
= 15.192 m3
|                     |             | 1              | 1              |     |
| ------------------- | ----------- | -------------- | -------------- | --- |
| ΣyA = 0.2(3.6)(0.4) | + 1.9(3)(3) | - 1.4 (3)(0.6) | - 2.4 (1.8)(3) |     |
|                     |             | 2              | 2              |     |
|                     |             | a b            | a b            |     |
= 9.648 m3
|               | 1                  | 1           |     |     |
| ------------- | ------------------ | ----------- | --- | --- |
| ΣA = 3.6(0.4) | + 3(3) -  (3)(0.6) | -  (1.8)(3) |     |     |
|               | 2                  | 2           |     |     |
6.84 m2
=
| ΣxA | 15.192 |     |     |     |
| --- | ------ | --- | --- | --- |
x
| =   | = = 2.22 m  |     |     | Ans. |
| --- | ----------- | --- | --- | ---- |
| ΣA  | 6.84        |     |     |      |
| ΣyA | 9.648       |     |     |      |
| y = | = = 1.41 m  |     |     | Ans. |
| ΣA  | 6.84        |     |     |      |
Ans:
x = 2.22 m, y = 1.41 m
949

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–70.
| Locate the centroid y |     |     | for the cross-sectional area of the |     |     |     |     |     |     |     |     |
| --------------------- | --- | --- | ----------------------------------- | --- | --- | --- | --- | --- | --- | --- | --- |
angle.
–y
|     |     |     |     |     |     |     |     |     |     | a a |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
C
| SOLUTION |     |     |     |     |     |     |     |     |     | t   | t   |
| -------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
Centroid :The area and the centroid for segments 1 and 2 are
|     |     |     |     | A 1 =    | t1a - t2 |     |     |       |     |     |     |
| --- | --- | --- | --- | -------- | -------- | --- | --- | ----- | --- | --- | --- |
|     | '   | a   | - t | t        | t        |     | 22  |       |     |     |     |
|     | y   | = a | +   | bcos 45° | +        | =   | 1a  | + 2t2 |     |     |     |
|     | 1   |     | 2   | 2        | 2cos 45° |     | 4   |       |     |     |     |
|     |     |     |     | A        | = at     |     |     |       |     |     |     |
2
|     |     | a   | t        |     | t        | 22  |       |     |     |     |     |
| --- | --- | --- | -------- | --- | -------- | --- | ----- | --- | --- | --- | --- |
|     | ' y |     | bcos 45° |     |          |     | 1a t2 |     |     |     |     |
|     | 2   | = a | -        | +   |          | =   | +     |     |     |     |     |
|     |     | 2   | 2        |     | 2cos 45° | 4   |       |     |     |     |     |
Listed in a tabular form,we have
|     |         |     |      |     |     | '     |     | '        |         |     |     |
| --- | ------- | --- | ---- | --- | --- | ----- | --- | -------- | ------- | --- | --- |
|     | Segment |     |      | A   |     | y     |     | yA       |         |     |     |
|     |         | 1   | t1a  | t2  | 22  |       | 22t |          |         |     |     |
|     |         |     |      | -   | 1a  | + 2t2 |     | 1a2 + at | - 2t2 2 |     |     |
|     |         |     |      |     | 4   |       | 4   |          |         |     |     |
|     |         | 2   |      | at  | 22  |       | 22t |          |         |     |     |
|     |         |     |      |     | 1a  | + t2  |     | 1a2 +    | at2     |     |     |
|     |         |     |      |     | 4   |       |     | 4        |         |     |     |
|     |         |     | t12a | t2  |     |       | 22t |          |         |     |     |
|     |         | ©   |      | -   |     |       |     | 1a2 + at | - t2 2  |     |     |
2
Thus,
22t
|     |     |     |     |     | 1a2  | at  | t2  |     |     |     |     |
| --- | --- | --- | --- | --- | ---- | --- | --- | --- | --- | --- | --- |
|     |     |     |     | '   | +    | -   | 2   |     |     |     |     |
|     |     |     | ©yA |     | 2    |     |     |     |     |     |     |
|     |     |     | y = | =   |      |     |     |     |     |     |     |
|     |     |     |     | ©A  | t12a | t2  |     |     |     |     |     |
-
|     |     |     |     | 22  | a2 + | at - t2 |     |     |      |     |     |
| --- | --- | --- | --- | --- | ---- | ------- | --- | --- | ---- | --- | --- |
|     |     |     |     | =   |      |         |     |     | Ans. |     |     |
|     |     |     |     |     | 2 2a | - t     |     |     |      |     |     |
Ans:
2(a2 + at - t2)
y =
2 2(2a - t)
950

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–71. Uniform blocks having a length Land mass mare
y
| stacked  | one  on  top  of  | the  other, with  | each  | block |
| -------- | ----------------- | ----------------- | ----- | ----- |
overhanging the other by a distance d,as shown.Show that
2d
the maximum number of blocks which can be stacked in
6 L>d.
this manner is n
d
x
L
Solution
|          | L L       | d   |     |     |
| -------- | --------- | --- | --- | --- |
| n = 2: x | = + d = + | 2   |     |     |
|          | 2 2       | 2   |     |     |
a b
|     | L       | L      |     |     |
| --- | ------- | ------ | --- | --- |
|     | d + W + | 2d + W |     |     |
|     | 2       | 2      | L   | d   |
n 3: x
| =   | =       |     | =   | + 3 |
| --- | ------- | --- | --- | --- |
|     | a b 2Wa | b   | 2   | 2   |
a b
In general:
| L   | d   |     |     |     |
| --- | --- | --- | --- | --- |
x = n
+
| 2   | 2   |     |     |     |
| --- | --- | --- | --- | --- |
a b
For stable stack:
| L     | d      |     |     |     |
| ----- | ------ | --- | --- | --- |
| x = + | n … L  |     |     |     |
| 2     | 2      |     |     |     |
a b
L
| n …   |     |     |     | Ans. |
| ----- | --- | --- | --- | ---- |
d
Ans:
L
n
…
d
951

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–72.
| A      | toy  skyrocket  |     | consists           |        | of  a    | solid     | conical    | top,  |     | a   |       |      |
| ------ | --------------- | --- | ------------------ | ------ | -------- | --------- | ---------- | ----- | --- | --- | ----- | ---- |
| r      | 600kg>m3,       |     | a hollow cylinder, |        | r        | 400kg>m3, |            | and a |     |     |       | 20mm |
| t      | =               |     |                    |        | c        | =         |            |       |     | 5mm | 100mm |      |
|        |                 |     |                    |        |          | r         | 300 kg>m3. |       | 3mm |     |       |      |
| stick  | having          | a   | circular           | cross  | section, | s         | =          |       |     |     |       |      |
10mm
Determine the length of the stick,x,so that the center of
| gravity Gof the skyrocket is located along line aa. |     |     |     |     |     |     |     |     |     | G   |     |     |
| --------------------------------------------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
a
x
SOLUTION
|     |       | 20              | 1                |                |      |          |            |       | x               |       |     |     |
| --- | ----- | --------------- | ---------------- | -------------- | ---- | -------- | ---------- | ----- | --------------- | ----- | --- | --- |
|     | 'xm a | bca             | bp(5)2(20)d(600) |                |      | CpA      | 52         | 2.52B | D C (x)p(1.5)2D |       |     |     |
| ©   | =     |                 |                  |                |      | - 50     | -          | (100) | (400) -         | (300) |     |     |
|     |       | 4               | 3                |                |      |          |            |       | 2               |       |     |     |
|     |       |                 | A 106B           | x2(1060.29) kg |      | # mm4>m3 |            |       |                 |       |     |     |
|     | =     | - 116.24        |                  | -              |      |          |            |       |                 |       |     |     |
|     |       | 1               |                  |                | pA   | 2.52B    |            |       | Cxp(1.5)2D      |       |     |     |
| ©   | m = c | p(5)2(20)d(600) |                  | +              | 52 - |          | (100)(400) | +     | (300)           |       |     |     |
3
|     | 2.670 | A 106B | 2120.58xkg   |           | # mm3/m3 |            |     |     |     |     |     |     |
| --- | ----- | ------ | ------------ | --------- | -------- | ---------- | --- | --- | --- | --- | --- | --- |
|     | =     |        | +            |           |          |            |     |     |     |     |     |     |
|     |       | 'x m   | -1 1 6 . 2 4 | ( 1 0 6 ) | x 2 (1   | 0 6 0 .29) |     |     |     |     |     |     |
|     | x ©   |        |              |           | -        |            |     |     |     |     |     |     |
|     | =     | =      |              |           |          |            | = - | 100 |     |     |     |     |
|     | ©     | m      | 2 . 6 7 0    | ( 1 0 6 ) | 2 1 2 0  | .5 8 x     |     |     |     |     |     |     |
+
|     |           | A 106B |               |         |          |         | A 106B |           | A 103Bx |     |     |     |
| --- | --------- | ------ | ------------- | ------- | -------- | ------- | ------ | --------- | ------- | --- | --- | --- |
|     | - 116.24  |        | - x2(1060.29) |         | =        | - 267.0 |        | - 212.058 |         |     |     |     |
|     |           |        |               | A 103Bx |          | A 106B  |        |           |         |     |     |     |
|     | 1060.29x2 |        | - 212.058     |         | - 150.80 |         | =      | 0         |         |     |     |     |

Solving for the positive root gives
x
|     |     |     |     |     | = 490mm |     |     |     | Ans. |     |     |     |
| --- | --- | --- | --- | --- | ------- | --- | --- | --- | ---- | --- | --- | --- |
Ans:
 x 490 mm
=
952

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–73.
| Determine the location x |     |     | of the centroid C |     | of the shaded |     |
| ------------------------ | --- | --- | ----------------- | --- | ------------- | --- |
y
area which is part of a circle having a radius r.
r
a
SOLUTION C
x
a
Using symmetry, to simplify, consider just the top half:
x
| '    | 1      | 2 r    | 1                   |     | 2       |     |
| ---- | ------ | ------ | ------------------- | --- | ------- | --- |
| © xA | = r2aa | sin ab | - (rsin a)(rcos a)a |     | rcos ab |     |
|      | 2      | 3 a    | 2                   |     | 3       |     |
|      | r3     | r3     |                     |     |         |     |
|      |        | sin a  | sin acos2a          |     |         |     |
|      | =      | -      |                     |     |         |     |
|      | 3      | 3      |                     |     |         |     |
r3
sin3a
=
3
|     | 1 r2a | 1 (rsin a)(rcos a) |           |           |     |      |
| --- | ----- | ------------------ | --------- | --------- | --- | ---- |
| ©A  | =     | -                  |           |           |     |      |
|     | 2     | 2                  |           |           |     |      |
|     | 1     | sin2a              |           |           |     |      |
|     | r2aa  |                    | b         |           |     |      |
|     | =     | -                  |           |           |     |      |
|     | 2     | 2                  |           |           |     |      |
|     | '     | r 3 sin3a          |           | 2 rsin3a  |     |      |
|     | © xA  | 3                  |           | 3         |     |      |
| x = |       | =                  | =         |           |     | Ans. |
|     | ©A    | 1 r2Aa             | sin  2 aB | a sin  2a |     |      |
|     |       | 2 -                | 2         | - 2       |     |      |
Ans:
2 r sin3 a
x = 3
  sin 2a
a -
2
953

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–74.
225mm 225mm
Locate the centroid yof the bulb-tee cross section.
50mm
400mm
SOLUTION 75mm
C
Centroid:The area of each segment and its respective centroid are tabulated below.
_
y
|         |          | '      | '         |     | 75mm |
| ------- | -------- | ------ | --------- | --- | ---- |
| Segment | A 1mm2 2 | y 1mm2 | yA 1mm3 2 |     |      |
100mm
| 1   | 450(50) | 600 | 13 500 000 |     | x   |
| --- | ------- | --- | ---------- | --- | --- |
300mm
| 2   | 475(75) | 337.5 | 12023437.5 |     |     |
| --- | ------- | ----- | ---------- | --- | --- |
1
| 3   | 122521752 | 125 | 1054 687.5 |     |     |
| --- | --------- | --- | ---------- | --- | --- |
2
| 4   | 300(100) | 50  | 1500000    |     |     |
| --- | -------- | --- | ---------- | --- | --- |
| ©   | 96 562.5 |     | 28 078 125 |     |     |
Thus,
'
©yA
28078125
| y = | = = 290.78mm | = 291mm |     | Ans. |     |
| --- | ------------ | ------- | --- | ---- | --- |
©A
96562.5
Ans:
y = 291 mm
954

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
| 9–75. Determine the distance x |     | to the centroid of the | y   |
| ------------------------------ | --- | ---------------------- | --- |
solid which consists of a cylinder with a hole of length
120 mm
h = 50 mmbored into its base.
40 mm
20 mm
h
Solution
| ΣV = p(40)2(120) | p(20)2(50) | = 172(103)p mm3 |     |
| ---------------- | ---------- | --------------- | --- |
-
| ΣxV = 60(p)(40)2(120) | 25(p)(20)2(50) | 11.02(106)p mm4 |     |
| --------------------- | -------------- | --------------- | --- |
|                       | -              | -               |     |
| ΣxV 11.02(106)p       |                |                 |     |
x
| = =          | = 64.1 mm  |     | Ans. |
| ------------ | ---------- | --- | ---- |
| ΣV 172(103)p |            |     |      |
Ans:
x = 64.1 mm
955

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
| *9–76. Determine the distance h |     |     |     | to which a hole must be |     |     | y   |
| ------------------------------- | --- | --- | --- | ----------------------- | --- | --- | --- |
bored into the cylinder so that the center of mass of the
120 mm
| assembly is located at x |     |     | = 64 mm. | The material has a |     |     |     |
| ------------------------ | --- | --- | -------- | ------------------ | --- | --- | --- |
density of 8 Mg>m3.
40 mm
x
20 mm
h
Solution
| ΣV pr2 | d pr2 | h    |         |     |     |     |     |
| ------ | ----- | ---- | ------- | --- | --- | --- | --- |
| =      | 2 -   | 1    |         |     |     |     |     |
| d      |       |      | h       |     |     |     |     |
|        | r2    |      |         | r2  |     |     |     |
| ΣxV =  | (p)   | d -  | p       | h   |     |     |     |
| 2      |       | 2    | 2       | 1   |     |     |     |
|        | 1 d2  | 2    | 1 21 h2 | 2   |     |     |     |
|        |       | p r2 | -       | p   | r2  |     |     |
| ΣxV    | 2     |      | 2 2     |     | 1   |     |     |
x
| =       | =      |         |           |      |     |     |     |
| ------- | ------ | ------- | --------- | ---- | --- | --- | --- |
| ΣV      |        | 1 2p1r2 | d2 - pr12 | h 21 | 2   |     |     |
|         |        |         | 2         | 1    |     |     |     |
| 2x r2 d | 2x     | r2 h    | d2r2      | h2r2 |     |     |     |
| 2       | -      | 1 =     | 2 -       | 1    |     |     |     |
| 1 2     | 1      | 2       |           |      |     |     |     |
|         |        |         | r 2       |      |     |     |     |
| h2      |        |         | 2         |      |     |     |     |
| - 2xh   | + d(2x | - d)    | =         | 0    |     |     |     |
r
1
|         |        | a   | b        |     |            |          |     |
| ------- | ------ | --- | -------- | --- | ---------- | -------- | --- |
| Set x = | 64 mm, | r   | = 40 mm, | r   | = 20 mm, d | = 120 mm |     |
|         |        | 2   |          |     | 1          |          |     |
h2
| - 128h | + 3840 | = 0 |     |     |     |     |     |
| ------ | ------ | --- | --- | --- | --- | --- | --- |
Solving,
| h = 80 mm  |     |     Ans.  |     | or    | h = 48 mm  |       Ans. |     |
| ---------- | --- | --------- | --- | ----- | ---------- | ---------- | --- |
Ans:
h = 48 mm
956

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
z
9–77.  Locate the center of mass z of the assembly. The
| material has a density of r | = 3 Mg/m3. There is a 30-mm  |     |     |
| --------------------------- | ---------------------------- | --- | --- |
diameter hole bored through the center. 40 mm
20 mm
30 mm
100 mm
–z
y
Solution
x
Centroid: Since the density is the same for the whole material, the centroid of the
volume coincide with centroid of the mass. The volume of each segment and its
respective centroid are tabulated below.
V(mm3) zV(mm4)
| Segment | z(mm) |     |     |
| ------- | ----- | --- | --- |
1
| 1 p(402)(60) | 115 | 3.68p(106) |     |
| ------------ | --- | ---------- | --- |
3
| 2 p(402)(100) | 50  | 8.00p(106) |     |
| ------------- | --- | ---------- | --- |
1
| 3 - p(202)(30) | 137.5 | -0.550p(106) |     |
| -------------- | ----- | ------------ | --- |
3
-p(152)(130) -1.90125p(106)
| 4              | 65  |               |     |
| -------------- | --- | ------------- | --- |
| Σ 158.75p(103) |     | 9.22875p(106) |     |
Thus,
9.22875p(106)
ΣzV
| z = = | = 58.13 mm | = 58.1 mm  | Ans. |
| ----- | ---------- | ---------- | ---- |
ΣV 158.75p(103)
Ans:
z = 58.1 mm
957

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–78. z
| Locate the centroid z | of the homogenous solid formed by |     |     |     |     |
| --------------------- | --------------------------------- | --- | --- | --- | --- |
boring a hemispherical hole into the cylinder that is capped
with a cone.
300 mm
SOLUTION
150 mm
400 mm
| Centroid: Since the solid is made of a homogeneous material, |     |     |     | its center of mass |     |
| ------------------------------------------------------------ | --- | --- | --- | ------------------ | --- |
coincides with the centroid of its volume.The centroid of each composite segment is
shown in Figs.aand b.Since segment (3) is a hole,its volume should be considered 150 mm
x
negative.We have y
|                      |     | 1             |                      | 3              | 2         |
| -------------------- | --- | ------------- | -------------------- | -------------- | --------- |
| ' p(0.2)(0.152)(0.4) |     | + p(0.4       | + 0.075)(0.152)(0.3) | + a (0.15)ba-  | p(0.153)b |
| ©z V                 |     | 3             |                      | 8              |  3        |
|  z = =               |     |               |                      |                |           |
| ©V                   |     |               | 1                    | 2              |           |
|                      |     | p(0.152)(0.4) | + p(0.152)(0.3)      | + a- p(0.153)b |           |
|                      |     |               | 3                    |  3             |           |
-3)p
2.7422(10
|   =  | = 0.3047m | = 305mm |     |     | Ans. |
| ---- | --------- | ------- | --- | --- | ---- |
| -3)p |           |         |     |     |      |
9(10
Ans:
z = 305 mm
958

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
| 9–79. |     |     |     |     |     |     | z   |     |
| ----- | --- | --- | --- | --- | --- | --- | --- | --- |
Locate the center of mass zof the solid formed by boring a
hemispherical hole into a cylinder that is capped with a cone.
The cone and cylinder are made of materials having densities
of 7.80 Mg>m3and 2.70 Mg>m3,respectively.
300 mm
| SOLUTION |     |     |     |     |     |     | 150 mm | 400 mm |
| -------- | --- | --- | --- | --- | --- | --- | ------ | ------ |
Centroid:The center of mass of each composite segment is shown in Figs.aand b. 150 mm
Since segment (3) is a hole,its mass should be considered negative.We have x
y
|     |     |     |     | 1   |     | 3   | 2   |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
' 0.2c2700cp(0.152)(0.4)d d + (0.4 + 0.075)7800c  p(0.152)(0.3)d + a  (0.15)bc-2700a  p(0.153)bd
©z
| m    |     | a                   |         | 3               |           | 8           | 3   |     |
| ---- | --- | ------------------- | ------- | --------------- | --------- | ----------- | --- | --- |
|  z = | =   |                     |         |                 |           |             |     |     |
| ©m   |     |                     |         | 1               |           | 2           |     |     |
|      |     | 2700cp(0.152)(0.4)d | + 7800c |  p(0.152)(0.3)d | + c-2700a |  p(0.153)bd |     |     |
|      |     |                     |         | 3               |           | 3           |     |     |
12.8545p
|  =  | = 0.3593 m | = 359 mm |     |     | Ans. |     |     |     |
| --- | ---------- | -------- | --- | --- | ---- | --- | --- | --- |
35.775p
Ans:
z = 359 mm
959

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–80.
| Locate the center of mass (x,y,z) |     |     |     |     | of the homogeneous |     |     |     |     | z   |     |
| --------------------------------- | --- | --- | --- | --- | ------------------ | --- | --- | --- | --- | --- | --- |
block assembly.
250 mm
200mm
| SOLUTION |     |     |     |     |     |     |     | x   |     |     | 150 mm |
| -------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ------ |
100 mm
150 mm
150 mm y
Centroid:Since the block is made of a homogeneous material,the center of mass of
theblock coincides with the centroid of its volume.The centroid of each composite
segment is shown in Fig.a.
1
|     |     |                     |                 |     |                      |     | (200)a b(150)(150)(100) |     |        |              |      |
| --- | --- | ------------------- | --------------- | --- | -------------------- | --- | ----------------------- | --- | ------ | ------------ | ---- |
|     | 'x  | (75)(150)(150)(550) |                 | +   | (225)(150)(150)(200) | +   |                         |     |        |              |      |
|     | © V |                     |                 |     |                      |     | 2                       |     | 2.16 5 | 6 2 5 ( 109) |      |
| x   |     |                     |                 |     |                      |     |                         |     |        | 120mm        | Ans. |
|     | = V | =                   |                 |     |                      |     |                         |     | =      | 6) =         |      |
|     | ©   |                     |                 |     |                      |     | 1                       |     | 1      | 8 ( 1 0      |      |
|     |     |                     | (150)(150)(550) |     | + (150)(150)(200)    | +   | (150)(150)(100)         |     |        |              |      |
2
1
|     |     | (275)(150)(150)(550) |     | +   | (450)(150)(150)(200) | +   | (50)a b(150)(150)(100) |     |               |     |     |
| --- | --- | -------------------- | --- | --- | -------------------- | --- | ---------------------- | --- | ------------- | --- | --- |
|     | 'yV |                      |     |     |                      |     | 2                      |     | 5.484375(109) |     |     |
y ©
|     | =   | =   |                 |     |                 |     |                 |     | =       | = 305mm | Ans. |
| --- | --- | --- | --------------- | --- | --------------- | --- | --------------- | --- | ------- | ------- | ---- |
|     | © V |     |                 |     |                 |     | 1               |     | 18(106) |         |      |
|     |     |     | (150)(150)(550) |     | (150)(150)(200) |     | (150)(150)(100) |     |         |         |      |
|     |     |     |                 |     | +               | +   |                 |     |         |         |      |
2
1
|     |     |                     |                 |     |                     | (50)a | b(150)(150)(100) |     |            |          |      |
| --- | --- | ------------------- | --------------- | --- | ------------------- | ----- | ---------------- | --- | ---------- | -------- | ---- |
|     | 'z  | (75)(150)(150)(550) |                 | +   | (75)(150)(150)(200) | +     |                  |     |            |          |      |
|     | © V |                     |                 |     |                     |       | 2                |     | 1.32 1 8 7 | 5 ( 109) |      |
| z   |     |                     |                 |     |                     |       |                  |     |            | 73.4mm   | Ans. |
|     | = V | =                   |                 |     |                     |       |                  |     | =          | =        |      |
|     | ©   |                     |                 |     |                     | 1     |                  |     | 1 8 ( 1    | 0 6)     |      |
|     |     |                     | (150)(150)(550) |     | + (150)(150)(200)   | +     | (150)(150)(100)  |     |            |          |      |
2
Ans:
x = 120 mm
y = 305 mm
z = 73.4 mm
960

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–81.
| Determine the distance zto the centroid of the shape which |     |     |                |     | z   |     |
| ---------------------------------------------------------- | --- | --- | -------------- | --- | --- | --- |
| consists of a cone with a hole of height h                 |     |     | 50mmbored into |     |     |     |
=
its base.
500mm
SOLUTION
| 'zV 1 p(0.15)2A | Ba  | 0 .5               | 0. 05 |     |     |     |
| --------------- | --- | ------------------ | ----- | --- | --- | --- |
| © =             | 0.5 | b - p(0.05)2(0.05) | a b   | h   | C   |     |
| 3               |     | 4                  |   2   |     |     | z   |
y
50mm
| 1.463(10-3)m4 |     |     |     |     | 150mm |     |
| ------------- | --- | --- | --- | --- | ----- | --- |
=
1
| V p(0.15)2(0.5) |     | p(0.05)2(0.05) |     |     |     |     |
| --------------- | --- | -------------- | --- | --- | --- | --- |
| © =             | -   |                |     |     |     |     |
3
x
0.01139m3
=
| 'z V  |                 | -3)        |         |      |     |     |
| ----- | --------------- | ---------- | ------- | ---- | --- | --- |
| ©     | 1.4 6 3   ( 1 0 |            |         |      |     |     |
| z = = |                 | = 0.12845m | = 128mm | Ans. |     |     |
V 0 .0 1 1 3 9
©
Ans:
z = 128 mm
961

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–82.
z
Determine the distance hto which a 100-mm diameter hole
must be bored into the base of the cone so that the center of
| mass of the resulting shape is located at z |     | = 115 mm. The |     |     |     |
| ------------------------------------------- | --- | ------------- | --- | --- | --- |
material has a density of 8 Mg>m3.
500 mm
| SOLUTION |     |     | h   | C   | _   |
| -------- | --- | --- | --- | --- | --- |
z
y
50 mm
| 1 p10.152210.52A0 | .5B p10.05221h2Ah | B   |     | 150 mm |     |
| ----------------- | ----------------- | --- | --- | ------ | --- |
| 3                 | 4 -               | 2   |     |        |     |
= 0.115
1 p10.152210.52 p10.05221h2
3  -
x
| 0.4313 - 0.2875 h | = 0.4688 -   | 1.25 h2 |     |     |     |
| ----------------- | ------------ | ------- | --- | --- | --- |
| h2 - 0.230 h      | - 0.0300 = 0 |         |     |     |     |
Choosing the positive root,
| h = 323 mm |     | Ans. |     |     |     |
| ---------- | --- | ---- | --- | --- | --- |
Ans:
h = 323 mm
962

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–83. z
Locate the center of mass zof the assembly.The assembly
consists of a cylindrical center core,A,having a density of
7.90 Mg/m3,and a cylindrical outer part,B,and a cone cap,
C,each having a density of 2.70 Mg>m3.
400 mm
C A
400 mm
SOLUTION 100 mm
600 mm
B
Center of mass:The assembly is broken into four composite segments,as shown in
Figs.a,b,and c.Since segment (3) is a hole to segments (1) and (2),its mass should x 300 mm
y
be considred negative.We have
1
2700(0.3)cp(0.32)(0.6)d + 2700(0.6 + 0.2)c p(0.32)(0.8)d + (0.5)c-2700cp(0.12)(1)dd + 7900(0.5)cp(0.12)(1)d
gzm 3
z = c =
gm 1
2700cp(0.32)(0.6)d + 2700c p(0.32)(0.8)d + c-2700cp(0.12)(1)dd + 7900cp(0.12)(1)d
3
121.58p
= = 0.4630 m = 463 mm Ans.
262.6p
Ans:
z = 463mm
963

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–84.
Locate the center of mass z of the assembly.The cylinder
z
and the cone are made from materials having densities of
5Mg>m3and 9Mg>m3,respectively.
0.4 m 0.6 m
SOLUTION
| Center of mass: | The assembly is broken into two composite segments,as shown in |     |     |     |
| --------------- | -------------------------------------------------------------- | --- | --- | --- |
Figs.aand b.
0.2m 0.8 m
|     | Cp(0.22)(0.8) D      | 0.15)c 1 p(0.42)(0.6)d |     |     |
| --- | -------------------- | ---------------------- | --- | --- |
| '   | 5000(0.4) + 9000(0.8 | +                      |     |     |
| ©zm |                      | 3                      |     |     |
z = = x
| ©m  | Cp(0.22)(0.8) D | 1             |     | y   |
| --- | --------------- | ------------- | --- | --- |
|     | 5000 + 9000c    | p(0.42)(0.6)d |     |     |
3
1060.60
| =   | = 0.754 m = 754mm |     | Ans. |     |
| --- | ----------------- | --- | ---- | --- |
1407.4
Ans:
z = 754 mm
964

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–85. a
a
2 2 a
Ahole having a radius ris to be drilled in the center of the 2
a
homogeneous block.Determine the depth hofthe hole so 2
r h
that the center of gravity Gis as low as possible.
G a
SOLUTION
| ©V = a3 | - pr2h       |                 |
| ------- | ------------ | --------------- |
|         | AaB AhBCpr2h | D               |
| ©zV =   | a3 -         | = 1(a4 - pr2h2) |
|         | 2 2          | 2               |
1(a4 - pr2h2)
| ©zV |                         | a4 - pr2h2     |
| --- | ----------------------- | -------------- |
| z = | = 2                     | =              |
| ©V  | a3 - pr2h               | 2(a3 - pr2h)   |
|     | (a3 - pr2h)(-2pr2h)-(a4 | - pr2h2)(-pr2) |
dz = 1 B R =
0
| dh 2    |               | (a3 - pr2h)2 |
| ------- | ------------- | ------------ |
| pr2h2 - | 2a3h + a4 = 0 |              |
Solving for the smaller root,
2a3 - 2(2a3)2-4(pr2)a4
|     | h   | =   |
| --- | --- | --- |
2(pr2)
a3 - a22a2 - pr2
= Ans.
pr2
Ans:

a3 - a2 a2 - pr2
h =
2pr2
965

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–86.
The composite plate is made from both steel (A)and brass
z
(B)segments.Determine the mass and location 1x,y,z2of
|      |       |         |          | r   | 7.85Mg>m3 |     |     |     |     |     |
| ---- | ----- | ------- | -------- | --- | --------- | --- | --- | --- | --- | --- |
| its  | mass  | center  | G. Take  |     | =         |     | and |     |     |     |
st
r = 8.74 Mg>m3.
br
A
225mm
G
y
150 mm
B
150mm
30 mm
SOLUTION
x
|     |        |          | 1                     |     |     |          | 1                     |     |     |     |
| --- | ------ | -------- | --------------------- | --- | --- | -------- | --------------------- | --- | --- | --- |
| ©m  | = © rV | = c8.74a | (0.15)(0.225)(0.03)bd |     |     | + c7.85a | (0.15)(0.225)(0.03)bd |     |     |     |
|     |        |          | 2                     |     |     |          | 2                     |     |     |     |
[7.85(0.15)(0.225)(0.03)]
+
|     |        | C 4.4246                | A 10-3BD | C 3.9741 | A 10-3BD       | C 7.9481 | A 10-3BD         |     |         |     |
| --- | ------ | ----------------------- | -------- | -------- | -------------- | -------- | ---------------- | --- | ------- | --- |
|     |        | =                       |          | +        |                | +        |                  |     |         |     |
|     |        | 16.347                  | A 10-3B  | 16.4kg   |                |          |                  |     | Ans.    |     |
|     |        | =                       |          | =        |                |          |                  |     |         |     |
|     |        | 2                       |          |          |                |          | 1                |     |         |     |
|     | a0.150 | (0.150)b(4.4246)        |          |          | A 10-3B        | a0.150   | (0.150)b(3.9741) |     | A 10-3B |     |
| ©xm | =      | +                       |          |          |                | +        | +                |     |         |     |
|     |        | 3                       |          |          |                |          | 3                |     |         |     |
|     |        | 1 (0.150)(7.9481)(10-3) |          |          | 2.4971(10-3)kg | #        |                  |     |         |     |
|     | +      |                         |          | =        |                |          | m                |     |         |     |
2
|     | 1      |                  | A   | 10-3B | 2                    |     | A 10-3B | 0.225 |           | A 10-3B |
| --- | ------ | ---------------- | --- | ----- | -------------------- | --- | ------- | ----- | --------- | ------- |
| ©zm | = a    | (0.225)b(4.4246) |     |       | + a (0.225)b(3.9471) |     |         | + a   | b(7.9481) |         |
|     | 3      |                  |     |       | 3                    |     |         |       | 2         |         |
|     | 1.8221 | A 10-3B kg       | # m |       |                      |     |         |       |           |         |
=
|     | ©xm | 2.4971(10-3) |     |        |         |     |     |     |      |     |
| --- | --- | ------------ | --- | ------ | ------- | --- | --- | --- | ---- | --- |
| x = |     | =            | =   | 0.153m | = 153mm |     |     |     | Ans. |     |
|     | ©m  | 16.347(10-3) |     |        |         |     |     |     |      |     |
Due to symmetry:
|     |     | y 15mm |     |     |     |     |     |     | Ans. |     |
| --- | --- | ------ | --- | --- | --- | --- | --- | --- | ---- | --- |
= -
|     |     | ©zm | 1.8221(10-3) |     |           |     |        |     |      |     |
| --- | --- | --- | ------------ | --- | --------- | --- | ------ | --- | ---- | --- |
|     |     | z = | =            |     | = 0.1115m | =   | 111 mm |     | Ans. |     |
|     |     | ©m  | 16.347(10-3) |     |           |     |        |     |      |     |
Ans:
Σm = 16.4 kg
x = 153 mm
y = -15 mm
z = 111 mm
966

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–87.
| The  | assembly  | is  made  | from  | a  steel  | hemisphere, |     |
| ---- | --------- | --------- | ----- | --------- | ----------- | --- |
z
| r    | Mg>m3, |            |          |            |                 |       |
| ---- | ------ | ---------- | -------- | ---------- | --------------- | ----- |
| st = | 7.80   |            | and  an  | aluminum   | cylinder,       |       |
| r    | Mg>m3. |            |          |            |                 | 80 mm |
| =    | 2.70   | Determine  |          | the  mass  | center  of  the |       |
al
| assembly if the height of the cylinder is h |     |     |     | =   | 200mm. |     |
| ------------------------------------------- | --- | --- | --- | --- | ------ | --- |
G h
_
z
160mm
y
SOLUTION x
|     | C       |            | DA2Bp(0.160)3(7.80) |     | A 0.2Bp(0.2)(0.08)2(2.70) |     |
| --- | ------- | ---------- | ------------------- | --- | ------------------------- | --- |
| ©zm | = 0.160 | - 3(0.160) |                     |     | + 0.160 +                 |     |
|     |         | 8          | 3                   |     | 2                         |     |
#
|     | = 9.51425(10-3)Mg |     | m   |     |     |     |
| --- | ----------------- | --- | --- | --- | --- | --- |
A2Bp(0.160)3(7.80)
| ©m  | =   |     | + p(0.2)(0.08)2(2.70) |     |     |     |
| --- | --- | --- | --------------------- | --- | --- | --- |
3
= 77.7706(10-3)Mg
|     | ©zm | 9.51425(10-3)   |        |        |     |      |
| --- | --- | --------------- | ------ | ------ | --- | ---- |
| z   |     |                 | 0.122m | 122 mm |     | Ans. |
| =   |     | = 77.7706(10-3) | =      | =      |     |      |
©m
Ans:
z = 122 mm
967

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–88.
| The  | assembly                          |            | is  made  from   | a  steel  | hemisphere,     |       | z   |
| ---- | --------------------------------- | ---------- | ---------------- | --------- | --------------- | ----- | --- |
| r    |                                   | Mg>m3,     |                  |           |                 |       |     |
| st   | = 7.80                            |            | and  an          | aluminum  | cylinder,       |       |     |
| r    | 2.70 Mg>m3.Determine the height h |            |                  |           |                 | 80 mm |     |
| al   | =                                 |            |                  |           | of the cylinder |       |     |
| so   | that                              | the  mass  | center  of  the  | assembly  | is  located  at |       |     |
z = 160 mm.
G h
z _
160 mm
y
SOLUTION
x
|     | zm                   | C           | 3(0.160) DA2Bp(0.160)3(7.80) |     | A hBp(h)(0.08)2(2.70) |     |     |
| --- | -------------------- | ----------- | ---------------------------- | --- | --------------------- | --- | --- |
| ©   | =                    | 0.160 -     |                              |     | + 0.160 +             |     |     |
|     |                      |             | 8 3                          |     | 2                     |     |     |
|     |                      | 6.691(10-3) | 8.686(10-3)h                 |     | 27.143(10-3)h2        |     |     |
|     | =                    |             | +                            | +   |                       |     |     |
|     | m A2Bp(0.160)3(7.80) |             | p(h)(0.08)2(2.70)            |     |                       |     |     |
| ©   | =                    |             | +                            |     |                       |     |     |
3
|     | 66.91(10-3) |           | 54.29(10-3)h  |            |                |     |     |
| --- | ----------- | --------- | ------------- | ---------- | -------------- | --- | --- |
|     | =           |           | +             |            |                |     |     |
|     | z m         | 6.691(10- | 3             | 0- 3 h     | 3(10-3)h2      |     |     |
|     | ©           |           | ) + 8 . 68    | 6 (1 )     | + 27 . 1 4     |     |     |
| z   | =           | =         |               |            | = 0.160        |     |     |
|     | m           |           | 6 6 .9 1( 1 0 | - 3) 5 4 . | 29 (10 - 3 ) h |     |     |
|     | ©           |           |               | +          |                |     |     |
Solving
h
|     |     |     | = 0.385m | =   | 385mm | Ans. |     |
| --- | --- | --- | -------- | --- | ----- | ---- | --- |
Ans:
h = 385 mm
968

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
| 9–89. |     |     |     |     |     |     |     |     | z   |
| ----- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
Locate the center of mass of the block.Materials 1,2,and 3
have densities of 2.70 Mg>m3,5.70 Mg>m3,and 7.80 Mg>m3,
20 mm
respectively.
30 mm
1
40 mm
2
3 y
SOLUTION
60 mm
20 mm
60 mm
Centroid:We have
x
1
| '        | 0.01c2700a |  (0.03)(0.06)(0.02)bd |     | +    | C A                   | BD + C | A                     |     | BD  |
| -------- | ---------- | --------------------- | --- | ---- | --------------------- | ------ | --------------------- | --- | --- |
|          |            |                       |     | 0.01 | 5700 0.04(0.06)(0.02) | 0.03   | 7800 0.06(0.06)(0.02) |     |     |
| gxm      |            | 2                     |     |      |                       |        |                       |     |     |
|  x =   = |            |                       |     |      |                       |        |                       |     |     |
gm
|     |     |       | 1                    |     | A                     | B A                     |     | B   |     |
| --- | --- | ----- | -------------------- | --- | --------------------- | ----------------------- | --- | --- | --- |
|     |     | 2700a |  (0.03)(0.06)(0.02)b | +   | 5700 0.04(0.06)(0.02) | + 7800 0.06(0.06)(0.02) |     |     |     |
2
| 20.07(10 | -3)       |     |         |     |     |      |     |     |     |
| -------- | --------- | --- | ------- | --- | --- | ---- | --- | --- | --- |
|  =       | =         |     | =       |     |     |      |     |     |     |
|          | 0.02271 m |     | 22.7 mm |     |     | Ans. |     |     |     |
0.8838
|     |     | 1   |     |     | C A | BD C | A   |     | BD  |
| --- | --- | --- | --- | --- | --- | ---- | --- | --- | --- |
' 0.02c2700a  (0.03)(0.06)(0.02)bd + 0.03 5700 0.04(0.06)(0.02) + 0.03 7800 0.06(0.06)(0.02)
| gy m |     | 2   |     |     |     |     |     |     |     |
| ---- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| = =  |     |     |     |     |     |     |     |     |     |
 y
| gm  |     |       | 1                    |     |                         |                             |     |     |     |
| --- | --- | ----- | -------------------- | --- | ----------------------- | --------------------------- | --- | --- | --- |
|     |     | 2700a |  (0.03)(0.06)(0.02)b | +   | 5700 A 0.04(0.06)(0.02) | B + 7800 A 0.06(0.06)(0.02) |     | B   |     |
2
-3)
26.028(10
|  =  | =   | 0.02945 m | = 29.5 mm |     |     | Ans. |     |     |     |
| --- | --- | --------- | --------- | --- | --- | ---- | --- | --- | --- |
0.8838
1
| '      | 0.07c2700a |  (0.03)(0.06)(0.02)bd |     | +    | C A                   | BD + C | A                     |     | BD  |
| ------ | ---------- | --------------------- | --- | ---- | --------------------- | ------ | --------------------- | --- | --- |
|        |            |                       |     | 0.04 | 5700 0.04(0.06)(0.02) | 0.01   | 7800 0.06(0.06)(0.02) |     |     |
| gz m   |            | 2                     |     |      |                       |        |                       |     |     |
|  z = = |            |                       |     |      |                       |        |                       |     |     |
gm
|     |     | 2700a | 1  (0.03)(0.06)(0.02)b | +   | A                     | B + A                 |     | B   |     |
| --- | --- | ----- | ---------------------- | --- | --------------------- | --------------------- | --- | --- | --- |
|     |     |       |                        |     | 5700 0.04(0.06)(0.02) | 7800 0.06(0.06)(0.02) |     |     |     |
2
| 19.962(10 | -3) |           |         |     |     |      |     |     |     |
| --------- | --- | --------- | ------- | --- | --- | ---- | --- | --- | --- |
|  =        | =   |           | =       |     |     |      |     |     |     |
|           |     | 0.02259 m | 22.6 mm |     |     | Ans. |     |     |     |
0.8838
Ans:
x = 22.7 mm
y 29.5 mm
=
z = 22.6 mm
969

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–90. z
Determine the outside surface area of the hopper.
1.5 m
4 m
1.2 m
SOLUTION
0.2 m
| Surface     | Area:     | Applying                       | Theorem  | of  Pappus  | and             | Guldinus, |     | Eq. 9–9, with  |
| ----------- | --------- | ------------------------------ | -------- | ----------- | --------------- | --------- | --- | -------------- |
| u = 2p rad, |           | =                              | =        | 21.22 +     | 1.32 = 23.13 m, |           |     | =              |
|             |           | L 1 4m,                        | L 2      |             |                 |           | N 1 | 1.5 m and      |
|             | 0.2 + 1.5 |                                |          |             |                 |           |     |                |
| N =         |           | = 0.85 mas indicated in Fig.a, |          |             |                 |           |     |                |
2
2
|     | A   | = u©NL | = 2p[1.5(4) | + 0.8523.13] |     |     |     |     |
| --- | --- | ------ | ----------- | ------------ | --- | --- | --- | --- |

|     |     | =        | =       |     |     |     |     |      |
| --- | --- | -------- | ------- | --- | --- | --- | --- | ---- |
|     |     | 47.15 m2 | 47.1 m2 |     |     |     |     | Ans. |
Ans:
47.1 m2
A =
970

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–91. z
The hopper is filled to its top with coal. Determine the
volume of coal if the voids (air space) are 30 percent of the 1.5 m
volume of the hopper.
4 m
1.2 m
SOLUTION 0.2 m
V = © u~rA = 2p[(0.75)(1.5)(4) + (0.1)(.2)(1.2) + (0.6333)a
1
b(1.3)(1.2)](0.70)
2
V = 22.1 m3 Ans.
Ans:
V = 22.1 m3
971

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–92.
Aring is generated by rotating the quartercircular area about
the xaxis.Determine its volume.
a
SOLUTION
2a
| Volume: | Applying the theorem of Pappus and Guldinus, |     |     | Eq. 9.8 , with u | 2p, |     |
| ------- | -------------------------------------------- | --- | --- | ---------------- | --- | --- |
=
|     | 6p  |     | p   |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
4a + 4
| r = 2a + | =     | aand A | = a2,we have |      |      |     |
| -------- | ----- | ------ | ------------ | ---- | ---- | --- |
|          | 3p 3p |        | 4            |      |      |     |
|          | 6p    | + 4 p  | p(6p         | + 4) |      |     |
| V urA    | 2p    | a      | a2           | a3   | Ans. |     |
| =        | = 3p  |        | =            |      |      |     |
|          |       | 4      | 6            |      |      | x   |
Ans:
p(6p + 4)
V a3
=
6
972

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–93.
A ring is generated by rotating the quartercircular area
about the xaxis.Determine its surface area.
a
SOLUTION
2a
Surface Area:Applying the theorem of Pappus and Guldinus,Eq.9.9,with u 2p,
=
2(p
|         |     | pa      |        | + 1) |        | 5         |     |
| ------- | --- | ------- | ------ | ---- | ------ | --------- | --- |
| L L     | a,L | ,r      | 2a,r   |      | aand r | a,we have |     |
| 1 = 3 = | 2 = | 1 =     | 2 =    | p    |        | 3 =       |     |
|         |     | 2       |        |      |        | 2         |     |
|         |     |         | 2(p 1) | pa   |        |           |     |
| u       | 2p  |         | +      | a    | b 5    |           |     |
| A = ©rL | =   | 2a(a) + |        | a    | + a(a) |           | x   |
|         |     |         | p      | 2    | 2      |           |     |
= p(2p + 11)a2 Ans.
Ans:
A = p(2p 11)a2
+
973

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
| 9–94. The water tank AB           | has a hemispherical top and is |                      |     |     |     |     |
| --------------------------------- | ------------------------------ | -------------------- | --- | --- | --- | --- |
| fabricated from thin steel plate. |                                | Determine the volume |     |     |     | B   |
within the tank.
1.6 m
1.5 m
1.6 m
A
0.2 m
Solution
Volume: The perpendicular distance measured from the z axis to the centroid of each area seg-
ment is indicated in Fig. a.
|           | 4(1.6)   | p(1.62)       | 1                 |               |      |     |
| --------- | -------- | ------------- | ----------------- | ------------- | ---- | --- |
| V 2pΣrA   | 2p       | 0.8(1.6)(1.5) | 0.6667 (1.4)(1.6) | 0.1(0.2)(1.6) |      |     |
| =         | =        | +             | +                 | +             |      |     |
|           | 3p       | 4             | 2                 |               |      |     |
|           | ca ba    | b             | a b               |               | d    |     |
| 2p(4.064) | 25.5 m3  |               |                   |               | Ans. |     |
| =         | =        |               |                   |               |      |     |
Ans:
25.5 m2
V =
974

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–95.The water tank AB has a hemispherical roof and is
fabricated from thin steel plate.If a liter of paint can cover B
3 m2 of the tank’s surface,determine how many liters are
required to coat the surface of the tank from Ato B. 1.6 m
1.5 m
1.6 m
A
0.2 m
Solution
Surface Area: The perpendicular distance measured from the z axis to the centroid
of each line segment is indicated in Fig. a.
|           | 2 1.6 p | 1.6       |         |      |
| --------- | ------- | --------- | ------- | ---- |
|           |         |           | 1.42    | 1.62 |
| A = 2pΣrL | = 2p    | + 1.6 1.5 | + 0.9 + |      |
p 2
|             | 1 2            | 1 2 | 2   |     |
| ----------- | -------------- | --- | --- | --- |
|             | ca 43.18 m2 ba | b 1 | 2 1 | 2 d |
| = 2p 6.8734 | =              |     |     |     |
| 1           | 2              |     |     |     |
Thus, the amount of paint required is
43.18
| Number of liters  | =   = 14.4 liters  |     |     | Ans. |
| ----------------- | ------------------ | --- | --- | ---- |
3
Ans:
Number of liters = 14.4 liters
975

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–96. A
The rim of a flywheel has the cross section A–A shown. A
Determine the volume of material needed for its construction.
60mm
300mm
20mm
40mm
20mm
SOLUTION SectionA–A
'
V = ©urA = 2p(350)(60)(20) + 2p(320)(40)(20)
V = 4.25(106)mm3 Ans.
Ans:
V = 4.25(106)mm3
976

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–97. 3 m 3 m
| The            | process  tank                            | is  used  | to  | store  | liquids  during |     |     |
| -------------- | ---------------------------------------- | --------- | --- | ------ | --------------- | --- | --- |
| manufacturing. | Estimate the outside surface area of the |           |     |        |                 |     |     |
tank.The tank has a flat top and the plates from which the
tank is made have negligible thickness. 6 m
4 m
SOLUTION
| Surface Area: | Applying Theorem of Pappus and Guldinus, |       |     |            |           | Eq. 9–9 with u | = 2p,   |
| ------------- | ---------------------------------------- | ----- | --- | ---------- | --------- | -------------- | ------- |
| L =           | 3 m,L = 6 m,L                            | = 232 | +   | 42 = 5 m,N | = 1.5 m,N | = 3 mand N     | = 1.5 m |
| 1             | 2                                        | 3     |     |            | 1         | 2              | 3       |
as indicated in Fig.a,
|     | A = u©NL | = 2p[1.5(3) |     | + 3(6) | + 1.5(5)] |     |     |
| --- | -------- | ----------- | --- | ------ | --------- | --- | --- |

|     |     | =         |     | =      |     |     |      |
| --- | --- | --------- | --- | ------ | --- | --- | ---- |
|     |     | 188.49 m2 |     | 188 m2 |     |     | Ans. |
Ans:
188 m2
A =
977

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–98. 3m 3m
| The  process  | tank  is  used  | to  store  liquids  | during |
| ------------- | --------------- | ------------------- | ------ |
manufacturing.Estimate the volume of the tank. The tank
has a flat top and the plates from which the tank is made
have negligible thickness. 6m
4m
SOLUTION
1
| = ©u~rA | = 2pB1 a b | + 1.5(3)(6)R |     |
| ------- | ---------- | ------------ | --- |
| V       | (3)(4)     |              |     |
2
| = 207.3m3 | = 207 m3 |     |     |
| --------- | -------- | --- | --- |
V Ans.
Ans:
V 207 m
=
978

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–99.
A ring is formed by rotating the area 360° about the x – x
axes. Determine its surface area.
80 mm
50 mm
30 mm 30 mm
100 mm
x x
Solution
| Surface Area. Referring to Fig. a, L |           |          | = 110 mm, L  |      | = 302 +                         | 802 = | 7300 mm  |
| ------------------------------------ | --------- | -------- | ------------ | ---- | ------------------------------- | ----- | -------- |
|                                      |           |          | 1            | 2    |                                 |       |          |
| L 50 mm, r                           | 100 mm, r |          | 140 mm and r |      | 180 2mm. Applying th2e theorem  |       |          |
| 3 =                                  | 1 =       | 2 =      |              | 3 =  |                                 |       |          |
| of Pappus and guldinus, with u       |           | =        | 2p rad,      |      |                                 |       |          |
|                                      | A = uΣrL  |          |              |      |                                 |       |          |
|                                      | 2p        | 100(110) | 2 (140)(     | 7300 | 180 (50)                        |       |          |
|                                      | =         |          | +            |      | +                               |       |          |
1
2753.98(103) mm2
|     | =   |     |     |     | 2   | 4   |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
276(103) mm2
|     | =   |     |     |     |     |     | Ans. |
| --- | --- | --- | --- | --- | --- | --- | ---- |
Ans:
A = 276(103) mm2
979

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–100.
A ring is formed by rotating the area 360° about the x – x
axes. Determine its volume.
80 mm
50 mm
30 mm 30 mm
100 mm
x x
Solution
1
| Volume. Referring to Fig. a, A | 1=  (60)(80)=2400 mm2, A                                  | = 50(80) =4000 mm2,   |     |
| ------------------------------ | --------------------------------------------------------- | --------------------- | --- |
|                                | 2                                                         | 2                     |     |
| r   = 126.67 mm and r          |   = 140 mm. Applying the theorem of Pappus and guldinus,  |                       |     |
| 1                              | 2                                                         |                       |     |
with u = 2p rad,
|     | V uΣrA |     |     |
| --- | ------ | --- | --- |
=
|     | = 2p 126.67(2400) + 140(4000) |     |     |
| --- | ----------------------------- | --- | --- |
5.4239(106) mm3
|     | =   | 4   |     |
| --- | --- | --- | --- |
5.43(106) mm3
|     | =   |     | Ans. |
| --- | --- | --- | ---- |
Ans:
5.43(106) mm3
V =
980

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–101.
Determine the volume of concrete needed to construct
the curb.
100 mm
150 mm
30(cid:31) 4 m
150 mm
150 mm
Solution
|             | p                     | p 1               |     |
| ----------- | --------------------- | ----------------- | --- |
|  V = Σu A r | = [(0.15)(0.3)(4.15)] | (0.15)(0.1)(4.25) |     |
+
|               | 6   | 6 2     |        |
| ------------- | --- | ------- | ------ |
|               | a b | a bca b | d      |
|  V = 0.114 m3 |     |         |   Ans. |
Ans:
V = 0.114 m3
981

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–102.
Determine the surface area of the curb. Do not include the
area of the ends in the calculation.
100 mm
150 mm
30(cid:31) 4 m
150 mm
150 mm
Solution
p
A = Σ u r L = {4(0.15) + 4.075(0.15) + (4.15 + 0.075)( 0.152 + 0.12)
6
2
+ 4.3(0.25) + 4.15(0.3)}
A = 2.25 m2 Ans.
Ans:
A = 2.25 m2
982

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–103.
Determine the surface area and the volume of the ring
b
formed by rotating the square about the vertical axis.
a
45
a
SOLUTION
|            |           | a              |           | a              |     |
| ---------- | --------- | -------------- | --------- | -------------- | --- |
| A = © u~rL | = 2c2p ab | - sin 45°b(a)d | + 2c2p ab | + sin 45°b(a)d |     |
|            |           | 2              |           | 2              |     |
|            | a2        | a2             |           |                |     |
4p
| = cba  | - sin 45° | + ba + | sin 45°d |     |      |
| ------ | --------- | ------ | -------- | --- | ---- |
|        | 2         | 2      |          |     |      |
| = 8pba |           |        |          |     | Ans. |
Also
| A = © urL | = 2p(b)(4a) | = 8pba |     |     |      |
| --------- | ----------- | ------ | --- | --- | ---- |
| u~rA      | 2p(b)(a)2   | 2pba2  |     |     | Ans. |
| V = ©     | =           | =      |     |     |      |
Ans:
A = 8pba
V = 2pba2
983

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
| *9–104.                                                   |              |     |                          |       |            |           |     |     | y   |
| --------------------------------------------------------- | ------------ | --- | ------------------------ | ----- | ---------- | --------- | --- | --- | --- |
| Using                                                     | integration, |     | determine                | both  | the  area  | and       | the |     | 2m  |
| centroidal distance x                                     |              |     | of the shaded area.Then, |       |            | using the |     |     |     |
| second                                                    | theorem      |     | of  Pappus–Guldinus,     |       | determine  |           | the |     |     |
| volume of the solid generated by revolving the area about |              |     |                          |       |            |           |     |     | C   |
the yaxis.
2m
y2=2x
x
_
x
SOLUTION
|     |     | '   | x   |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
x =
2
'
=
|     |     | y   | y   |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
=
|     |     | dA  | xdy   |     |           |       |        |      |     |
| --- | --- | --- | ----- | --- | --------- | ----- | ------ | ---- | --- |
|     |     |     |       | 2y2 | y3        | 2     |        |      |     |
|     |     | =   | =     |     | = c       | d =   | =      |      |     |
|     |     | A   | dA    | dy  |           | 1.333 | 1.33m2 | Ans. |     |
|     |     |     | L L   | 2   | 6         |       |        |      |     |
|     |     |     |       | 0   |           | 0     |        |      |     |
|     | '   |     | 2y4   | y5  | 2         |       |        |      |     |
|     | xdA | =   | dy    | = c | d = 0.8m3 |       |        |      |     |
|     | L   |     | L 0 8 | 40  | 0         |       |        |      |     |
'
xdA
|     |     | '   | L   | 0.8 |         |     |     |      |     |
| --- | --- | --- | --- | --- | ------- | --- | --- | ---- | --- |
|     |     | x = | =   |     | = 0.6 m |     |     | Ans. |     |
1.333
dA
L
Thus,
'
|     |     |     | = urA = | 2p  |       | = 5.03m3 |     |      |     |
| --- | --- | --- | ------- | --- | ----- | -------- | --- | ---- | --- |
|     |     | V   |         | 0.6 | 1.333 |          |     | Ans. |     |
Ans:
= 5.03m3
V
984

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–105.
y
D e t e rm in e  t h e   v o lu m e   o f   a n  e l l ip s o i d   f o r m e d   b y  r e v o lv i n g 2 y 2
– x – (cid:2)  –   –    (cid:3) 1
th e   sh ad ed   a r e a   ab o ut   t h e   x a x i s  u s i n g   t h e  s e c o n d   th e o r e m a 2   b 2
of Pappus–Guldinus.The area and centroid yof the shaded
area should first be obtained by using integration.
b
x
SOLUTION
a
Area and Centroid:The differential element parallel to the xaxis is shown shaded
in Fig.a.The area of this element is given by
a
| dA = xdy | = 2b2 | - y2 dy |     |     |
| -------- | ----- | ------- | --- | --- |
b
Integrating,
|        |     | ba          | pab |     |
| ------ | --- | ----------- | --- | --- |
| A = dA | =   | 2b2 - y2 dy | =   |     |
|        |     | b           | 4   |     |
| L A    | L 0 |             |     |     |
'
=
The centroid ycan be obtained by applying Eq.9–4 with y y.
| '   |     | b a      |        |     |
| --- | --- | -------- | ------ | --- |
| ydA |     | yc 2b2 - | y2 dyd |     |
| L A | L   | 0 b      | 4b     |     |
| y = | =   |          | =      |     |
|     |     | pab      | 3p     |     |
dA
| L   |     | 4   |     |     |
| --- | --- | --- | --- | --- |
A
Volume:Applying the second theorem of Pappus–Guldinus and using the results
obtained above,we have
|        |       | 4b pab | 2        |      |
| ------ | ----- | ------ | -------- | ---- |
| = 2pyA | = 2pa | ba     | b = pab2 |      |
| V      |       | 3p     |          | Ans. |
|        |       | 4      | 3        |      |
Ans:
2
V  pab2
=
3
985

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–106.
The heat exchanger radiates thermal energy at the rate of
0.5m
| 2500       | kJ h | for  each  | square  | meter  of  | its  surface  area. |     |     |
| ---------- | ---- | ---------- | ------- | ---------- | ------------------- | --- | --- |
| Determine  |      | how  many  | joules  | (J)  are   | radiated  within  a |     |     |
5-hour period.
0.75m
0.75m 1.5m
0.75m
SOLUTION
|     |     |      | 0.75 | 0.5         |                 |            | 1m  |
| --- | --- | ---- | ---- | ----------- | --------------- | ---------- | --- |
|     | urL | (2p) | 2a   | + b2(0.75)2 | (0.25)2         |            |     |
| A   | = © | =    |      |             | + + (0.75)(1.5) | + (0.5)(1) |     |
|     |     |      | B    | 2           |                 | R          |     |
16.419m2
=
|     | A 103Ba |     | J bA 16.416m2B |       |         |      | 0.5m |
| --- | ------- | --- | -------------- | ----- | ------- | ---- | ---- |
| Q   | = 2500  |     |                | (5 h) | = 205MJ | Ans. |      |
|     |         | h   | # m2           |       |         |      |      |
Ans:
Q = 205 MJ
986

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–107.
Determine the height h to which liquid should be poured
into the cup so that it contacts three-fourths the surface
40 mm
area on the inside of the cup. Neglect the cup’s thickness for
the calculation.
160 mm
h
Solution
Surface Area. From the geometry shown in Fig. a,
|     |     |     | r 40  | 1         |     |     |     |
| --- | --- | --- | ----- | --------- | --- | --- | --- |
|     |     |     | =     | ;  r =  h |     |     |     |
|     |     |     | h 160 | 4         |     |     |     |
|     | 1   |     | 1 2   | 17        |     |     |     |
Thus, r =  h and L = h + h2  =  h, Fig. b. Applying the theorem of Pappus and
|                      | 8   |               | 4      | 24     |      |     |     |
| -------------------- | --- | ------------- | ------ | ------ | ---- | --- | --- |
| guldinus, with u     |     | 2p raAd ,     |        |        |      |     |     |
|                      |     | = a           | b      |        |      |     |     |
|                      |     |               |        | 1      | 17 p | 17  |     |
|                      |     | A             | u Σr L | 2p   h |  h   |  h2 |     |
|                      |     | =             | =      |        | =    |     |     |
|                      |     |               |        | 8      | 24   | 216 |     |
|                      |     |               |        | a ba   | b    |     |     |
| For the whole cup, h |     | 160 mm.  Thus |        |        |      |     |     |
=
p 17
|     |     |     |     | 1602 | 1600p 17 mm2 |     |     |
| --- | --- | --- | --- | ---- | ------------ | --- | --- |
|     |     | A   | o = |      | =            |     |     |
216
2
a b
|                       |     | 3     | 3     | 1 2  |                    |     |     |
| --------------------- | --- | ----- | ----- | ---- | ------------------ | --- | --- |
|                       |     |       | 1600p |      | 1200p 17 mm2. Thus |     |     |
| It is required that A |     | =   A | o =   | 17 = |                    |     |     |
|                       |     | 4     | 4     |      |                    |     |     |
|                       |     |       |       | 2    | 2                  |     |     |
|                       |     |       | 1     | 2    |                    |     |     |
|                       |     |       |       |      | p 17               |     |     |
|                       |     |       | 1200p | 17 = |  h2                |     |     |
216
2
|     |     |     | h = | 138.56 mm = | 139 mm  |     | Ans. |
| --- | --- | --- | --- | ----------- | ------- | --- | ---- |
Ans:
h = 139 mm
987

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–108.
Determine the interior surface area of the brake piston.It
consists of a full circular part.Its cross section is shown in
| the figure. |     |     |     | 40mm |
| ----------- | --- | --- | --- | ---- |
60mm
80mm
| SOLUTION          |                    |                  |          | 20mm |
| ----------------- | ------------------ | ---------------- | -------- | ---- |
| A © urL 2p[20(40) |                    |                  |          |      |
| = =               | + 552(30)2         | + (80)2 + 80(20) |          |      |
|                   | + 90(60) + 100(20) | + 110(40)]       | 40mm30mm | 20mm |
A
= 119(103)mm2 Ans.
Ans:
A 119(103)mm2
=
988

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–109.
Determine the height hto which liquid should be poured into
the cup so that it contacts half the surface area on the inside
30mm
ofthe cup.Neglect the cup’s thickness for the calculation.
50mm
h
SOLUTION
10mm
uz~rL
| A = | = 2p{202(20)2     | + (50)2 + 5(10)} |     |
| --- | ----------------- | ---------------- | --- |
|     | = 2p(1127.03) mm2 |                  |     |
20h 2h
|     | x = = |     |     |
| --- | ----- | --- | --- |
50 5
|     |                   | h 2h 2    | 1                 |
| --- | ----------------- | --------- | ----------------- |
|     | 2pb5(10)          |           | h2r (2p)(1127.03) |
|     | + a10             | + b a b + | =                 |
|     |                   | 5 B 5     | 2                 |
|     | 10.77h + 0.2154h2 | = 513.5   |                   |
| h   | = 29.9mm          |           | Ans.              |
Ans:
h = 29.9 mm
989

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–110.  Determine the volume of material needed to make
the casting.
20 mm
|     |     |     |     | 60 mm |     |     |     |     | 60 mm 40 mm |
| --- | --- | --- | --- | ----- | --- | --- | --- | --- | ----------- |
Solution
| Given: |     |     |     |     | Side View |     |     |     | Front View |
| ------ | --- | --- | --- | --- | --------- | --- | --- | --- | ---------- |
r 1 = 40 mm
r 2 = 60 mm
| r 3 | = r 2 - r | 1         |       |           |       |     |      |     |      |
| --- | --------- | --------- | ----- | --------- | ----- | --- | ---- | --- | ---- |
|     |           |           | 4 # r |           | r     |     |      | 4   | # r  |
|     | # #       | # p       | # # 2 | # # #     | # 2   | # p | # #  |     | 3    |
| V   | = 2 p     | 2         | r2 #  | + 2 r 2 r |       | - 2 | r2 r | -   | #    |
|     |           | 4         | 2 3 p | 2 3       | 2     | 2   | 3    | 2 3 | p    |
|     | c         | a b       | a     | b 1       | 2 a b | a   | b a  |     | bd   |
| V   | = 1.403   | 106  mm3  |       |           |       |     |      |     | Ans. |
1 2
Ans:
1.403 (106) mm3
V =
990

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–111.
y
The water tank has a paraboloid-shaped roof.If one liter of
paint can cover 3 m2of the tank,determine the number of
liters required to coat the roof.
1
y (cid:31)  –   –  (144 (cid:29) x2)
96
x
2.5 m
  12 m
SOLUTION
| Length and Centroid: |     | The length of the differential element shown shaded in |     |     |     |     |     |     |
| -------------------- | --- | ------------------------------------------------------ | --- | --- | --- | --- | --- | --- |
Fig.ais
dy 2
| dL     | = 2dx2   | +   | dy2 = | 1 + a | b dx |     |     |     |
| ------ | -------- | --- | ----- | ----- | ---- | --- | --- | --- |
|        |          |     | A     | dx    |      |     |     |     |
| dy     | 1        |     |       |       |      |     |     |     |
| where  | x. Thus, |     |       |       |      |     |     |     |
= - 48
dx
|     |     |            | 1 2   |     | x2  | 1           |         |     |
| --- | --- | ---------- | ----- | --- | --- | ----------- | ------- | --- |
| dL  | =   | 1 + a - 48 | xb dx | =   | 1 + |   dx = 2482 | + x2 dx |     |
|     | B   |            |       | B   | 482 | 48          |         |     |
Integrating,
12 m 1
|     |      |     | 2482 |     | x2 dx |            |     |     |
| --- | ---- | --- | ---- | --- | ----- | ---------- | --- | --- |
| L   | = dL | =   |      | +   |       | = 12.124 m |     |     |
48
LL L0
| The centroid xof the line can be obtained by applying Eq.9–5 with x |     |     |     |     |     |     | x.  |     |
| ------------------------------------------------------------------- | --- | --- | --- | --- | --- | --- | --- | --- |
c =
12 m
1
|     | x~ dL |     | xc  | 2482 | + x2 dxd |     |     |     |
| --- | ----- | --- | --- | ---- | -------- | --- | --- | --- |
48
|     | LL  |     | L0  |        |     | 73.114 |           |     |
| --- | --- | --- | --- | ------ | --- | ------ | --------- | --- |
| x   | =   | =   |     |        |     | =      | = 6.031 m |     |
|     |     |     |     | 12.124 |     | 12.124 |           |     |
dL
LL
Surface Area: Applying the first theorem of Pappus and Guldinus and using the
| results obtained above with r |        |                     | x   | 6.031 m, we have |             |     |     |     |
| ----------------------------- | ------ | ------------------- | --- | ---------------- | ----------- | --- | --- | --- |
|                               |        |                     | = = |                  |             |     |     |     |
| A                             | = 2prL | = 2p(6.031)(12.124) |     |                  | = 459.39 m2 |     |     |     |
Thus,the amount of paint required is
459.39
| Number of liters = |     |     | = 153 liters |     |     |     |     | Ans. |
| ------------------ | --- | --- | ------------ | --- | --- | --- | --- | ---- |
3
Ans:
153 liters
991

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–112.
Half the cross section of the steel housing is shown in the 20mm
30mm
figure.There are six 10-mm-diameter bolt holes around its 40mm
rim.Determine its mass.The density of steel is 7.85 Mg m3.
The housing is a full circular part.
10mm
30 mm
10mm
10 mm
10mm
SOLUTION
V = 2p[(40)(40)(10) + (55)(30)(10) + (75)(30)(10)] - 6 Cp(5)2(10) D = 340.9 A 103B mm3
kg
m = rV = a7850 b(340.9) A 103B A 10-9B m3
m3
= 2.68kg Ans.
Ans:
m = 2.68 kg
992

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–113.
Determine the surface area of the roof of the structure if it
y
isformed by rotating the parabola about the yaxis.
y 16 (x2/16)
16m
SOLUTION x
2dx2 +dy2
Centroid: The  length  of  the  differential  element  is  dL = 16m
|     | dy  | 2   |     |     | dy x |     |
| --- | --- | --- | --- | --- | ---- | --- |
a b
| = C | 1 + | dx  | and its centroid is x | = x.Here, | = - .Evaluating the  |     |
| --- | --- | --- | --------------------- | --------- | -------------------- | --- |
| ¢   | dx  | ≤   |                       |           | dx 8                 |     |
integrals,we nave
|     |     |      | 16 m  | x2     |         |     |
| --- | --- | ---- | ----- | ------ | ------- | --- |
|     | L   | = dL | = C 1 | + dx = | 23.663m |     |
|     |     |      | ¢     | 64≤    |         |     |
|     |     | L    | L0    |        |         |     |
16m
|     |     | '   | '   | x 2          |     |     |
| --- | --- | --- | --- | ------------ | --- | --- |
|     |     | xdL | x 1 | dx 217.181m2 |     |     |
|     |     | =   | C + | =            |     |     |
|     | LL  | L0  | ¢   | 6 4 ≤        |     |     |
Applying Eq.9–5,we have
'
xdL
|     |     |     | LL 217.181 |          |     |     |
| --- | --- | --- | ---------- | -------- | --- | --- |
|     |     | x = | =          | = 9.178m |     |     |
23.663
dL
LL
| Surface Area:Applying the theorem of Pappus and Guldinus,Eq. 9–7,with u |     |     |     |     |     | 2p, |
| ----------------------------------------------------------------------- | --- | --- | --- | --- | --- | --- |
=
| L = 23.663m,r |     | = x = | 9.178 m,we have    |         |     |      |
| ------------- | --- | ----- | ------------------ | ------- | --- | ---- |
|               |     | urL   | 2p(9.178) (23.663) | 1365 m2 |     | Ans. |
|               |     | A =   | =                  | =       |     |      |
Ans:
A = 1365 m2
993

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–114.
Asteel wheel has a diameter of 840 mm and a cross section
100mm
as shown in the figure. Determine the total mass of the A 30mm 60mm
| wheel if r | 5Mg>m3. |     |     |     |
| ---------- | ------- | --- | --- | --- |
=
420mm
250mm
30mm
840mm
80mm
SOLUTION
with u 2p, A
Volume: Applying the theorem of Pappus and Guldinus, Eq. 9.10, = SectionA–A
| r = 0.095m,  | r = 0.235m,     | r = 0.39m,    | A = 0.110.032   | = 0.003m2, |
| ------------ | --------------- | ------------- | --------------- | ---------- |
| 1            | 2               | 3             | 1               |            |
| A 0.2510.032 | 0.0075m2and A   | 10.1210.062   | 0.006m2,we have |            |
| 2 =          | =               | 3 =           | =               |            |
| V u ©rA      | 2p30.09510.0032 | 0.23510.00752 | 0.3910.00624    |            |
| =            | =               | +             | +               |            |
8.775p110-32m3
=
The mass of the wheel is
|     | m = rV = | 51103238.775110-32p4 |     |      |
| --- | -------- | -------------------- | --- | ---- |
|     | =        | 138kg                |     | Ans. |
Ans:
m = 138 kg
994

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–115.
p
The loading acting on a square plate is represented by a 4kPa
| parabolic pressure distribution. |     |     |     | Determine the magnitude |     |     |
| -------------------------------- | --- | --- | --- | ----------------------- | --- | --- |
of the resultant force and the coordinates 1x,y2of the point p 2y1/2
y
where the line of action of the force intersects the plate.
Also,what are the reactions at the rollers Band Cand the
C
ball-and-socket joint A?Neglect the weight of the plate.
B
A
4m
4m 2m
x
SOLUTION
y = y
dA = pdy
| x = | 0   | (Due to symmetry) |     |           |     | Ans. |
| --- | --- | ----------------- | --- | --------- | --- | ---- |
|     |     | 4                 |     | 4 4       |     |      |
|     | =   | 2y1/2 dy          | = B | y3/2R =   |     |      |
|     | dA  |                   |     | 10.67kN/m |     |      |
| L   |     | L                 |     | 3         |     |      |
|     |     | 0                 |     | 0         |     |      |
4
|     | '     |           |     | 4 4               |     |     |
| --- | ----- | --------- | --- | ----------------- | --- | --- |
|     | ydA = | 2y 3/2 dy | =   | B y 5/2R = 25.6kN |     |     |
| L   |       | L         |     | 5                 |     |     |
|     |       | 0         |     | 0                 |     |     |
'
ydA
|     | L   | 25.6 |         |     |     |      |
| --- | --- | ---- | ------- | --- | --- | ---- |
| y = |     | =    | = 2.40m |     |     | Ans. |
10.67
dA
L
| F   | = 10.67(4) | = 42.7 kN |     |     |     | Ans. |
| --- | ---------- | --------- | --- | --- | --- | ---- |
R
| ©M  | = 0; |     | B = C       |            |     |      |
| --- | ---- | --- | ----------- | ---------- | --- | ---- |
|     | y    |     | y           | y          |     |      |
| ©M  | = 0; |     | 42.67(2.40) | - 2B (4) = | 0   |      |
|     | x    |     |             | y          |     |      |
|     |      |     | B = C       | = 12.8kN   |     | Ans. |
|     |      |     | y           | y          |     |      |
c
| +   | ©F  | = 0; | A - 42.67 | + 12.8 + 12.8 | = 0 |     |
| --- | --- | ---- | --------- | ------------- | --- | --- |
y
|     |     |     | A = 17.1kN |     |     | Ans. |
| --- | --- | --- | ---------- | --- | --- | ---- |
y
Ans:
x 0
=
y 2.40 m
=
B y = C y = 12.8 kN
A = 17.1 kN
y
995

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–116.
The load over the plate varies linearly along the sides of the
p
|                   |     |     | 2[x14                 | y2]kPa.Determine the resultant |     |     |     |     |      |
| ----------------- | --- | --- | --------------------- | ------------------------------ | --- | --- | --- | --- | ---- |
| plate such that p |     |     | =                     | -                              |     |     |     |     |      |
|                   |     |     | 3  1x,y2on the plate. |                                |     |     |     |     | 8kPa |
force and its position y
3m
4m
x
SOLUTION
| Resultant Force  |       |         | and its Location: |          | The                             | volume   | of  the  differential  | element  | is   |
| ---------------- | ----- | ------- | ----------------- | -------- | ------------------------------- | -------- | ---------------------- | -------- | ---- |
|                  |       |         | 2                 |          |                                 |          |                        | '        | '    |
| dV               | = dF  | = pdxdy | =                 | (xdx)[(4 | - y)dy]and its centroid is at x |          |                        | = xand y | = y. |
|                  |       | R       | 3                 |          |                                 |          |                        |          |      |
|                  |       |         |                   | 3m2      |                                 | 4m       |                        |          |      |
|                  | F     | dF      |                   | (xdx)    |                                 | (4       | y)dy                   |          |      |
|                  | R =   |         | R =               |          |                                 | -        |                        |          |      |
|                  |       | LFR     | L0                | 3        | L0                              |          |                        |          |      |
|                  |       |         | x2 3m             |          | y2 4m                           |          |                        |          |      |
|                  |       | 2       | a b               | a4y      | b                               |          |                        |          |      |
|                  |       | =       |                   | -        |                                 | = 24.0kN |                        |          | Ans. |
|                  |       | 3 B     | 2 2               |          | 2 2                             | R        |                        |          |      |
|                  |       |         | 0                 |          | 0                               |          |                        |          |      |
|                  |       | 3m2     |                   | 4m       |                                 |          |                        |          |      |
|                  | xdF   |         | (x2dx)            |          | (4 y)dy                         |          |                        |          |      |
|                  | R     | =       |                   |          | -                               |          |                        |          |      |
| LFR              |       | L0      | 3                 | L0       |                                 |          |                        |          |      |
|                  |       |         | x3 3m             |          | y2 4m                           |          |                        |          |      |
|                  |       | 2       |                   |          |                                 |          | #                      |          |      |
|                  |       | =       | a b               | a4y -    | b                               | = 48.0kN | m                      |          |      |
|                  |       | 3 B     | 3 2               |          | 2 2                             | R        |                        |          |      |
|                  |       |         | 0                 |          | 0                               |          |                        |          |      |
|                  |       | 3m      | 2                 | 4m       |                                 |          |                        |          |      |
|                  | ' ydF |         | (xdx)             | y(4      | y)dy                            |          |                        |          |      |
|                  | R     | =       |                   |          | -                               |          |                        |          |      |
| LFR              |       | L0      | 3                 | L0       |                                 |          |                        |          |      |
|                  |       |         | x2 3m             |          | y3 4m                           |          |                        |          |      |
|                  |       | 2       |                   |          |                                 |          | #                      |          |      |
|                  |       | =       | a b               | a2y2 -   | b                               | =        | 32.0kN m               |          |      |
|                  |       | 3 B     | 2 2               |          | 3 2                             | R        |                        |          |      |
|                  |       |         | 0                 |          | 0                               |          |                        |          |      |
' xdF
R
|     |     | LFR | 48.0 |     |        |     |     |     |      |
| --- | --- | --- | ---- | --- | ------ | --- | --- | --- | ---- |
|     | x   | =   | =    | =   | 2.00 m |     |     |     | Ans. |
24.0
|     |     |     | dF R |     |     |     |     |     |     |
| --- | --- | --- | ---- | --- | --- | --- | --- | --- | --- |
LFR
'
ydF
|     |     |     | R 32.0 |     |     |     |     |     |     |
| --- | --- | --- | ------ | --- | --- | --- | --- | --- | --- |
LFR
|     | y   | =   | =   | =   | 1.33 m |     |     |     | Ans. |
| --- | --- | --- | --- | --- | ------ | --- | --- | --- | ---- |
24.0
dF
R
LFR
Ans:
F = 24.0 kN
R
x = 2.00 m
y = 1.33 m
996

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–117.
The load over the plate varies linearly along the sides of the  p
| plate such that p |  (12 | 6x 4y) kPa. Determine the  |     |     |     |        |
| ----------------- | ---- | -------------------------- | --- | --- | --- | ------ |
|                   | = -  | +                          |     |     |     | 12 kPa |
magnitude of the resultant force and the coordinates (x, y)
18 kPa
| of the point where the line of action of the force intersects  |     |     |     | x   |     |     |
| -------------------------------------------------------------- | --- | --- | --- | --- | --- | --- |
the plate.
1.5 m 6 kPa
2 m
y
Solution
Centroid. Perform the double integration.
|     |               | 1.5 m | 2 m       |         |     |     |
| --- | ------------- | ----- | --------- | ------- | --- | --- |
|     | F = r(x, y)dA | =     | (12 -6x + | 4y)dxdy |     |     |
R
|     | LA  | L0    | L0  |     |     |     |
| --- | --- | ----- | --- | --- | --- | --- |
|     |     | 1.5 m |     | 2 m |     |     |
3x2
|     |     | =   | 12x - + 4xy | dy  |     |     |
| --- | --- | --- | ----------- | --- | --- | --- |
L0
0
`
|     |     | 1.5 m1 |              | 2   |     |     |
| --- | --- | ------ | ------------ | --- | --- | --- |
|     |     | =      | (8y  + 12)dy |     |     |     |
L0
1.5 m
(4y2
|     |     | = + | 12y) |     |     |     |
| --- | --- | --- | ---- | --- | --- | --- |
0
`
|     |     | 27.0 kN  |     |     | Ans. |     |
| --- | --- | -------- | --- | --- | ---- | --- |
=
|     |            | 1.5 m | 2 m     |           |     |     |
| --- | ---------- | ----- | ------- | --------- | --- | --- |
|     | xr(x, y)dA |       | 12x 6x2 | 4xy dx dy |     |     |
|     |            | =     | -       | +         |     |     |
|     | LA         | L0    | L0      |           |     |     |
|     |            | 1.5 m | 1       | 2         |     |     |
2 m
|     |     | =   | (6x2 - 2x3 + 2x2y) | dy  |     |     |
| --- | --- | --- | ------------------ | --- | --- | --- |
|     |     | L0  |                    | 0   |     |     |
`
1.5 m
|     |     | =   | (8y + 8)dy |     |     |     |
| --- | --- | --- | ---------- | --- | --- | --- |
L0
1.5 m
|     |     | = 4y2 + | 8y  |     |     |     |
| --- | --- | ------- | --- | --- | --- | --- |
0
|     |     | 211.0 kN | # m2 ` |     |     |     |
| --- | --- | -------- | ------ | --- | --- | --- |
=
|     |            | 1.5 m  | 2 m           |           |     |     |
| --- | ---------- | ------ | ------------- | --------- | --- | --- |
|     | yr(x, y)dA |        | 12y 6xy       | 4y2 dx dy |     |     |
|     |            | =      | -             | +         |     |     |
|     | LA         | L0     | L0            |           |     |     |
|     |            | 1.5 m  | 1             | 22 m      |     |     |
|     |            | =      | 12xy - 3x2y + | 4xy2 dy   |     |     |
|     |            | L0     |               | 0         |     |     |
|     |            | 1.5 m1 |               | 2 `       |     |     |
(8y2 12y)dy
|     |     | =   | +   |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
L0
1.5 m
8
|     |     | =  y3 + | 6y2 |     |     |     |
| --- | --- | ------- | --- | --- | --- | --- |
3
0
|     |     | a         | # b` |     |     |     |
| --- | --- | --------- | ---- | --- | --- | --- |
|     |     | = 22.5 kN | m    |     |     |     |
997

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–117. Continued
Thus,
xp(x, y)dA
|     | LA  | 21.0 kN | # m 7 |     |
| --- | --- | ------- | ----- | --- |
x
|     | =   | =       | =  m = 0.778 m  | Ans. |
| --- | --- | ------- | --------------- | ---- |
|     |     | 27.0 kN | 9               |      |
p(x, y)dA
LA
yp(x, y)dA
#
|     | LA  | 22.5 kN | m          |      |
| --- | --- | ------- | ---------- | ---- |
|     | y = | =       | = 0.833 m  | Ans. |
27.0 kN
p(x, y)dA
LA
Ans:
F = 27.0 kN
R
x = 0.778 m
y = 0.833 m
998

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–118.
A wind loading creates a positive pressure on one side of
the chimney and a negative (suction) pressure on the other
side, as shown. If this pressure loading acts uniformly along
p u
| the  chimney’s  | length,  determine  | the  magnitude  | of  the  |     |
| --------------- | ------------------- | --------------- | -------- | --- |
resultant force created by the wind.
p (cid:31) p cos u
0
Solution
l
|         | p                        | p                     |     |     |
| ------- | ------------------------ | --------------------- | --- | --- |
|  F = 2l | 2  (p  cos u) cos u r du | = 2rlp   2  cos2 u du |     |     |
| Rx      | p 0                      | 0 p                   |     |     |
|         | L- 2                     | L- 2                  |     |     |
p
|  = 2rlp | 0   |     |     | Ans. |
| ------- | --- | --- | --- | ---- |
2
a b
 F = plrp
| Rx  | 0   |     |     |     |
| --- | --- | --- | --- | --- |
p
|  F = 2l | 2 (p  cos u) sin u r du | = 0 |     |     |
| ------- | ----------------------- | --- | --- | --- |
| Ry      | p 0                     |     |     |     |
|         | L -2                    |     |     |     |
Thus,
|     |     | F = plrp   |     | Ans. |
| --- | --- | ---------- | --- | ---- |
|     |     | R 0        |     |      |
Ans:
p
F 2rlp
Rx = 0
2
F R = plrp 0 a b
999

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–119.
The rectangular plate is subjected to a distributed load over p
| its entire |              | surface. |  The load is defined by the expression |     |         |                  |     |     |     |
| ---------- | ------------ | -------- | -------------------------------------- | --- | ------- | ---------------- | --- | --- | --- |
| p          | p sin (px>a) |          | sin (py>b),                            |     | where p | represents  the  |     |     |     |
=
|                                             | 0   |     |     |     |     | 0              |     |     |     |
| ------------------------------------------- | --- | --- | --- | --- | --- | -------------- | --- | --- | --- |
| pressure acting at the center of the plate. |     |     |     |     |     | Determine the  |     |     |     |
magnitude and  location  of  the  resultant  force  acting  on
the plate. p 0
y
a
x
SOLUTION
b
| Resultant Force and its Location: |      |         |     |       | The volume of the differential element is |       |         |         |     |
| --------------------------------- | ---- | ------- | --- | ----- | ----------------------------------------- | ----- | ------- | ------- | --- |
|                                   |      |         |     |       | px                                        | py    |         |         |     |
|                                   |      |         |     | asin  | dxbasin                                   |       | dyb.    |         |     |
| dV                                | = dF | = pdxdy | = p |       |                                           |       |         |         |     |
|                                   | R    |         |     | 0     |   a                                       |   b   |         |         |     |
|                                   |      |         |     | a     | px                                        | b     | py      |         |     |
|                                   | F    | dF      |     | p     | asin                                      | dxb   | asin    | dyb     |     |
|                                   |      | R =     | R = | 0     |                                           |       |         |         |     |
|                                   |      | LFR     |     | L0    | a                                         | L0    | b       |         |     |
|                                   |      |         |     |       |                                           | px a  |         | px b    |     |
|                                   |      |         |     | a     | a                                         | b a   | b       | b       |     |
|                                   |      |         | =   | p -p  | cos                                       |       | -p cos  |         |     |
|                                   |      |         |     | 0B    |                                           |   a 2 |         |   b 2 R |     |
|                                   |      |         |     |       |                                           | 0     |         | 0       |     |
4ab
|     |     |     |     | p    |     |     |     |     | Ans. |
| --- | --- | --- | --- | ---- | --- | --- | --- | --- | ---- |
|     |     |     | =   | p2 0 |     |     |     |     |      |
Since the loading is symmetric,the location of the resultant force is at the center of
the plate.Hence,
|     |     |     |     |     | a   | b   |     |     |      |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | ---- |
|     |     |     |     | x = |     | y = |     |     | Ans. |
|     |     |     |     |     | 2   | 2   |     |     |      |
Ans:
4ab
F p
R = 0
p2
a
x =
2
b
y =
2
1000

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–120.
| The  concrete  |     | dam  | in  the  | shape  of  | a  quarter  | circle. |     |     |     |
| -------------- | --- | ---- | -------- | ---------- | ----------- | ------- | --- | --- | --- |
Determine the magnitude of the resultant hydrostatic force
that acts on the dam per meter of length.The density of
| water is r | =   | 1 Mg>m3. |     |     |     |     |     |     |     |
| ---------- | --- | -------- | --- | --- | --- | --- | --- | --- | --- |
w
3 m
SOLUTION
Loading:The hydrostatic force acting on the circular surface of the dam consists of
| the vertical component F   |     |     | and the horizontal component F |                          |     |     | as shown in Fig.a.     |     |     |
| -------------------------- | --- | --- | ------------------------------ | ------------------------ | --- | --- | ---------------------- | --- | --- |
|                            |     |     | v                              |                          |     |     | h                      |     |     |
| Resultant Force Component: |     |     |                                | The vertical component F |     |     | consists of the weight |     |     |
v
of water contained in the shaded area shown in Fig.a.For a 1-m length of dam,
wehave
p
| rgA                                           |             |                             |     |                                                    | (32)  |                                 |            |            |         |
| --------------------------------------------- | ----------- | --------------------------- | --- | -------------------------------------------------- | ----- | ------------------------------- | ---------- | ---------- | ------- |
| F =                                           | b           | = (1000)(9.81)              |     | (3)(3) -                                           | 4     | (1) =                           | 18947.20 N | = 18.95 kN |         |
| v                                             | ABC         |                             |     | B                                                  |       | R                               |            |            |         |
| The horizontal component F                    |             |                             |     | h consists of the horizontal hydrostatic pressure. |       |                                 |            |            |         |
| Since the width of the dam is constant (1 m), |             |                             |     |                                                    |       | this loading can be represented |            |            |         |
| by a                                          | triangular  | distributed                 |     | loading                                            | with  | an  intensity                   |            | of  w =    | rgh b = |
|                                               |             |                             |     |                                                    |       |                                 |            | C          | C       |
| 1000(9.81)(3)(1)                              |             | 29.43 kN>mat point C,Fig.a. |     |                                                    |       |                                 |            |            |         |
=
1
|     | F = | (29.43)(3) |     | = 44.145 kN |     |     |     |     |     |
| --- | --- | ---------- | --- | ----------- | --- | --- | --- | --- | --- |
h 2
Thus,the magnitude of the resultant hydrostatic force acting on the dam is
|     |     | 3F  | 2       | 2 344.145 | 2       | 2   |         |     |      |
| --- | --- | --- | ------- | --------- | ------- | --- | ------- | --- | ---- |
|     | F R | =   | h + F v | =         | + 18.95 | =   | 48.0 kN |     | Ans. |
|     |     |     |         |           |         |     |         |     |      |
Ans:
F = 48.0 kN
R
1001

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–121.
The concrete “gravity” dam is held in place by its own 1 m
weight. If the density of concrete is r c = 2.5 Mg m3, and
water has a density of r w = 1.0 Mg m3, determine the
smallest dimension d that will prevent the da > m from
overturning about its end A. >
6 m
A
d – 1
d
Solution
Loadings. The computation will be based on b = 1 m width of the dam. The pressure
at the base of the dam is.
P = rgh = 1000(9.81)(6) = 58.86(103) pa = 58.86 kPa
Thus
w = pb = 58.86(1) = 58.86 kN m
The forces that act on the dam and their respective points> of application, shown in
Fig. a, are
W 1 = 2500 1(6)(1) (9.81) = 147.15(103) N = 147.15 kN
31 4
W 2 = 2500 2 (d - 1)(6)(1) (9.81) = 73.575(d - 1)(103) = 73.575(d - 1) kN
c d
1
(F R ) v = 1000 2 (d - 1)(6)(1) (9.81) = 29.43(d - 1)(103) = 29.43(d - 1) kN
c d
1
(F R ) h = 2 (58.86)(6) = 176.58 kN
1 1 2 1
x 1 = 0.5 x 2 = 1 + 3 (d - 1) = 3 (d + 2) x 3 = 1 + 3 (d - 1) = 3 (2d + 1)
1
y = (6) = 2 m
3
Equation of Equilibrium. Write the moment equation of equilibrium about A by
referring to the FBD of the dam, Fig. a,
1
a+ΣM A = 0; 147.15(0.5) + [73.575(d - 1)] 3 (d + 2)
c d
1
+ [29.43(d - 1)] (2d + 1) - 176.58(2) = 0
3
c d
44.145d2 + 14.715d - 338.445 = 0
Solving and chose the positive root
d = 2.607 m = 2.61 m Ans.
Ans:
d = 2.61 m
1002

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–122.
The factor of safety for tipping of the concrete dam is defined as the  y
ratio of the stabilizing moment due to the dam’s weight divided by  1 m
the overturning moment about O due to the water pressure.
| Determine  |          | this               | factor  | if  the  | concrete  | has  | a  density  of  |     |
| ---------- | -------- | ------------------ | ------- | -------- | --------- | ---- | --------------- | --- |
| r          | = 2.5 Mg | m3 and for water r |         |          | = 1 Mg    | m3.  |                 |     |
| conc       |          |                    |         |          | w         |      |                 |     |
6 m
|     |     | >   |     |     |     | >   |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
O
x
4 m
Solution
| Loadings. The computation will be based on b |     |     |     |     |     | =   | 1m width of the dam. The pressure  |     |
| -------------------------------------------- | --- | --- | --- | --- | --- | --- | ---------------------------------- | --- |
at the base of the dam is
|     |   P = | p = 1000(9.81)(6) |     |     | = 58.86(103)p | =   | 58.86 kPa |     |
| --- | ----- | ----------------- | --- | --- | ------------- | --- | --------- | --- |
|     |       | wgh               |     |     |               | a   |           |     |
Thus,
|     |     w | = Pb = | 58.86(1) | = 58.86 kN | m   |     |     |     |
| --- | ----- | ------ | -------- | ---------- | --- | --- | --- | --- |
The forces that act on the dam and thei>r respective points of application, shown in
Fig. a, are
|     |   W | (2500)[(1)(6)(1)](9.81) |     |     | 147.15(103) N |     | 147.15 kN |     |
| --- | --- | ----------------------- | --- | --- | ------------- | --- | --------- | --- |
|     | 1 = |                         |     |     | =             |     | =         |     |
1
|     |   W | (2500) | (3)(6)(1) | (9.81) | 220.725(103) N |     | 220.725 kN |     |
| --- | --- | ------ | --------- | ------ | -------------- | --- | ---------- | --- |
|     | 2 = |        |           |        | =              |     | =          |     |
2
|     |     | c   |     | d   |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
1
|     |   F |  (58.86)(6) |     | 176.58 kN |     |     |     |     |
| --- | --- | ----------- | --- | --------- | --- | --- | --- | --- |
|     | R = |             | =   |           |     |     |     |     |
2
|     |         | 1       |          |     | 2         |       | 1               |     |
| --- | ------- | ------- | -------- | --- | --------- | ----- | --------------- | --- |
|     |   x 1 = | 3 + (1) | = 3.5 m  |     | x 2 = (3) | = 2m  |   y = (6) = 2 m |     |
|     |         | 2       |          |     | 3         |       | 3               |     |
Thus, the overturning moment about O is
#
|     |   M | = 176.58(2) | =   | 353.16 kN | m   |     |     |     |
| --- | --- | ----------- | --- | --------- | --- | --- | --- | --- |
OT
And the stabilizing moment about O is
|     |   M = | 147.15(3.5) | +   | 220.725(2) | = 956.475 kN |     | # m |     |
| --- | ----- | ----------- | --- | ---------- | ------------ | --- | --- | --- |
s
Thus, the factor of safety is
|     |     | M   | 956.475 |     |     |     |     |     |
| --- | --- | --- | ------- | --- | --- | --- | --- | --- |
s
|     |   F.S. = | =   |        | = 2.7083 | = 2.71  |     |     | Ans. |
| --- | -------- | --- | ------ | -------- | ------- | --- | --- | ---- |
|     |          | M   | 353.16 |          |         |     |     |      |
OT
Ans:
F.S. = 2.71
1003

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–123. The storage tank contains oil having a specific 10 m
A
weight of g o = 9 kN/m3. If the tank is 6 m wide, calculate
the resultant force acting on the inclined side BC of the 2 m
B
tank, caused by the oil, and specify its location along BC,
measured from B. Also compute the total resultant force
acting on the bottom of the tank. 8 m
C
4 m
D
4 m 3 m
Solution
Given:
g = 9 kN m3 c = 8 m
w = 6 m d = 4 m
>
a = 10 m e = 3 m
b = 2 m f = 4 m
# # # #
w B = w g b w B = 108 kN m w C = w g b + c w C = 540 kN m
> 1 2 >
# 1# # # # # 1# # # #
F h1 = w B c F h2 = 2 w C - w B c F v1 = g w b e F v2 = 2 g w c e
1 2
The resultant force
F Rx = F h1 + F h2 F Ry = F v1 + F v2 F R = F R 2 x + F R 2 y F R = 2.77 MN Ans.
2
The location h measured from point B. Guess h = 1 m. Given
# # # #
#e #2 e #c #2 c # c h # e h
F v1 2 + F v2 3 + F h1 2 + F h2 3 = F Rx c2 + e2 + F Ry c2 + e2
2 2
On the bottom of the tank h = Find (h) h = 5.22 m Ans.
# # #
F bot = g w f b + c + d F bot = 3.02 MN Ans.
1 2
Ans:
F R = 2.77 MN
h = 5.22 m
F bot = 3.02 MN
1004

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–124.
When the tide water Asubsides,the tide gate automatically
swings open to drain the marsh B.For the condition of high
C
tide shown,determine the horizontal reactions developed
| at the hinge C            |     | and stop block D.The length of the gate is |     |           |     |     |     |     |
| ------------------------- | --- | ------------------------------------------ | --- | --------- | --- | --- | --- | --- |
| 6mand its height is 4 m.r |     |                                            |     | 1.0Mg/m3. |     |     |     |     |
w = 4m
A
3m
B
2m
D
SOLUTION
| Fluid Pressure: |     | The fluid pressure at points D |     |     |     | and E | can be determined using  |     |
| --------------- | --- | ------------------------------ | --- | --- | --- | ----- | ------------------------ | --- |
| Eq.9–13,p       |     | rgz.                           |     |     |     |       |                          |     |
=
|     | p   | 1.01103 | 219.812122 |     | 19620 N>m2  |     | 19.62 kN>m2 |     |
| --- | --- | ------- | ---------- | --- | ----------- | --- | ----------- | --- |
|     | D   | =       |            | =   |             | =   |             |     |
|     | p   | 1.01103 | 219.812132 |     | 29 430 N>m2 |     | 29.43kN>m2  |     |
|     | E   | =       |            | =   |             | =   |             |     |
Thus,
|     |     |     | w = 19.62162 |     | = 117.72kN>m |     |     |     |
| --- | --- | --- | ------------ | --- | ------------ | --- | --- | --- |
D
|     |     |     | w = 29.43162 |     | = 176.58 kN>m |     |     |     |
| --- | --- | --- | ------------ | --- | ------------- | --- | --- | --- |
E
Resultant Forces:
1
|     |     |     | F = 1176.582132 |     | =   | 264.87 kN |     |     |
| --- | --- | --- | --------------- | --- | --- | --------- | --- | --- |
|     |     |     | R1 2            |     |     |           |     |     |
1
|     |     |     | F 1117.722122 |     |     | 117.72 kN |     |     |
| --- | --- | --- | ------------- | --- | --- | --------- | --- | --- |
|     |     |     | R2 =          |     | =   |           |     |     |
2
Equations of Equilibrium:
| a+©M | =   | 0;  | 264.87132 | - 117.7213.3332 |     | - D | x142 = 0 |     |
| ---- | --- | --- | --------- | --------------- | --- | --- | -------- | --- |
C
|     |     |     | D   | = 100.55kN |     | = 101kN |     | Ans. |
| --- | --- | --- | --- | ---------- | --- | ------- | --- | ---- |
x
| :+ ©F | = 0; |     | 264.87 | - 117.72 | - 100.55 | -   | C = 0 |      |
| ----- | ---- | --- | ------ | -------- | -------- | --- | ----- | ---- |
|       | x    |     |        |          |          |     | x     |      |
|       |      |     |        | C        | = 46.6kN |     |       | Ans. |
x
Ans:
D x = 101 kN
C = 46.6 kN
x
1005

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–125.
| The  tank  | is  filled  with  water  | to  a  depth  | of  d 4m. |     |
| ---------- | ------------------------ | ------------- | --------- | --- |
=
2m
Determine the resultant force the water exerts on side Aand 3m
side Bof the tank.If oil instead of water is placed in the tank,
| to what depth d     | should it reach so that it creates the same |     |            |     |
| ------------------- | ------------------------------------------- | --- | ---------- | --- |
| resultant forces? r | 900 kg>m3and r                              |     | 1000kg>m3. |     |
|                     | o =                                         | w = |            |     |
A B
d
SOLUTION
For water
At side A:
|     | w br gd |     |     |     |
| --- | ------- | --- | --- | --- |
|     | A = w   |     |     |     |
2(1000)(9.81) (4)
=
78480N/m
=
1
|     | F RA = (78 480)(4) | = 156960N | = 157kN | Ans. |
| --- | ------------------ | --------- | ------- | ---- |
2
At side B:
|     | w br gd |     |     |     |
| --- | ------- | --- | --- | --- |
B = w
3(1000)(9.81)(4)
=
117720N>m
=
1
|     | F RB = (117 720)(4) | = 235440N | = 235kN | Ans. |
| --- | ------------------- | --------- | ------- | ---- |
2
Foroil
At side A:
|     | w = br          | gd  |     |     |
| --- | --------------- | --- | --- | --- |
|     | A               | o   |     |     |
|     | = 2(900)(9.81)d |     |     |     |
|     | = 17658 d       |     |     |     |
1
|     | F (17 658 d)(d) |     | 156960 N |     |
| --- | --------------- | --- | -------- | --- |
|     | RA =            |     | =        |     |
2
|     | d = 4.22m |     |     | Ans. |
| --- | --------- | --- | --- | ---- |
Ans:
For water: F = 157 kN
RA
F = 235 kN
RB
For oil: d = 4.22 m
1006

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–126.
The 2-m-wide rectangular gate is pinned at its center Aand
isprevented from rotating by the block at B.Determine the
reactions at these supports due to hydrostatic pressure.
r = 1.0Mg>m3.
w
6m
1.5m
A
1.5m
B
SOLUTION
| w = 1000(9.81)(3)(2) | = 58860N/m |     |     |     |
| -------------------- | ---------- | --- | --- | --- |
1
| w = 1000(9.81)(3)(2) | = 58860N/m |     |     |     |
| -------------------- | ---------- | --- | --- | --- |
2
1
| F (3)(58 860) | 88 290N |     |     |     |
| ------------- | ------- | --- | --- | --- |
| 1 =           | =       |     |     |     |
2
F
| 2 = (58 860)(3) = | 176580N    |              |     |     |
| ----------------- | ---------- | ------------ | --- | --- |
| M                 |            | F            |     |     |
| a+© A = 0;        | 88290(0.5) | - B(1.5) = 0 |     |     |
F
|          | B = 29430N      | = 29.4 kN |         | Ans. |
| -------- | --------------- | --------- | ------- | ---- |
| :+ F     |                 |           | F       |      |
| © x = 0; | 88290 + 176 580 | - 29430   | - A = 0 |      |
F
|     | A = 235440N | = 235 kN |     | Ans. |
| --- | ----------- | -------- | --- | ---- |
Ans:
F = 29.4 kN
B
F 235 kN
A =
1007

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–127.
The tank is filled with a liquid which has a density of
y
900kg>m3.
Determine the resultant force that it exerts on
the elliptical end plate, and the location of the center of 1m
1m
pressure,measured from the xaxis.
4y2 x2 1
0.5m
x
0.5m
SOLUTION
| Fluid Pressure:            | The fluid pressure at an arbitrary point along y |         |      |                 |      | axis can be |       |
| -------------------------- | ------------------------------------------------ | ------- | ---- | --------------- | ---- | ----------- | ----- |
| determined using Eq.9–13,p |                                                  | = g(0.5 | - y) | = 900(9.81)(0.5 | - y) | = 8829(0.5  | - y). |
4y2.
| Resultant  | Force  and  | its  Location: | Here, | x = | 21 - The  | volume  | of  the |
| ---------- | ----------- | -------------- | ----- | --- | --------- | ------- | ------- |
differential element is dV = dF = p(2xdy) = 8829(0.5 - y)[221 - 4y2]dy. the
R
Evaluating integrals using Simpson’s rule,we have
0.5 m
| F = | dF = 17658 | (0.5    | - y)(21 | - 4y2)dy |     |     |      |
| --- | ---------- | ------- | ------- | -------- | --- | --- | ---- |
| R   | R          |         |         |          |     |     |      |
| LFR |            | L-0.5 m |         |          |     |     |      |
|     | 6934.2 N   | 6.93kN  |         |          |     |     | Ans. |
|     | =          | =       |         |          |     |     |      |
0.5 m
4y2)dy
| ydF | = 17658 | y(0.5 - | y)(21 | -   |     |     |     |
| --- | ------- | ------- | ----- | --- | --- | --- | --- |
R
| LFR | L-0.5m |     |     |     |     |     |     |
| --- | ------ | --- | --- | --- | --- | --- | --- |
#
|     | = -866.7N | m   |     |     |     |     |     |
| --- | --------- | --- | --- | --- | --- | --- | --- |
'
ydF
R
| LFR | -866.7 |           |     |     |     |     |      |
| --- | ------ | --------- | --- | --- | --- | --- | ---- |
| y = | =      | = -0.125m |     |     |     |     | Ans. |
6934.2
dF
R
LFR
Ans:
F = 6.93 kN
R
y = -0.125 m
1008

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
*9–128.
Determine the magnitude of the resultant force acting on
| the gate ABC     | due to hydrostatic pressure.The gate has a |           |     |     |     |
| ---------------- | ------------------------------------------ | --------- | --- | --- | --- |
| width of 1.5 m.r |                                            | 1.0Mg>m3. |     |     |     |
=
w
1.5m
1.25m
B
C
SOLUTION
2m
| w = 1000(9.81)(1.5)(1.5) |     |     | = 22.072kN>m |     |     |
| ------------------------ | --- | --- | ------------ | --- | --- |
1 60°
A
| w = 1000(9.81)(2)(1.5) |     | =   | 29.43kN>m |     |     |
| ---------------------- | --- | --- | --------- | --- | --- |
2
1
| F = (29.43)(2) | +   | (22.0725)(2) |     | = 73.58kN |     |
| -------------- | --- | ------------ | --- | --------- | --- |
x 2
2
| c(22.072)a1.25 |     |     | bd  |            |     |
| -------------- | --- | --- | --- | ---------- | --- |
| F 1 =          |     | +   |     | = 53.078kN |     |
tan 60°
| 1           |         | 2             |     |         |     |
| ----------- | ------- | ------------- | --- | ------- | --- |
| F (1.5)(2)a |         | b(1000)(9.81) |     | 16.99kN |     |
| 2 = 2       | tan 60° |               |     | =       |     |
70.069 kN
| F y = F 1 + | F 2 = |           |           |       |      |
| ----------- | ----- | --------- | --------- | ----- | ---- |
| 2F2         | F2    | 2(73.58)2 | (70.069)2 | 102kN | Ans. |
| F = x       | + y = |           | +         | =     |      |
Ans:
F = 102 kN
1009

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–129.
| The tank is filled to the top 1y |     |     |     | = 0.5m2with water having |     |     |     |     |
| -------------------------------- | --- | --- | --- | ------------------------ | --- | --- | --- | --- |
y
| adensity of r |     | = 1.0 Mg/m3.Determine the resultant force |     |     |     |     |     |     |
| ------------- | --- | ----------------------------------------- | --- | --- | --- | --- | --- | --- |
w
of the water pressure acting on the flat end plate Cof the x2+y2=(0.5)2
tank,and its location,measured from the top of the tank.
x
C
0.5m
SOLUTION
|     | dF = pdA | = 11219.81210.5 |     | - y22xdy |     |     |     |     |
| --- | -------- | --------------- | --- | -------- | --- | --- | --- | --- |
0.5
|     | = 219.812 |     | 10.5 - | y21210.522 | - y2dy |     |     |     |
| --- | --------- | --- | ------ | ---------- | ------ | --- | --- | --- |
F
L-0.5
0.5
|     | 9.81 |           |     |              | -1 y |     |     |     |
| --- | ---- | --------- | --- | ------------ | ---- | --- | --- | --- |
|     | =    | cy210.522 | -   | y2 + 0.52sin | a bd |     |     |     |
|     | 2    |           |     |              | 0.5  |     |     |     |
-0.5
219.812
|     |     |     | +   | C2510.522 | - y263D0.5 |     |     |     |
| --- | --- | --- | --- | --------- | ---------- | --- | --- | --- |
|     |     |     | 3   |           | -0.5       |     |     |     |
=
|     | F 3.85 kN |     |     |     |     |     |     | Ans. |
| --- | --------- | --- | --- | --- | --- | --- | --- | ---- |
0.5
0.5 0.5
ydF = 219.812 10.5y - y221210.522 - y2dy = 19.62bc- 2510.522 - y263d +
| L   |     | L-0.5 |     |     |     |     | 3   |     |
| --- | --- | ----- | --- | --- | --- | --- | --- | --- |
A -0.5
|       | y            |     |            | 10.522 |           |        |           | y 0.5    |
| ----- | ------------ | --- | ---------- | ------ | --------- | ------ | --------- | -------- |
|       | C2510.522    |     | - y263D0.5 | -      | cy210.522 | - y2 + | 10.522sin | -1a bd r |
|       | 4            |     |            | -0.5   | 8         |        |           | 0.5 -0.5 |
|       | = -0.481kN m |     |            |        |           |        |           |          |
| F1-d2 | =            | ydF |            |        |           |        |           |          |
L
-0.481
|     | =   | =   | -0.125m |     |     |     |     |     |
| --- | --- | --- | ------- | --- | --- | --- | --- | --- |
d
3.85
Hence,measured from the top of the tank,
|     |     |     | d¿ = | +     | =      |     |     |      |
| --- | --- | --- | ---- | ----- | ------ | --- | --- | ---- |
|     |     |     | 0.5  | 0.125 | 0.625m |     |     | Ans. |
Ans:
F 3.85 kN
=
d(cid:30) = 0.625 m
1010

© Pearson Education Limited 2017. All rights reserved. This material is protected under all copyright laws as they currently exist.
No portion of this material may be reproduced, in any form or by any means, without permission in writing from the publisher.
9–130. The underwater tunnel in the aquatic center is
| fabricated  | from  a  transparent  | polycarbonate  | material |     |     | y   |
| ----------- | --------------------- | -------------- | -------- | --- | --- | --- |
formed in the shape of a parabola.Determine the magnitude
of the hydrostatic force that acts per meter length along the
| surface  AB | of  the  tunnel. | The  density  of  | the  water  is |     |     |     |
| ----------- | ---------------- | ----------------- | -------------- | --- | --- | --- |
2 m
r = 1000 kg/m3.
w
y (cid:2) 4 (cid:3) x2 A
4 m
Solution x
B
2 m 2 m
Resultant Force Component: The hydrostatic force acting on the parabolic surface AB
of the tunnel consists of the vertical component F  and the horizontal component F  as
|     |     |     | v   |     | h   |     |
| --- | --- | --- | --- | --- | --- | --- |
shown in Fig. a.
The vertical component F  represents the weight of water contained in the shaded area
v
shown in Fig. a
1
| F = r gAABCDb | = 1000 | 9.81 2 2  | + 2 4 1  | = 65 400 N  | =  65.4 kN |     |
| ------------- | ------ | --------- | -------- | ----------- | ---------- | --- |
| v w           |        |           | 3        |             |            |     |
|               | 1      | 21 2c 1 2 | 1 21 2d1 | 2           |            |     |
The horizontal component F  represents the horizontal hydrostatic pressure. Since the
h
width of the tunnel is constant (1 m), this horizontal loading can be represented by a
trapezoidal distributed loading shown in Fig. a. The intensity of this distributed load-
ing at points A and B are w A = r w gh A b = 1000 9.81 2 1 = 19620 N m and
| w = r gh | b = 1000 9.81 | 6 1 = 58860 N | m = 58.86 kN | m. Thus, |     |     |
| -------- | ------------- | ------------- | ------------ | -------- | --- | --- |
| B w      | B             |               |              |          |     |     |
|          |               |               | 1 21         | 21 2     | >   |     |
|          | 1             | 21 21 2       | >            | >        |     |     |
1
|     | F   | = 19.62 + 58.86 | 4 = 156.96 kN |     |     |     |
| --- | --- | --------------- | ------------- | --- | --- | --- |
|     | h   | 2               |               |     |     |     |
|     |     | 1               | 21 2          |     |     |     |
Resultant: The resultant hydrostatic force acting on the surface AB of the tunnel is
therefore
|     | F   | F 2 F 2 156.962 | 65.42 170 kN  |     | Ans. |     |
| --- | --- | --------------- | ------------- | --- | ---- | --- |
|     | R = | h + v =         | + =           |     |      |     |
|     | 2   | 2               |               |     |      |     |
Ans:
F R = 170 kN
1011