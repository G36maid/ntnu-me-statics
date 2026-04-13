# ME Statics - 課程材料與筆記

機械工程靜力學 (ME Statics) 課程材料倉庫，包含課程講義、習題解答及筆記。

## 📁 目錄結構

```
me-statics/
├── AGENTS.md                    # 專案指南與結構規範
├── README.md                    # 本文件
├── course-materials/            # 原始課程材料
│   ├── ch01 General Principles.pdf
│   ├── ch02 Force Vectors(modified).pdf
│   ├── ch03 Equilibrium of a Particle_N.pdf
│   ├── ch04N Force System Resultants.pdf
│   ├── Solution_Chpter 1.pdf ~ 11.pdf
├── notes/                       # Markdown 筆記
│   ├── 01-general-principles.md
│   ├── 02-force-vectors.md
│   ├── 03-particle-equilibrium.md
│   ├── 04-force-system-resultants.md
│   ├── 05-equilibrium-rigid-body.md
│   ├── solution/                # 習題解答 Markdown
│   │   ├── 01-general-principles.md ~ 11-virtual-work.md
│   └── resources/               # 筆記資源檔案
```

## 📚 課程內容索引

### 講義 (Lecture Materials)

| 章節 | 標題 | 筆記 | 原始 PDF |
|------|------|------|---------|
| Ch 1 | General Principles | [📝 筆記](notes/01-general-principles.md) | [PDF](course-materials/ch01%20General%20Principles.pdf) |
| Ch 2 | Force Vectors | [📝 筆記](notes/02-force-vectors.md) | [PDF](course-materials/ch02%20Force%20Vectors(modified).pdf) |
| Ch 3 | Equilibrium of a Particle | [📝 筆記](notes/03-particle-equilibrium.md) | [PDF](course-materials/ch03%20Equilibrium%20of%20a%20Particle_N.pdf) |
| Ch 4 | Force System Resultants | [📝 筆記](notes/04-force-system-resultants.md) | [PDF](course-materials/ch04N%20Force%20System%20Resultants.pdf) |
| Ch 5 | Equilibrium of a Rigid Body | [📝 筆記](notes/05-equilibrium-rigid-body.md) | [PDF](course-materials/ch05%20Equilibrium%20of%20a%20Rigid%20Body.pdf) |

### 習題解答 (Solution Sets)

| 章節 | Markdown 解答 | 原始 PDF |
|------|-------------|---------|
| Ch 1 | [📝 解答](notes/solution/01-general-principles.md) | [PDF](course-materials/Solution_Chpter%201.pdf) |
| Ch 2 | [📝 解答](notes/solution/02-force-vectors.md) | [PDF](course-materials/Solution_Chpter%202.pdf) |
| Ch 3 | [📝 解答](notes/solution/03-particle-equilibrium.md) | [PDF](course-materials/Solution_Chpter%203.pdf) |
| Ch 4 | [📝 解答](notes/solution/04-force-system-resultants.md) | [PDF](course-materials/Solution_Chpter%204.pdf) |
| Ch 5 | [📝 解答](notes/solution/05-equilibrium-rigid-body.md) | [PDF](course-materials/Solution_Chpter%205.pdf) |
| Ch 6 | [📝 解答](notes/solution/06-structural-analysis.md) | [PDF](course-materials/Solution_Chpter%206.pdf) |
| Ch 7 | [📝 解答](notes/solution/07-internal-forces.md) | [PDF](course-materials/Solution_Chpter%207.pdf) |
| Ch 8 | [📝 解答](notes/solution/08-friction.md) | [PDF](course-materials/Solution_Chpter%208.pdf) |
| Ch 9 | [📝 解答](notes/solution/09-center-of-gravity.md) | [PDF](course-materials/Solution_Chpter%209.pdf) |
| Ch 10 | [📝 解答](notes/solution/10-moments-of-inertia.md) | [PDF](course-materials/Solution_Chpter%2010.pdf) |
| Ch 11 | [📝 解答](notes/solution/11-virtual-work.md) | [PDF](course-materials/Solution_Chpter%2011.pdf) |

## 🎯 主要主題

本課程涵蓋靜力學的核心主題：

- **一般原理** (General Principles) - 靜力學基本概念與定義、牛頓定律、SI 單位制
- **力向量** (Force Vectors) - 力的向量表示與運算、直角坐標向量、點積
- **質點平衡** (Equilibrium of a Particle) - 自由體圖、共面與三維力系平衡
- **力系合量** (Force System Resultants) - 力矩、叉積、力偶、分佈載荷
- **剛體平衡** (Equilibrium of a Rigid Body) - 自由體圖、二力/三力構件、支撐反力、靜定與靜不定

## 📝 如何使用此倉庫

### 存取課程材料

1. **Markdown 筆記**：點選上方索引表格中的「📝 筆記」連結，可直接在 GitHub 上閱讀結構化筆記
2. **講義與解答**：所有原始 PDF 檔案位於 `course-materials/` 目錄
3. **瀏覽內容**：點選上方索引表格中的連結即可查看或下載

### 筆記整理流程

根據 `AGENTS.md` 的規範，筆記整理遵循以下流程：

1. **原始材料存放**：將課程 PDF、簡報等原始檔案放置於 `course-materials/`
2. **轉換為 Markdown**：使用轉換工具將 PDF 轉換為結構化的 Markdown 筆記
3. **筆記命名規則**：
   - 主筆記：`notes/XX-topic.md`（例如：`notes/01-general-principles.md`）
   - 詳細資源：`notes/resources/detailed-resource.md`
4. **連結管理**：在 `README.md` 中新增所有筆記的連結

## 🚀 待辦事項

- [x] 將課程 PDF 轉換為 Markdown 筆記 (Ch1–Ch4)
- [x] 建立 `notes/01-general-principles.md`
- [x] 建立 `notes/02-force-vectors.md`
- [x] 建立 `notes/03-particle-equilibrium.md`
- [x] 建立 `notes/04-force-system-resultants.md`
- [x] 建立 `notes/05-equilibrium-rigid-body.md`
- [x] 將習題解答 PDF 轉換為 Markdown (Ch1–Ch11)
- [ ] 為每章節補充更多例題與學習重點
- [ ] 新增相關參考資源與連結

## 📖 規範文件

- **[AGENTS.md](AGENTS.md)** - 專案結構指南、檔案命名規則、筆記整理流程

## 📄 許可證

本專案內容僅供學習使用，版權屬於原作者。

---

**最後更新**：2026-04-14
