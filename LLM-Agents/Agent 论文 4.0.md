# Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents
#ICLR2025 

- 细分领域：**提示注入攻击、后门攻击、记忆投毒、多阶段混合攻击、防御评测、安全基准**
- 聚焦**基于大语言模型（LLM）的智能体安全**，针对 LLM Agent 在系统提示、用户提示、工具调用、记忆检索全流程的安全漏洞，**构建统一的攻击与防御评测基准**， formalize（形式化）主流攻击方法并量化防御效果，填补 LLM Agent 安全评测体系空白。
# Towards Effective Offensive Security LLM Agents: Hyperparameter Tuning, LLM as a Judge, and a Lightweight CTF Benchmark
#AAAI2026 
#2026/3/14

- 细分领域：**网络安全攻防、CTF、漏洞利用、对抗性 Agent、自动化渗透测试、Agent 评测**
- 针对**LLM 攻防 Agent 在 CTF 场景下评测粗糙、超参数不明、基准缺失**的问题，提出**CTFJudge 细粒度评测、超参数优化、CTFTiny 轻量基准**，显著提升自动化网络攻防 Agent 的可靠性与可评估性。
# SAGA: A Security Architecture for Governing AI Agentic Systems
#NDSS2026 

- 细分领域：**AI Agent 治理、多 Agent 安全通信、身份认证、访问控制、权限管理、对抗防御**
- 针对多 LLM Agent 缺乏安全治理、身份混乱、通信不可控的问题，提出**SAGA 安全架构**，通过密码学令牌与用户策略实现细粒度、可扩展、可验证的 Agent 安全管控，几乎无性能损耗。
# ARuleCon: Agentic Security Rule Conversion
#www2026 
#2026/4/12

- 细分领域：**SIEM 安全规则、安全规则自动化转换、Agent 自动化、RAG 增强、安全检测逻辑一致性校验** 
- 针对企业 SIEM 安全规则无法跨平台迁移的痛点，提出**ARuleCon 自治 Agent 转换框架**，通过中间表示 + RAG + 执行校验实现高精度、全自动、逻辑等价的安全规则跨平台转换，性能远超普通 LLM。
# Safe Multi-Agent Reinforcement Learning via Distributional Safety Critic and Maximum Entropy Optimization
#2026/3/14 
#AAAI2026 

- 细分领域：**多智能体强化学习安全、分布鲁棒性、风险约束、最大熵探索、CVaR 尾风险约束**
- 针对多智能体强化学习探索不足、无法保证极端风险安全的问题，提出**基于分布代价评论家与最大熵的 WCMASAC 算法**，实现兼顾高回报、强探索、全程安全的 MARL，性能与安全性全面超越现有方法。
# FirmAgent: Leveraging Fuzzing to Assist LLM Agents with IoT Firmware Vulnerability Discovery
#NDSS2026 

- 细分领域：**IoT 固件安全、漏洞挖掘、模糊测试、LLM Agent、污点分析、PoC 自动生成**
- 针对 IoT 固件静态分析误报高、模糊测试漏报高的痛点，提出**模糊测试 + 双 LLM Agent 协同的 FirmAgent 系统**，实现高精度、全自动、可验证的固件漏洞挖掘。
# BadRobot: Jailbreaking Embodied LLM Agents in the Physical World
#ICLR2025 
#2025/1/23 

- 细分领域：**具身智能 Agent 越狱、物理世界攻击、多模态 LLM 安全、机器人安全、对抗提示攻击**
- 首次发现并验证**具身 LLM Agent 存在物理世界越狱风险**，提出 BadRobot 三位一体攻击，可让机器人在仿真与真实世界中执行伤人、破坏、偷拍等危险动作，主流具身框架全线失守，并给出针对性防御思路。
# How Contaminated Is Your Benchmark? Measuring Dataset Leakage in Large Language Models with Kernel Divergence
#ICML2025

- 细分领域：**LLM 数据集污染检测、数据泄露、成员推理攻击（MIA）、模型隐私安全、评测基准污染**
- 针对 LLM 评测集污染导致性能虚高的问题，提出**KDS 核散度分数**，通过微调前后嵌入核矩阵差异量化数据泄露，稳定、准确、通用，成为更可靠的基准污染检测工具。
