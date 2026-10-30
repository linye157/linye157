<div align="center">

# Lian Shun

**AI Agents · Retrieval-Augmented Generation · LLM Engineering**

M.S. Student in Artificial Intelligence · Northeastern University, China

Building LLM applications with a focus on retrieval, tool use, context management, and evaluation.

[Public Projects](#selected-projects) · [Open Source](#open-source) · [Technical Focus](#technical-focus)

</div>

---

## About Me

- B.S. in Artificial Intelligence from Northeastern University, China; currently pursuing an M.S. in the same field, with expected graduation in **2027**.
- Focused on **AI agents, RAG, and LLM application engineering**, alongside industrial time-series modeling and process optimization.
- I value reproducible bug reports, boundary checks, and regression tests when turning prototypes into reliable tools.

## Technical Focus

| Area | Technologies & Interests |
| --- | --- |
| **Agent Systems** | Agent Loop · ReAct · Function Calling · Multi-Agent Workflows · MCP · Skills |
| **Retrieval & Memory** | Hybrid Search · Reranking · Agentic RAG · Qdrant · Context & Memory |
| **LLM Alignment & Evaluation** | SFT · DPO · LoRA · Unsloth · TRL · LLM-as-Judge |
| **Modeling** | PyTorch · Transformers · Time-Series Forecasting · scikit-learn · SHAP |
| **Engineering** | Python · FastAPI · Flask · Vue · Docker · Git · pytest |

## Selected Projects

### [PaperRAGonDeerFlow](https://github.com/linye157/PaperRAGonDeerFlow)
**Local Paper Retrieval & Research Assistant**

An extension of ByteDance's open-source DeerFlow that integrates a local paper vector database and retrieval tools for evidence-based question answering with source references.

`Agent Workflow` · `RAG` · `Qdrant` · `Ollama` · `FastAPI`

### [TimeMixerpp](https://github.com/linye157/TimeMixerpp)
**Agent Tools for Time-Series Analysis**

Exposes TimeMixer++ training, prediction, evaluation, feature extraction, and case retrieval as tools, with both natural-language ReAct interaction and direct function calling.

`Time Series` · `Tool Calling` · `ReAct` · `RAG`

### [DPO-Safety-LLM](https://github.com/linye157/DPO-Safety-LLM)
**Safety Preference Fine-Tuning for LLMs**

Explores DPO with LoRA on Qwen2.5-7B using Unsloth and TRL, with scripts for data analysis, training visualization, and evaluation before and after fine-tuning.

`Qwen` · `DPO` · `LoRA` · `Evaluation`

### [Predict](https://github.com/linye157/Predict)
**Steel Mechanical Property Prediction & Process Optimization**

Combines data preprocessing, multi-model training, evaluation, SHAP analysis, and process optimization experiments for yield strength, tensile strength, and elongation, with a Flask API and Vue interface.

`PyTorch` · `Machine Learning` · `SHAP` · `Bayesian Optimization` · `Flask / Vue`

## Open Source

Contributing improvements to agent tool calling, runtime reliability, and evaluation feedback.

| Project | Proposed Improvement | Status |
| --- | --- | --- |
| [Qwen-Agent #1021](https://github.com/QwenLM/Qwen-Agent/pull/1021) | Correct DeepPlanning attraction-constraint messages to match the actual time thresholds, with regression tests for boundaries and input formats | Open |
| [Hermes Agent #74723](https://github.com/NousResearch/hermes-agent/pull/74723) | Add bounded retries for native tool calls when tool-call markup leaks into plain text, with regression coverage | Open |
| [Hermes Agent #146708](https://github.com/NousResearch/hermes-agent/pull/146708) | Fix a null-origin crash in completion preflight, with messaging regressions and LOCAL ownership-boundary tests | Open |

<sub>Status checked on October 30, 2026. Follow each contribution link for the latest status and discussion.</sub>

[View All Public Contributions →](https://github.com/pulls?q=is%3Apr+author%3Alinye157)

## Exploration Roadmap

| Focus | Public Work | Further Exploration |
| --- | --- | --- |
| **Agentic RAG** | Paper knowledge bases, retrieval tools, and source references | Multi-turn retrieval, reranking, and evidence-quality evaluation |
| **Agent Engineering** | Time-series model tools, upstream bug fixes, and regression tests | Context management, state recovery, and tool execution boundaries |
| **LLM Alignment** | DPO / LoRA fine-tuning and comparative evaluation | Preference data quality, over-refusal, and capability retention |
| **Time-Series Intelligence** | Prediction, case retrieval, and process optimization experiments | Time-series retrieval, interpretability, and reliable evaluation |

---

Happy to exchange ideas on **AI agents, RAG, LLM engineering, and time-series intelligence**. Questions and suggestions are welcome through project Issues.
