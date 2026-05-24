# Ba₂N Electronic Structure Calculations

本项目为 Ba₂N 的第一性原理计算作业报告及相关文件。

**课程**：计算材料学，中山大学材料学院，2026 春  
**作者**：林嘉馨

## 计算内容

1. 结构优化（Structural Relaxation）
2. 能带结构与态密度（Band Structure & DOS）
3. 电子局域函数（Electron Localization Function, ELF）
4. 部分电荷密度（Partial Charge Density, PCD）

详细计算方法、INCAR 参数设置见 [`report/Ba2N_计算报告.pdf`](report/Ba2N_计算报告.pdf)。

## 结构信息

- 化学式：Ba₂N（电子化物，[Ba₂N]⁺·e⁻）
- 空间群：R-3m（反 CdCl₂ 型六方层状结构）
- 晶格参数：a = 4.046 Å，c = 23.025 Å
- 超胞：Ba₆N₃（3 个化学式单元，共 9 个原子）

## 计算参数

| 参数 | 值 |
|---|---|
| 软件 | VASP |
| 泛函 | GGA-PBE |
| 截断能 | 520 eV |
| EDIFF | 1×10⁻⁶ eV |
| EDIFFG | −0.02 eV/Å |
| 展宽方法 | Methfessel-Paxton (ISMEAR=0, σ=0.05 eV) |
| 自旋 | 非自旋极化 (ISPIN=1) |
| 赝势 | PAW_PBE Ba_sv / N（见 POTCAR.info）|

## 结果预览

## 结果预览

| Band & DOS |
|:---:|
| ![](figures/band_dos_final.png) |

| ELF | PCD |
|:---:|:---:|
| ![](figures/elf.png) | ![](figures/pcd.png) |
> 📄 报告含完整图文分析，PDF 较大请下载后查看。

## 计算流程
01_relax → 02_scf → 03_band / 04_dos / 05_elf / 06_pcd

## 主要结论

- Ba₂N 为金属性材料，能带穿越费米能级
- 费米能级处电子态主要由 Ba 的 5d 轨道贡献
- ELF 与 PCD 共同证实层间存在准二维自由电子气
- N 以 N³⁻ 形式存在，2p 满壳层态位于 −1.5 ~ −2.5 eV

## License

MIT License
