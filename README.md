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

## 2026-07-26

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Visualization of Defect Electronic States in Layered Semiconductor CrSBr](https://arxiv.org/abs/2607.21301v1)** | ⭐ 78/100 | 利用STM揭示CrSBr中硫空位缺陷的电子态结构 | 结合STM实验与第一性原理计算，深入解析了材料缺陷特性。 | <details><summary>展开</summary>Chromium sulfur bromide (CrSBr) is a layered magnetic semiconducting material combining a rich magnetic phase diagram with axis-dependent electronic and optical properties. While defects in CrSBr have been shown to affect magnetic order and excitonic responses, their microscopic nature, atomic structure, and electronic properties are not yet fully understood. In this work, we use scanning tunneling microscopy/spectroscopy (STM/STS) to explore the structure and electronic signatures of two prominent defects in bulk CrSBr. Their structure reflects the symmetries of the underlying lattice, with electronic features near the valence band edge. By comparing experimental data with ab initio simulated STM images, we infer that a common defect corresponds to a b-axis-aligned double sulfur vacancy, in line with findings from a recent growth analysis study. This result advances our understanding of the role of intrinsic defects in shaping the electronic structure of CrSBr.</details> |
| **[Lifetime effects and satellites in the photoelectron spectrum of platinum metal](https://arxiv.org/abs/2607.21298v1)** | ⭐ 78/100 | 揭示铂金属光电子能谱的精细结构与多体效应 | 实验与理论结合紧密，为铂基材料研究提供基准 | <details><summary>展开</summary>This work presents a comprehensive investigation of the electronic structure and many-body photoemission effects in metallic platinum using reflection high-energy electron energy-loss spec- troscopy (RHEELS), soft X-ray photoelectron spectroscopy (SXPS), and hard X-ray photoelectron spectroscopy (HAXPES), supported by ab initio calculations. Shallow and deep core state spectra enable the systematic characterisation of intrinsic line-shape asymmetries and satellite structures. Correlation of photoelectron satellites with RHEELS loss features allows the assignment of inter- band transitions, surface and bulk plasmons, plasmonic overtones, and semi-core ionisation losses across the Pt spectrum. Several previously unresolved satellite features and spin-orbit splittings are identified and discussed. Comparison of experimental valence band spectra with orbital-projected densities of states calculated using ab initio density functional theory (DFT) and G0W0 approaches, with and without spin-orbit coupling, demonstrates the critical role of relativistic effects in reproducing the Pt valence electronic structure. Together, these results establish a unified, internally consistent spectroscopic reference for metallic platinum, providing a robust framework for interpreting photoelectron spectra of Pt-containing catalysts, electronic materials, and related 5d transition metal systems.</details> |
| **[Thermal Hall Resistivity as a Unifying Description of Phonon Thermal Hall Effect in Various Insulators](https://arxiv.org/abs/2607.21157v1)** | ⭐ 78/100 | 揭示声子热霍尔效应的统一描述 | 通过实验证实了热霍尔电阻率在绝缘体中的普适性 | <details><summary>展开</summary>A considerable phonon thermal Hall effect was recently discovered across a diverse collection of materials. To clarify this enigmatic thermal Hall response in various insulators, we investigate the doped Mott insulator La$_{5/3}$Sr$_{1/3}$NiO$_4$ as an example material system and reveal a characteristic phonon-dominated thermal Hall effect. As a sensitive probe of the transverse thermal response, the thermal Hall resistivity $w_{xy}$ exhibits an insulating-like temperature dependence $w_{xy}(T)$, a linear magnetic-field dependence $w_{xy}(H)$ near $H=0$, and a $T$-linear thermal Hall angle at low temperatures. The presence of similar phenomena across a series of insulators suggests that $w_{xy}$ serves as a unifying description of phonon thermal Hall effect, corroborated by an apparent correlation between the insulating-like $w_{xy}(T)$ and material's localized electronic state.</details> |
| **[Matrix-free phase-field modeling of fracture in micromechanical testing simulations of inelastic materials](https://arxiv.org/abs/2607.21150v1)** | ⭐ 78/100 | 提出矩阵无关相场断裂模拟方法 | 高效实现高阶有限元断裂模拟，计算性能优异 | <details><summary>展开</summary>Resolving steep damage gradients across diffuse cracks in the phase-field modeling of fracture favors the use of high-order finite elements, for which matrix-free methods can provide superior performance and scalability. Here, we implement the Peric &amp; Dettmer constitutive framework for visco-elastoplastic materials in an open source solid mechanics library supporting matrix-free operators for high-order finite elements with p-multigrid preconditioning on GPUs. We introduce a rheological fracture element assembled in series so that inelastic and fracture properties can appear to affect each other only at homogenization length scales. Numerical simulations of tensile and compressive tests are conducted for synthetic particle-matrix microstructures on an El Capitan high performance computing prototype. Results are shown to reproduce characteristic inelastic responses and crack propagation patterns.</details> |
| **[Magneto-Caloric effect and Multiple magnetic phases in Al doped Ni2MnSn0.75Al0.25 Heusler Alloys](https://arxiv.org/abs/2607.21181v1)** | ⭐ 74/100 | 研究了Al掺杂Ni2MnSn合金的磁热效应与磁相变 | 实验设计严谨，对复杂磁性状态的分析具有一定深度 | <details><summary>展开</summary>Among Heusler compounds,Ni based alloys have been extensively investigated because they exhibit desirable properties such as high Curie temperatures, which are advantageous for advanced magnetic and spintronic devices.The effect of Al substitution on the magnetic ground state of Ni2MnSn was investigated using the Ni2MnSn0.75Al0.25 Heusler alloy.Temperature-dependent magnetisation measurements identify a second-order paramagnetic to ferromagnetic transition at TC is 734K,followed by a first-order martensitic transformation near 263K,demonstrating strong magnetostructural coupling.Curie Weiss analysis yields a positive Weiss temperature theta CW is 746.4K and an effective magnetic moment of 6.82muB,confirming the predominance of ferromagnetic exchange interactions. The bifurcation between the ZFC and FCW magnetization curves,together with non saturating hysteretic M vs H loops, indicates the coexistence of competing ferromagnetic and antiferromagnetic interactions.Further magnetic investigations establish the formation of an interacting reentrant cluster glass state accompanied by an exchange-bias effect.The observed magnetic behavior is attributed to the modification of Mn Mn exchange interactions induced by Al substitution and the associated atomic disorder,resulting in a complex magnetic ground state.</details> |

