# 计算材料学课程仓库 | Computational Materials Science Coursework

> 中山大学材料学院 · 2026年春季学期 · 朱升财副教授
>
> School of Materials, Sun Yat-sen University · Spring 2026 · Assoc. Prof. Zhu Shengcai

---

## 关于本仓库 | About

本仓库收录了2026年春季学期《计算材料学》课程的理论笔记与课程作业，主要涵盖第一性原理计算方法（基于 VASP）。

This repository contains theoretical notes and coursework for the *Computational Materials Science* course (Spring 2026), focusing on first-principles calculation methods using VASP.

**内容包括 | Contents:**
- 📖 理论前置笔记（量子力学基础 → DFT → 计算方法）
- 🧪 课程作业（结构优化、能带、态密度、ELF、PCD 等）

---

## 目录结构 | Repository Structure

```
computational-materials-SYSU-2026/
├── notes/                        # 理论笔记 | Theoretical Notes
│   ├── 01_quantum_mechanics_basics.md
│   ├── 02_DFT_fundamentals.md
│   └── 03_computational_methods.md
│
├── homework/                     # 课程作业 | Coursework
│   ├── hw01/                     # 第一次作业
│   └── hw02_Ba2N/                # 第二次作业：Ba₂N 第一性原理计算
│
├── resources/                    # 参考资料 | References
│   └── references.md
│
├── .gitignore
└── README.md
```

---

## 理论笔记 | Theoretical Notes

| 编号 | 文件 | 主要内容 |
|------|------|----------|
| 01 | [量子力学基础](./notes/01_quantum_mechanics_basics.md) | 单/多电子薛定谔方程、绝热近似、Hartree-Fock 近似 |
| 02 | [密度泛函理论](./notes/02_DFT_fundamentals.md) | Thomas-Fermi 理论、DFT、Kohn-Sham 方程、LDA、GGA |
| 03 | [计算方法](./notes/03_computational_methods.md) | 赝势理论、平面波基底、截断能、K 点取样、超胞 |

---

## 课程作业 | Homework

| 编号 | 内容 | 状态 |
|------|------|------|
| [HW01](./homework/hw01/) | 氢分子的精确电子波函数-Kolos & Roothaan (1960) 论文翻译与批注 | ✅ 已完成 |
| [HW02](./homework/hw02_Ba2N/) | Ba₂N 第一性原理计算（结构优化、能带、DOS、ELF、PCD） | ✅ 已完成 |
| [HW03] | -- | waiting |


---

## 使用说明 | Usage & License

本仓库内容仅供**学习交流**使用。

如有同学希望参考本仓库内容，**请先通过我的 GitHub 主页邮箱联系我**，说明用途，经同意后方可使用。欢迎学术交流与讨论。

This repository is for **personal learning and academic exchange** only.  
If you wish to reference any content, please **contact me via the email on my GitHub profile**, state your purpose, and obtain my consent before use. Academic discussion is always welcome.

---

## 计算环境 | Computational Environment

- **软件 | Software:** VASP (Vienna Ab initio Simulation Package)
- **方法 | Method:** DFT, Plane-wave basis, PAW pseudopotentials
- **泛函 | Functional:** GGA-PBE

---

*持续更新中 | Continuously updated throughout Spring 2026*
