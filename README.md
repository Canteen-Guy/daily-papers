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

## 2026-07-13

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[An Efficient Method for Gibbs Free Energy Evaluation under Volume Compression](https://arxiv.org/abs/2607.08608v1)** | ⭐ 78/100 | 提出一种高效吉布斯自由能评估插值法 | 方法显著提升计算效率且验证充分，具有实用价值 | <details><summary>展开</summary>Accurate evaluation of Gibbs free energies is essential for constructing pressure-temperature phase diagrams. Conventional methods based on the quasi-harmonic approximation (QHA) require phonon spectra at many volume points and are therefore expensive in general. Here we develop an efficient method based on the interpolation of a few ab initio data points for Gibbs free energy evaluation under volume compression. Phonon spectra are calculated only at selected volumes. An effective Gruneisen parameter derived from the zero-point energy (ZPE) reconstructs the static-ZPE branch, while piecewise mode-resolved Gruneisen slopes reconstruct the finite-temperature vibrational branches on the target volume grids. The method is validated against QHA benchmarks for diamond (C), Al, Si, Ge, rutile TiO2, beta-PtO2, and Ta2O5 polymorphs. For simple benchmark systems (C, Al, Si, Ge, rutile TiO2, and beta-PtO2), the Gibbs free energy mean absolute errors (MAEs) relative to the QHA benchmarks remain below 0.53 meV/atom, with a six-system average of 0.148 meV/atom, while the number of explicit phonon volume points is reduced from about 20-21 to 3 in the lowest-cost implementation. For the more complex Ta2O5 polymorphs, the reconstructed free energies reproduce the main phase-stability topology despite larger phase-dependent errors. With reference to the QHA workflows, the interpolation method in this work achieves speedups of 5.911-9.023 times and remains reliable for moderate compression ranges where phonon frequencies vary smoothly with volume.</details> |
| **[Intracellular luminescence thermometry: A story of disagreement, trust, and hope](https://arxiv.org/abs/2607.08574v1)** | ⭐ 78/100 | 综述细胞内发光测温的挑战与改进策略 | 系统梳理了测温误差来源，对提升实验可靠性有指导意义。 | <details><summary>展开</summary>Intracellular luminescence thermometry has long promised to reveal how heat is generated, dissipated, and regulated inside living cells. Yet, despite substantial progress, the field remains shaped by disagreement over the magnitude and physical plausibility of reported intracellular temperature gradients. In this manuscript, we discuss luminescence thermometry as a powerful approach for probing temperature at subcellular length scales, while emphasizing the experimental care required to make such measurements meaningful. After outlining the field's development, we outline the relevant heat-transfer concepts, before introducing luminescence thermometry and the performance metrics used to describe precision and accuracy. We then examine how thermometer design, intracellular localization, calibration, microscopy configuration, and data treatment influence the final thermal readout. Particular attention is given to two recurrent sources of error: bias, arising from measurement conditions and optical distortions, and cross-sensitivity, arising when the probe responds to parameters other than temperature, such as pH, viscosity, ionic strength, or biomolecular interactions. Finally, we outline practical directions for improving reproducibility, including multi-feature readouts, machine-learning-assisted analysis, and FAIR data practices, while suggesting future research directions.</details> |
| **[Best Practices for First-Principles Modeling of Amorphous Oxide Semiconductors: A Statistical Framework and Application to Zn-Sn-O](https://arxiv.org/abs/2607.08667v1)** | ⭐ 76/100 | 提出非晶氧化物半导体建模框架 | 方法论严谨，对非晶材料计算提供了重要参考。 | <details><summary>展开</summary>Ternary and quaternary amorphous oxide semiconductors have many properties that make them promising candidates for use in electronic applications like display, memory, and back end of line logic. However, finding the right material for a given application and optimizing its properties, deposition, and integration, requires a thorough understanding of the physics and chemistry at play. When properly carried out, first principles computations can play a crucial role in enhancing this understanding. In this work, we highlight several pitfalls often observed in research applying these computations, with the Zn-Sn-O system as an example. We show that a proper understanding of the fundamental differences between the physics of the crystalline and amorphous or disordered phases is crucial, as is a proper statistical sampling of structural models. For the Zn-Sn-O system we conclude that from a performance point of view, mobility and initial threshold voltage, it is a promising material class. However, our computed results show that a similar sensitivity to hydrogen induced doping may be present as in IGZO.</details> |
| **[Physical aging of glasses of an organic semiconductor](https://arxiv.org/abs/2607.08653v1)** | ⭐ 76/100 | 揭示TPD玻璃物理老化机制与稳定性提升 | 研究深入且方法严谨，对有机半导体器件稳定性有指导意义。 | <details><summary>展开</summary>All glasses, including organic semiconductor glasses, are non-equilibrium materials whose properties will change with time. This physical aging process is poorly understood for organic semiconductors, hindering the rational design of highly durable devices. In this study, we investigated the volume and enthalpy recovery processes in both thin films and bulk glasses of N,N'-Bis(3-methylphenyl)-N,N'-diphenylbenzidine (TPD). Our results revealed that volume recovery kinetics exhibit negligible dependence on film thickness for liquid-cooled TPD films between 400 nm and 100 nm. Additionally, the volume recovery process in TPD films was strongly coupled to the enthalpy recovery observed in bulk TPD glasses during annealing near the glass transition temperature. Remarkably, TPD films prepared by physical vapor deposition at room temperature demonstrated exceptional resistance to physical aging, with an aging rate approximately one order of magnitude lower than that of their liquid-cooled counterparts. These results not only enhance our understanding of the non-equilibrium dynamics in amorphous systems but also offer valuable insights for the design of next-generation organic devices with significantly improved stability and durability.</details> |

