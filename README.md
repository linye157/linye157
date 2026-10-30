<div align="center">

# Lian Shun · 连顺

**AI Agents · Retrieval-Augmented Generation · LLM Engineering**

东北大学人工智能硕士在读 · Northeastern University, China

关注 Agent 的检索、工具调用、上下文管理与评测，探索可验证、可追溯的 LLM 应用。

[Public Projects](#selected-projects) · [Open Source](#open-source) · [Technical Focus](#technical-focus)

</div>

---

## About Me

- 本科与硕士均就读于东北大学，专业为人工智能，硕士预计于 **2027 年毕业**。
- 主要关注 **Agent / RAG / LLM 应用工程**，同时研究工业时序建模与预测优化。
- 重视问题复现、边界条件与回归验证，希望把实验原型逐步做成可靠的工具。

## Technical Focus

| 方向 | 技术与关注点 |
| --- | --- |
| **Agent Systems** | Agent Loop · ReAct · Function Calling · Multi-Agent Workflows · MCP · Skills |
| **Retrieval & Memory** | Hybrid Search · Reranking · Agentic RAG · Qdrant · Context & Memory |
| **LLM Alignment & Evaluation** | SFT · DPO · LoRA · Unsloth · TRL · LLM-as-Judge |
| **Modeling** | PyTorch · Transformers · Time-Series Forecasting · scikit-learn · SHAP |
| **Engineering** | Python · FastAPI · Flask · Vue · Docker · Git · pytest |

## Selected Projects

### [PaperRAGonDeerFlow](https://github.com/linye157/PaperRAGonDeerFlow)
**本地论文检索与研究助手**

基于字节跳动开源 DeerFlow 二次开发，接入本地论文向量库与检索工具，支持基于论文证据的问答及来源引用。

`Agent Workflow` · `RAG` · `Qdrant` · `Ollama` · `FastAPI`

### [TimeMixerpp](https://github.com/linye157/TimeMixerpp)
**面向时间序列分析的 Agent 工具链**

将 TimeMixer++ 模型的训练、预测、评估、特征提取与案例检索封装为工具，提供自然语言 ReAct 与直接 Function Calling 两种使用方式。

`Time Series` · `Tool Calling` · `ReAct` · `RAG`

### [DPO-Safety-LLM](https://github.com/linye157/DPO-Safety-LLM)
**大语言模型安全偏好微调实验**

基于 Qwen2.5-7B、Unsloth 与 TRL，探索 DPO / LoRA 安全偏好微调，提供数据分析、训练可视化与微调前后的对比评测脚本。

`Qwen` · `DPO` · `LoRA` · `Evaluation`

### [Predict](https://github.com/linye157/Predict)
**钢材力学性能预测与工艺优化平台**

围绕屈服强度、抗拉强度与延伸率，整合数据预处理、多模型训练、预测评估、SHAP 分析与工艺参数优化实验，提供 Flask API 与 Vue 界面。

`PyTorch` · `Machine Learning` · `SHAP` · `Bayesian Optimization` · `Flask / Vue`

## Open Source

围绕 Agent 工具调用、运行时可靠性与评测反馈参与开源改进。

| 项目 | 提交的改进 | 状态 |
| --- | --- | --- |
| [Qwen-Agent #1021](https://github.com/QwenLM/Qwen-Agent/pull/1021) | 校正 DeepPlanning 景点约束检查的时间阈值提示，补充边界与输入形式回归测试 | Open |
| [Hermes Agent #74723](https://github.com/NousResearch/hermes-agent/pull/74723) | 针对文本形式泄漏的工具调用标记，增加有界的原生工具调用重试与回归验证 | Open |
| [Hermes Agent #146708](https://github.com/NousResearch/hermes-agent/pull/146708) | 修复 completion 预检中的空 origin 崩溃，补充消息场景及 LOCAL 所有者边界测试 | Open |

<sub>状态核对日期：2026-10-30。最新状态与讨论请查看各贡献链接。</sub>

[查看全部公开贡献 →](https://github.com/pulls?q=is%3Apr+author%3Alinye157)

## Exploration Roadmap

| 主线 | 公开实践 | 继续探索 |
| --- | --- | --- |
| **Agentic RAG** | 论文知识库、检索工具与来源引用 | 多轮检索、重排与证据质量评估 |
| **Agent Engineering** | 时序模型工具化、上游缺陷修复与回归测试 | 上下文管理、状态恢复、工具执行边界 |
| **LLM Alignment** | DPO / LoRA 微调与对比评测 | 偏好数据质量、过度拒绝与能力保持 |
| **Time-Series Intelligence** | 预测、案例检索与工艺优化实验 | 时序检索、可解释性与可靠评估 |

---

欢迎围绕 **Agent、RAG、LLM 工程与时序智能** 交流，也欢迎通过项目 Issues 提出问题与建议。
