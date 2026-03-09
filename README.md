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

- AgentSelect: Benchmark for Narrative Query-to-Agent Recommendation [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.03761)]
- Self-Evolving Recommendation System: End-To-End Autonomous Model Optimization With LLM Agents [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.10226)]
- Self-EvolveRec: Self-Evolving Recommender Systems with LLM-based Directional Feedback [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.12612)]
- Internalizing Multi-Agent Reasoning for Accurate and Efficient LLM-based Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.09829)]
- ChainRec: An Agentic Recommender Learning to Route Tool Chains for Diverse and Evolving Interests [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.10490)]
- AgenticTagger: Structured Item Representation for Recommendation with LLM Agents [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.05945)]
- AMEM4Rec: Leveraging Cross-User Similarity for Memory Evolution in Agentic LLM Recommenders [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.08837)]
- ScienceDB AI: An LLM-Driven Agentic Recommender System for Large-Scale Scientific Data Sharing Services [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.01118)]
- RobustExplain: Evaluating Robustness of LLM-Based Explanation Agents for Recommendation [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.19120)]
- RecNet: Self-Evolving Preference Propagation for Agentic Recommender Systems [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.21609)]
- PersonaAct: Simulating Short-Video Users with Personalized Agents for Counterfactual Filter Bubble Auditing [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.22547)]
- PCN-Rec: Agentic Proof-Carrying Negotiation for Reliable Governance-Constrained Recommendation [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.09771)]
- Less is More: Benchmarking LLM Based Recommendation Agents [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.20316)]
- LLMs as Orchestrators: Constraint-Compliant Multi-Agent Optimization for Recommendation Systems [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.19121)]
- Exploring Recommender System Evaluation: A Multi-Modal User Agent Framework for A/B Testing [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.04554)]

## 🧠 LLM for Recsys (Non-agent)

> LLMs used as encoders/rankers/generators for recsys, but not framed as agents.

- SORT: A Systematically Optimized Ranking Transformer for Industrial-scale Recommenders [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.03988)]
- SafeCRS: Personalized Safety Alignment for LLM-Based Conversational Recommender Systems [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.03536)]
- Sensory-Aware Sequential Recommendation via Review-Distilled Representations [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.02709)]
- AlphaFree: Recommendation Free from Users, IDs, and GNNs [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.02653)]
- IDProxy: Cold-Start CTR Prediction for Ads and Recommendation at Xiaohongshu with Multimodal LLMs [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.01590)]
- GeMi: A Graph-based, Multimodal Recommendation System for Narrative Scroll Paintings [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.00854)]
- Balancing Domestic and Global Perspectives: Evaluating Dual-Calibration and LLM-Generated Nudges for Diverse News Recommendation [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.05780)]
- Beyond Factual Correctness: Mitigating Preference-Inconsistent Explanations in Explainable Recommendation [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.03080)]
- MLLMRec-R1: Incentivizing Reasoning Capability in Large Language Models for Multimodal Sequential Recommendation [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.06243)]
- Whose Name Comes Up? Benchmarking and Intervention-Based Auditing of LLM-Based Scholar Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.08873)]
- Variable-Length Semantic IDs for Recommender Systems [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.16375)]
- VENOMREC: Cross-Modal Interactive Poisoning for Targeted Promotion in Multimodal LLM Recommender Systems [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.06409)]

## 🛠️ Tool Use / Planning / Reasoning for Recsys Tasks

> Agents doing search/browsing, candidate generation, filtering, constraint satisfaction, explanation, bundle recommendation, etc.

- MLLMRec-R1: Incentivizing Reasoning Capability in Large Language Models for Multimodal Sequential Recommendation [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.06243)]
- Beyond Factual Correctness: Mitigating Preference-Inconsistent Explanations in Explainable Recommendation [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.03080)]
- SARM: LLM-Augmented Semantic Anchor for End-to-End Live-Streaming Ranking [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.09401)]
- Reasoning-guided Collaborative Filtering with Language Models for Explainable Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.05544)]
- Reasoning to Rank: An End-to-End Solution for Exploiting Large Language Models for Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.12530)]
- RGAlign-Rec: Ranking-Guided Alignment for Latent Query Reasoning in Recommendation Systems [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.12968)]
- QARM V2: Quantitative Alignment Multi-Modal Recommendation for Reasoning User Sequence Modeling [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.08559)]
- Offline Reasoning for Efficient Recommendation: LLM-Empowered Persona-Profiled Item Indexing [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.21756)]
- MiniRec: Data-Efficient Reinforcement Learning for LLM-based Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.04278)]
- Learning User Interests via Reasoning and Distillation for Cross-Domain News Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.15005)]
- Internalizing Multi-Agent Reasoning for Accurate and Efficient LLM-based Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.09829)]
- High Fidelity Textual User Representation over Heterogeneous Sources via Reinforcement Learning [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.07333)]
- Give Users the Wheel: Towards Promptable Recommendation Paradigm [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.18929)]
- Following the TRAIL: Predicting and Explaining Tomorrow's Hits with a Fine-Tuned LLM [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.04225)]
- Experimentation Accelerator: Interpretable Insights and Creative Recommendations for A/B Testing with Content-Aware ranking [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.13852)]
- De-conflating Preference and Qualification: Constrained Dual-Perspective Reasoning for Job Recommendation with Large Language Models [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.03097)]
- ChainRec: An Agentic Recommender Learning to Route Tool Chains for Diverse and Evolving Interests [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.10490)]
- Awakening Dormant Users: Generative Recommendation with Counterfactual Functional Role Reasoning [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.13134)]
- An Industrial-Scale Sequential Recommender for LinkedIn Feed Ranking [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.12354)]

