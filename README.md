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

## 2026-08-31

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Benchmarking of Fast and Interpretable UF Machine Learning Potentials](https://arxiv.org/abs/2608.27277v1)** | ⭐ 78/100 | 评估UF3势函数的精度与可解释性 | 该研究系统评估了UF3模型，方法严谨且具有实用价值。 | <details><summary>展开</summary>Machine learning interatomic potentials (MLIPs) have emerged as a powerful alternative to density functional theory (DFT) for molecular dynamics simulations, offering near-DFT accuracy at a fraction of the computational cost. However, many state-of-the-art MLIPs remain computationally demanding and act as black boxes, limiting physical interpretability. In this work, we evaluate the ultra-fast force field (UF$^3$) potential, which employs linear regression with cubic B-spline basis to represent effective two- and three-body interactions. We show that UF$^3$ displays accuracy comparable to established models such as GAP, MTP, NNP (Behler Parrinello), and qSNAP MLIPs. We further investigate the transferability of UF$^3$ by computing melting points for six elemental systems with potentials fitted without any solid-liquid interface configurations or explicit thermodynamic information about melting. The model reproduces experimental melting points within $\sim$6% for simple metals (Ni, Cu, Li), but substantially underestimates them for Mo and Si and fails to yield a stable potential for Ge, reflecting the limitations of a fixed expansion truncated at the three-body term for systems with strong angular or covalent bonding. We further illustrate how UF$^3$'s spline-based formulation allows direct visualization of the learned interactions, enabling identification of unphysical behavior that black-box approaches often obscure.</details> |
| **[Grain-Boundary Premelting in High-Entropy Transition Metal Carbides](https://arxiv.org/abs/2608.27273v1)** | ⭐ 78/100 | 揭示高熵碳化物晶界预熔化机制 | 利用机器学习势函数深入研究了晶界化学与预熔化的关系，方法严谨。 | <details><summary>展开</summary>Grain-boundary segregation and thermally induced interfacial disordering were investigated in four high-entropy transition metal carbides using Monte Carlo (MC) sampling and molecular dynamics (MD) with the universal MACE-OMAT-0 machine-learning interatomic potential. MC sampling segregated the group-VI element (Cr, Mo, or W) and Zr to grain boundaries, where the group-VI content reached approximately 45 at.%, consistent with STEM-EDS observations. During MD heating, the grain-boundary Lindemann index, a normalized measure of interatomic distance fluctuations, reached the liquid-like threshold of $δ=0.15$ near $1390^{\circ}\mathrm{C}$ for the Cr-containing carbides, $1660^{\circ}\mathrm{C}$ for Mo, and $1890^{\circ}\mathrm{C}$ for W, while the grain interiors remained below the threshold. A chemically random (Cr,Hf,Ta,Ti,Zr)C reference crossed about $60^{\circ}\mathrm{C}$ later and showed less boundary-localized disorder, highlighting the role of interfacial chemistry in premelting. Species-resolved displacements showed enhanced grain-boundary mobility, particularly for carbon. Overall, Cr-rich interfaces showed the earliest and most extensive premelting-like response, followed by Mo- and W-containing boundaries.</details> |
| **[Multi-orbital physics in inverse Lieb lattice altermagnets](https://arxiv.org/abs/2608.27200v1)** | ⭐ 78/100 | 揭示反Lieb晶格反铁磁的多轨道物理机制 | 通过多轨道模型深入解析了反铁磁态的稳定性与拓扑性质 | <details><summary>展开</summary>The inverse Lieb lattice has recently emerged as a promising platform for altermagnetism, with several materials with this structure proposed as $d$-wave altermagnetic candidates. Here, we develop a symmetry-based microscopic Hamiltonian for these materials that includes both sublattice and orbital degrees of freedom, going beyond the sublattice-only minimal models that have been extensively used to study such altermagnets. We apply these models to examine multi-orbital electron correlation physics in the vanadium oxychalcogenide family altermagnets, which contain dominant $xy$ and $xz/yz$ orbitals character at the Fermi level in the altermagnetic state. We demonstrate that $xy$ orbitals are crucial to stabilize the altermagnetic state observed within a single V$_2$O layer, and altermagnetic order in the $xz/yz$ orbitals is induced through Hund's coupling. Additionally, we show that these multi-orbital models reveal topological regimes in which topological edge states are naturally orbital selective.</details> |
| **[Influence of Many-Body Dipole-Dipole Interactions on Excitation Transfer in a Dense Gas](https://arxiv.org/abs/2608.27250v1)** | ⭐ 70/100 | 揭示高密度铷蒸气中多体偶极相互作用对激发转移的影响 | 研究了偶极激发转移的非线性密度依赖，理论分析合理但创新性中等。 | <details><summary>展开</summary>We study non-radiative dipole-dipole induced excitation transfer in dense Rb vapour. We show that density dependence of characteristic time of the excitation diffusion changes from linear to non-linear for high Rb density. It is attributed to the breakdown of binary collisions approach to the dipole-dipole excitation transfer. It is shown that the observed result can be qualitatively described if the mean free path is replaced by mean interatomic distance for the chracteristic diffusion length.</details> |

