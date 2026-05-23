# Daily Papers - 自动化每日精选 arxiv 论文

**自动抓取ArXiv论文，使用 Google Gemini 评分筛选高质量内容**

专为 **计算机科学学者/程序员** 设计

## ✨ 特性

- **🆓 完全免费** - 使用 Google AI Studio 免费 API
- **🤖 自动运行** - GitHub Actions 每天自动运行
- **🎯 智能评分** - 四维度评估（0-100分）
- **💡 AI摘要** - 自动生成论文核心贡献摘要

## 🚀 快速开始

1. **Fork 本仓库**
2. **配置 API Key** - 添加 `GOOGLE_AI_API_KEY` 到 GitHub Secrets（[获取地址](https://aistudio.google.com/apikey)）
3. **启用 Actions** - Actions → Daily Papers → Enable workflow
4. **订阅通知** - Watch → All Activity

完成！系统每天 UTC 17:00（北京时间 1:00）自动运行。

📖 **详细设置请查看 [SETUP.md](SETUP.md)**

## 📚 历史论文

查看所有历史精选论文：[papers](papers/)

---

<!-- PAPERS_START -->

## 2026-05-24

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[A sulfonitride transparent conductive thin film with ultra-high refractive index](https://arxiv.org/abs/2605.22483v1)** | ⭐ 88/100 | 实现高折射率透明导电硫氮化锆薄膜生长 | 材料合成具突破性，光学与电学性能优异，实验严谨。 | <details><summary>展开</summary>With the rise of AI-assisted materials screening, extraordinary properties are now frequently predicted in experimentally uncharted material systems, highlighting the need to develop new synthesis methods for unconventional materials beyond the classic bulk powder form. Here, we establish the first thin-film growth route for any metal sulfonitride compound by realizing Zr2SN2 films with a rare and compelling combination of optical and electrical properties. Zr2SN2 is transparent across most of the visible range while exhibiting a very high average refractive index of 2.95 in the visible, exceeding expectations based on conventional refractive index-bandgap scaling. Importantly, the same Zr2SN2 film shows degenerate n-type conductivity with carrier density above 10^20 cm-3 and intragrain mobility above 8 cm2V-1s-1, approaching those of established transparent conductive oxides. Zr2SN2 thus demonstrates that strong light-matter interaction, optical transparency and electrical conductivity can be reconciled within a single material platform, revealing a new class of high-refractive-index transparent conductors.</details> |
| **[Competing incommensurability, electronic correlations, and superconductivity in a hybrid transition metal dichalcogenide](https://arxiv.org/abs/2605.22522v1)** | ⭐ 82/100 | 揭示4Hb-TaS2中非公度势与强关联及超导的耦合机制 | 结合STM与DFT-DMFT，深入阐述了层间非公度势对电子关联的影响。 | <details><summary>展开</summary>The engineering of superlattices in two-dimensional van der Waals materials has enabled the realization of rich phase diagrams hosting topological and strongly correlated phases. While incommensurability is widespread in three-dimensional systems, the role of moiré potentials in bulk materials remains largely unexplored. Here, using scanning tunneling microscopy, we demonstrate that a bulk transition-metal dichalcogenide polytype, 4Hb-TaS$_2$, hosts an emergent incommensurate potential between its alternating 1T and 1H layers. Interplay with a concomitant incommensurate charge-density wave suppresses the long-range order of this potential, leading to intricate coupling with electronic correlations in the doped 1T surface layer. Combining density functional theory with dynamical mean-field theory, we show that the lattice mismatch locally modulates the interlayer distance, thereby tuning both hybridization and charge transfer between the correlated 1T and metallic 1H layers. This redistribution of charge drives the system towards a doped Mott regime, in which the remaining local moments become self-screened, giving rise to a zero-bias resonance. We further find that bulk superconductivity competes with both the underlying landscape and the associated charge transfer. Our results establish incommensurate potentials as a previously overlooked ingredient in hybrid transition-metal dichalcogenides, highlighting their central role in the interplay between electronic correlations, charge-density-wave order, and unconventional superconductivity.</details> |
| **[Harnessing Linear and Nonlinear Optical Responses in Ferroelectric LaMoN$_3$ for Enhanced Photovoltaic Efficiency](https://arxiv.org/abs/2605.22453v1)** | ⭐ 78/100 | 压力调控LaMoN3光伏性能 | 利用第一性原理系统研究了压力对材料光电特性的调控机制。 | <details><summary>展开</summary>Nitride perovskites are an emerging class of materials predicted to exhibit diverse functional properties, yet remain underexplored due to synthesis challenges of oxygen-free nitrides. Recently, LaMoN$_3$ has been reported as an oxygen-free nitride perovskite with polar symmetry, exhibiting excellent dynamic stability and ferroelectric properties under moderate pressure. However, its phase stability, linear and non-linear optical response, excitonic and polaronic behavior, and efficiency under high pressure remain unexplored. Applying pressure enables systematic tuning of the electronic structure properties, thereby facilitating the identification of phases optimized for either linear or nonlinear optical responses. Therefore, in this work, we systematically investigate these properties of LaMoN$_3$ up to 40 GPa using first-principles methods, including density functional theory, density functional perturbation theory, many-body perturbation theory (namely G$_0$W$_0$ and BSE), and tight binding approximation model. Our study shows that LaMoN$_3$ remains dynamically stable and retains its single-phase structure up to 40 GPa. The compound exhibits an indirect bandgap that decreases from 2.17 eV (0 GPa) to 1.45 eV (40 GPa) at the G$_0$W$_0$@PBE level. Using the BSE, we find that pressure enhances the SLME while lowering the exciton binding energy, both favorable for photovoltaic applications. The bulk photovoltaic efficiency trend with pressure mimics the behavior of the shift current density J$_SC$ , peaking near 15 GPa before declining at higher pressures due to a diminished nonlinear shift current response. These results highlight pressure-tuned regimes to enhance photovoltaic performance. We thereby propose multi-junction device, combining absorber layers optimized for linear and nonlinear optical currents, together boosting solar energy conversion through complementary mechanisms.</details> |
| **[Summarizing Time-Varying Digital Image Correlation Strain Fields Using Sankey Diagrams](https://arxiv.org/abs/2605.22627v1)** | ⭐ 76/100 | 利用桑基图可视化DIC应变场演化 | 创新性地将桑基图引入DIC分析，方法严谨且实用。 | <details><summary>展开</summary>Digital Image Correlation (DIC) enables dense, time-resolved measurement of surface strain in deforming materials, providing insight into strain localization and failure mechanisms. However, the resulting strain fields are typically explored frame-by-frame through spatial visualizations, making global temporal patterns difficult to discern. We present a visual summarization approach that represents the evolution of high-strain regions as a single Sankey diagram constructed from superlevel sets of the von Mises equivalent strain field. By tracking connected components over time via spatial overlap, the diagram encodes the birth, persistence, merging, and disappearance of strain concentrations. Applied to four tensile test datasets with varying notch geometries, the approach compactly captures differences in deformation regimes and qualitative precursors to failure, complementing traditional spatial strain visualizations with a global temporal overview.</details> |
| **[Emergent magnetic and charge ordered phases in freestanding ultrathin \ce{LaVO3}](https://arxiv.org/abs/2605.22415v1)** | ⭐ 76/100 | 揭示了自由站立LaVO3薄膜的磁性与电荷序演变 | 利用DFT计算系统研究了厚度与掺杂对磁相变的影响，方法严谨。 | <details><summary>展开</summary>Transition metal oxide perovskites are an ideal platform for exploring the interplay between spin, orbital, charge and lattice degrees of freedom. Among them, \ce{LaVO3} has been extensively studied in heterostructures and superlattices, where exotic phases have been reported. Motivated by the advances in freestanding oxide membranes, we investigate the intrinsic properties of freestanding ultrathin \ce{LaVO3} films using density functional theory. Our calculations reveal a sequence of magnetic phase transitions with thickness, starting from stripe-AFM in monolayer until the bulk like C-AFM is recovered. Beyond four layers, polar catastrophe driven charge transfer dopes the surface layers giving rise to stripe-AFM and ferromagnetic surface states while the central layers remain bulk like. We further explore this fact by studying charge doped monolayer, discovering that hole doping drives the system into ferromagnetic state. Doping also induced charge ordering in the system. A striped charge ordering pattern is observed at 0.5 h/fu, while a 3:1 stripe pattern emerges at 0.25 h/fu, indicating that the periodicity of the superstructure changes with doping concentration.</details> |