## 👤 User Modeling & Personalization with Agents

> Memory, long-term preference modeling, profiles, privacy-preserving personalization, on-device agents.

- WinFLoRA: Incentivizing Client-Adaptive Aggregation in Federated LoRA under Privacy Heterogeneity [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.01126)]
- U-CAN: Utility-Aware Contrastive Attenuation for Efficient Unlearning in Generative Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.23400)]
- S-GRec: Personalized Semantic-Aware Generative Recommendation with Asymmetric Advantage [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.10606)]
- RAIE: Region-Aware Incremental Preference Editing with LoRA for LLM-based Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2603.00638)]
- Offline Reasoning for Efficient Recommendation: LLM-Empowered Persona-Profiled Item Indexing [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.21756)]
- FeDecider: An LLM-Based Framework for Federated Cross-Domain Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.16034)]
- Enhancing Bandit Algorithms with LLMs for Time-varying User Preferences in Streaming Recommendations [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.08067)]
- Empowering Contrastive Federated Sequential Recommendation with LLMs [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.09306)]
- De-conflating Preference and Qualification: Constrained Dual-Perspective Reasoning for Job Recommendation with Large Language Models [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.03097)]
- AMEM4Rec: Leveraging Cross-User Similarity for Memory Evolution in Agentic LLM Recommenders [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.08837)]
- ALPBench: A Benchmark for Attribution-level Long-term Personal Behavior Understanding [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.03056)]
- Post-Training Denoising of User Profiles with LLMs in Collaborative Filtering Recommendation [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.18009)]
- PersonaAct: Simulating Short-Video Users with Personalized Agents for Counterfactual Filter Bubble Auditing [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.22547)]
- One Persona, Many Cues, Different Results: How Sociodemographic Cues Impact LLM Personalization [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.18572)]
- Netflix Artwork Personalization via LLM Post-training [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.02764)]
- MALLOC: Benchmarking the Memory-aware Long Sequence Compression for Large Sequential Recommendation [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.20234)]
- Enriching Semantic Profiles into Knowledge Graph for Recommender Systems Using Large Language Models [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.08148)]
- Enhancing LLM-based Recommendation with Preference Hint Discovery from Knowledge Graph [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.18096)]

## 💬 Conversational / Interactive Recommendation

> Dialogue-based recommendation, critiquing, preference elicitation, interactive ranking.

