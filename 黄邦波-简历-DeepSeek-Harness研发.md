# 黄邦波

**应聘岗位：DeepSeek Harness 研发工程师**

北京大学 · 人工智能硕士（保送）　｜　NeurIPS 投稿通讯作者　｜　8 年 AI 研发经验

181****9303　｜　734****@qq.com（完整联系方式可面谈提供）

---

## 科研与论文

**RepoContraAudit: Explainable Repository-Level Code Auditing via Multimodal Anti-Fact Reasoning**

- **状态：** NeurIPS 投稿中　｜　**角色：** 通讯作者
- **方向：** 仓库级代码审计、多模态推理、可解释性反事实验证——与代码类 Agent / Harness 在真实代码库上的行为分析、评测与反馈闭环高度相关
- **个人贡献：** 主导问题定义与研究路线，设计多模态 Anti-Fact 推理框架，推动可解释审计链路从假设生成到证据核验的完整闭环；与研究员协作完成实验设计与论文撰写

---

## 个人简介

- 北京大学人工智能硕士，本科中南大学软件工程；一线 AI 研发 8 年，完整经历 **算法 → 大模型端侧部署 → Agent 平台 → Harness 式经验沉淀框架** 的技术演进。
- **Agent / Harness 深度实践者：** 日常高强度使用 Cursor、Claude Code 等代码类 Agent 及通用 Agent 产品，将 Agent 辅助开发融入产研全流程；对模型行为、开发者体验（DX）与 Harness 设计有持续判断力。
- **Harness 相关一手经验：** 主导设计 SkillRL（Agent 经验沉淀与复用框架）、组织级 Agent 平台 AIP 的 Plan 引擎与上下文调度、ClawEval 确定性评测沙箱——覆盖 Agent Loop、Tool Use、Memory、Context Engineering、评测回归等 Harness 核心课题。
- 有与研究员深度协作经验（论文、框架预研、模型行为分析），擅长在 AI 辅助下快速进入新语言/新框架并保证工程质量；小团队快速迭代经验丰富。

---

## 与岗位要求的能力对应

| 岗位要求 | 对应经验 |
|----------|----------|
| Harness 技术架构与选型 | SkillRL 四层架构（SkillCreate / AutoAgent / ClawEval / Skill Hub）；AIP「SOP + Plan 引擎 + 资源协同」底座设计 |
| Harness 产品开发 | 带队落地 Agent 平台核心模块：规划引擎、记忆调度、上下文优化、多角色协作与管理驾驶舱 |
| 与研究员协作、前沿创新 | NeurIPS 投稿通讯作者；端侧长上下文压缩与内化路线预研；SkillRL 经验蒸馏与失败反思机制 |
| 模型与 Harness 共同进化 | 机械臂任务引入技能记忆后成功率 60%→85%；复杂任务上下文调度由数十秒级降至毫秒级；端侧 Qwen/DeepSeek 部署与端云协同 |
| 内部真实任务驱动迭代 | ClawEval 沙箱确定性评测 + AB 对比 + 回归；导诊多轮对话引擎在真实边缘设备上迭代至 200ms / 90% 准确率 |
| Agent 高强度用户 & DX 感知 | 推动团队 AI Native 研发转型，搭建低代码 + AI 工具链，12 项目并行、周期缩短约 60% |
| LLM / Agent 机制 | Agent Loop · Tool Use · Reasoning · Planning · Skills · MCP · Memory · Subagent · Multi-Agent · KV Cache · RAG |
| Prompt / Context / Harness Engineering | 分层记忆与角色隔离、技能分层检索、上下文窗口优化、引导式对话与 Plan 动态重跑 |

---

## Harness 相关核心项目

### SkillRL —— Agent 经验沉淀与 Harness 评测框架（道通科技 · 2026）

> 在不改动模型权重的前提下，通过 Harness 层沉淀与复用交互经验提升任务表现。

- **SkillCreate：** 基于行业知识 RAG 冷启动生成种子 Skills
- **AutoAgent：** 从成功轨迹蒸馏策略、从失败轨迹反事实提炼教训（Reflection）
- **ClawEval：** 沙箱内确定性评分与 AB 对比，不依赖 LLM 自评，支撑 Harness 回归评测
- **Skill Hub：** 语义检索与分层复用，降低轨迹上下文占用
- **效果：** 机械臂抓取成功率约 60%→85%；为「模型行为 ↔ Harness 能力」共同迭代提供可量化反馈源

