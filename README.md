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

## 2026-06-08

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Resolving room temperature microscale fracture and plasticity of iron oxides along the cascade of iron ore reduction via nanoindentation and microcantilever bending](https://arxiv.org/abs/2606.06001v1)** | ⭐ 75/100 | 研究了铁氧化物在还原过程中的微观塑性与断裂行为。 | 实验设计严谨，为氢基直接还原工艺提供了重要的力学数据支持。 | <details><summary>展开</summary>Understanding the fundamental mechanical behaviour of iron oxide phases is essential for controlling attrition and fracture during iron ore reduction process, particularly in hydrogen-based direct reduction systems. This study investigates the room temperature plasticity and fracture behaviour of single-crystal hematite, magnetite, and Wustite using nanoindentation and micro-cantilever fracture testing. Hematite exhibited the highest hardness, H and elastic modulus, E (H=18.5 GPa, E=281 GPa), followed by magnetite (H=8.7 GPa, E=165 GPa) and Wustite (H=7.5 GPa, E=145 GPa), reflecting differences in slip activity along the iron oxide reduction sequence. Furthermore, fracture toughness was measured using notched microcantilevers for all three iron oxide phases, aligned along low index and high index crystallographic planes, respectively. For the low index-oriented case hematite showed increased fracture toughness owing to crack deviation and faceting while magnetite and Wustite exhibited single plane cleavage fracture. Distinct changes in the deformation behavior in terms of plasticity and cracking of the three iron oxides were evident from both methods. Further investigation of a magnetite-gangue interface, particularly relevant to low-concentration ores, revealed significantly reduced fracture toughness compared to the magnetite phase. Overall, these results provide a comprehensive set of mechanical properties of iron oxides with potential application in material models for predicting fracture and attrition during hydrogen-based direct reduction.</details> |
| **[Optical Signature of Moiré Superlattices Formed by Twisted SrTiO$_3$ Membranes](https://arxiv.org/abs/2606.06289v1)** | ⭐ 74/100 | 制备了大面积扭曲钛酸锶双层膜并发现其莫尔超晶格光学特征。 | 实验与理论结合较好，展示了氧化物莫尔界面的非线性光学与声子特性。 | <details><summary>展开</summary>Moiré superlattices formed at the interfaces of mismatched lattices have attracted significant interest over the past decade due to their large tunability of band parameters and interactions among electrons, spins, and lattices. Superlattices made from twisted perovskite oxides may have strong structure and potential modulation, but evidence of such modulation over macroscopic areas, particularly at large twisting angles, has not been clearly demonstrated so far. Here, we fabricated millimeter-scale twisted oxide bilayers at $36^\circ$ angle, close to the simple coincidence site lattice condition $\Sigma5$, from freestanding SrTiO$_3$ membranes. We discovered new low-frequency vibrational modes whose Raman activity, according to molecular dynamics simulations, is greatly enhanced by an asymmetric, twisted interface between the SrO and TiO$_2$ layers. Such an interface is energetically favorable from first-principles calculations and is corroborated by the observation of strong second harmonic generation from the interface comparable to that from the SrTiO$_3$ surface throughout the bilayer region. The results are consistent with interlayer coupling enhanced by high-temperature annealing and confirmed by cross-sectional scanning transmission electron microscopy imaging. Our work sheds light on the structural behavior of twisted oxides and provides directions for tuning their phononic and nonlinear optical properties in future studies.</details> |
| **[Coupled simulation of plasma-surface interactions during early stages of vacuum arcing](https://arxiv.org/abs/2606.05893v1)** | ⭐ 72/100 | 耦合分子动力学与等离子体模拟，揭示真空电弧热失控机制。 | 采用多物理场耦合方法，揭示了焦耳热及纳米颗粒辅助的两种热失控路径。 | <details><summary>展开</summary>We describe fully coupled simulations that bridge atomistic cathode dynamics and plasma formation during the earliest stages of vacuum arcing. The model combines molecular dynamics, finite element electrothermal calculations, electron emission and particle-in-cell plasma simulations via dynamic transfer of particles between the surface and plasma domains. Simulations of Cu nanoprotrusions reveal two routes to thermal runaway: direct Joule heating-driven instability and a novel nanoparticle-assisted mechanism, where detached nanoparticles generate neutral vapor that becomes ionized.</details> |
| **[Quantum Thermal Logic Gates](https://arxiv.org/abs/2606.06432v1)** | ⭐ 71/100 | 提出利用量子点热流实现量子热逻辑门的新概念。 | 概念新颖，将热流逻辑扩展至量子领域，理论推导严谨且具有实验可行性。 | <details><summary>展开</summary>We propose a new concept for quantum thermal logic gates -- analogous to classical electronic logic gates -- that exploit the heat current in a coupled quantum-dot system tunnel-coupled to metallic thermal reservoirs for logic operations in quantum circuits. We obtained a remarkable one-to-one correspondence with the structure of classical electronic logic gate circuits. An experimental setup is presented that demonstrates a realizable nano-electronic quantum circuit architecture for implementing such quantum thermal logic operations.</details> |
| **[PolyGraphPy: A unified Python framework for atomistic simulation and machine learning-driven polymer design](https://arxiv.org/abs/2606.06415v1)** | ⭐ 70/100 | 推出集成原子模拟与机器学习的聚合物设计Python框架。 | 整合DFTB计算与贝叶斯图神经网络，实现了聚合物的高效预测与生成设计。 | <details><summary>展开</summary>Polymers are indispensable materials with applications ranging from electronics to medicine owing to their versatility, which can be tailored by adjusting their chemical composition and architecture. The design space for these compounds is vast and governed by factors such as monomer classes, copolymer configurations (e.g., linear, branched, random, and alternating), chain size, stoichiometry, and material properties (e.g., density, refractive index, solubility, and Poisson's ratio). Exploring this space requires efficient computational methodologies for polymer science. To address this challenge, we introduce PolyGraphPy, an open-source Python framework that integrates atomistic simulations with machine learning for accurate property prediction and property-guided polymer design. The framework automates Density Functional Tight Binding calculations to efficiently construct structured datasets for monomers, homopolymers, and alternating copolymers. For property prediction, PolyGraphPy employs Bayesian Graph Neural Networks (GNNs) with stochastic graph representations to predict target properties, such as static polarizability, while providing robust uncertainty quantification. Furthermore, the platform incorporates two complementary generative models for the de novo design of targeted molecules: a SELFIES-based Generative Pretrained Transformer (GPT) and a Genetic Algorithm (GA) based on BRICS graph fragmentation. Demonstrated on a dataset of acrylates, PolyGraphPy provides a highly customizable end-to-end pipeline that reduces computational costs and accelerates data-driven polymer informatics.</details> |

