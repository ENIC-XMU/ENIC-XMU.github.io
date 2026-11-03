---
title: 课题组2篇论文被机器学习三大会NeurIPS'2026接收
date: 2026-09-25
tag: 论文发表
abstract: 祝贺课题组胡靖伟、陈佳松和朱彦同、石伟宁、李可羿、谢晓燕等同学在NeurIPS'2026上发表可重构电池网络和动态图表示学习相关工作！NeurIPS会议全称为Conference on Neural Information Processing Systems，在CCF学术推荐列表中被认定为A类会议。
---
&emsp;&emsp;祝贺课题组胡靖伟、陈佳松和朱彦同、石伟宁、李可羿、谢晓燕等同学在NeurIPS'2026上发表可重构电池网络和动态图表示学习相关工作！

&emsp;&emsp;NeurIPS会议全称为Conference on Neural Information Processing Systems，在CCF学术推荐列表中被认定为A类会议。NeurIPS'2026将于2026年12月6日至12日于澳大利亚悉尼召开。

---

- 论文标题：DGRAF: Observation-Quality-Aware Reinforcement Learning for Dynamic Reconfigurable Batteries
- 录用类型：NeurIPS 2026
- 论文作者：Jingwei Hu, Jiasong Chen, Zheng Fang, Zhihong Zhang*
- 完成单位：厦门大学

![DGRAF框架示意图](news/260925/diagram.png)

- 论文简介：动态可重构电池系统通过电力电子开关实现电池单元之间的灵活互联，这对电动汽车和储能系统至关重要。然而，在实际应用中，传感器故障会导致部分观测丢失，从而给安全控制带来严重挑战。现有能量控制方法大都假设状态完全可观测，在面对观测缺失时无法在不确定性下有效平衡安全性和性能。根本问题在于，这些方法缺乏根据推断可靠性自适应调整决策保守程度的机制，导致在复杂故障场景下决策不稳定。我们提出了一种名为扩散引导风险自适应框架来解决这一问题。该框架通过联合扩散推断与质量量化处理时空耦合的故障模式，并将推断质量与分布型决策相结合，实现对激进优化与保守维护之间自动调节的灵活控制。通过广泛的仿真和硬件实验，我们证明了提出模型在复杂故障模式下始终优于基线方法，实现了更高的能效、决策稳定性和风险韧性。

---

- 论文标题：WavCIL: Wavelet Coefficient-Domain Invariant Learning for Dynamic Graph OOD Generalization
- 录用类型：NeurIPS 2026, Main Track
- 论文作者：Yantong Zhu, Weining Shi, Keyi Li, Xiaoyan Xie, Yi Chang, Qinggang Zhang, Tianjiao Pu, Ji Qiao, Zhihong Zhang*
- 完成单位：厦门大学，中国电力科学研究院，吉林大学

![WavCIL框架示意图](news/260925/diagram_wavcil.png)

- 论文简介：动态图神经网络（DyGNNs）通过利用图结构和时序动态，在关键时间序列系统中展现出强大的表示能力。然而，现有的动态图模型常常受到由突发事件等复杂时变因素引发的不可预测分布偏移的影响，由于其分布外（OOD）泛化能力较低，导致性能严重下降。图不变学习已被广泛研究，旨在通过时域或谱域中的特征解耦来解决这一问题。尽管近期取得了进展，现有方法在实践中仍存在关键局限：基于时域的方法难以解耦在同一时段内高度重叠且相互纠缠的瞬态扰动与稳定模式；而基于谱域的方法虽试图通过全局傅里叶变换实现谱域解耦，但这类方法本质上会丢失时间定位信息，无法有效刻画由时变因素驱动的分布偏移。为此，本文提出小波系数域不变学习（WavCIL），这是一种通过在具有时频定位能力的小波系数域内进行解耦来解决分布偏移的新框架。具体而言，WavCIL由两个关键组件构成：（i）小波变换模块，利用一组小波基将输入时间信号映射到小波系数域，同时捕获频率分量并定位其发生时间；（ii）系数域不变学习模块，利用自适应掩码机制在系数域中将不受时变因素影响的稳定因果模式与由时变因素驱动的虚假模式解耦，引导预测过程更多地依赖因果模式。在多个基准数据集上的大量实验表明，WavCIL在处理分布偏移时达到了最先进的泛化性能。

# 供稿：胡靖伟，朱彦同