### 组织级 Agent 平台 AIP（遥望科技 · 2025）

> 面向复杂任务的组织级 Agent Harness：SOP 编排 + 智能 Plan + 多维资源协同。

- **Plan 引擎：** 任务动态调整、暂停与重跑；复杂任务上下文调度由数十秒级优化至毫秒级
- **Memory：** 短期缓存 + 长期记忆双层结构；角色专属知识库 + 元知识库优先级调度；跨会话人设一致
- **Multi-Agent：** 多角色画像、记忆隔离与协作机制；对接云盘 / 知识库 / 数据库等资源
- **工程指标：** 数据一致性保障率约 99%

### 代码审计与 Agent 行为研究（科研 · 2025–2026）

- 主导 RepoContraAudit 研究：面向仓库级代码的 Multimodal Anti-Fact 推理与可解释审计
- 与 Harness 场景衔接：代码库级上下文理解、工具调用链验证、反事实检验——为代码类 Agent 的可靠性评测提供研究基础

---

## 工作经历（Harness / Agent 视角）

### 道通科技 ｜ 技术 VP（Digital Agent 团队）　　2026.01 – 2026.04

- 主导 SkillRL Harness 框架设计与落地；牵头巡检行业「数据 OS + AgentOS + 快慢双系统 + 端边云执行」分层架构
- 以「虚拟沙盒迭代 + 真实场景校验」打通数字 Agent 与物理执行环节，覆盖电力、化工、安防、轨交等场景

### 遥望科技（A 股上市）｜ 产研总监　　2025.07 – 2026.01

- 负责组织级 Agent 平台 AIP 产研，确立「组织智慧中枢」定位，交付 Plan 引擎、记忆与人格、资源协同等 Harness 核心模块
- 推动研发流程 AI Native 转型，以 Agent 驱动内部真实任务提效

### 广东明日联合 ｜ 高级 AI 技术总监　　2025.04 – 2025.07

- 重构低算力场景引导式对话算法（Context / Prompt Engineering），多轮对话引擎覆盖 12 种疾病；边缘设备约 200ms 响应，准确率约 65%→90%
- 搭建低代码平台与 AI 工具链，支撑 12 项目并行快速迭代

### 摩尔线程 ｜ AI 战略经理　　2025.01 – 2025.04

- 端侧大模型（Qwen、DeepSeek）部署与端云协同方案；数字人全双工交互 Harness，端到端延迟控制在 2 秒内
- 参与长上下文压缩与内化路线预研，关注 KV Cache 与端侧推理优化

### 某军工单位 ｜ 项目负责人　　2020 – 2024

- 反无人机多智能体系统：目标检测、轨迹预测、拦截决策的多 Agent 协同与 Tool Use 式模块编排

### 新素代科技 ｜ CTO（创业）　　2019 – 2020

- 小团队快速迭代：系统架构升级，并发能力提升约两个量级，用户规模破千万

### 百度 · 国际化产品总部 ｜ 阿里巴巴 · 移动事业部（实习）　　2015 – 2018

- NLP 智能推荐与缓存架构；搜索质量监控与大数据挖掘

---

## 教育背景

| 时间 | 学校 | 专业 |
|------|------|------|
| 2016 – 2020 | 北京大学 | 人工智能（硕士），保送 |
| 2012 – 2016 | 中南大学 | 软件工程（本科） |

---

## 技术栈

**Harness & Agent：** Agent Loop · Tool Use · MCP · Skills · Subagent · Multi-Agent · Planning · Reasoning · Memory（分层 / 检索 / 反思）· Context Engineering · Harness Engineering · Prompt Engineering

**LLM & 工程：** LLM API · KV Cache · RAG · 向量检索 · 微调 · 端侧部署（量化 / 剪枝）· 端云协同 · 高并发架构 · 确定性评测与 AB 回归

**开发方式：** 熟练使用 Cursor、Claude Code 等 AI Agent 工具进行软件开发；AI 辅助下快速上手新语言 / 新框架并保证代码质量

---

## 荣誉与其他

- 福布斯 U30 创新型领军人才
- 军工年度优秀项目（反无人机，项目总额约 3.2 亿元）
- 英文工作能力：百度国际化产品、技术文档与开源社区阅读写作
