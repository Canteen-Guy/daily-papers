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

## 2026-05-18

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Limitations of Debye-Waller lattice temperature extraction under electronic excitation](https://arxiv.org/abs/2605.15140v1)** | ⭐ 75/100 | 揭示电子激发下德拜温度变化对原子温度提取的影响 | 指出了超快衍射分析中的关键误差来源，具有理论指导意义 | <details><summary>展开</summary>Ultrafast diffraction is the cutting-edge technique to extract the atomic temperature at femtosecond timescales, and further related quantities - in particular, electron-phonon coupling strength at elevated electronic temperatures. The present work demonstrates limitations of such an analysis, emphasizing the importance of careful evaluation of the evolution of the Debye temperature. It is shown that, due to the sensitivity of the Debye-Waller analysis to this parameter, neglecting its changes under electronic excitation may lead to significant deviations of the atomic temperature extracted from its true values.</details> |
| **[Thermal expansion of FeWO$_4$ (Ferberite) and FeWO$_4$:Fe$_2$WO$_6$ (7:1): a comparative X-ray and neutron diffraction study](https://arxiv.org/abs/2605.14792v1)** | ⭐ 73/100 | 研究了铁钨矿及其复合物的热膨胀特性 | 实验方法严谨，数据详实，但创新性属于常规表征 | <details><summary>展开</summary>The thermal expansion of natural FeWO$_4$ (ferberite) and synthetic FeWO$_4$:Fe$_2$WO$_6$ (7:1) was investigated over the 2-1123 K temperature range combining single-crystal and powder X-ray diffraction together with neutron powder diffraction. High-precision lattice parameters were obtained for both samples. The temperature dependence of the unit-cell volume was analysed using physically based thermodynamic models, including the Kroll and Berman approaches as implemented in EoSFit7. All datasets are well reproduced within their respective temperature intervals. However, significant differences are observed between the behavior of ferberite and FeWO$_4$:Fe$_2$WO$_6$, which has a \~40% smaller thermal expansion coefficient and a reduced reference volume. Possible origins, including microstructural and phase-coexistence effects, are discussed. The results provide a comprehensive description of the thermal expansion behavior of FeWO$_4$ across a wide temperature range.</details> |
| **[Image Force Effects on Tunneling Currents in an STM -- I `Point charge in the Barrier Region' - Model](https://arxiv.org/abs/2605.14964v1)** | ⭐ 70/100 | 分析STM中镜像电荷对隧穿电流的影响 | 模型揭示了点电荷假设在STM中的局限性，理论严谨但应用有限。 | <details><summary>展开</summary>In a Scanning Tunneling Microscope (STM), when a tunneling electron treated as a point charge enters the barrier region between the tip and the sample, it induces image charges on the conducting surfaces, which modifies the shape of the potential barrier it sees. In this paper, the effect of the modification in the barrier potential due to these induced charges on the tunneling current density and currents in an STM,is studied as a function of the tip-sample distance $d$ and the Bias Potential $eV_b$. The image potential is found to reduce the height and the effective width of the potential barrier, leading to a huge increase in the tunneling current densities. This huge increase (by several order of magnitudes) is however unreasonable, prompting a revisit of the assumption that the electron in the barrier region is a point particle.</details> |

