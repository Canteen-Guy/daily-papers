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

## 2026-08-16

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Insight into SRF cavity performance from simulations of Nb's surface oxide dissolution and diffusion](https://arxiv.org/abs/2608.13540v1)** | ⭐ 78/100 | 模拟铌表面氧化层扩散对超导性能的影响 | 通过数值模拟建立了氧扩散与超导性能的微观联系，方法严谨。 | <details><summary>展开</summary>We report simulations of the dissolution and diffusion of Nb's surface oxide layer in vacuum. While this chemical doping process is important for the surface preparation of Nb superconducting radio frequency (SRF) cavities - common components of particle accelerators - quantitatively linking the resulting oxygen distributions to superconducting performance remains challenging. In this work, we simulate the reaction-diffusion process numerically for treatment temperatures $T = 50^{\circ}$C to $200^{\circ}$C and times $t = 0.5$ h to $120$ h, and calculate the effect of the spatially inhomogeneous oxygen doping on Nb's superconducting properties. We find that oxygen doping redistributes the Meissner screening current, reducing its value at the surface and shifting its maximum several nanometres into the material. These results provide a microscopic link between oxygen diffusion profiles and the electromagnetic response of Nb relevant for SRF cavity operation. This work provides a quantitative framework linking oxygen diffusion profiles to superconducting performance and establishes a foundation for future studies involving time-dependent and multi-step heat treatment protocols.</details> |
| **[Ultrafast Tracking of the Spallation Layer in Bulk Gold, Aluminum, and Steel](https://arxiv.org/abs/2608.13198v1)** | ⭐ 78/100 | 利用PPI技术实现超快激光剥离层的高精度追踪 | 结合PPR与PPI技术有效解决了金属剥离层追踪难题，方法严谨且具有工业应用价值。 | <details><summary>展开</summary>Extreme manufacturing with ultrashort-pulse (USP) lasers at the physical limit of precision and efficiency requires understanding ablation dynamics on the picosecond-to-nanosecond timescale. Pump-probe reflectometry (PPR) provides direct access to photomechanical spallation through Newton ring (NR) interference, but this signature vanishes when the spallation layer becomes optically opaque or the ablated material strongly attenuates the probe. Here, we combine PPR with phase-sensitive interferometric pump-probe (PPI) measurements to track the spallation layer in bulk steel, aluminum, and gold. PPI resolves the propagating layer even when the reflected probe signal is suppressed by &gt;95%. Joint PPR/PPI analysis with transfer-matrix modelling (TMM) yields spallation layer thickness, vapor layer absorption, and the layer disintegration times. These quantities are key determinants of the energy coupling of subsequent pulses in GHz burst processing.</details> |
| **[Magnetism in antiperovskite (Li$_2$\textit{M})\textit{Ch}O (\textit{M} = Fe, Mn, Co; \textit{Ch} = S, Se) diluted magnets with fixed 1/3 filling: the key role of magnetic anisotropy](https://arxiv.org/abs/2608.13111v1)** | ⭐ 75/100 | 研究反钙钛矿磁性稀释晶格的磁有序演化机制 | 系统研究了磁各向异性对稀释磁性反钙钛矿的影响 | <details><summary>展开</summary>We report the magnetic properties of a series of lithium-rich antiperovskites (Li$_2M$)$Ch$O ($M$ = Fe, Co, Mn and $Ch$ = Se, S) where transition metal and lithium ions are randomly distributed on the X-sites of the X$_3$BA structure, thereby forming a strongly diluted magnetic sublattice. Our study hence enables us to investigate the evolution of magnetic order at fixed 1/3-filling -- which is in the vicinity but slightly above the percolation threshold -- upon variation of the spin size, the magnetic anisotropy, and the orbital configuration. The data imply the absence of a distinct Curie-Weiss behavior up to 350~K but show rather large and weakly temperature-dependent magnetic susceptibility. We observe clear signatures of long-range antiferromagnetic order evolving in the 1/3-filled and strongly diluted magnetic X-site lattice with increasing Néel temperatures from $T_{\rm{N}}\simeq 30$~K in (Li$_2$Mn)$Ch$O to $\simeq 50$~K in (Li$_2$Fe)$Ch$O and $70-90$~K in (Li$_2$Co)$Ch$O. Except for $M$ = Co, the chalcogenide has no sizable effect on $T_{\rm N}$. We conclude significant magnetic coupling and short-range magnetic correlations at well above $T_{\rm N}$ which is in line with the observation of a broad electron spin resonance signal at room temperature. The actual ordering temperatures are strongly diminished by magnetic dilution. While structural parameters such as the tolerance factor and bonding angles do not strongly affect $T_{\rm N}$, a key parameter is the magnetic anisotropy of the transition metals.</details> |
| **[Micro- and nanoscale focusing across the XUV range of the ASTRID2 light source with a capillary optic](https://arxiv.org/abs/2608.13128v1)** | ⭐ 74/100 | 利用毛细管光学实现XUV光束微纳米聚焦 | 实验设计严谨，有效提升了同步辐射光束聚焦性能 | <details><summary>展开</summary>Focusing of synchrotron light across extreme ultraviolet (XUV) and soft X-ray regimes is increasingly desired for photoemission-based techniques where reduced beam width gives access to smaller samples such as microscopic single crystals and functioning two-dimensional (2D) heterostructures and devices. Many existing focusing methods, however, are not able to take full advantage of the synchrotron beam due to limited photon energy range or low transmission. Modern capillary optics have enabled achromatic, high transmission focusing of XUV and X-ray light. Here, we present a detailed characterisation of such an achromatic capillary optic installed at the AU-SGM4 beamline for spatial- and angle-resolved photoemission spectroscopy (ARPES) experiments at the ASTRID2 light source. The transmission of the capillary as a function of photon energy is given, and the dependence of the beam width, position, and transmission are measured against the source size. Analysis of the far-field image of the beam allows for slope errors on the inner surface of the capillary to be overcome by selectively aperturing the beam, resulting in a minimum beam width of 900 nm measured in a photoemission geometry.</details> |

