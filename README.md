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

## 2026-10-12

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Multifunctional synaptic learning and neuromorphic computing using crystalline TiO$_x$/NiO$_x$ heterojunction-based memory devices](https://arxiv.org/abs/2610.11992v1)** | ⭐ 72/100 | 基于TiOx/NiOx异质结实现多功能突触学习与类脑计算。 | 异质结设计实现了无成形双极性开关，成功模拟多种突触功能并应用于MNIST识别。 | <details><summary>展开</summary>An attempt is made here to mimic different properties of biological synapses using Ag/TiO$_x$/NiO$_x$/p$^{++}$-Si memristor structure by studying its different transport properties under dc and pulsed bias. The presence of crystalline NiO$_x$ with smaller gains is found to be helpful to get TiO$_x$ deposited on its top with crystalline properties and larger grains. The heterostructure offers stable bipolar forming free non-volatile resistive switching characteristics under reverse biased condition with gradual set and reset features. These devices are also able to successfully implement the classical Pavlov's learning, study artificial nociceptor and Morse code detection. While incorporating synaptic weights derived from the measured conductance programming pulse relationship, an artificial neural network achieves nearly 95\% accuracy in MNIST digit recognition. In brief, NiO$_x$/TiO$_x$ heterojunction plays the pivotal role in getting such reproducible $I-V$ characteristics for mimicking different properties of biological synapses.</details> |
| **[The Stability of Rutile Oxides for Oxygen Evolution Catalysis: From Mechanistic Understanding to New Descriptors](https://arxiv.org/abs/2610.12297v1)** | ⭐ 70/100 | 通过电子结构描述符揭示金红石氧化物析氧催化稳定性。 | 该研究通过计算分析金属-氧键能，为提升催化剂稳定性提供新视角。 | <details><summary>展开</summary>Polymer electrolyte water electrolysis is considered as a pivotal technology for green hydrogen production. Iridium dioxide (IrO2) serves as the benchmark electrocatalyst for the anodic oxygen evolution reaction (OER) in these cells. However, the scarcity and cost of iridium drives efforts to find durable and cost-effective replacements or drastically reduce the iridium loading. While ruthenium dioxide (RuO2) offers comparable activity, its practical utility is impacted by its stability being inferior to IrO2. The presented computational study analyzes the metal-oxygen bond strengths in bulk IrO2 and RuO2 to provide insights into the electronic origins of their differing stabilities. Through a comparative analysis of the electronic structure of bulk rutile IrO2, RuO2, and selected MO2 systems, it is able to discriminate the covalent and ionic contributions to the metal-oxygen bond using crystal-orbital-derived electronic descriptors.</details> |
| **[Comprehensive study of massively overlapping cascades in common elemental metals](https://arxiv.org/abs/2610.11910v1)** | ⭐ 70/100 | 模拟21种金属的重叠级联碰撞，揭示势函数敏感性及缺陷演化。 | 覆盖面广，对比了多种势函数，对理解金属辐照损伤有重要参考价值。 | <details><summary>展开</summary>Massively overlapping cascades simulations were carried out in 21 elemental metals: Be, Al, Ti, V, Cr, Fe, Co, Ni, Cu, Zr, Nb, Mo, Rh, Pd, Ag, Hf, Ta, W, Pt, Au and Pb. These elements have simple FCC, BCC and HCP lattice structures. For each element, 2000 cumulative 5 keV cascades were simulated using molecular dynamics. The overlapping cascades were simulated using various classical analytical interatomic potentials as well as with machine-learning interatomic potentials for many of the elements. The general conclusion is that results from massively overlapping cascades simulations are very sensitive to the choice of interatomic potential across the periodic table. Furthermore, we see that FCC metals all form stacking fault tetrahedra due to irradiation, and also typically include interstitial type Shockley partial and Frank type dislocations. In BCC materials typically form interstitial 1/2$\langle$1 1 1$\rangle$ dislocations, but vacancy type 1/2$\langle$1 1 1$\rangle$ dislocations were also observed in V and Nb. HCP materials tend to form complex dislocation structures mainly consisting of a-type dislocations that can be of both vacancy or interstitial type. Correlations between saturated defect concentrations and fundamental underlying material properties are explored.</details> |

