# Awesome LLM Agent Recommender Systems

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<img src="https://img.shields.io/github/stars/yuhuo03/Awesome-LLM-Agent-Recsys">
<img src="https://img.shields.io/badge/PRs-Welcome-red">
<img src="https://img.shields.io/github/last-commit/yuhuo03/Awesome-LLM-Agent-Recsys">

🌟 A curated list of papers, surveys, benchmarks, datasets, and open-source projects about **LLM Agents for Recommendation / Recommender Systems (Recsys)**.

If you want to contribute to this list (please do), feel free to send me a pull request. 🚀 If you have any further questions, feel free to contact [Yu Huo](https://github.com/yuhuo03).

## 📚 Contents

- [🤖 Agentic Recommenders (End-to-end)](#-agentic-recommenders-end-to-end)
- [🧠 LLM for Recsys (Non-agent)](#-llm-for-recsys-non-agent)
- [🛠️ Tool Use / Planning / Reasoning for Recsys Tasks](#-tool-use--planning--reasoning-for-recsys-tasks)
- [👤 User Modeling & Personalization with Agents](#-user-modeling--personalization-with-agents)
- [💬 Conversational / Interactive Recommendation](#-conversational--interactive-recommendation)
- [🤝 Multi-Agent Recommendation](#-multi-agent-recommendation)
- [📊 Evaluation, Benchmarks & Simulators](#-evaluation-benchmarks--simulators)
- [🗂️ Datasets](#-datasets)
- [🧩 Open-source Projects](#-open-source-projects)

---

## 🤖 Agentic Recommenders (End-to-end)

> Systems where an LLM agent (often with tools/RAG/memory) performs recommendation-related tasks end-to-end.

- ScienceDB AI: An LLM-Driven Agentic Recommender System for Large-Scale Scientific Data Sharing Services [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.01118)]

## 🧠 LLM for Recsys (Non-agent)

> LLMs used as encoders/rankers/generators for recsys, but not framed as agents.

- Large Language Model Enhanced Recommender Systems: A Survey [2024-12-arXiv] [[📄 paper](https://arxiv.org/abs/2412.13432)]
- Towards Next-Generation LLM-based Recommender Systems: A Survey and Beyond [2024-10-arXiv] [[📄 paper](https://arxiv.org/abs/2410.19744)]
- ThinkRec: Thinking-based recommendation via LLM [2025-05-arXiv] [[📄 paper](https://arxiv.org/abs/2505.15091)]
- Large Language Models for Multimodal Generative Recommendation with Causal Debiasing [2025-10-arXiv] [[📄 paper](https://arxiv.org/abs/2510.01622)]
- RecGOAT: Graph Optimal Adaptive Transport for LLM-Enhanced Multimodal Recommendation with Dual Semantic Alignment [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.00682)] [[🔗 repo](https://github.com/6lyc/RecGOAT-LLM4Rec)]

## 🛠️ Tool Use / Planning / Reasoning for Recsys Tasks

> Agents doing search/browsing, candidate generation, filtering, constraint satisfaction, explanation, bundle recommendation, etc.

- Reasoning to Rank: An End-to-End Solution for Exploiting Large Language Models for Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.12530v1)]
- De-conflating Preference and Qualification: Constrained Dual-Perspective Reasoning for Job Recommendation with Large Language Models [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.03097v1)]
- Give Users the Wheel: Towards Promptable Recommendation Paradigm [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.18929v2)]
- MiniRec: Data-Efficient Reinforcement Learning for LLM-based Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.04278v1)]
- Beyond Factual Correctness: Mitigating Preference-Inconsistent Explanations in Explainable Recommendation [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.03080v1)]

## 👤 User Modeling & Personalization with Agents

> Memory, long-term preference modeling, profiles, privacy-preserving personalization, on-device agents.

- Offline Reasoning for Efficient Recommendation: LLM-Empowered Persona-Profiled Item Indexing [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.21756v1)]
- RAIE: Region-Aware Incremental Preference Editing with LoRA for LLM-based Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2603.00638v1)]
- S-GRec: Personalized Semantic-Aware Generative Recommendation with Asymmetric Advantage [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.10606v3)]
- Enhancing Bandit Algorithms with LLMs for Time-varying User Preferences in Streaming Recommendations [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.08067v1)]
- SafeCRS: Personalized Safety Alignment for LLM-Based Conversational Recommender Systems [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.03536v1)]

## 💬 Conversational / Interactive Recommendation

> Dialogue-based recommendation, critiquing, preference elicitation, interactive ranking.

- Recommendation-as-Experience: A framework for context-sensitive adaptation in conversational recommender systems [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.07401)]

## 🤝 Multi-Agent Recommendation

> Debate/collaboration, role-based agents (e.g., critic, planner, ranker), self-play for recsys.

- Internalizing Multi-Agent Reasoning for Accurate and Efficient LLM-based Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.09829v2)]
- LLMs as Orchestrators: Constraint-Compliant Multi-Agent Optimization for Recommendation Systems [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.19121v3)]
- AgentRec: Next-Generation LLM-Powered Multi-Agent Collaborative Recommendation with Adaptive Intelligence [2025-10-arXiv] [[📄 paper](https://arxiv.org/abs/2510.01609v1)]
- Multi-Agent Collaborative Filtering: Orchestrating Users and Items for Agentic Recommendations [2025-11-arXiv] [[📄 paper](https://arxiv.org/abs/2511.18413v3)]
- RecNet: Self-Evolving Preference Propagation for Agentic Recommender Systems [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.21609v1)]
- AgenticTagger: Structured Item Representation for Recommendation with LLM Agents [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.05945v2)]

## 📊 Evaluation, Benchmarks & Simulators

> Offline metrics, online simulation, user simulators, agent evaluation protocols for recommendation.

- On the Reliability of User-Centric Evaluation of Conversational Recommender Systems [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.17264)] [[🔗 repo](https://github.com/michael-mue/reliable-crs-eval)]
- Benchmark Leakage Trap: Can We Trust LLM-based Recommendation? [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.13626v1)]
- AgentSelect: Benchmark for Narrative Query-to-Agent Recommendation [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.03761v1)]
- ConvApparel: A Benchmark Dataset and Validation Framework for User Simulators in Conversational Recommenders [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.16938v1)]
- Conv-FinRe: A Conversational and Longitudinal Benchmark for Utility-Grounded Financial Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.16990v1)]
- No-Human in the Loop: Agentic Evaluation at Scale for Recommendation [2025-11-arXiv] [[📄 paper](https://arxiv.org/abs/2511.03051v1)]

## 🗂️ Datasets

- MovieLens (GroupLens) [[🔗 site](https://grouplens.org/datasets/movielens/)]
- Amazon Reviews / Amazon Product Data (McAuley et al.) [[🔗 site](https://nijianmo.github.io/amazon/index.html)]
- MIND: Microsoft News Dataset [[🔗 site](https://msnews.github.io/)]
- ConvApparel (conversational recommendation benchmark dataset) [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.16938v1)]
- Conv-FinRe (conversational & longitudinal benchmark) [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.16990v1)]

## 🧩 Open-source Projects

- RecGOAT-LLM4Rec [[🔗 repo](https://github.com/6lyc/RecGOAT-LLM4Rec)]
- reliable-crs-eval (user-centric CRS evaluation reliability) [[🔗 repo](https://github.com/michael-mue/reliable-crs-eval)]

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Citation

If you find this repo useful, feel free to cite it (add your bibtex here).
