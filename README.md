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

## 2026-07-05

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Plaid-Like Spin Splitting and Chirality of Magnon Bands in Antiferromagnetic MnTe$_2$](https://arxiv.org/abs/2607.02114v1)** | ⭐ 88/100 | 揭示MnTe2反铁磁体中手性磁振子带与交错磁性特征 | 结合拉曼光谱与DFT计算，实验证实了新型交错磁性材料的磁振子特性。 | <details><summary>展开</summary>Altermagnets constitute an emerging class of magnetic materials that combine compensated antiferromagnetic order with spin-split excitations arising from crystalline symmetries. Despite strong theoretical interest, their experimental identification remains challenging. Here, we demonstrate that helicity- and angle-resolved Raman scattering measurements reveal reduced rotational symmetries of magnons and a pronounced imbalance between left- and right-circular polarization channels, indicating momentum-dependent magnon handedness. First-principles DFT+$U$ calculations combined with linear spin-wave theory uncover a characteristic plaid-like spin-splitting structure in momentum space. The resulting magnon spin textures are dictated by the unconventional sublattice symmetries of MnTe$_2$ and closely emulate those of altermagnetic electronic bands. Our work provides evidence of chiral spin-wave excitations unique to this non-coplanar antiferromagnet.</details> |
| **[Interfacial Strain and Structural Defects Govern the Performance of Tantalum Superconducting Waveguide Resonators](https://arxiv.org/abs/2607.02238v1)** | ⭐ 82/100 | 揭示界面应变与缺陷对钽超导谐振器性能的影响 | 实验详尽，深入探究了界面工程对量子电路性能的优化机制。 | <details><summary>展开</summary>Tantalum (Ta) is a promising material for reaching long coherence times in superconducting qubits. A detailed understanding of the underlying structure-property relationship remains elusive though. In the present study, we sputter-deposited 200 nm thick Ta films on high-resistivity silicon (100) substrates at temperatures ranging from T = 20°C to 600°C, as well as on different seed layers (Nb, TiN and TaN). Alpha-Ta thin films were readily obtained at temperatures above 500°C and on all seed layers. The films were characterized in terms of surface morphology, residual-resistance ratio, crystal phase composition and superconducting transition temperature, as well as RF-performance using coplanar waveguide resonators. Internal quality factors of up to 1.5 million were measured at 100 mK in the single-photon regime. Despite similar bulk material properties, alpha-Ta films on different seed layers exhibit markedly different RF-performance, which we attribute to dissimilar strain and structural defects at the substrate-metal interfaces. Williamson-Hall analysis of XRD data reveals a clear correlation between decreasing microstrain and increasing quality factor. Cross-sectional HR-TEM further supports this interpretation by directly resolving interfacial disorder. Our results highlight the critical role of interface engineering in optimizing superconducting thin films for low-loss quantum computing circuitry.</details> |
| **[Electrical transport in ultra-thin films: from Fuchs-Sondheimer to quantum-confinement](https://arxiv.org/abs/2607.02120v1)** | ⭐ 82/100 | 综述超薄膜电输运的量子限域效应 | 系统梳理了从经典到量子限域的输运机制，理论深度与实用价值兼备。 | <details><summary>展开</summary>Ultra-thin films are fundamental components of modern nanoelectronics, where reducing thickness to the few-nanometer scale leads to a dramatic increase in electrical resistivity. For decades, this behavior has been interpreted in terms of classical size effects, primarily surface scattering within the Fuchs--Sondheimer theory and grain-boundary scattering in the Mayadas--Shatzkes model. While these approaches successfully describe transport when the film thickness is comparable to the electronic mean free path, growing experimental evidence indicates that they become insufficient under extreme confinement. This review discusses the crossover from classical scattering to a quantum-confinement regime in which the electronic states available for transport are fundamentally restructured by finite size. We review the recently proposed reciprocal-space confinement theory, which predicts an exponential increase of resistivity with decreasing thickness at the nanoscale, and discuss how it can be combined with classical surface-scattering models to provide a unified description of ultra-thin metallic and semiconducting films. Finally, we summarize recent experimental evidence supporting this picture and discuss its implications for future nanoelectronic devices, nanoscale interconnects, and quantum transport under extreme spatial confinement.</details> |
| **[Anisotropic nanoscale coherent polariton transport in CrSBr](https://arxiv.org/abs/2607.02071v1)** | ⭐ 82/100 | 揭示CrSBr中各向异性极化子输运特性 | 结合阴极荧光技术实现纳米级极化子输运表征 | <details><summary>展开</summary>In a combined experimental and theoretical study, we demonstrate anisotropic polariton transport on the nanoscale in the van der Waals antiferromagnet CrSBr. While effective cavity-polariton formation emerges via the self-hybridization of ultra-high oscillator strength excitons with a thin slab photonic mode, the absence of external mirrors facilitates spectroscopic investigation of these polaritons via cathodoluminescence (CL) on length scales determined by the electron wavelength. This direct access allows us to perform precise charting of the polariton landscape with nanometric resolution, and to probe polariton interference phenomena. The main finding of the work highlights that the coherent polariton transport follows the $C_{2v}$ symmetry of CrSBr, allowing exclusive transport along the crystallographic a-axis, while no coherent feature is found along the b-axis direction. Our work sets the foundation to use CL spectroscopy in cavity-polaritonics in more advanced landscapes, such as photonic crystals or optical lattices, and establishes the technique as a powerful tool to probe anisotropic expansion and relaxation phenomena on the nanoscale</details> |
| **[Intrinsic orbital Hall effect in a nonuniform electric field](https://arxiv.org/abs/2607.02418v1)** | ⭐ 78/100 | 揭示非均匀电场下轨道霍尔效应的几何机制 | 理论框架严谨，建立了轨道输运与量子几何的联系 | <details><summary>展开</summary>Geometric analysis of electronic Bloch states offers a universal framework for understanding electronic properties, yet its role in the transport of orbital angular momentum remains unexplored. In this work, we establish an analytic connection between orbital angular momentum transport and the geometric properties of Bloch wave functions in electronic systems. Focusing on the intrinsic orbital Hall effect in the dc limit under a spatially nonuniform electric field, we show that its conductivity can be expressed in terms of universal geometric quantities, such as the orbital Berry curvature and quantum metric. This formulation provides a term-by-term correspondence with the geometric description of intrinsic charge Hall transport established in previous studies. Using a tight-binding model, we further illustrate that the higher-order orbital Hall response can exhibit enhanced sensitivity to the orientation of an anisotropic sample. Our work deepens the understanding of diverse intrinsic transverse transport phenomena and the role of quantum geometry in electronic systems.</details> |

