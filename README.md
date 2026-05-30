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

## 2026-05-31

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Carrier-coupled ultrafast structural dynamics and interlayer energy transport of supported transition metal dichalcogenide heterostructures](https://arxiv.org/abs/2605.30130v1)** | ⭐ 78/100 | 揭示了二维异质结的超快载流子耦合与界面热输运机制。 | 实验方法严谨，对二维材料界面动力学提供了深入见解。 | <details><summary>展开</summary>Understanding the electronic coupling and energy flow across layered two-dimensional heterostructures (HSs) is crucial to the exploitation of carrier and phonon transports as well as thermal management in next-generation optoelectronic devices. By using reflection ultrafast electron diffraction, we directly examine photoinduced out-of-plane structural dynamics of supported MoS2/WS2 bilayer HSs and their individual monolayers. Experimental evidence reveals the launch of ultrafast carrier-coupled intralayer atomic motions due to interlayer charge transfer across the van der Waals (vdW) heterojunctions that is absent for individual monolayers. Such a notable carrier-lattice correlation is in addition to the electronic coupling manifested in the enhanced optical absorption for HSs. Also, different pathways of energy flow as a result of carrier-phonon coupling and phonon scattering are reported with the corresponding characteristic times. On longer timescales, relaxation of thermalized atomic motions can be sufficiently described by a thermal transport model. A higher thermal boundary conductance (TBC) across MoS2/WS2 HSs is obtained compared to those at the monolayer-substrate interfaces; however, the similar TBC values suggest comparable couplings of phonons across vdW contacts. These results further shed light on the optical, phonon, and interfacial thermal properties of vertically-stacked vdW HSs.</details> |
| **[Charting the thermodynamic stability of hybrid perovskite alloys with machine learning](https://arxiv.org/abs/2605.30012v1)** | ⭐ 78/100 | 利用机器学习预测钙钛矿合金热力学稳定性 | 提出双层ML策略高效模拟复杂合金，方法严谨且具实用价值。 | <details><summary>展开</summary>Alloy-based perovskite solar cells offer tunable properties and improved stability, but their complexity has impeded accurate modeling, hindering development. We present a machine-learning (ML) accelerated atomistic modeling approach for the phase stability of (Cs/FA)Pb(Br/I)3 and (Cs/FA)Sn(Br/I)3 perovskites, with FA being formamidinium. To make such quaternary alloys tractable, we adopt a two-level ML strategy, combining 1) graph neural network interatomic potentials trained on density functional theory data for efficient structure relaxations with 2) secondary ML models for direct energy prediction from unrelaxed structures. These models enable computations of free energy landscapes across compositions and phases, capturing alloy disorder and FA molecular orientations. Our results reveal narrower stable composition regions for the Sn-based system compared to its Pb-based counterpart, limiting options for compositional engineering. Maximum stability occurs at high I content, and no stabilization is observed near the center of the composition space. Our results guide the design of stable perovskites.</details> |
| **[Stability Analysis of Superconductivity in $\textit{P6/mmm}$-LaSc$_2$H$_{24}$ and its Experimental Reproducibility from La-Sc Alloys](https://arxiv.org/abs/2605.29985v1)** | ⭐ 78/100 | LaSc2H24超导性稳定性与实验重现性分析 | 结合理论计算与实验验证，揭示了该材料合成的局限性。 | <details><summary>展开</summary>In this work, we analyze the feasibility of room-temperature superconductivity in the lanthanum-scandium hydride $\textit{P6/mmm}$-LaSc$_2$H$_{24}$. We demonstrate that the electron-phonon coupling calculations performed using the $σ$-broadening of the double $δ$-function at the Fermi surface lead to a very strong dependence of $\textit{T$_c$}(σ)$ on the arbitrary $σ$, whereas the tetrahedral method for the electron-phonon interaction is free from this drawback and leads to $\textit{T$_c$}$ &gt; 300 K at 300 GPa in agreement with previous predictions. By analyzing the stability of the metallic state of LaSc$_2$H$_{24}$ at 250-300 GPa, we show that this compound is at the edge of the stability region ($ξ$ = 0.54), similar to $\textit{fcc}$ LaH$_{10}$ at 140-150 GPa. Experimental attempts to synthesize LaSc$_2$H$_{24}$ at 250-280 GPa starting from the (La,Sc$_2$) alloy are unsuccessful and indicate the absence of even traces of superconductivity at 245-300 K in all the resulting La-Sc-H hydrides. The method for preparing the precursor by simultaneous deposition of La and Sc metals may be a key factor for the successful synthesis of LaSc$_2$H$_{24}$.</details> |

