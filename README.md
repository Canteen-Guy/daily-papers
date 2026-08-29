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

## 2026-08-30

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Data-efficient crack quantification in lithium-ion cathodes using foundation model transfer](https://arxiv.org/abs/2608.27162v1)** | ⭐ 82/100 | 利用基础模型实现锂电池阴极裂纹高效定量分析 | 通过迁移学习解决微观图像标注瓶颈，方法创新且实用性强。 | <details><summary>展开</summary>Battery lifetime is central to sustainable electrification, yet the particle cracking that drives lithium-ion cathode aging is hard to measure: quantitative microscopy of this degradation is bottlenecked by annotation, because each destructive electron-microscopy cross-section spans hundreds of megapixels and pixel-level expert labelling requires hours per image. We show that a frozen self-supervised vision-transformer encoder, combined with a lightweight trainable decoder and iterative model-assisted annotation, turns this sparse labelling budget into population-scale degradation measurements. Applied to three 120-megapixel NMC cathode cross-sections representing initial, cycled-aged and calendar-aged states, the framework distinguishes intragranular cracks from early- and late-stage intergranular cracks and yields per-particle distributions of crack width, tortuosity and area fraction. Late intergranular crack coverage reaches 4.6% in the cycled sample versus 0.5% in the initial and calendar-aged samples, forming more tortuous, higher-coverage networks, consistent with degradation from repeated electrochemical cycling rather than elevated-temperature storage alone. A single destructive image yields the population-level statistics needed for lifetime-extending design, aging assessment and second-life decisions.</details> |
| **[Quantifying the effects of nickel on Earth's inner-core nucleation](https://arxiv.org/abs/2608.27139v1)** | ⭐ 82/100 | 揭示镍对地核成核过程的影响 | 通过原子模拟量化镍含量对地核成核的促进作用 | <details><summary>展开</summary>The formation of Earth's solid inner core marks a major transition in the thermal and chemical evolution of the deep Earth, yet its origin remains paradoxical, as initial nucleation appears to require unrealistically large undercooling in the outer core. Here, we use atomistic simulations to quantify how Ni affects this process under inner-core conditions. While Fe-Ni alloys preserve strong thermodynamic competition between the hcp and bcc phases, the bcc phase consistently forms smaller critical nuclei and has lower nucleation barriers than hcp. Increasing Ni content in the melts further lowers the nucleation barrier and shortens the nucleation waiting time. Local chemical fluctuations also strongly affect the macroscopic nucleation rate. Combining these effects, bcc nucleation in Fe80Ni20 reaches about 250 K of undercooling, approaching geophysical constraints. We demonstrate that Ni enrichment, bcc nucleation, and chemical heterogeneity substantially narrow the inner-core nucleation paradox.</details> |
| **[THz-induced phonomagnetism in diamagnetic quantum paraelectric KTaO$_3$](https://arxiv.org/abs/2608.27060v1)** | ⭐ 82/100 | THz脉冲诱导量子顺电体磁响应 | 实验设计巧妙，揭示了声子磁效应的新机制。 | <details><summary>展开</summary>The current efforts striving to develop new ways of data manipulation are aimed at ultrafast control of magnetization in magnetic materials, as well as at inducing magnetic moments in diamagnetics. We demonstrate that in the diamagnetic quantum paraelectric KTaO$_3$, the electric field of circularly polarized THz pulses with an amplitude of $\sim 300\,$kV/cm induces a transient magnetic-like response by resonantly exciting its degenerate soft polar phonon. This phonon-mediated response was measured using the THz pump---optical probe technique via the time-resolved magneto-optic Faraday effect. Our detection scheme was set up to cancel out the major part of the electro-optic Kerr effect which also usually significantly contributes to the transient response. The Kerr-effect-related signal was further suppressed by subtracting the experimental data related to oppositely circularly polarized THz radiation. Thus, we were able to unambiguously identify a temperature-dependent magnetic-like behavior of the KTaO$_3$ crystal manifested by the extracted Faraday rotation. We developed a theoretical model describing well quantitatively the measured curves of the transient Faraday effect signal. However, their amplitudes exhibit an unexpected temperature dependence, which might be a key to a deeper understanding of the observed phonomagnetic effect.</details> |
| **[Band's Geometry Origin of Quantum Spin Transport Phenomena](https://arxiv.org/abs/2608.27445v1)** | ⭐ 78/100 | 揭示费米面几何与自旋输运的内在联系 | 理论框架严谨且具有创新性，对自旋电子学有重要意义 | <details><summary>展开</summary>We develop a geometric description of spin-dependent transport based on the local geometric structure of electronic bands and the Fermi surfaces. For quasi-two-dimensional systems, we show that hyperbolic regions of constant-energy surfaces generate a geometrical contribution to the Fermi velocity that couples naturally to electron spin and produces a spin-current response. We further show that, in the presence of time-reversal symmetry, the algebra of spin operators can be related to the exterior algebra of the band's tangent space, providing an additional geometric interpretation of spin in momentum space. This framework motivates a symplectic description of spin-separated transport on Fermi surfaces and its extension to three-dimensional band manifolds through contact geometry. Our results establish a direct connection between Fermi-surface geometry and intrinsic spin transport.</details> |
| **[3D Cloud Component Analysis of Atomic Structures](https://arxiv.org/abs/2608.27304v1)** | ⭐ 78/100 | 提出一种基于密度场的原子结构三维组分分解方法 | 方法创新且实用，逻辑清晰，在材料分析领域具有应用价值。 | <details><summary>展开</summary>We present a method for decomposing atomic structures into physically meaningful components by converting discrete atomic coordinates into continuous three-dimensional density fields. Each element is represented by a Gaussian-smeared density map with values ranging from 0 to 1, computed efficiently through a bin-then-blur approach with periodic boundary conditions. The sum of all element densities, truncated at unity, defines the material region; its complement defines the vacuum. Every voxel is first assigned a chemical formula from the set of elements present above a threshold; the resulting formula map is then cleaned so that only regions with a genuine bulk interior-measured by the Euclidean distance to their own boundary-survive as components. Thin surface terminations (e.g., a Ga monolayer on GaAs) and one-to-two-voxel boundary layers between two crystals are absorbed by the neighboring stable region, so the decomposition contains exactly the bulk-like chemical-formula components and the vacuum, with no surface or interface components. For each component we determine the crystal phase with a neural prototype classifier: one phase if the trusted interior atoms vote unanimously, two phases (e.g., crystalline and amorphous Si) if they split into two confident groups, in which case the component is divided into two. Interfaces and surfaces are then derived as boundaries-material-material and material-vacuum-and every atom is labeled bulk, surface, interface, or vertex, with vertex reserved for geometric corners of a component. Inside crystalline components, inner defects are detected from coordination-number and local-density deviations. We demonstrate the approach on Si/GaAs and Si/SiO2 heterojunctions, crystalline/amorphous silicon junctions, vacancy-containing crystals, and bulk crystals.</details> |

