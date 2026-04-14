# 靜力學公式速查表

> Engineering Mechanics: Statics, 14th Edition (SI Units) — Ch01~Ch04

---

## 第一章 — 基本原理 (General Principles)

### 牛頓定律 (Newton's Laws)

| 定律 | 內容 |
|------|------|
| 第一定律 (First Law) | Sum F = 0 → 質點靜止或等速運動 |
| 第二定律 (Second Law) | F = m × a |
| 第三定律 (Third Law) | 作用力與反作用力大小相等、方向相反、共線 |

### 重量 (Weight)

- W = m × g，g = 9.81 m/s²
- 重量不是絕對量，會隨位置改變

### SI 基本單位 (SI Base Units)

| 物理量 | 單位 | 符號 |
|--------|------|------|
| 長度 (Length) | 公尺 | m |
| 時間 (Time) | 秒 | s |
| 質量 (Mass) | 公斤 | kg |
| 力 (Force, 導出單位) | 牛頓 | N = kg·m/s² |

---

## 第二章 — 力向量 (Force Vectors)

### 2.1 純量與向量 (Scalars and Vectors)

- 純量 (Scalar)：只有大小（質量、時間、長度）
- 向量 (Vector)：大小 + 方向 (Direction) + 指向 (Sense)

### 2.2 向量加法 (Vector Addition)

- 平行四邊形法則 (Parallelogram Law)：R = A + B，對角線即合力
- 三角形法則 (Triangle Rule)：B 的尾接 A 的頭，起點到終點即合力
- 向量減法：A - B = A + (-B)

### 2.4 共面力合成 (Coplanar Force Resultants, 2D)

- Fx = F cos(theta), Fy = F sin(theta)
- F = Fx i + Fy j
- (F_R)x = Sum Fx, (F_R)y = Sum Fy
- F_R = sqrt((F_R)x² + (F_R)y²)
- theta = arctan |(F_R)y / (F_R)x|

### 2.5 直角坐標向量 (Cartesian Vectors, 3D)

- A = Ax i + Ay j + Az k
- |A| = sqrt(Ax² + Ay² + Az²)

**方向餘弦 (Direction Cosines)：**

- cos(alpha) = Ax / |A|（與正 x 軸夾角）
- cos(beta) = Ay / |A|（與正 y 軸夾角）
- cos(gamma) = Az / |A|（與正 z 軸夾角）
- cos²(alpha) + cos²(beta) + cos²(gamma) = 1

**單位向量 (Unit Vector)：**

- u_A = A / |A| = cos(alpha) i + cos(beta) j + cos(gamma) k

**橫角與方位角 (Transverse/Azimuth Angles)：**

- Ax = A sin(phi) cos(theta)
- Ay = A sin(phi) sin(theta)
- Az = A cos(phi)

### 2.7 位置向量 (Position Vectors)

- r = (xB - xA) i + (yB - yA) j + (zB - zA) k
- |r| = sqrt((xB-xA)² + (yB-yA)² + (zB-zA)²)

### 2.8 沿線力 (Force Directed along a Line)

- F = F × u = F × (r / |r|)

### 2.9 點積 (Dot Product)

- A . B = |A| |B| cos(theta)
- A . B = AxBx + AyBy + AzBz

**應用 (Applications)：**

- 兩向量夾角：theta = arccos( (A . B) / (|A| |B|) )
- 若 A . B = 0 → 兩向量垂直 (Perpendicular)
- 投影 — 平行分量：A_parallel = (A . u) × u
- 投影 — 垂直分量：A_perp = A - A_parallel
- |A_perp| = sqrt(|A|² - |A_parallel|²)

---

## 第三章 — 質點平衡 (Equilibrium of a Particle)

### 3.1 平衡條件 (Equilibrium Condition)

- Sum F = 0

### 3.2 自由體圖常見元件 (FBD Components)

| 元件 | 關鍵性質 |
|------|---------|
| 彈簧 (Spring) | F = k × s，s = l - l0（變形量） |
| 繩索 (Cable) | 只承受張力 (Tension)，連續繩張力大小恆定 |
| 光滑面 (Smooth Surface) | 力垂直於接觸面 (Normal Force) |

### 3.3 共面平衡 (Coplanar Equilibrium, 2D)

- Sum Fx = 0
- Sum Fy = 0
- 最多解 2 個未知數

### 3.4 三維平衡 (3D Equilibrium)

- Sum Fx = 0, Sum Fy = 0, Sum Fz = 0
- 最多解 3 個未知數

---

## 第四章 — 力系合量 (Force System Resultants)

### 4.1 力矩 — 純量形式 (Moment, Scalar Formulation)

- M_O = F × d（d = 力臂 Moment Arm，垂直距離）
- (M_R)_O = Sum(F × d)（逆時針 CCW 正，順時針 CW 負）
- 單位：N·m

### 4.2 叉積 (Cross Product)

- A × B = (AyBz - AzBy) i - (AxBz - AzBx) j + (AxBy - AyBx) k

