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

## 2026-08-03

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[An iterative method bridging DFT, disorder averaging, and experiment in intercalated materials: application to Au-intercalated graphene](https://arxiv.org/abs/2607.28296v1)** | ⭐ 78/100 | 提出结合DFT与SCTMA的迭代法模拟插层石墨烯电子结构 | 方法论创新且与实验吻合度高，逻辑严谨，具有较好应用潜力。 | <details><summary>展开</summary>Intercalation can strongly modify the electronic dispersion of a host material, as directly revealed by angle-resolved photoemission spectroscopy (ARPES). We develop a general iterative method combining density functional theory (DFT), tight-binding (TB), disorder averaging within the self-consistent T-matrix approximation (SCTMA), and experiment, to construct an effective model of the intercalated system. DFT identifies the relevant microscopic degrees of freedom and constrains selected model parameters, while comparison of SCTMA calculations with experiment guides their further refinement. We apply this method to graphene intercalated with Au clusters and show that it reproduces the main ARPES signatures of the Au-cluster phase, including the broadening of the V12an Hove singularity and the emergence of kink-like features in the dispersion. The essential microscopic ingredients identified by the analysis are the hybridization between selected intercalant orbitals and the graphene states, together with an intercalation-induced local scattering potential.</details> |

