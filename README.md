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

## 2026-07-06

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Molecular interpretability of the bulk electrochemical impedance of concentrated electrolytes](https://arxiv.org/abs/2607.02316v1)** | ⭐ 78/100 | 提出基于IO模型的电解质阻抗解析方法 | 理论创新性强，通过分子动力学验证了模型的有效性。 | <details><summary>展开</summary>Electrochemical impedance spectroscopy (EIS) is a widely used technique to understand time-dependent response and relaxation under applied voltage. While these spectra contain a wealth of information, major gaps in our understanding can hinder our ability to interpret EIS spectra in terms of microscopic chemical mechanisms. We propose an alternative approach to common empirical fitting procedures for describing the contribution of the bulk electrolyte to the EIS spectrum. This new approach is rooted in determining the moments of the frequency-dependent conductivity, with molecular interpretability provided by a generalized Langevin equation description of an effective single particle dynamics; the `itinerant oscillator' (IO) model. In contrast to a Debye--Falkenhagen description, the IO model makes no assumptions regarding the concentration of the electrolyte, a fact we demonstrate by analysing molecular dynamics simulations of a room-temperature ionic liquid. By analysing the memory function from simulation within the framework provided by the IO model, we reveal the importance of capturing the separation of timescales within the memory function for describing the temperature dependent $β$-relaxation process. We go on to show how our impedance model directly reports on this distribution of timescales while retaining the simplicity of commonly employed workflows.</details> |
| **[From Bloch to Néel: Anisotropy-dependent Domain-Wall Character in FePd Thin Films](https://arxiv.org/abs/2607.02256v1)** | ⭐ 78/100 | 揭示FePd薄膜磁畴壁手性随深度的演变规律 | 实验设计严谨，深入探讨了结构有序度对磁畴壁的影响。 | <details><summary>展开</summary>We report an experimental investigation of the depth-dependent domain wall formation in L1$_0$-FePd thin films with high perpendicular magnetic anisotropy. Using circular dichroism X-ray resonant magnetic scattering (CD-XRMS) as a function of the incident X-ray angle, we explore the depth evolution of chiral spin textures in two samples with different strengths of magnetocrystalline anisotropy. Combined with CD-STXM, CD-ptychography, and macroscopic characterization of the structural order, magnetic properties, and surface morphology, we relate these observations to differences in the long-range order of the L1$_0$ phase of FePd. One FePd thin film with very high magnetocrystalline anisotropy, characterized by $Q_{PMA}=1.8$, exhibits an unexpectedly large Néel contribution. Angular-dependent CD-XRMS directly reveals a smooth transition from a hybrid Bloch-Néel chirality within the upper FePd layer towards a purely Néel-type structure at the lower FePd interface. In the second FePd sample, despite a still relatively large $Q_{PMA}=1.45$, the domain walls were found to be purely Néel type. These results indicate a crucial role of the long-range structural order in determining the formation of the magnetic structure.</details> |
| **[Efficient Large-Scale STEM-EELS Simulations With Torched-TACAW](https://arxiv.org/abs/2607.02236v1)** | ⭐ 78/100 | 提出torched-TACAW以高效模拟STEM-EELS | 方法创新且实用，显著提升了大规模电子能量损失谱模拟效率。 | <details><summary>展开</summary>The time auto-correlation of auxiliary wave functions (TACAW) method enables efficient simulations of ultra-low-loss electron energy loss spectra (EELS) arising from vibrational and magnon excitations. In practical applications to realistic materials systems, however, TACAW calculations become challenging due to the large system sizes required for models containing defects, interfaces, impurities, or grain boundaries, as well as the substantial computational cost and data throughput associated with molecular dynamics and multislice calculations. Here we discuss a practical methodology for large-scale TACAW simulations and present torched-TACAW, a freely available implementation of the TACAW part of the described workflow for efficient STEM-EELS simulations. The overall approach combines molecular dynamics based on foundational machine-learned interatomic potentials, partitioning of elongated supercells, and on-the-fly processing of multislice outputs in order to enable near ab initio quality simulations with tractable memory use and data flow. Using rutile TiO2 as a model system, we analyze important numerical aspects of the method, including windowing and supercell partitioning, and demonstrate atomic-resolution STEM-EELS simulations for thick samples.</details> |
| **[Coherent two-dimensional electronic spectroscopy integrated with confocal back focal plane microscopy](https://arxiv.org/abs/2607.02178v1)** | ⭐ 78/100 | 集成共聚焦显微的二维电子光谱技术 | 该技术有效结合了光谱与显微成像，实验设计严谨且实用。 | <details><summary>展开</summary>We introduce a setup for coherent two-dimensional electronic spectroscopy in the pump-probe reflection geometry that is integrated with a confocal back focal plane imaging microscope. The angle-resolved capability is utilized to control pump and probe wavevectors, while real space imaging enables co-localization of the collection spots for linear and ultrafast experiments. Compression of pulses down to 20 fs is achieved. We demonstrate the capabilities of this approach on an exfoliated WSe$_2$ monolayer on Si/SiO$_2$. The setup is suited to investigate excitons and exciton-polaritons in 2D Materials and their heterostructures.</details> |
| **[Bottlenecks in Hamiltonian-Adaptive Resolution Simulation Method for Modeling Interfaces](https://arxiv.org/abs/2607.02415v1)** | ⭐ 74/100 | 分析H-AdResS模拟中的热浴与静电模型瓶颈 | 深入探讨了H-AdResS在界面模拟中的局限与参数选择，具有实用价值。 | <details><summary>展开</summary>The Hamiltonian-Adaptive Resolution Simulation (H-AdResS) method allows to combine atomistic and particle-based coarse-grained models in a single simulation box, which makes it very attractive to model systems containing interfaces or reactive regions surrounded by an interacting environment. In our previous work [arXiv:2604.21867], we implemented H-AdResS in LAMMPS 2023 and extended its use to interfaces, focusing on MOF/CO$_2$ interfaces as an example. We found that, despite its advantages, using this method properly for this kind of systems is not trivial. In this work, an in-depth analysis of the impact of the choice of thermostatting schemes and long-range electrostatics models is presented. Even though its Hamiltonian formulation enables performing H-AdResS simulations within constant temperatures ensembles, not every thermostat is appropriate. We demonstrate that Langevin thermostat is a reliable choice for this method, while Nosé-Hoover results in artifacts. In addition, we show that using short-range models such as the Damped Shifted Force method for electrostatics, a popular choice for H-AdResS simulations, can lead to non-physical results when modeling interfaces. The need of capping strategies to deal with discontinuities in forces and energies arising from abrupt changes in resolution is also discussed. Finally, the impossibility of changing the definition of the H-AdResS Hamiltonian to include a gradual interpolation of the bonded degrees of freedom is discussed. We hope that this contribution helps the reader to appropriately set up H-AdResS simulations and to assess if this method can be used to accurately model their system of interest.</details> |