**ijk 速記（逆時針繞圈 = 正）：**

| 叉積 | 結果 | 叉積 | 結果 |
|------|------|------|------|
| i × j | k | j × i | -k |
| j × k | i | k × j | -i |
| k × i | j | i × k | -j |
| i × i | 0 | j × j | 0 | k × k | 0 |

**運算律 (Laws of Operations)：**

- A × B ≠ B × A（不滿足交換律 Not Commutative）
- A × B = -(B × A)
- 分配律 (Distributive)：A × (B + D) = (A × B) + (A × D)

### 4.3 力矩 — 向量形式 (Moment, Vector Formulation)

- M_O = r × F
- r = 從 O 到力作用線上任意一點的位置向量 (Position Vector)
- 可傳性 (Principle of Transmissibility)：力可沿作用線滑動，力矩不變
- M_O 垂直於 r 和 F 所在平面
- (M_R)_O = Sum(r × F)

### 4.4 力矩原理 (Principle of Moments / Varignon's Theorem)

- M_O = r × F = r × F1 + r × F2（合力矩 = 分量力矩之和）
- **2D 速算：M_O = Fx × y - Fy × x**

### 4.5 力對指定軸的力矩 (Moment about a Specified Axis)

- 純量法：M_a = F × d_a
- **向量法：M_a = u_a . (r × F)**（純量三重積 Scalar Triple Product）
- 行列式展開：M_a = | uax uay uaz | 的行列式
- M_a 正 → 與 u_a 同向
- M_a 負 → 與 u_a 反向
- 向量形式：M_a (向量) = M_a × u_a

### 4.6 力偶矩 (Moment of a Couple)

- 力偶 (Couple)：兩個大小相等、方向相反、互相平行的力
- 合力 = 0，純旋轉效果
- 純量：M = F × d
- 向量：M = r × F（r 為兩力之間的位置向量）
- **力偶矩是自由向量 (Free Vector)** — 可作用在任意位置
- 等效力偶 (Equivalent Couples)：M 大小和方向相同即等效
- (M_R) = 力偶矩向量和 (Vector Addition)

### 4.7 力系與力偶系統簡化 (Simplification of a Force and Couple System)

- **F_R = Sum F**（與參考點 O 無關）
- **(M_R)_O = Sum M + Sum(r × F)**（與參考點 O 有關）

**2D 共面情況 (Coplanar)：**

- (F_R)x = Sum Fx, (F_R)y = Sum Fy
- (M_R)_O = Sum M_O + Sum M

### 4.8 進一步簡化 (Further Simplification)

條件：F_R 與 (M_R)_O 垂直 → 可化簡為單一等效力

**三種可簡化力系：** 共點 (Concurrent)、共面 (Coplanar)、平行 (Parallel)

- **d = (M_R)_O / F_R**（等效力到參考點的距離）

**平行力系 — 求 (x, y)：**

- 對 x 軸取力矩 → 解 y
- 對 y 軸取力矩 → 解 x

**扳手 (Wrench，一般 3D)：**

- 若 F_R 與 (M_R)_O 不垂直
- 將 (M_R)_O 分解為 M_parallel 和 M_perp
- M_perp 可藉由移動 F_R 消除
- 結果：F_R + M_parallel = 扳手（像螺絲一樣又推又轉）

### 4.9 分佈載荷簡化 (Reduction of Distributed Loading)

**核心規則：**

- **F_R = 載荷圖面積 (Area under loading diagram)**
- **合力作用於面積的形心 (Centroid)**

**常用形狀：**

| 形狀 | 面積 (F_R) | 從尖端算形心 |
|------|-----------|-------------|
| 矩形 (Rectangle，均佈 w) | w × L | L/2（正中間） |
| 三角形 (Triangle，0 到 w0) | w0 × L / 2 | 2L/3 |
| 拋物線 (Parabola，0 到 w0) | w0 × L / 3 | 3L/4 |

**梯形 (Trapezoid)：** 拆成矩形 + 三角形，各自算再合成：

- F_R = F1 + F2
- x_bar = (F1 × x1 + F2 × x2) / F_R

**一般積分形式 (Integral Form)：**

- F_R = 積分 w(x) dx
- x_bar = 積分(x × w(x) dx) / 積分(w(x) dx)

---

## 計算機速查 (Casio fx-991ES+)

| 操作 | 按法 |
|------|------|
| 向量模式 (Vector Mode) | MENU → VCT |
| 點積 (Dot Product) | Dot(VctA, VctB) |
| 叉積 (Cross Product) | Cross(VctA, VctB) |
| 向量大小 (Magnitude) | Abs(Vct) = Shift + Hyp |
| 方向角 (Direction Angles) | cos⁻¹(Dot / (Abs × Abs)) |
| 投影 (Projection) | F × cos(Ans)，接在算完角度後 |
| 混合三重積 (Triple Product) | Dot(VctA, Cross(VctB, VctC)) |

---

*最後更新：2026-04-14*
