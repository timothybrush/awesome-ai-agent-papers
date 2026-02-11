

<div align="center">

<a href="https://github.com/VoltAgent/voltagent">
<img width="1500" height="500" alt="cover-image" src="https://github.com/user-attachments/assets/23718e60-9ad3-4105-999c-8372713c3fbb" />
</a>

<br/>
<br/>

<div align="center">
    <strong>Hand-picked research papers on the AI agent ecosystem, published in 2026.
    </strong>
    <br />
    <br />

</div>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<a href="https://github.com/VoltAgent/voltagent">
  <img alt="VoltAgent" src="https://cdn.voltagent.dev/website/logo/logo-2-svg.svg" height="20" />
</a>

![Papers Count](https://img.shields.io/badge/Research%20Papers-49+-b31b1b)
![Last Update](https://img.shields.io/github/last-commit/VoltAgent/awesome-ai-agent-papers?label=Last%20update)
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)

</div>

# Awesome AI Agent Papers

A curated collection of research papers **published in 2026** and sourced from arXiv, covering core topics from the AI agent ecosystem like **multi-agent coordination**, **memory & RAG**, **tooling**, **evaluation & observability**, and **security**.

Whether you're an AI engineer building agent systems, a researcher exploring new architectures, or a developer integrating LLM agents into products, these papers help you stay on top of what's actually working, what's breaking, and where the field is heading. Updated weekly from arXiv.

### Table of Contents

- [Multi-Agent](#multi-agent) (9)
- [Memory & RAG](#memory--rag) (8)
- [Eval & Observability](#eval--observability) (10)
- [Agent Tooling](#agent-tooling) (9)
- [AI Agent Security](#ai-agent-security) (12)

<br>

<details open id="multi-agent">
<summary><h3 style="display:inline">Multi-Agent (9)</h3></summary>

<br>

| Paper | arXiv ID |
|---|:---:|
| **[DyTopo: Dynamic Topology Routing for Multi-Agent Reasoning via Semantic Matching](https://arxiv.org/pdf/2602.06039v1)** - Investigates dynamically rewiring agent-to-agent connections at each reasoning round via semantic matching instead of fixed communication topologies. | <a href="https://arxiv.org/abs/2602.06039v1"><img src="https://img.shields.io/badge/arXiv-2602.06039-b31b1b.svg" alt="arXiv" /></a> |
| **[RuleSmith: Multi-Agent LLMs for Automated Game Balancing](https://arxiv.org/pdf/2602.06232v1)** - Explores automated game balancing by combining multi-agent LLM self-play with Bayesian optimization on a civ-style game. | <a href="https://arxiv.org/abs/2602.06232v1"><img src="https://img.shields.io/badge/arXiv-2602.06232-b31b1b.svg" alt="arXiv" /></a> |
| **[CommCP: Efficient Multi-Agent Coordination via LLM-Based Communication with Conformal Prediction](https://arxiv.org/pdf/2602.06038v1)** - Examines how conformal prediction can filter noisy inter-agent messages to improve multi-robot coordination. | <a href="https://arxiv.org/abs/2602.06038v1"><img src="https://img.shields.io/badge/arXiv-2602.06038-b31b1b.svg" alt="arXiv" /></a> |
| **[AgenticPay: A Multi-Agent LLM Negotiation System for Buyer-Seller Transactions](https://arxiv.org/pdf/2602.06008v1)** - Introduces a 110+ task benchmark to evaluate how well multi-agent LLM systems handle buyer-seller negotiation through natural language. | <a href="https://arxiv.org/abs/2602.06008v1"><img src="https://img.shields.io/badge/arXiv-2602.06008-b31b1b.svg" alt="arXiv" /></a> |
| **[Gender Dynamics and Homophily in a Social Network of LLM Agents](https://arxiv.org/pdf/2602.02606v1)** - Analyzes social network formation among 70K+ autonomous LLM agents on Chirper.ai to study emergent group behavior and bias. | <a href="https://arxiv.org/abs/2602.02606v1"><img src="https://img.shields.io/badge/arXiv-2602.02606-b31b1b.svg" alt="arXiv" /></a> |
| **[ROMA: Recursive Open Meta-Agent Framework for Long-Horizon Multi-Agent Systems](https://arxiv.org/pdf/2602.01848v1)** - Proposes breaking large tasks into subtask trees that run in parallel across multiple agents to handle long-horizon workflows without exceeding context windows. | <a href="https://arxiv.org/abs/2602.01848v1"><img src="https://img.shields.io/badge/arXiv-2602.01848-b31b1b.svg" alt="arXiv" /></a> |
| **[INDIBATOR: Diverse and Fact-Grounded Individuality for Multi-Agent Debate in Molecular Discovery](https://arxiv.org/pdf/2602.01815v1)** - Explores assigning each agent a unique research profile built from real publication history instead of generic roles to improve multi-agent debate in molecular discovery. | <a href="https://arxiv.org/abs/2602.01815v1"><img src="https://img.shields.io/badge/arXiv-2602.01815-b31b1b.svg" alt="arXiv" /></a> |
| **[ORCH: many analyses, one merge — a deterministic multi-agent orchestrator](https://arxiv.org/pdf/2602.01797v1)** - Proposes a deterministic multi-agent orchestrator where multiple LLMs analyze a problem independently and a merge agent selects the best answer without any training. | <a href="https://arxiv.org/abs/2602.01797v1"><img src="https://img.shields.io/badge/arXiv-2602.01797-b31b1b.svg" alt="arXiv" /></a> |
| **[H-AdminSim: A Multi-Agent Simulator for Realistic Hospital Administrative Workflows](https://arxiv.org/pdf/2602.05407v1)** - Simulates end-to-end hospital administrative workflows with multi-agent LLMs and FHIR integration to test LLM-driven automation in healthcare settings. | <a href="https://arxiv.org/abs/2602.05407v1"><img src="https://img.shields.io/badge/arXiv-2602.05407-b31b1b.svg" alt="arXiv" /></a> |

</details>

<br>

<details open id="memory--rag">
<summary><h3 style="display:inline">Memory & RAG (8)</h3></summary>

<br>

| Paper | arXiv ID |
|---|:---:|
| **[BudgetMem: Learning Query-Aware Budget-Tier Routing for Runtime Agent Memory](https://arxiv.org/pdf/2602.06025v1)** - Investigates routing agent memory queries to different processing tiers based on query difficulty to control the cost-accuracy trade-off at runtime. | <a href="https://arxiv.org/abs/2602.06025v1"><img src="https://img.shields.io/badge/arXiv-2602.06025-b31b1b.svg" alt="arXiv" /></a> |
| **[Learning to Share: Selective Memory for Efficient Parallel Agentic Systems](https://arxiv.org/pdf/2602.05965v1)** - Proposes a shared memory bank with a learned controller that decides what information is worth passing between parallel agent teams to reduce redundant work. | <a href="https://arxiv.org/abs/2602.05965v1"><img src="https://img.shields.io/badge/arXiv-2602.05965-b31b1b.svg" alt="arXiv" /></a> |
| **[CompactRAG: Reducing LLM Calls and Token Overhead in Multi-Hop Question Answering](https://arxiv.org/pdf/2602.05728v1)** - Explores converting a corpus into atomic QA pairs offline to resolve multi-hop questions with just two LLM calls regardless of hop count. | <a href="https://arxiv.org/abs/2602.05728v1"><img src="https://img.shields.io/badge/arXiv-2602.05728-b31b1b.svg" alt="arXiv" /></a> |
| **[Mitigating Hallucination in Financial Retrieval-Augmented Generation via Fine-Grained Knowledge Verification](https://arxiv.org/pdf/2602.05723v1)** - Examines breaking financial RAG answers into atomic facts and verifying each against retrieved documents using reinforcement learning rewards. | <a href="https://arxiv.org/abs/2602.05723v1"><img src="https://img.shields.io/badge/arXiv-2602.05723-b31b1b.svg" alt="arXiv" /></a> |
| **[Graph-based Agent Memory: Taxonomy, Techniques, and Applications](https://arxiv.org/pdf/2602.05665v1)** - Surveys graph-based memory architectures for agents, covering extraction, storage, retrieval, and how memory evolves over time. | <a href="https://arxiv.org/abs/2602.05665v1"><img src="https://img.shields.io/badge/arXiv-2602.05665-b31b1b.svg" alt="arXiv" /></a> |
| **[AI Agent Systems for Supply Chains: Structured Decision Prompts and Memory Retrieval](https://arxiv.org/pdf/2602.05524v1)** - Proposes a multi-agent system for inventory management that retrieves similar past decisions to adapt ordering across various supply chain scenarios. | <a href="https://arxiv.org/abs/2602.05524v1"><img src="https://img.shields.io/badge/arXiv-2602.05524-b31b1b.svg" alt="arXiv" /></a> |
| **[SOPRAG: Multi-view Graph Experts Retrieval for Industrial Standard Operating Procedures](https://arxiv.org/pdf/2602.01858v1)** - Explores replacing flat chunk-based RAG with graph experts that understand entity relationships, causality, and process flows for structured documents like SOPs. | <a href="https://arxiv.org/abs/2602.01858v1"><img src="https://img.shields.io/badge/arXiv-2602.01858-b31b1b.svg" alt="arXiv" /></a> |
| **[ProcMEM: Learning Reusable Procedural Memory from Experience via Non-Parametric PPO for LLM Agents](https://arxiv.org/pdf/2602.01869v1)** - Investigates letting agents save step-by-step procedural skills from past runs and reuse them later without retraining to reduce repeated computation. | <a href="https://arxiv.org/abs/2602.01869v1"><img src="https://img.shields.io/badge/arXiv-2602.01869-b31b1b.svg" alt="arXiv" /></a> |

</details>

<br>

<details open id="eval--observability">
<summary><h3 style="display:inline">Eval & Observability (10)</h3></summary>

<br>

| Paper | arXiv ID |
|---|:---:|
| **[From Features to Actions: Explainability in Traditional and Agentic AI Systems](https://arxiv.org/pdf/2602.06841v1)** - Examines why standard feature-attribution explanations fail for debugging agent failures and proposes trace-based diagnostics for multi-step agent runs. | <a href="https://arxiv.org/abs/2602.06841v1"><img src="https://img.shields.io/badge/arXiv-2602.06841-b31b1b.svg" alt="arXiv" /></a> |
| **[Agentic Uncertainty Reveals Agentic Overconfidence](https://arxiv.org/pdf/2602.06948v1)** - Investigates whether agents can accurately predict their own success rates in agentic tasks. | <a href="https://arxiv.org/abs/2602.06948v1"><img src="https://img.shields.io/badge/arXiv-2602.06948-b31b1b.svg" alt="arXiv" /></a> |
| **[AIRS-Bench: a Suite of Tasks for Frontier AI Research Science Agents](https://arxiv.org/pdf/2602.06855v1)** - Introduces 20 research tasks from real ML papers covering idea generation, experiments, and refinement for benchmarking science agents. | <a href="https://arxiv.org/abs/2602.06855v1"><img src="https://img.shields.io/badge/arXiv-2602.06855-b31b1b.svg" alt="arXiv" /></a> |
| **[JADE: Expert-Grounded Dynamic Evaluation for Open-Ended Professional Tasks](https://arxiv.org/pdf/2602.06486v1)** - Proposes evaluating agent outputs by decomposing responses into individual claims and checking each against expert knowledge. | <a href="https://arxiv.org/abs/2602.06486v1"><img src="https://img.shields.io/badge/arXiv-2602.06486-b31b1b.svg" alt="arXiv" /></a> |
| **[Completing Missing Annotation: Multi-Agent Debate for Accurate Relevant Assessment](https://arxiv.org/pdf/2602.06526v1)** - Explores using multi-agent debate to fill missing labels in information retrieval benchmarks. | <a href="https://arxiv.org/abs/2602.06526v1"><img src="https://img.shields.io/badge/arXiv-2602.06526-b31b1b.svg" alt="arXiv" /></a> |
| **[TrajAD: Trajectory Anomaly Detection for Trustworthy LLM Agents](https://arxiv.org/pdf/2602.06443v1)** - Proposes a specialized verifier that detects and locates errors in agent execution trajectories at runtime to enable precise rollback-and-retry. | <a href="https://arxiv.org/abs/2602.06443v1"><img src="https://img.shields.io/badge/arXiv-2602.06443-b31b1b.svg" alt="arXiv" /></a> |
| **[Emulating Aggregate Human Choice Behavior and Biases with GPT Conversational Agents](https://arxiv.org/pdf/2602.05597v1)** - Examines whether GPT-4/5 agents can reproduce aggregate human cognitive biases in interactive decision-making scenarios. | <a href="https://arxiv.org/abs/2602.05597v1"><img src="https://img.shields.io/badge/arXiv-2602.05597-b31b1b.svg" alt="arXiv" /></a> |
| **[Capture the Flags: Family-Based Evaluation of Agentic LLMs](https://arxiv.org/pdf/2602.05523v1)** - Proposes generating families of equivalent CTF challenges through code transformations to test whether agents truly understand exploits or just memorize patterns. | <a href="https://arxiv.org/abs/2602.05523v1"><img src="https://img.shields.io/badge/arXiv-2602.05523-b31b1b.svg" alt="arXiv" /></a> |
| **[PieArena: Frontier Language Agents Achieve MBA-Level Negotiation](https://arxiv.org/pdf/2602.05302v1)** - Introduces a negotiation benchmark where frontier LLM agents are evaluated against MBA students to reveal cross-model differences in deception, accuracy, and trustworthiness. | <a href="https://arxiv.org/abs/2602.05302v1"><img src="https://img.shields.io/badge/arXiv-2602.05302-b31b1b.svg" alt="arXiv" /></a> |
| **[ES-MemEval: Benchmarking Conversational Agents on Personalized Long-Term Emotional Support](https://arxiv.org/pdf/2602.01885v1)** - Benchmarks how well conversational agents retain and use personal information over long emotional support conversations. | <a href="https://arxiv.org/abs/2602.01885v1"><img src="https://img.shields.io/badge/arXiv-2602.01885-b31b1b.svg" alt="arXiv" /></a> |

</details>

<br>

<details open id="agent-tooling">
<summary><h3 style="display:inline">Agent Tooling (9)</h3></summary>

<br>

| Paper | arXiv ID |
|---|:---:|
| **[TraceCoder: A Trace-Driven Multi-Agent Framework for Automated Debugging](https://arxiv.org/pdf/2602.06875v1)** - Proposes a multi-agent observe-analyze-repair loop that uses runtime traces to find and fix bugs in LLM-generated code. | <a href="https://arxiv.org/abs/2602.06875v1"><img src="https://img.shields.io/badge/arXiv-2602.06875-b31b1b.svg" alt="arXiv" /></a> |
| **[RocqSmith: Can Automatic Optimization Forge Better Proof Agents?](https://arxiv.org/pdf/2602.05762v1)** - Tests automated agent optimization methods on theorem proving, comparing simple few-shot bootstrapping against fancier optimizers like DSPy and TextGrad. | <a href="https://arxiv.org/abs/2602.05762v1"><img src="https://img.shields.io/badge/arXiv-2602.05762-b31b1b.svg" alt="arXiv" /></a> |
| **[Generative Ontology: When Structured Knowledge Learns to Create](https://arxiv.org/pdf/2602.05636v1)** - Explores constraining LLM generation with executable schemas and multi-agent roles to produce structurally valid yet creative outputs. | <a href="https://arxiv.org/abs/2602.05636v1"><img src="https://img.shields.io/badge/arXiv-2602.05636-b31b1b.svg" alt="arXiv" /></a> |
| **[LinguistAgent: A Reflective Multi-Model Platform for Automated Linguistic Annotation](https://arxiv.org/pdf/2602.05493v1)** - Proposes a dual-agent Annotator-Reviewer workflow for linguistic annotation that supports prompting, RAG, and fine-tuning with built-in quality checks. | <a href="https://arxiv.org/abs/2602.05493v1"><img src="https://img.shields.io/badge/arXiv-2602.05493-b31b1b.svg" alt="arXiv" /></a> |
| **[Structured Context Engineering for File-Native Agentic Systems](https://arxiv.org/pdf/2602.05447v1)** - Tests how context format (YAML, JSON, Markdown) affects agent accuracy across 9,649 experiments in file-native agentic systems. | <a href="https://arxiv.org/abs/2602.05447v1"><img src="https://img.shields.io/badge/arXiv-2602.05447-b31b1b.svg" alt="arXiv" /></a> |
| **[M2-Miner: Multi-Agent Enhanced MCTS for Mobile GUI Agent Data Mining](https://arxiv.org/pdf/2602.05429v1)** - Proposes automatically mining high-quality training trajectories for mobile GUI agents using multi-agent MCTS without manual annotation. | <a href="https://arxiv.org/abs/2602.05429v1"><img src="https://img.shields.io/badge/arXiv-2602.05429-b31b1b.svg" alt="arXiv" /></a> |
| **[ProAct: Agentic Lookahead in Interactive Environments](https://arxiv.org/pdf/2602.05327v1)** - Explores training agents to think ahead by distilling environment search into causal reasoning chains in interactive environments. | <a href="https://arxiv.org/abs/2602.05327v1"><img src="https://img.shields.io/badge/arXiv-2602.05327-b31b1b.svg" alt="arXiv" /></a> |
| **[Autonomous Question Formation for Large Language Model-Driven AI Systems](https://arxiv.org/pdf/2602.01556v1)** - Investigates teaching agents to ask themselves the right questions before acting to adapt to new situations autonomously. | <a href="https://arxiv.org/abs/2602.01556v1"><img src="https://img.shields.io/badge/arXiv-2602.01556-b31b1b.svg" alt="arXiv" /></a> |
| **[From Perception to Action: Spatial AI Agents and World Models](https://arxiv.org/pdf/2602.01644v1)** - Surveys the connection between agentic architectures and spatial tasks like robotics and navigation, covering memory, planning, and world models in embodied agents. | <a href="https://arxiv.org/abs/2602.01644v1"><img src="https://img.shields.io/badge/arXiv-2602.01644-b31b1b.svg" alt="arXiv" /></a> |

</details>

<br>

<details open id="ai-agent-security">
<summary><h3 style="display:inline">AI Agent Security (12)</h3></summary>

<br>

| Paper | arXiv ID |
|---|:---:|
| **[LLM Active Alignment: A Nash Equilibrium Perspective](https://arxiv.org/pdf/2602.06836v1)** - Models multi-agent LLM populations as a game where agents choose which user groups to align with, examining scenarios where some groups get ignored. | <a href="https://arxiv.org/abs/2602.06836v1"><img src="https://img.shields.io/badge/arXiv-2602.06836-b31b1b.svg" alt="arXiv" /></a> |
| **[Confundo: Learning to Generate Robust Poison for Practical RAG Systems](https://arxiv.org/pdf/2602.06616v1)** - Trains an LLM to generate RAG poison that survives real-world content processing and query variation for stress-testing RAG defenses. | <a href="https://arxiv.org/abs/2602.06616v1"><img src="https://img.shields.io/badge/arXiv-2602.06616-b31b1b.svg" alt="arXiv" /></a> |
| **[Malicious Agent Skills in the Wild: A Large-Scale Security Empirical Study](https://arxiv.org/pdf/2602.06547v1)** - Analyzes 98K agent skills from community registries to study the prevalence and nature of malicious third-party agent plugins. | <a href="https://arxiv.org/abs/2602.06547v1"><img src="https://img.shields.io/badge/arXiv-2602.06547-b31b1b.svg" alt="arXiv" /></a> |
| **[Subgraph Reconstruction Attacks on Graph RAG Deployments with Practical Defenses](https://arxiv.org/pdf/2602.06495v1)** - Investigates whether attackers can reconstruct knowledge graphs from Graph RAG outputs through multi-turn probing. | <a href="https://arxiv.org/abs/2602.06495v1"><img src="https://img.shields.io/badge/arXiv-2602.06495-b31b1b.svg" alt="arXiv" /></a> |
| **[Zero-Trust Runtime Verification for Agentic Payment Protocols](https://arxiv.org/pdf/2602.06345v1)** - Proposes consume-once mandate semantics for AI agent payment protocols to prevent replay and redirect attacks in autonomous transactions. | <a href="https://arxiv.org/abs/2602.06345v1"><img src="https://img.shields.io/badge/arXiv-2602.06345-b31b1b.svg" alt="arXiv" /></a> |
| **[Identifying Adversary Tactics and Techniques in Malware Binaries with an LLM Agent](https://arxiv.org/pdf/2602.06325v1)** - Explores using an LLM agent to identify attack techniques in stripped malware binaries through incremental context retrieval. | <a href="https://arxiv.org/abs/2602.06325v1"><img src="https://img.shields.io/badge/arXiv-2602.06325-b31b1b.svg" alt="arXiv" /></a> |
| **[Trustworthy AI Software Engineers](https://arxiv.org/pdf/2602.06310v1)** - Defines trustworthiness criteria for AI coding agents across technical quality, transparency, epistemic humility, and ethics. | <a href="https://arxiv.org/abs/2602.06310v1"><img src="https://img.shields.io/badge/arXiv-2602.06310-b31b1b.svg" alt="arXiv" /></a> |
| **[Agent2Agent Threats in Safety-Critical LLM Assistants: A Human-Centric Taxonomy](https://arxiv.org/pdf/2602.05877v1)** - Maps attack paths in agent-to-agent communication protocols for automotive LLM assistants, from driver distraction to unauthorized vehicle control. | <a href="https://arxiv.org/abs/2602.05877v1"><img src="https://img.shields.io/badge/arXiv-2602.05877-b31b1b.svg" alt="arXiv" /></a> |
| **[Learning to Inject: Automated Prompt Injection via Reinforcement Learning](https://arxiv.org/pdf/2602.05746v1)** - Explores using reinforcement learning to auto-generate prompt injection attacks that transfer across multiple frontier LLM models. | <a href="https://arxiv.org/abs/2602.05746v1"><img src="https://img.shields.io/badge/arXiv-2602.05746-b31b1b.svg" alt="arXiv" /></a> |
| **[A Dual-Loop Agent Framework for Automated Vulnerability Reproduction](https://arxiv.org/pdf/2602.05721v1)** - Proposes an LLM agent with dual feedback loops for strategy and code to automate vulnerability reproduction from CVE descriptions. | <a href="https://arxiv.org/abs/2602.05721v1"><img src="https://img.shields.io/badge/arXiv-2602.05721-b31b1b.svg" alt="arXiv" /></a> |
| **[Human Society-Inspired Approaches to Agentic AI Security: The 4C Framework](https://arxiv.org/pdf/2602.01942v1)** - Organizes agentic security risks into four layers (Core, Connection, Cognition, Compliance) to address trust and governance issues beyond prompt injection. | <a href="https://arxiv.org/abs/2602.01942v1"><img src="https://img.shields.io/badge/arXiv-2602.01942-b31b1b.svg" alt="arXiv" /></a> |
| **[MAGIC: A Co-Evolving Attacker-Defender Adversarial Game for Robust LLM Safety](https://arxiv.org/pdf/2602.01539v2)** - Proposes a co-evolving RL game between an attacker and defender agent to stress-test safety alignment against novel attack patterns. | <a href="https://arxiv.org/abs/2602.01539v2"><img src="https://img.shields.io/badge/arXiv-2602.01539-b31b1b.svg" alt="arXiv" /></a> |

</details>

## Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

- Submit new papers via PR
- Suggest category improvements

## License

MIT License - see [LICENSE](LICENSE)

This is a curated list. Papers listed here are created and published by their respective authors, not by us. We curate papers relevant to the AI agent ecosystem and do not audit, endorse, or guarantee the correctness of listed research.

If you find an issue with a listed paper or want a paper removed, please [open an issue](https://github.com/VoltAgent/awesome-ai-agent-papers/issues) and we'll take care of it promptly.
