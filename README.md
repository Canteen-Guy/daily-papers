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

## 2026-09-07

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Machine learning-assisted design and explainable optimization of CdSnP2-based integrated solar-photodetector devices](https://arxiv.org/abs/2609.03642v1)** | ⭐ 78/100 | 利用ML优化CdSnP2太阳能电池与光电探测器性能 | 结合机器学习与SCAPS-1D实现器件性能显著提升，方法严谨且具有应用潜力。 | <details><summary>展开</summary>CdSnP2-based integrated solar cell-photodetector (SC-PD) devices employing CdS and CuGaSe2 (CGS) as the window and back surface field (BSF) layers, respectively are investigated using a hybrid machine learning (ML)-assisted SCAPS-1D framework. Device optimization is performed by varying the thickness, doping concentration, and defect density of individual layers. SCAPS-generated data are used to train six ML models and one deep learning model, with ensemble-based algorithms exhibiting the highest predictive accuracy. The ML-guided optimization identifies the n-CdS/p-CdSnP2 (CTP)/p+-CGS architecture as the optimum configuration among thirteen candidate structures. Incorporation of a 200 nm CGS BSF layer significantly enhances both photovoltaic and photodetection performance, increasing the efficiency from 20.67% to 32.69%, responsivity from 0.53 AW-1 to 0.72 AW-1, and detectivity from 2.51x1014 Jones to 1.78x1016 Jones. SHapley Additive exPlanations (SHAP) analysis reveales that band-offset engineering, particularly at the window/absorber and absorber/BSF interfaces, together with absorber properties, governs device performance. These findings demonstrate the potential of CdSnP2 and the proposed data-driven SCAPS-ML framework for the accelerated design of high-efficiency multifunctional optoelectronic devices.</details> |
| **[Strengthened Silicate Glasses by Residual Stress: Depth of Compression and Surface Flaws Stability Conditions](https://arxiv.org/abs/2609.04109v1)** | ⭐ 74/100 | 利用断裂力学评估强化玻璃表面裂纹稳定性。 | 方法严谨且具有实用价值，但创新性属于领域内优化。 | <details><summary>展开</summary>The application of silicate glasses in severe service environments requires a precise evaluation of structural strength under mechanical loads and surface tribological conditions. Because glass strength is governed by surface flaws and microcracks rather than being an intrinsic material property, residual surface compression fields, balanced by interior tensile zones, are widely implemented to inhibit flaw opening. Rather than relying on conventional allowable stress criteria to establish product acceptance, this study adopts a fracture mechanics framework based on the stress intensity factor KI and fundamental material limits: the critical stress intensity factor KIC for rapid fracture and the threshold stress intensity factor KIth for time-delayed static fatigue failure. Using the Weight Function Method (WFM), KI is evaluated across generic surface flaw depths for two-dimensional continuous (2D-Continuous) surface cracks subjected to non-uniform internal residual stress fields and external loads. Flaw stability criteria are established for both zero-risk and moderate-risk design methodologies. Finally, the interaction and superposition of externally applied mechanical and thermal stresses with internal residual stress fields are evaluated.</details> |
| **[Performance of Nanoring-based Transparent Conductors: a Computational Investigation](https://arxiv.org/abs/2609.03876v1)** | ⭐ 74/100 | 计算研究纳米环网络的导电与光学性能 | 通过计算模拟评估了纳米环电极的性能与退化机制 | <details><summary>展开</summary>Metallic nanoring networks can serve as promising flexible transparent electrodes. These materials are crucial components in a wide range of applications, including solar cells, touchscreens and displays. In this work, a computational investigation considers in detail (i) the electrical conductance and optical performance of nanoring networks and (ii) the breakdown of these networks due to electrical damage. The electrical resistance of both the nanorings and the contacts between the rings (junctions) is taken into account. In part (i), the effects of 5 parameters on the electrical sheet resistance and optical transparency are presented. It is shown that several parameter combinations achieve better performance in comparison to indium tin oxide, currently the most widely used transparent electrode. In part (ii), due to electrical damage, the nanoring systems display the formation of a crack, running parallel to the vertical terminals, where a voltage difference is applied. The network degradation is measured by its sheet resistance, and a universal effect is observed: networks with varying filling factors exhibit the same degradation profile.</details> |

