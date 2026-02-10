# Awesome AI Agent Papers

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A weekly curated list of the freshest AI agent research straight from arXiv. These are brand-new papers published in 2026, hand-picked for AI/LLM agent developers who want to stay ahead of the curve.

## Latest (2026-02-02 to 2026-02-09)

<details>
<summary><strong>Observability</strong> (2)</summary>

| Paper |
|---|
| **[From Features to Actions: Explainability in Traditional and Agentic AI Systems](https://arxiv.org/pdf/2602.06841v1)** - Shows that standard feature-attribution explanations don't work for debugging agent failures. Trace-based diagnostics catch execution breakdowns much better, helping developers pinpoint where multi-step agent runs go wrong. |
| **[TrajAD: Trajectory Anomaly Detection for Trustworthy LLM Agents](https://arxiv.org/pdf/2602.06443v1)** - Catches and pinpoints errors in agent runs as they happen, so developers can retry from the exact failure point instead of restarting the whole thing. |

</details>

<details>
<summary><strong>Evaluation</strong> (7)</summary>

| Paper |
|---|
| **[Agentic Uncertainty Reveals Agentic Overconfidence](https://arxiv.org/pdf/2602.06948v1)** - Tests whether agents can predict their own success. Spoiler: agents that succeed only 22% of the time predict 77% success, helping developers understand when not to trust agent self-assessments. |
| **[AIRS-Bench: a Suite of Tasks for Frontier AI Research Science Agents](https://arxiv.org/pdf/2602.06855v1)** - 20 research tasks from real ML papers covering idea generation, experiments, and refinement, helping developers benchmark science agents on realistic end-to-end challenges. |
| **[JADE: Expert-Grounded Dynamic Evaluation for Open-Ended Professional Tasks](https://arxiv.org/pdf/2602.06486v1)** - Breaks agent responses into individual claims and checks each one against expert knowledge, helping developers catch mistakes that a single LLM judge would miss. |
| **[Completing Missing Annotation: Multi-Agent Debate for Accurate Relevant Assessment](https://arxiv.org/pdf/2602.06526v1)** - Uses multi-agent debate to find missing labels in IR benchmarks, achieving 95% accuracy with only 3.5% human involvement. Helps developers build fairer retrieval evaluations. |
| **[Capture the Flags: Family-Based Evaluation of Agentic LLMs](https://arxiv.org/pdf/2602.05523v1)** - Generates families of equivalent CTF challenges via code transformations to test if agents truly understand exploits or just memorize patterns, helping developers evaluate agent robustness. |
| **[PieArena: Frontier Language Agents Achieve MBA-Level Negotiation](https://arxiv.org/pdf/2602.05302v1)** - A negotiation benchmark where frontier LLM agents match or beat MBA students. Reveals cross-model differences in deception, accuracy, and trustworthiness that simple win-rate metrics hide. |
| **[ES-MemEval: Benchmarking Conversational Agents on Personalized Long-Term Emotional Support](https://arxiv.org/pdf/2602.01885v1)** - A benchmark that tests how well agents remember things over long conversations, helping developers spot memory weaknesses like forgetting past context or hallucinating outdated info. |

</details>

<details>
<summary><strong>Tooling</strong> (7)</summary>

| Paper |
|---|
| **[TraceCoder: A Trace-Driven Multi-Agent Framework for Automated Debugging](https://arxiv.org/pdf/2602.06875v1)** - Uses runtime traces to find and fix bugs in LLM-generated code through a multi-agent observe-analyze-repair loop, helping developers automate debugging with 34% better fix rates. |
| **[SeeUPO: Sequence-Level Agentic-RL with Convergence Guarantees](https://arxiv.org/pdf/2602.06554v1)** - A critic-free RL algorithm that actually converges in multi-turn agent training, helping developers avoid the training instability that current PPO/GRPO methods suffer from. |
| **[RocqSmith: Can Automatic Optimization Forge Better Proof Agents?](https://arxiv.org/pdf/2602.05762v1)** - Tests automated agent optimization methods on theorem proving. Finds that simple few-shot bootstrapping beats fancier optimizers, helping developers set realistic expectations for auto-tuning agents. |
| **[Generative Ontology: When Structured Knowledge Learns to Create](https://arxiv.org/pdf/2602.05636v1)** - Constrains LLM generation with executable schemas and multi-agent roles so outputs are structurally valid, helping developers get creative results without hallucinated nonsense. |
| **[LinguistAgent: A Reflective Multi-Model Platform for Automated Linguistic Annotation](https://arxiv.org/pdf/2602.05493v1)** - A dual-agent Annotator-Reviewer workflow for annotation that supports prompting, RAG, and fine-tuning, helping developers automate complex labeling tasks with built-in quality checks. |
| **[Structured Context Engineering for File-Native Agentic Systems](https://arxiv.org/pdf/2602.05447v1)** - Tests how format (YAML, JSON, Markdown) and file-based context affect agent accuracy across 9,649 experiments. Model capability matters far more than format, helping developers skip format bike-shedding. |
| **[M2-Miner: Multi-Agent Enhanced MCTS for Mobile GUI Agent Data Mining](https://arxiv.org/pdf/2602.05429v1)** - Automatically mines high-quality training trajectories for GUI agents using multi-agent MCTS, helping developers build better mobile agents without expensive manual annotation. |

</details>

<details>
<summary><strong>Memory</strong> (4)</summary>

| Paper |
|---|
| **[BudgetMem: Learning Query-Aware Budget-Tier Routing for Runtime Agent Memory](https://arxiv.org/pdf/2602.06025v1)** - Gives agents a router that picks cheap or expensive memory processing per query, helping developers control the cost-accuracy trade-off of agent memory at runtime. |
| **[Learning to Share: Selective Memory for Efficient Parallel Agentic Systems](https://arxiv.org/pdf/2602.05965v1)** - Adds a shared memory bank across parallel agent teams with a learned controller that decides what's worth sharing, helping developers cut redundant work when running multiple agent teams. |
| **[Graph-based Agent Memory: Taxonomy, Techniques, and Applications](https://arxiv.org/pdf/2602.05665v1)** - A comprehensive survey of graph-based memory for agents covering extraction, storage, retrieval, and evolution, helping developers pick the right memory architecture for their use case. |
| **[ProcMEM: Learning Reusable Procedural Memory from Experience via Non-Parametric PPO for LLM Agents](https://arxiv.org/pdf/2602.01869v1)** - Lets agents save step-by-step "how-to" skills from past runs and reuse them later without retraining, helping developers cut repeated computation and make agents more consistent. |

</details>

<details>
<summary><strong>Planning</strong> (2)</summary>

| Paper |
|---|
| **[ProAct: Agentic Lookahead in Interactive Environments](https://arxiv.org/pdf/2602.05327v1)** - Trains agents to "think ahead" by distilling environment search into causal reasoning chains. A 4B model trained with ProAct beats all open-source baselines and rivals closed-source models. |
| **[Autonomous Question Formation for Large Language Model-Driven AI Systems](https://arxiv.org/pdf/2602.01556v1)** - Teaches agents to ask themselves the right questions before acting, helping developers build agents that adapt to new situations instead of waiting for human prompts. |

</details>

<details>
<summary><strong>Multi-Agent</strong> (6)</summary>

| Paper |
|---|
| **[DyTopo: Dynamic Topology Routing for Multi-Agent Reasoning via Semantic Matching](https://arxiv.org/pdf/2602.06039v1)** - Rebuilds the communication graph between agents at each reasoning round based on what each agent needs and offers, helping developers avoid fixed patterns that waste messages. |
| **[CommCP: Efficient Multi-Agent Coordination via LLM-Based Communication with Conformal Prediction](https://arxiv.org/pdf/2602.06038v1)** - Filters out noisy messages between agents so they only share what actually matters, helping developers build multi-agent systems that coordinate without drowning in chatter. |
| **[AgenticPay: A Multi-Agent LLM Negotiation System for Buyer-Seller Transactions](https://arxiv.org/pdf/2602.06008v1)** - A benchmark for multi-agent buyer-seller negotiation through natural language with 110+ tasks, helping developers test how well agents handle strategic economic interactions. |
| **[ROMA: Recursive Open Meta-Agent Framework for Long-Horizon Multi-Agent Systems](https://arxiv.org/pdf/2602.01848v1)** - Breaks big tasks into subtask trees that run in parallel across multiple agents, helping developers handle long, complex workflows without blowing up the context window. |
| **[INDIBATOR: Diverse and Fact-Grounded Individuality for Multi-Agent Debate in Molecular Discovery](https://arxiv.org/pdf/2602.01815v1)** - Gives each agent a unique research profile instead of a generic "reviewer" role, helping developers get higher-quality debate and discovery from multi-agent setups. |
| **[ORCH: many analyses, one merge — a deterministic multi-agent orchestrator](https://arxiv.org/pdf/2602.01797v1)** - Multiple LLMs analyze a problem independently, then a merge agent picks the best answer. Deterministic and training-free, helping developers get reproducible multi-agent results. |

</details>

<details>
<summary><strong>RAG</strong> (3)</summary>

| Paper |
|---|
| **[CompactRAG: Reducing LLM Calls and Token Overhead in Multi-Hop Question Answering](https://arxiv.org/pdf/2602.05728v1)** - Converts a corpus into atomic QA pairs offline, then resolves multi-hop questions with just 2 LLM calls regardless of hop count, helping developers slash RAG costs while keeping accuracy. |
| **[Mitigating Hallucination in Financial Retrieval-Augmented Generation via Fine-Grained Knowledge Verification](https://arxiv.org/pdf/2602.05723v1)** - Breaks financial answers into atomic facts and checks each against retrieved docs using RL rewards, helping developers build RAG systems that stay faithful to source data. |
| **[SOPRAG: Multi-view Graph Experts Retrieval for Industrial Standard Operating Procedures](https://arxiv.org/pdf/2602.01858v1)** - Replaces flat chunk-based RAG with graph experts that understand entity relationships, causality, and process flows, helping developers build more accurate retrieval for structured documents. |

</details>

<details>
<summary><strong>Safety</strong> (10)</summary>

| Paper |
|---|
| **[LLM Active Alignment: A Nash Equilibrium Perspective](https://arxiv.org/pdf/2602.06836v1)** - Shows that when multiple LLMs compete for users, some user groups can get ignored entirely. Helps developers spot and fix blind spots in alignment before deployment. |
| **[Confundo: Learning to Generate Robust Poison for Practical RAG Systems](https://arxiv.org/pdf/2602.06616v1)** - Trains an LLM to generate RAG poison that survives real-world content processing and query variation, helping developers stress-test their RAG defenses against realistic attacks. |
| **[Malicious Agent Skills in the Wild: A Large-Scale Security Empirical Study](https://arxiv.org/pdf/2602.06547v1)** - Analyzes 98K agent skills from community registries and confirms 157 malicious ones averaging 4 vulnerabilities each, helping developers understand the real threat of third-party agent plugins. |
| **[Subgraph Reconstruction Attacks on Graph RAG Deployments with Practical Defenses](https://arxiv.org/pdf/2602.06495v1)** - Shows how attackers can reconstruct knowledge graphs from Graph RAG outputs using multi-turn probing, helping developers protect proprietary knowledge bases from extraction. |
| **[Zero-Trust Runtime Verification for Agentic Payment Protocols](https://arxiv.org/pdf/2602.06345v1)** - Makes sure AI agents can only spend money exactly once per approval, blocking replay and redirect attacks in autonomous payments with barely any latency cost. |
| **[Trustworthy AI Software Engineers](https://arxiv.org/pdf/2602.06310v1)** - Lays out what "trustworthy" actually means for AI coding agents — quality, honesty, knowing what they don't know — giving developers a checklist for evaluating AI dev tools. |
| **[Agent2Agent Threats in Safety-Critical LLM Assistants: A Human-Centric Taxonomy](https://arxiv.org/pdf/2602.05877v1)** - Maps attack paths in agent-to-agent communication (like Google A2A) for automotive LLM assistants, helping developers model threats from driver distraction to unauthorized vehicle control. |
| **[Learning to Inject: Automated Prompt Injection via Reinforcement Learning](https://arxiv.org/pdf/2602.05746v1)** - Uses RL to auto-generate prompt injection attacks that transfer across GPT-5, Claude, and Gemini on AgentDojo, helping developers red-team their agent defenses at scale. |
| **[Human Society-Inspired Approaches to Agentic AI Security: The 4C Framework](https://arxiv.org/pdf/2602.01942v1)** - Organizes agentic security risks into four layers (Core, Connection, Cognition, Compliance), helping developers think beyond prompt injection to broader trust and governance issues. |
| **[MAGIC: A Co-Evolving Attacker-Defender Adversarial Game for Robust LLM Safety](https://arxiv.org/pdf/2602.01539v2)** - Pits an attacker agent against a defender agent in a co-evolving RL game, helping developers stress-test safety alignment against novel attack patterns that static datasets miss. |

</details>

<details>
<summary><strong>Applications</strong> (6)</summary>

| Paper |
|---|
| **[Identifying Adversary Tactics and Techniques in Malware Binaries with an LLM Agent](https://arxiv.org/pdf/2602.06325v1)** - An LLM agent that reads malware binaries and identifies the attack techniques inside them at 93% precision, helping security developers automate threat analysis. |
| **[RuleSmith: Multi-Agent LLMs for Automated Game Balancing](https://arxiv.org/pdf/2602.06232v1)** - LLM agents play a civ-style game via self-play while Bayesian optimization tunes the rules, helping developers automate game balancing without manual playtesting. |
| **[A Dual-Loop Agent Framework for Automated Vulnerability Reproduction](https://arxiv.org/pdf/2602.05721v1)** - Give it a CVE description and it writes a working exploit to reproduce the bug. Two feedback loops — one for strategy, one for code — hit 83% success on real vulnerabilities. |
| **[AI Agent Systems for Supply Chains: Structured Decision Prompts and Memory Retrieval](https://arxiv.org/pdf/2602.05524v1)** - Agents remember past inventory decisions and reuse what worked before, helping developers build smarter supply chain systems that learn from experience. |
| **[H-AdminSim: A Multi-Agent Simulator for Realistic Hospital Administrative Workflows](https://arxiv.org/pdf/2602.05407v1)** - Simulates end-to-end hospital admin workflows with multi-agent LLMs and FHIR integration, helping developers test LLM-driven automation in healthcare settings. |
| **[From Perception to Action: Spatial AI Agents and World Models](https://arxiv.org/pdf/2602.01644v1)** - A large survey connecting agentic architectures with spatial tasks like robotics and navigation, helping developers understand where memory, planning, and world models fit in embodied agents. |

</details>

<details>
<summary><strong>Other</strong> (2)</summary>

| Paper |
|---|
| **[Emulating Aggregate Human Choice Behavior and Biases with GPT Conversational Agents](https://arxiv.org/pdf/2602.05597v1)** - Shows that GPT-4/5 agents reproduce human cognitive biases with precision in interactive decisions, helping developers understand when LLM agents might inherit and amplify human biases. |
| **[Gender Dynamics and Homophily in a Social Network of LLM Agents](https://arxiv.org/pdf/2602.02606v1)** - Studies how 70K+ autonomous LLM agents form social clusters on Chirper.ai, showing developers that emergent group behavior and bias can appear even without explicit programming. |

</details>

## Archive

- 2026-02-02 to 2026-02-09 — [list](lists/awesome-agents-2026-02-02-to-2026-02-09.md)

## Contributing

- Add new weekly lists under `lists/` and link them from the `Archive` section.
- Keep entries in the format `**Title** (YYYY-MM-DD) — 1–2 sentences. [arXiv] | [PDF]`.
- Assign exactly one category per paper.

## License

MIT — see `LICENSE`.
