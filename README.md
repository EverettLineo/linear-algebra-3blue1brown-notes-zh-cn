# Linear Algebra Notes | 3Blue1Brown Essence of Linear Algebra
## Comprehensive Lecture Notes in English, Persian & Chinese | یادداشت‌های جبر خطی | 线性代数讲义

[![License: Educational](https://img.shields.io/badge/License-Educational-blue.svg)](#license)
[![LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)
[![3Blue1Brown](https://img.shields.io/badge/Based%20on-3Blue1Brown-blue)](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

> **Complete PDF lecture notes** for Grant Sanderson's famous [Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) video series. Available in **English**, **Persian (فارسی)** and **Chinese (中文)**.

---

## 📥 Download PDFs

| Language | Pages | Download |
|----------|-------|----------|
| **English** | 77 | [📄 Download PDF](english_notes/Linear-Algebra-3Blue1Brown-English.pdf) |
| **Persian (فارسی)** | 78 | [📄 Download PDF](persian_notes/Linear-Algebra-3Blue1Brown-Persian.pdf) |
| **Chinese (中文)** | 74 | [📄 Download PDF](chinese_notes/Linear-Algebra-3Blue1Brown-Chinese.pdf) |

> ✅ 中文版已完成全部 12 章翻译, 由英文版译出, 术语采用中英对照。The Chinese version covers all 12 chapters, translated from the English version with bilingual terminology.

---

## 📚 What's Inside

These notes cover all core concepts of linear algebra with emphasis on **geometric intuition** - the signature teaching style of 3Blue1Brown.

### Topics Covered

| Chapter | Topic | Key Concepts |
|---------|-------|--------------|
| 1 | **Vectors** | Vector basics, coordinate systems, vector addition |
| 2 | **Linear Combinations** | Span, basis vectors, linear independence |
| 3 | **Linear Transformations** | Matrix representation, transformation visualization |
| 4 | **Matrix Multiplication** | Composition of transformations, 3D transformations |
| 5 | **Determinants** | Area/volume scaling, orientation |
| 6 | **Inverse Matrices** | Column space, null space, rank |
| 7 | **Dot Products** | Projections, duality |
| 8 | **Cross Products** | 3D perpendicular vectors, applications |
| 9 | **Cramer's Rule** | Solving linear systems geometrically |
| 10 | **Change of Basis** | Coordinate transformations |
| 11 | **Eigenvectors & Eigenvalues** | Special directions, characteristic equation |
| 12 | **Abstract Vector Spaces** | Beyond arrows, function spaces |

---

## ✨ Features

- **🎯 Geometric Intuition** - Visual understanding of every concept
- **📐 Rigorous Definitions** - Precise mathematical formulations
- **💡 Practical Applications** - Physics, computer graphics, machine learning
- **✏️ Exercises** - Practice problems with varying difficulty
- **🎨 TikZ Diagrams** - Beautiful vector and transformation visualizations

---

## 🔧 Build from Source

### English Version
```bash
cd english_notes
pdflatex main.tex
pdflatex main.tex  # Run twice for references
```

### Persian Version
Requires XeLaTeX with XePersian package.
```bash
cd persian_notes
xelatex main.tex
xelatex main.tex  # Run twice for references
```

### Chinese Version (中文版)
Requires XeLaTeX with ctex package (Chinese support).
```bash
cd chinese_notes
xelatex main.tex
xelatex main.tex  # Run twice for references
```

---

## 📁 Project Structure

```
├── english_notes/
│   ├── main.tex                                 # Main document
│   ├── preamble.tex                             # LaTeX configuration
│   ├── commands.tex                             # Math macros
│   ├── Linear-Algebra-3Blue1Brown-English.pdf  # Compiled PDF
│   └── lectures/                                # 12 chapter files
│
├── persian_notes/
│   ├── main.tex                                 # Main document
│   ├── preamble.tex                             # XePersian configuration
│   ├── commands.tex                             # Math macros
│   ├── Linear-Algebra-3Blue1Brown-Persian.pdf  # Compiled PDF
│   ├── lectures/                                # 12 chapter files
│   └── figures/                                 # Images
│
├── chinese_notes/
│   ├── main.tex                                 # 主文档 (XeLaTeX + ctex)
│   ├── preamble.tex                             # 中文 LaTeX 配置
│   ├── commands.tex                             # 数学宏 (与英文版一致)
│   ├── Linear-Algebra-3Blue1Brown-Chinese.pdf  # 编译产物
│   └── lectures/                                # 12 章文件 (已全部翻译)
```

---

<div dir="rtl">

## 🇮🇷 نسخه فارسی

این یادداشت‌ها ترجمه کامل مجموعه ویدیویی **ذات جبر خطی** از کانال 3Blue1Brown هستند.

### ویژگی‌ها
- شهود هندسی برای همه مفاهیم
- تعاریف دقیق ریاضی
- مثال‌های کاربردی از فیزیک و علوم کامپیوتر
- تمرین‌های متنوع

</div>

---

## 🇨🇳 中文版

本笔记是 3Blue1Brown **《线性代数的本质》** 视频系列的完整中文讲义, 由英文版翻译而来。

### 翻译规范
- 中文为主, 关键术语附英文对照, 如: 向量 (vector)、秩 (rank)
- 数学公式、TikZ 插图、LaTeX 命令与英文版保持一致
- 定理环境与提示框已汉化: 定义 / 例 / 练习 / 几何直观 / 实际应用 / 重点 / 注意 / 本章小结
- 使用 XeLaTeX + ctex 编译, 详见 `chinese_notes/`

### 翻译进度
- [x] 第 1 章: 向量简介
- [x] 第 2 章: 线性组合、张成与基
- [x] 第 3 章: 线性变换与矩阵
- [x] 第 4 章: 三维变换与行列式
- [x] 第 5 章: 逆矩阵、列空间与零空间
- [x] 第 6 章: 点积与对偶性
- [x] 第 7 章: 叉积及应用
- [x] 第 8 章: 克拉默法则
- [x] 第 9 章: 基变换
- [x] 第 10 章: 特征向量与特征值
- [x] 第 11 章: 特征值计算与特征基
- [x] 第 12 章: 抽象向量空间

---

## 👥 Credits

**Sharif University of Technology Physics Association**
انجمن علمی فیزیک دانشگاه صنعتی شریف

Contributors:
- Ebrahim Khosravani (ابراهیم خسروانی)
- Mohammadhasan Shiri (محمدحسن شیری)
- Zahra Amiri (زهرا امیری)
- Amin Azizi (امین عزیزی)
- Bita Qorbani (بیتا قربانی)
- Yasamin Yazdani (یاسمین یزدانی)
- Sepehr Talaei (سپهر طلایی)

---

## 🔗 Resources

- **Original Video Series:** [Essence of Linear Algebra - 3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
- **Creator:** Grant Sanderson
- **Channel:** [3Blue1Brown](https://www.youtube.com/@3blue1brown)

---

## 📄 License

This work is for **educational purposes**. The original video content belongs to 3Blue1Brown.

---

## 🌟 Star This Repo

If you find these notes helpful, please ⭐ star this repository to help others discover it!

**Keywords:** Linear Algebra, 3Blue1Brown, Essence of Linear Algebra, Math Notes, Lecture Notes, Eigenvectors, Eigenvalues, Matrices, Vectors, Determinants, PDF, LaTeX, Persian, Farsi, English, Chinese, Grant Sanderson, Mathematics Education, STEM, 线性代数, 线性代数的本质, 中文讲义