- SafeCRS: Personalized Safety Alignment for LLM-Based Conversational Recommender Systems [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.03536)]
- Proactive Guiding Strategy for Item-side Fairness in Interactive Recommendation [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.03094)]
- Fairness Begins with State: Purifying Latent Preferences for Hierarchical Reinforcement Learning in Interactive Recommendation [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.03820)]
- VENOMREC: Cross-Modal Interactive Poisoning for Targeted Promotion in Multimodal LLM Recommender Systems [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.06409)]
- On the Reliability of User-Centric Evaluation of Conversational Recommender Systems [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.17264)]
- ConvApparel: A Benchmark Dataset and Validation Framework for User Simulators in Conversational Recommenders [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.16938)]
- Conv-FinRe: A Conversational and Longitudinal Benchmark for Utility-Grounded Financial Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.16990)]
- STCRank: Spatio-temporal Collaborative Ranking for Interactive Recommender System at Kuaishou E-shop [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.10027)]
- Recommendation-as-Experience: A framework for context-sensitive adaptation in conversational recommender systems [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.07401)]
- LLM-Enhanced Reinforcement Learning for Long-Term User Satisfaction in Interactive Recommendation [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.19585)]
- Integrating Vision-Centric Text Understanding for Conversational Recommender Systems [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.13505)]
- UserSimCRS v2: Simulation-Based Evaluation for Conversational Recommender Systems [2025-12-arXiv] [[📄 paper](https://arxiv.org/abs/2512.04588)]
- Know Your Users! Estimating User Domain Knowledge in Conversational Recommenders [2025-12-arXiv] [[📄 paper](https://arxiv.org/abs/2512.13173)]
- RecToM: A Benchmark for Evaluating Machine Theory of Mind in LLM-based Conversational Recommender Systems [2025-11-arXiv] [[📄 paper](https://arxiv.org/abs/2511.22275)]
- Enhancing Conversational Recommender Systems with Tree-Structured Knowledge and Pretrained Language Models [2025-11-arXiv] [[📄 paper](https://arxiv.org/abs/2511.12579)]
- Emotion-Aware Conversational Recommender Systems: a Case Study [2025-11-arXiv] [[📄 paper](https://arxiv.org/abs/2511.18548)]
- VOGUE: A Multimodal Dataset for Conversational Recommendation in Fashion [2025-10-arXiv] [[📄 paper](https://arxiv.org/abs/2510.21151)]
- Rank-GRPO: Training LLM-based Conversational Recommender Systems with Reinforcement Learning [2025-10-arXiv] [[📄 paper](https://arxiv.org/abs/2510.20150)]
- Limitations of Current Evaluation Practices for Conversational Recommender Systems and the Potential of User Simulation [2025-10-arXiv] [[📄 paper](https://arxiv.org/abs/2510.05624)]
- USB-Rec: An Effective Framework for Improving Conversational Recommendation Capability of Large Language Model [2025-09-arXiv] [[📄 paper](https://arxiv.org/abs/2509.20381)]
- Synthetic Dialogue Generation for Interactive Conversational Elicitation & Recommendation (ICER) [2025-09-arXiv] [[📄 paper](https://arxiv.org/abs/2510.02331)]

## 🤝 Multi-Agent Recommendation

> Debate/collaboration, role-based agents (e.g., critic, planner, ranker), self-play for recsys.

- Internalizing Multi-Agent Reasoning for Accurate and Efficient LLM-based Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.09829)]
- AgenticTagger: Structured Item Representation for Recommendation with LLM Agents [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.05945)]
- RecNet: Self-Evolving Preference Propagation for Agentic Recommender Systems [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.21609)]
- Learning to Recommend Multi-Agent Subgraphs from Calling Trees [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.22209)]
- LLMs as Orchestrators: Constraint-Compliant Multi-Agent Optimization for Recommendation Systems [2026-01-arXiv] [[📄 paper](https://arxiv.org/abs/2601.19121)]
- Towards Efficient Hypergraph and Multi-LLM Agent Recommender Systems [2025-12-arXiv] [[📄 paper](https://arxiv.org/abs/2512.06590)]
- MaRCA: Multi-Agent Reinforcement Learning for Dynamic Computation Allocation in Large-Scale Recommender Systems [2025-12-arXiv] [[📄 paper](https://arxiv.org/abs/2512.24325)]
- Multi-Agent Collaborative Filtering: Orchestrating Users and Items for Agentic Recommendations [2025-11-arXiv] [[📄 paper](https://arxiv.org/abs/2511.18413)]

## 📊 Evaluation, Benchmarks & Simulators

> Offline metrics, online simulation, user simulators, agent evaluation protocols for recommendation.

- The DSA's Blind Spot: Algorithmic Audit of Advertising and Minor Profiling on TikTok [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.05653)]
- FlashEvaluator: Expanding Search Space with Parallel Evaluation [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.02565)]
- Cryo-Bench: Benchmarking Foundation Models for Cryosphere Applications [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.01576)]
- AgentSelect: Benchmark for Narrative Query-to-Agent Recommendation [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.03761)]
- A Simulation Study to Compare Inferential Properties when Modelling Ordinal Outcomes: The Case for the (Plain but Robust) Proportional Odds Model [2026-03-arXiv] [[📄 paper](https://arxiv.org/abs/2603.01943)]
- Whose Name Comes Up? Benchmarking and Intervention-Based Auditing of LLM-Based Scholar Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.08873)]
- WarpRec: Unifying Academic Rigor and Industrial Scale for Responsible, Reproducible, and Efficient Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.17442)]
- Vision Transformers for Zero-Shot Clustering of Animal Images: A Comparative Benchmarking Study [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.03894)]
- Towards Reliable Negative Sampling for Recommendation with Implicit Feedback via In-Community Popularity [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.18759)]
- TopoFair: Linking Topological Bias to Fairness in Link Prediction Benchmarks [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.11802)]
- TherapyProbe: Generating Design Knowledge for Relational Safety in Mental Health Chatbots Through Adversarial Simulation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.22775)]
- The Illusion of Generalization: Re-examining Tabular Language Model Evaluation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.04031)]
- Seeing Graphs Like Humans: Benchmarking Computational Measures and MLLMs for Similarity Assessment [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.22416)]
- RelBench v2: A Large-Scale Benchmark and Repository for Relational Data [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.12606)]
- RAT-Bench: A Comprehensive Benchmark for Text Anonymization [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.12806)]
- On the Reliability of User-Centric Evaluation of Conversational Recommender Systems [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.17264)]
- OmniReview: A Large-scale Benchmark and LLM-enhanced Framework for Realistic Reviewer Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.08896)]
- LingLanMiDian: Systematic Evaluation of LLMs on TCM Knowledge and Clinical Reasoning [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.01779)]
- Learning Under Extreme Data Scarcity: Subject-Level Evaluation of Lightweight CNNs for fMRI-Based Prodromal Parkinsons Detection [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2603.00060)]
- FrameRef: A Framing Dataset and Simulation Testbed for Modeling Bounded Rational Information Health [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.15273)]
- Extracting Consumer Insight from Text: A Large Language Model Approach to Emotion and Evaluation Measurement [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.15312)]
- EditFlow: Benchmarking and Optimizing Code Edit Recommendation Systems via Reconstruction of Developer Flows [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.21697)]
- ConvApparel: A Benchmark Dataset and Validation Framework for User Simulators in Conversational Recommenders [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.16938)]
- Conv-FinRe: A Conversational and Longitudinal Benchmark for Utility-Grounded Financial Recommendation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.16990)]
- Binge Watch: Reproducible Multimodal Benchmarks Datasets for Large-Scale Movie Recommendation on MovieLens-10M and 20M [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.15505)]
- Benchmarking of algorithms for set partitions [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.01350)]
- Benchmark Leakage Trap: Can We Trust LLM-based Recommendation? [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.13626)]
- BASS: Benchmarking Audio LMs for Musical Structure and Semantic Reasoning [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.04085)]
- Auditing Reciprocal Sentiment Alignment: Inversion Risk, Dialect Representation and Intent Misalignment in Transformers [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.17469)]
- Audit After Segmentation: Reference-Free Mask Quality Assessment for Language-Referred Audio-Visual Segmentation [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.03892)]

