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

## 2026-07-12

## Condensed Matter Physics

| 标题 | 评分 | Gemini 摘要 | 评分理由 | 原始摘要 |
|------|------|-------------|----------|----------|
| **[Complex polar superstructure controlled thermal conductivity in ferroelectric PbTiO3/SrTiO3 superlattices](https://arxiv.org/abs/2607.08683v1)** | ⭐ 82/100 | 揭示极性超结构对热导率的调控机制 | 实验设计严谨，创新性地将拓扑结构与热输运结合 | <details><summary>展开</summary>Integrating epitaxial thin films of ferroelectric PbTiO3 and paraelectric SrTiO3 into artificially layered periodic superlattices provides a unique platform for tuning strain, depolarization, and interfacial/surface energies, thereby accessing a rich phase diagram of topological polar structures (skyrmions, vortices, merons, or sinusoidal waves) and superstructures (polar supercrystals). Here we show that the 3D arrangement of polar vortices in a supercrystal suppresses thermal conductivity (k) of PTO/STO superlattices (SLs). The temperature dependence of k reflects the evolution of the polar superstructure, as determined by X-ray diffraction and transmission electron microscopy. The comparison with other SLs suggests that the 3D arrangement is crucial for controlling thermal conductivity beyond the usual interfacial scattering. Moreover, we observed an unexpected reduction in thermal conductivity with increasing superlattice thickness, a phenomenon reminiscent of phonon-wave Anderson localization. Our results show that complex polar superstructures can be useful active elements for modulating heat transport in technologies where control over heat dissipation is critical.</details> |
| **[Triangulene-based diradicals as a blueprint for molecular quantum platforms with optical addressability and long spin coherence times](https://arxiv.org/abs/2607.08634v1)** | ⭐ 82/100 | 提出三角烯分子量子比特设计方案 | 理论严谨，为分子量子计算提供新颖设计思路。 | <details><summary>展开</summary>The identification of molecules that combine long spin coherence times and efficient spin-optical interfaces, ideally at room temperature, is pivotal towards the development of molecular quantum technology. By means of advanced first-principles methods, we here unravel the electronic structure for triangulene (1), its aza-cation derivative (2), and the crystal of 2,6,10-tri-tert-butyl-4,8,12-trimesityl-triangulene (3), and show that these organic diradicals possess a triplet ground state well separated from the first singlet excited state approaching 0.5 eV, closely resembling solid-state defects like nitrogen vacancy centers. In addition, we compute spin decoherence times due to the interaction with phonons and surrounding nuclear spins, showing that a deuterated molecule of 3 in a nuclear spin-free environment would support $T_2 = 0.21$ ms at 10 K. Importantly, we show that the engineering of specific low-energy vibrations could significantly improve $T_2$ toward the limit imposed by the molecular core spin relaxation, here estimated to be as long as $T_1=27$ ms at 300 K for 2. Finally, we compute two-phonon contributions to inter-system crossing at 300 K for2 as a luminescent prototype, and find that it is highly spin-selective, supporting the possibility to engineer optical read out and spin initialization. These results advance a unified first-principles theoretical foundation of spin decoherence and spin-selective excited-state processes and point to novel chemical design strategies for optically addressable, highly coherent molecular qubits.</details> |
| **[Heterostructuring as Gateway to Electron Doping of Nickelate Superconductors](https://arxiv.org/abs/2607.08553v1)** | ⭐ 82/100 | 利用异质结实现镍基超导体的电子掺杂 | 通过第一性原理提出新型掺杂路径，理论价值高 | <details><summary>展开</summary>Despite enormous expenditures in the research field, the electron-doped side of nickelate superconductors remains uncharted territory. Substituting the trivalent rare-earth cations by a tetravalent one hitherto failed. Here, we demonstrate by first-principles calculations a disorder-free route to electron dope Ruddlesden-Popper nickelates. When intercalating wide-band-gap insulating layers such as La$X$O$_3$ ($X$=Al, Ga, Sc) into La$_2$NiO$_4$, the extra (LaO)$^+$ layers act as electron donors, releasing carriers into the Ni-3$d$ orbitals. This electron doping puts La$_2$NiO$_4$:La$_2$AlO$_4$ naturally in the optimal region for $d_{x^2-y^2}$-wave superconductivity with T$_c$ exceeding 50 K. The same concept also allows us to electron dope La$_3$Ni$_2$O$_7$, the superconductor in the limelight.</details> |
| **[A crystal-field route to THz-driven magnetization](https://arxiv.org/abs/2607.08519v1)** | ⭐ 82/100 | 揭示晶体场激发作为THz光驱动磁化的新机制 | 实验设计严谨，发现了光角动量转化的新微观路径。 | <details><summary>展开</summary>Light carries angular momentum, but the microscopic pathways that transform it into magnetization remain elusive. Here we establish that crystal-field excitations, historically viewed primarily as equilibrium spectroscopic fingerprints of localized 4$f$ electrons, constitute an active microscopic route through which circularly-polarized terahertz (THz) light creates magnetic polarization. Using wavelength-selective ultrafast Faraday spectroscopy on the paramagnetic insulator CeF$_3$, we show that resonant excitation of localized 4$f$ crystal-field transitions generates a helicity-dependent magnetization that survives for up to about 100 ps. Most strikingly, while the optical helicity is held fixed, the THz-driven response reverses sign as the excitation wavelength is tuned across the crystal-field resonance. The resulting dispersive spectral response follows the crystal-field excitation spectrum rather than that of optical phonons, and is captured by resonant electronic theory of the inverse Faraday effect. Our results identify crystal-field excitations as a previously unrecognized dynamical reservoir for optical angular momentum and broaden the microscopic pathways through which THz light can create and manipulate magnetic states.</details> |
| **[Microwave Studies of Single Crystal TeO2 at Cryogenic Temperatures](https://arxiv.org/abs/2607.08668v1)** | ⭐ 78/100 | 表征TeO2低温微波介电性能 | 实验严谨，为低温微波应用提供重要参数。 | <details><summary>展开</summary>We use whispering-gallery-mode analysis to characterise the microwave dielectric properties of single-crystal TeO$_2$ at cryogenic temperatures and compare its loss performance with other low-loss dielectric materials. Finite-element modelling is combined with measurements at room temperature, 4 K, and 20 mK to develop accurate cryogenic simulations and extract the anisotropic dielectric permittivities, giving $\varepsilon_\parallel=25.75\pm0.08$ and $\varepsilon_\perp=20.90\pm0.07$. Loss measurements reveal quality factors as high as $9\times10^6$ and minimum loss tangents approaching $3\times10^{-8}$, placing TeO$_2$ among promising low-loss dielectrics for cryogenic microwave applications. Electron-spin-resonance spectroscopy further indicates a clean spin environment, while identifying distinct spin systems consistent with the known properties of the crystal.</details> |

