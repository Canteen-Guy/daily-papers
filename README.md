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

## 2026-10-25

## Topological Photonics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Confinement of hybridized light modes in nonlinear-optical superpotentials](https://arxiv.org/abs/2610.31643v1)** | ⭐ 82/100 | 利用超势实现非线性光学模式的受限捕获 | 理论创新性强，结合超对称量子力学，应用前景明确。 | <details><summary>展开</summary>In this work, we present a spatial and temporal light trapping mechanism induced by coherent frequency conversion. We consider a wave-mixing process, where a pumped nonlinearity mediates a frequency-domain beamsplitter interaction between two signal modes. When these wave modes are counterpropagating, temporally trapped eigenmodes emerge at the zero of the nonlinearity profile. We establish that such spatio-temporal trapping has a direct connection to supersymmetric quantum mechanics, which ensures the existence and robustness of the trapped modes and allows us to derive analytic solutions of the bound eigenmodes. Backwards sum-frequency conversion may thus enable a unique class of active photonic memory devices, whose design parameters are compatible with the state of the art in integrated nonlinear photonics. We propose proof-of-principle experiments to study this nonlinear-optical trapping effect on thin-film lithium niobate. In addition, as a case study, we show how the temporal trap can be used alongside parametric gain. Our work unveils potential applications ranging from classical integrated photonics to multimode quantum nonlinear photonics.</details> |

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Screening strongly correlated materials in solid oxide cells with quantum simulation](https://arxiv.org/abs/2610.31591v1)** | ⭐ 82/100 | 提出量子计算筛选固体氧化物电池材料框架 | 结合量子模拟与宏观工程指标，具有极高应用价值。 | <details><summary>展开</summary>We develop an end-to-end framework for assessing a quantum-computing application in industrial materials science: the screening of strongly correlated oxygen-electrode materials for SOFCs and SOECs. We formulate the materials problem in terms of interface observables including oxygen-vacancy formation energies, vacancy migration barriers, and electronic conductivity. We describe how these observables can be obtained using a diagrammatic GW-based embedding, either GW+DMFT or self-energy embedding theory (SEET), applied to a DFT-screened shortlist. The atomistic electrode/electrolyte interface defines the electronic structure problem from which the correlated impurity models are constructed. Quantum impurity solvers would provide the finite-temperature impurity Green's functions required by the embedding. The computational challenges that classical solvers may encounter as the interacting active space grows, together with the polynomial scaling of quantum Hamiltonian simulation for efficiently represented discretized models, open an opportunity for quantum advantage. We identify the benchmarks needed to assess this opportunity through convergence of vacancy and migration energetics and comparison with the best applicable classical solvers. We provide illustrative logical qubit counts and identify the thermal state preparation, simulation, measurement, and repeated-solve costs needed for a complete resource assessment. We connect microscopic observables to macroscopic engineering metrics using a continuum model for mixed ionic--electronic conducting oxygen electrodes that couples oxygen surface exchange, solid-state oxygen transport, electrode microstructure, and finite electrode thickness. Finally, we estimate the potential worldwide business value of improved electrode materials under SOFC and SOEC deployment scenarios informed by public technical targets and electrolyser deployment data.</details> |
| **[Occupancy Driven Phase Transitions in Gapped Systems](https://arxiv.org/abs/2610.31564v1)** | ⭐ 78/100 | 提出激发态占据驱动的相变机制 | 理论新颖且解释了复杂材料的相变行为 | <details><summary>展开</summary>Systems characterized by an energy gap between the ground state and excited states support a growing number of thermal excitations upon raising the temperature. Provided these excitations interact with each other, their number affects the size of the energy gap akin to a harmonic oscillator where the oscillation frequency is damping dependent. Here we show that once a critical number of excitations is reached, the excitation population becomes thermodynamically unstable and the system transitions between two states. This transition is marked by a divergence in the specific heat, which does not have to be accompanied by an order parameter, nor by the full closure of the gap. We illustrate the thermodynamics using a simple two level system and superfluid $^4$He as examples, and we argue that the hidden order transition in URu$_2$Si$_2$ is an example of such an occupancy driven transition in the absence of an order parameter.</details> |
| **[Mn-deficient Ni-Mn-Ga alloys: phase transitions, magnetic properties, and disappearance of martensitic transformation](https://arxiv.org/abs/2610.31206v1)** | ⭐ 74/100 | 利用成分梯度研究Ni-Mn-Ga合金相变与磁性 | 实验方法创新，系统揭示了电子浓度对相变的影响。 | <details><summary>展开</summary>Composition gradients formed during directional solidification are generally considered undesirable in Ni-Mn-Ga magnetic shape-memory alloys. However, these gradients offer a highly effective platform for systematically investigating composition-property relationships under identical growth and heat-treatment conditions. To exploit this approach, one Mn-deficient and two near-stoichiometric Ni-Mn-Ga oligocrystals were grown by optical zone remelting and characterized by X-ray fluorescence mapping, optical microscopy, X-ray diffraction, low-field magnetic measurements, and vibrating-sample magnetometry. The ingots contained elongated grains and axial compositional gradients, primarily associated with the redistribution of Mn and Ga, whereas Ni remained relatively uniformly distributed. The martensitic and premartensitic transformation temperatures generally increased with increasing Mn content. Neither transformation was detected between 10 and 400 K in specimens containing 20.5-22.0 at.% Mn, all of which had $e/a &lt; 7.40$. In contrast, both transformations were observed in the investigated specimens containing at least 22.1 at.% ($e/a \geq 7.46$). This abrupt change may indicate a possible electron-concentration threshold for the occurrence of these transformations. Saturation magnetization increased with Mn content up to 25.8 at.%, reaching 96.9 A m$^2$/kg at 10 K and 71.2 A m$^2$/kg at 300 K. Post-growth annealing increased the transition temperatures and changed the low-field magnetic response. The results indicate that composition-gradient oligocrystals serve as an effective platform for investigating the relationships between composition, structure, and magnetic properties in Ni-Mn-Ga alloys with the same processing history.</details> |