## 🗂️ Datasets

- MovieLens (GroupLens) [[🔗 site](https://grouplens.org/datasets/movielens/)]
- Amazon Reviews / Amazon Product Data (McAuley et al.) [[🔗 site](https://nijianmo.github.io/amazon/index.html)]
- MIND: Microsoft News Dataset [[🔗 site](https://msnews.github.io/)]
- Yelp Open Dataset [[🔗 site](https://www.yelp.com/dataset)]
- Goodreads datasets (collection) [[🔗 repo](https://github.com/MengtingWan/goodreads)]
- Last.fm 1K/360K (music listening logs; collection) [[🔗 repo](https://github.com/MTG/lastfm-dataset-360K)]
- OpenDialKG (conversational recommendation / knowledge-grounded dialog) [[🔗 repo](https://github.com/facebookresearch/opendialkg)]
- ReDial (recommendation dialog) [[🔗 repo](https://github.com/ReDialData/website)]
- DuRecDial (Chinese conversational recommendation dialog) [[🔗 repo](https://github.com/PaddlePaddle/Knover/tree/develop/projects/DuRecDial)]
- INSPIRED (CRS dataset) [[🔗 repo](https://github.com/sunnweiwei/INSPIRED)]
- ConvApparel (conversational recommendation benchmark dataset) [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.16938)]
- Conv-FinRe (conversational & longitudinal benchmark) [2026-02-arXiv] [[📄 paper](https://arxiv.org/abs/2602.16990)]

## 🧩 Open-source Projects

- RecGOAT-LLM4Rec [[🔗 repo](https://github.com/6lyc/RecGOAT-LLM4Rec)]
- reliable-crs-eval (user-centric CRS evaluation reliability) [[🔗 repo](https://github.com/michael-mue/reliable-crs-eval)]
- RecBole (recsys library) [[🔗 repo](https://github.com/RUCAIBox/RecBole)]
- RecStudio (recsys library) [[🔗 repo](https://github.com/USTCLLM/RecStudio)]
- Transformers4Rec (NVIDIA; transformer-based recommendation) [[🔗 repo](https://github.com/NVIDIA-Merlin/Transformers4Rec)]
- Merlin (NVIDIA recommender systems framework) [[🔗 repo](https://github.com/NVIDIA-Merlin/Merlin)]
- DeepCTR (classic CTR / rec models) [[🔗 repo](https://github.com/shenweichen/DeepCTR)]
- Microsoft Recommenders (utils + examples) [[🔗 repo](https://github.com/microsoft/recommenders)]
- OpenHands (general LLM agent platform; useful for building agentic recommenders) [[🔗 repo](https://github.com/All-Hands-AI/OpenHands)]

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Citation

If you find this repo useful, feel free to cite it (add your bibtex here).
