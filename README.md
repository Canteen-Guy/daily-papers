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

## 2026-07-20

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Plug Flow and Cavitation in Rough Lubricated Contacts: Molecular Dynamics of Single- vs. Two-Component Fluids](https://arxiv.org/abs/2607.15008v1)** | ⭐ 78/100 | 揭示粗糙接触下流体空化与润滑机制 | 分子动力学模拟深入分析了润滑流体动力学，方法严谨且具有应用价值。 | <details><summary>展开</summary>We present non-equilibrium molecular dynamics simulations of lubricated sliding between rough, deformable surfaces under conditions representative of boundary and mixed lubrication. One aim is to reduce the gap between highly idealized simulations of smooth interfaces and real, rough, load-bearing contacts. Another aim is to determine whether favorable tribological properties of two-fluid lubrication reported for solvated hydrophilic-hydrophobic polymer-brush interfaces can also be realized in rough contacts without brushes. To this end, we compare aqueous (water), hydrocarbon ($n$-dodecane), which has a similar equilibrium viscosity to water at ambient conditions, and immiscible two-fluid lubrication under identical geometric conditions. For the single-component lubricants, the simulations reproduce established trends: Water shows stronger speed dependence but reduced load-bearing capacity than $n$-dodecane, despite their similar ambient viscosities. Beyond this expected behavior, the simulations reveal that the combination of strong confinement and large height gradients can cause plug flow and cavitation after asperity collisions. For a high-surface-tension liquid like water, cavitation provides a mechanism for abrupt shear-stress release observable on scales much exceeding the size of the cavity. The mixed lubricant exhibits the lowest friction and material transfer, while maintaining plug flow to the lowest sliding velocity. It is also the only system in which folding lips form, occasionally developing into transient wear particles at high speeds.</details> |
| **[Local magnetic correlations and light-sensitive centers in the Cr2AlC MAX phase](https://arxiv.org/abs/2607.15110v1)** | ⭐ 76/100 | 揭示Cr2AlC的磁性特征及光敏中心机制 | 结合实验与理论深入分析了MAX相的局部磁性，严谨且具有参考价值。 | <details><summary>展开</summary>Cr2AlC MAX phase is synthesized by high-pressure solid-state annealing and investigated as a candidate platform for optically responsive magnetism. Structural characterization confirms the formation of the Cr2AlC phase, while magnetic and optical-magnetic properties are examined by superconducting quantum interference device (SQUID) magnetometry, electron spin resonance (ESR), and first principles calculations. SQUID magnetometry identifies Cr 2AlC as a weak, field-linear metallic paramagnet dominated by Pauli-like susceptibility of itinerant Cr-derived states. Its non-monotonic temperature dependence is described by an additional contribution from antiferromagnetically coupled Cr-Cr dimers, whereas the low-temperature Curie-like upturn originates from only a trace population of localized Cr centers. Under red-light illumination, SQUID magnetometry does not reveal an intrinsic macroscopic optomagnetic response. In contrast, ESR at 4 K shows a reversible light-induced reduction of a local magnetic signal, but the optically modified spin population corresponds only to several tens of ppm of the Cr sublattice. Ab initio Bethe-Salpeter equation (ai-BSE) calculations combined with the maximally localized Wannier function analysis suggest that optical excitation can redistribute spin polarization between neighboring Cr sites with the opposite local moments. The combined experiment-theory approach therefore establishes the hierarchy of magnetic contributions in Cr 2AlC and identifies the microscopic origin of its local optical sensitivity. This provides a reference for designing MAX phases and related MXenes in which defects, surface terminations or reduced dimensionality may enhance optically active magnetic states.</details> |

