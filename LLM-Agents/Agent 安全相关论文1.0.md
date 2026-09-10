# Transferability of Adversarial Attacks in Video-based MLLMs: A Cross-modal Image-to-Video Approach
#AAAI2026第40届AAAI人工智能会议
#2026/1/20-1/27
#CCFA
#对抗样本迁移

研究对抗视频的跨模型迁移性，发现现有方法有三大缺陷,提出 I2V-MLLM 攻击：用图片模型当替身，结合多模态与时空信息，加扰动传播，生成能通用攻击各种视频模型的对抗样本。
# TWINFUZZ: Dual-Model Fuzzing for Robustness Generalization in Deep Learning
#AAAI2026第40届AAAI人工智能会议
#2026/1/20-1/27
#CCFA
#对抗攻击

现有对抗训练仅能防御已知攻击，面对未知攻击时效果大幅下降，而传统模糊测试缺乏专门提升泛化鲁棒性的指导指标。为此，本文提出双模型模糊测试框架 TWINFUZZ,解决深度学习模型在安全关键场景中的鲁棒性泛化不足问题。
# RBLJAN: Robust Byte-Label Joint Attention Network for Network Traffic Classification
#TDSC/IEEE/Transactions/on/Dependable/and/Secure/Computing
#CCFA 
#SCIQ1
#2024/10/11
#网络流量与加密安全

针对现有网络流量分类方法依赖人工特征、难以处理加密流量、对抗扰动鲁棒性差、识别速度慢等问题，提出一种”鲁棒字节 - 标签联合注意力网络 RBLJAN“，可同时支持包级别与流级别分类。
# BAZZAFL: Moving Fuzzing Campaigns Towards Bugs via Grouping Bug-Oriented Seeds
#TDSC/IEEE/Transactions/on/Dependable/and/Secure/Computing
#CCFA 
#SCIQ1
#2024/4/22
#漏洞发现

针对传统覆盖指导灰盒模糊测试仅关注代码覆盖率、难以有效挖掘多类型漏洞的问题，提出一种面向漏洞的种子分组模糊测试框架”BAZZAFL“。
# SHAPFUZZ: Efficient Fuzzing via Shapley-Guided Byte Selection
#NDSS2024
#CCFA 
#2024/2/26-3/1
#模糊测试
#漏洞发现 

针对现有模糊测试在字节选择上盲目变异、效率低下的问题，提出一种基于**夏普里值（Shapley Value）** 引导的高效模糊测试框架**SHAPFUZZ**。SHAPFUZZ 相比 AFL++、GreyOne、Angora、NEUZZ 等 10 种主流模糊器，边缘覆盖提升显著，多发现**20 个以上漏洞**与**6 个 CVE**，在 6 个主流程序最新版本中发现**11 个新漏洞**，其中 3 个已被厂商确认。
# LogoStyleFool: Vitiating Video Recognition Systems via Logo Style Transfer
#AAAI2024
#CCFA 
#视频对抗攻击

针对现有视频对抗攻击存在的全局风格迁移自然度差、基于补丁的强化学习搜索空间有限、难以实现有效定向攻击等问题，提出一种基于**Logo 风格迁移**的黑盒视频对抗攻击框架**LogoStyleFool**。
# Genos: General In-Network Unsupervised Intrusion Detection by Rule Extraction
#IEEE/INFOCOM/2024
#CCFA 
#无监督网络入侵检测系统
#2024/8/12

针对现有无监督网络入侵检测系统（A-NIDS）存在吞吐量低、可解释性差、更新开销大，以及现有网内智能方案仅支持监督模型、无法通用适配等问题，提出一种通用的网内无监督入侵检测框架**Genos**，通过规则提取实现各类无监督模型在可编程交换机上的高速部署。
# TFE-GNN: A Temporal Fusion Encoder Using Graph Neural Networks for Fine-grained Encrypted Traffic Classification
#WWW2023-The/ACM/Web/Conference
#CCFA
#网络流量与加密安全 

针对**细粒度加密流量分类**任务，提出的 TFE-GNN，解决传统方法依赖流统计特征、短流量不准、包头与载荷混用、字节关联挖掘不足等问题。
# StyleFool: Fooling Video Classification Systems via Style Transfer
#S&P2023（IEEE Symposium on Security and Privacy）
#CCFA
#基于风格迁移的视频黑盒对抗攻击方法
#2023/7/21

提出 **StyleFool**，一个**基于风格迁移的视频黑盒对抗攻击方法**，解决现有视频攻击查询量大、易被防御、不自然的问题。
# Path Transitions Tell More: Optimizing Fuzzing Schedules via Runtime Program States
#ICSE2022
#CCFA 
#模糊测试

提出 **Truzz**解决模糊测试（Fuzzing）里最头疼的两个效率问题**：

1. 很多输入卡在**校验检查（validation check）**，进不去真正的功能代码
2. 种子优先级乱排，算力浪费在没用的种子上
# SHAPFUZZ: Efficient Fuzzing via Shapley-Guided Byte Selection
#IJCAI2022
#CCFA 
#漏洞发现 
#模糊测试 

针对传统模糊测试方法在输入变异阶段存在的盲目性与效率瓶颈，SHAPFUZZ 提出了一种基于 Shapley 值的字节级贡献度量化框架，用以精准评估输入字节对新代码路径发现的边际贡献。该方法通过上下文多臂老虎机算法动态平衡高贡献度字节的优先变异与低选择频率字节的探索性变异，有效提升了模糊测试的路径覆盖效率与漏洞挖掘能力。
