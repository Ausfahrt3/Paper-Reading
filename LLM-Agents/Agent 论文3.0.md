# The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies
#综述
#ACM_CSUR
#2025/10/9

- 核心细分领域：**LLM Agent 安全与隐私综述（含攻击分类 + 防御方案）**
- 具体覆盖子方向：
    1. Agent 越狱（Jailbreaking）
    2. 提示注入攻击（Prompt Injection）
    3. 后门攻击（Backdoor Attack）
    4. 知识 / 内存投毒（Knowledge/Memory Poisoning）
    5. 数据窃取与隐私泄露（Data Extraction & Privacy Leakage）
    6. 功能操纵攻击（Functional Manipulation）
    7. 多 Agent 系统安全
    8. 全套防御策略（幻觉缓解、投毒检测、越狱防御、隐私保护等）
# TRiSM for Agentic AI: A review of Trust, Risk, and Security Management in LLM-based Agentic Multi-Agent Systems
#综述 
#AI_Open 
#2026_

**细分领域**：**多智能体系统安全治理 + 对抗性攻击防御 + 隐私保护 + 可信 AI 框架**

- 核心覆盖：提示注入攻击、内存投毒、Agent 共谋、功能滥用、多 Agent 级联风险
- 解决方案：安全架构、隐私保护技术、可解释性、审计追踪、权限控制、运行时监控
# Large Model-Based Agents: State-of-the-Art, Cooperation Paradigms, Security and Privacy, and Future Trends
#综述 
#IEEE_COMST
#2025/6/3

### 核心内容

1. **安全攻击**
    
    认证伪造、DoS、对抗样本、提示注入、Agent 越狱、数据 / 模型 / RAG / 记忆投毒、后门攻击。
2. **隐私风险**
    
    模型记忆泄露、成员推理、模型 / 提示词窃取、多智能体交互泄密。
3. **可靠性问题**
    
    大模型幻觉（输入 / 上下文 / 知识 / 事实冲突），且会在多智能体间级联放大。
4. **解决方案**
    
    身份认证、输入过滤、对抗训练、后门检测、差分隐私、数据清洗、RAG 增强、幻觉检测与修正。
# Generative AI-Empowered Signal Processing for Collaborative Embodied Agents: A Survey on Agentic Security
#IEEE_TCCN 
#CCFB 
#2026/3/20 

- **细分领域**：**具身智能体安全、物理层对抗防御、Agent 身份隐匿安全、Agent 内生安全自进化**
- **核心安全内容**
    1. 攻击面：智能干扰、信号伪造、窃听、物理层指纹追踪、信道污染
    2. 解决方案：
        - 内生安全：信道预测、CSI 补全、硬件损伤自校准、频谱自主规划
        - 外生防御：OODA 循环自主对抗、异常检测、行为隐匿、身份伪装
        - 生成式 AI 安全：GAN/VAE/ 扩散模型用于抗干扰、隐蔽通信、RF 指纹混淆
# MAPS: A Multilingual Benchmark for Agent Performance and Security
#EACL
#2026/3
#CCFB 

**细分领域**：**多语言 Agent 安全评测、Agent 越狱 / 提示注入防御、多语言安全鲁棒性**
- **研究问题**
    
    非英语语言会显著降低 LLM Agent 的**安全性**，多语言环境会放大越狱、提示注入、违规行为等安全漏洞。
    
- **核心工作**
    
    提出**MAPS**：首个**多语言 Agent 安全与性能基准**，基于 ASB（Agent Security Benchmark）等 4 个权威基准，覆盖 12 种语言。
    
- **安全威胁验证**
    
    实验证实：切换到非英语后，Agent**攻击成功率大幅上升（最高↑27%）**，安全防护显著下降。
    
- **解决方案 / 价值**
    
    - 提供多语言 Agent 安全评测标准
    - 揭示语言带来的安全漏洞
    - 为多语言安全对齐、防御设计提供依据
# Security in the Age of AI Teammates: An Empirical Study of Agentic Pull Requests on GitHub
#预印版

**细分领域：代码 Agent 安全、软件供应链安全、Agent 代码安全审查、安全 PR 风险预测** 
- **研究对象**
    
    自主代码 Agent 在 GitHub 上提交的**安全相关 PR**（漏洞修复、安全加固、认证授权、依赖安全等）。
    
- **核心发现**
    
    - 安全相关 PR 占 Agent 总提交量的 **3.85%**，不同 Agent 安全产出差异大。
    - 安全 PR**合并率更低、审核时间更长**，人类对 Agent 安全代码审查更严格。
    - PR 被拒主要与**复杂度、冗长性**相关，而非安全关键词本身。
    
- **安全威胁**
    
    代码 Agent 可能引入潜在漏洞、不安全实现、不合规配置，影响软件供应链安全。
    
- **解决方案 / 贡献**
    
    - 建立**Agent 安全 PR 实证分析框架**，量化安全行为与审查规律。
    - 提出**早期风险信号**（PR 长度、标题复杂度、代码规模）用于风险预判。
    - 给出**可落地的安全审查建议**：简化 Agent 安全 PR、增强可解释性、分语言 / 场景适配。
# Sola-Visibility-ISPM: Benchmarking Agentic AI for Identity Security Posture Management Visibility
#预印版

**细分领域**：**身份安全态势管理（ISPM）、云身份安全、Agent 安全评测基准、权限治理安全**
- **研究问题**
    
    缺少标准化方法评测 Agent 在企业 ** 身份安全（IAM/ISPM）** 中的能力，身份权限错误会引发重大安全风险。
    
- **核心工作**
    
    提出**SOLA-VISIBILITY-ISPM**：**全球首个面向 Agent 的身份安全态势管理评测基准**，覆盖 AWS、Okta、Google Workspace。
    
- **安全威胁**
    
    身份配置违规、权限过度、MFA 缺失、账号闲置、越权访问、配置幻觉。
    
- **解决方案**
    
    - 构建**生产级真实身份安全环境**作为评测底座
    - 设计**双路径推理 Agent**（Fast-path/Full-path）自动完成安全检查
    - 建立**专家 + LLM-as-Judge**多维评测体系
    - 给出**77 道企业真实身份安全检测题**覆盖资产、权限、合规、配置

