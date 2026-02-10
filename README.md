<br/>

<div align="center">
    <strong>Hand-picked research papers on the AI/LLM agent ecosystem, published in 2026 and sourced from arXiv.
    </strong>
    <br />
    <br />

</div>

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<a href="https://github.com/VoltAgent/voltagent">
  <img alt="VoltAgent" src="https://cdn.voltagent.dev/website/logo/logo-2-svg.svg" height="20" />
</a>

![Papers Count](https://img.shields.io/badge/Research%20Papers-49+-b31b1b)
![Last Update](https://img.shields.io/github/last-commit/VoltAgent/awesome-ai-agent-papers?label=Last%20update)
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)

</div>

# Awesome AI Agent Papers

Brand-new papers published in 2026, curated weekly for AI/LLM agent developers who want to stay ahead of the curve.

<details open>
<summary><strong>Tooling</strong> (10)</summary>

<br>

| Paper | arXiv ID |
|---|:---:|
| **[TraceCoder: A Trace-Driven Multi-Agent Framework for Automated Debugging](https://arxiv.org/pdf/2602.06875v1)** - Uses runtime traces to find and fix bugs in LLM-generated code through an observe-analyze-repair loop. Gets 34% better fix rates than existing approaches. | <a href="https://arxiv.org/abs/2602.06875v1"><img src="https://img.shields.io/badge/arXiv-2602.06875-b31b1b.svg" alt="arXiv" /></a> |
| **[SeeUPO: Sequence-Level Agentic-RL with Convergence Guarantees](https://arxiv.org/pdf/2602.06554v1)** - Current PPO/GRPO methods are unstable when training multi-turn agents. This is a critic-free RL algorithm that actually converges. | <a href="https://arxiv.org/abs/2602.06554v1"><img src="https://img.shields.io/badge/arXiv-2602.06554-b31b1b.svg" alt="arXiv" /></a> |
| **[RocqSmith: Can Automatic Optimization Forge Better Proof Agents?](https://arxiv.org/pdf/2602.05762v1)** - Tests automated agent optimization methods on theorem proving. Simple few-shot bootstrapping outperforms fancier optimizers like DSPy and TextGrad. | <a href="https://arxiv.org/abs/2602.05762v1"><img src="https://img.shields.io/badge/arXiv-2602.05762-b31b1b.svg" alt="arXiv" /></a> |
| **[Generative Ontology: When Structured Knowledge Learns to Create](https://arxiv.org/pdf/2602.05636v1)** - Constrains LLM generation with executable schemas and multi-agent roles so outputs are structurally valid while still being creative. | <a href="https://arxiv.org/abs/2602.05636v1"><img src="https://img.shields.io/badge/arXiv-2602.05636-b31b1b.svg" alt="arXiv" /></a> |
| **[LinguistAgent: A Reflective Multi-Model Platform for Automated Linguistic Annotation](https://arxiv.org/pdf/2602.05493v1)** - A dual-agent Annotator-Reviewer workflow for labeling tasks. Supports prompting, RAG, and fine-tuning, with built-in quality checks between the two agents. | <a href="https://arxiv.org/abs/2602.05493v1"><img src="https://img.shields.io/badge/arXiv-2602.05493-b31b1b.svg" alt="arXiv" /></a> |
| **[Structured Context Engineering for File-Native Agentic Systems](https://arxiv.org/pdf/2602.05447v1)** - Tests whether YAML, JSON, or Markdown affects agent accuracy across 9,649 experiments. Result: model capability matters far more than format choice. | <a href="https://arxiv.org/abs/2602.05447v1"><img src="https://img.shields.io/badge/arXiv-2602.05447-b31b1b.svg" alt="arXiv" /></a> |
| **[M2-Miner: Multi-Agent Enhanced MCTS for Mobile GUI Agent Data Mining](https://arxiv.org/pdf/2602.05429v1)** - Automatically mines high-quality training trajectories for mobile GUI agents using multi-agent MCTS. No expensive manual annotation needed. | <a href="https://arxiv.org/abs/2602.05429v1"><img src="https://img.shields.io/badge/arXiv-2602.05429-b31b1b.svg" alt="arXiv" /></a> |
| **[ProAct: Agentic Lookahead in Interactive Environments](https://arxiv.org/pdf/2602.05327v1)** - Trains agents to think ahead by turning environment search into causal reasoning chains. A 4B model beats all open-source baselines and rivals closed-source models. | <a href="https://arxiv.org/abs/2602.05327v1"><img src="https://img.shields.io/badge/arXiv-2602.05327-b31b1b.svg" alt="arXiv" /></a> |
| **[Autonomous Question Formation for Large Language Model-Driven AI Systems](https://arxiv.org/pdf/2602.01556v1)** - Teaches agents to ask themselves the right questions before acting. Agents that do this adapt to new situations instead of waiting for human prompts. | <a href="https://arxiv.org/abs/2602.01556v1"><img src="https://img.shields.io/badge/arXiv-2602.01556-b31b1b.svg" alt="arXiv" /></a> |
| **[From Perception to Action: Spatial AI Agents and World Models](https://arxiv.org/pdf/2602.01644v1)** - A big survey connecting agentic architectures with spatial tasks like robotics and navigation. Covers where memory, planning, and world models fit in embodied agents. | <a href="https://arxiv.org/abs/2602.01644v1"><img src="https://img.shields.io/badge/arXiv-2602.01644-b31b1b.svg" alt="arXiv" /></a> |

</details>

<details>
<summary><strong>Memory & RAG</strong> (8)</summary>

<br>

| Paper | arXiv ID |
|---|:---:|
| **[BudgetMem: Learning Query-Aware Budget-Tier Routing for Runtime Agent Memory](https://arxiv.org/pdf/2602.06025v1)** - Not every memory lookup needs heavy processing. Routes agent memory queries to cheap or expensive tiers based on difficulty, so simple lookups don't cost as much as complex ones. | <a href="https://arxiv.org/abs/2602.06025v1"><img src="https://img.shields.io/badge/arXiv-2602.06025-b31b1b.svg" alt="arXiv" /></a> |
| **[Learning to Share: Selective Memory for Efficient Parallel Agentic Systems](https://arxiv.org/pdf/2602.05965v1)** - When parallel agent teams work on related tasks, they waste effort rediscovering the same things. This adds a shared memory with a filter that decides what's worth passing between teams. | <a href="https://arxiv.org/abs/2602.05965v1"><img src="https://img.shields.io/badge/arXiv-2602.05965-b31b1b.svg" alt="arXiv" /></a> |
| **[CompactRAG: Reducing LLM Calls and Token Overhead in Multi-Hop Question Answering](https://arxiv.org/pdf/2602.05728v1)** - Pre-processes a corpus into atomic QA pairs offline, then answers multi-hop questions with just 2 LLM calls no matter how many hops. Slashes RAG costs without losing accuracy. | <a href="https://arxiv.org/abs/2602.05728v1"><img src="https://img.shields.io/badge/arXiv-2602.05728-b31b1b.svg" alt="arXiv" /></a> |
| **[Mitigating Hallucination in Financial Retrieval-Augmented Generation via Fine-Grained Knowledge Verification](https://arxiv.org/pdf/2602.05723v1)** - Breaks financial RAG answers into atomic facts and checks each one against the retrieved docs. Uses RL rewards to keep outputs faithful to source data. | <a href="https://arxiv.org/abs/2602.05723v1"><img src="https://img.shields.io/badge/arXiv-2602.05723-b31b1b.svg" alt="arXiv" /></a> |
| **[Graph-based Agent Memory: Taxonomy, Techniques, and Applications](https://arxiv.org/pdf/2602.05665v1)** - A survey of how agents can use graphs to store and retrieve memory — covers extraction, storage, retrieval, and how memory evolves over time. | <a href="https://arxiv.org/abs/2602.05665v1"><img src="https://img.shields.io/badge/arXiv-2602.05665-b31b1b.svg" alt="arXiv" /></a> |
| **[AI Agent Systems for Supply Chains: Structured Decision Prompts and Memory Retrieval](https://arxiv.org/pdf/2602.05524v1)** - A multi-agent system for inventory management that retrieves similar past decisions to adapt ordering. Outperforms standard baselines across various supply chain scenarios. | <a href="https://arxiv.org/abs/2602.05524v1"><img src="https://img.shields.io/badge/arXiv-2602.05524-b31b1b.svg" alt="arXiv" /></a> |
| **[SOPRAG: Multi-view Graph Experts Retrieval for Industrial Standard Operating Procedures](https://arxiv.org/pdf/2602.01858v1)** - Flat chunk-based RAG doesn't work well for structured docs like SOPs. Uses graph experts that understand entity relationships, causality, and process flows instead. | <a href="https://arxiv.org/abs/2602.01858v1"><img src="https://img.shields.io/badge/arXiv-2602.01858-b31b1b.svg" alt="arXiv" /></a> |
| **[ProcMEM: Learning Reusable Procedural Memory from Experience via Non-Parametric PPO for LLM Agents](https://arxiv.org/pdf/2602.01869v1)** - Agents save step-by-step "how-to" skills from past runs and reuse them later without retraining. Cuts repeated computation and makes agents more consistent across similar tasks. | <a href="https://arxiv.org/abs/2602.01869v1"><img src="https://img.shields.io/badge/arXiv-2602.01869-b31b1b.svg" alt="arXiv" /></a> |

</details>

<details>
<summary><strong>Multi-Agent</strong> (9)</summary>

<br>

| Paper | arXiv ID |
|---|:---:|
| **[DyTopo: Dynamic Topology Routing for Multi-Agent Reasoning via Semantic Matching](https://arxiv.org/pdf/2602.06039v1)** - Instead of fixed communication patterns, rewires which agents talk to each other at every reasoning step based on what each one needs. Wastes fewer messages. | <a href="https://arxiv.org/abs/2602.06039v1"><img src="https://img.shields.io/badge/arXiv-2602.06039-b31b1b.svg" alt="arXiv" /></a> |
| **[RuleSmith: Multi-Agent LLMs for Automated Game Balancing](https://arxiv.org/pdf/2602.06232v1)** - LLM agents play a civ-style game via self-play while Bayesian optimization tunes the rules. Automates game balancing without manual playtesting. | <a href="https://arxiv.org/abs/2602.06232v1"><img src="https://img.shields.io/badge/arXiv-2602.06232-b31b1b.svg" alt="arXiv" /></a> |
| **[CommCP: Efficient Multi-Agent Coordination via LLM-Based Communication with Conformal Prediction](https://arxiv.org/pdf/2602.06038v1)** - Filters out noisy messages between agents so they only share what actually matters. Tested on multi-robot coordination tasks. | <a href="https://arxiv.org/abs/2602.06038v1"><img src="https://img.shields.io/badge/arXiv-2602.06038-b31b1b.svg" alt="arXiv" /></a> |
| **[AgenticPay: A Multi-Agent LLM Negotiation System for Buyer-Seller Transactions](https://arxiv.org/pdf/2602.06008v1)** - A benchmark with 110+ buyer-seller negotiation tasks in natural language. Tests how well agents handle strategic economic interactions. | <a href="https://arxiv.org/abs/2602.06008v1"><img src="https://img.shields.io/badge/arXiv-2602.06008-b31b1b.svg" alt="arXiv" /></a> |
| **[Gender Dynamics and Homophily in a Social Network of LLM Agents](https://arxiv.org/pdf/2602.02606v1)** - Studies 70K+ autonomous LLM agents on Chirper.ai. They naturally form gender-based social clusters without being programmed to — emergent bias in an all-AI network. | <a href="https://arxiv.org/abs/2602.02606v1"><img src="https://img.shields.io/badge/arXiv-2602.02606-b31b1b.svg" alt="arXiv" /></a> |
| **[ROMA: Recursive Open Meta-Agent Framework for Long-Horizon Multi-Agent Systems](https://arxiv.org/pdf/2602.01848v1)** - Breaks big tasks into subtask trees that run in parallel across multiple agents. Keeps context windows under control for long, complex workflows. | <a href="https://arxiv.org/abs/2602.01848v1"><img src="https://img.shields.io/badge/arXiv-2602.01848-b31b1b.svg" alt="arXiv" /></a> |
| **[INDIBATOR: Diverse and Fact-Grounded Individuality for Multi-Agent Debate in Molecular Discovery](https://arxiv.org/pdf/2602.01815v1)** - Instead of generic "reviewer" roles, gives each agent a unique research profile built from real publication history. Leads to higher-quality debate in multi-agent discovery. | <a href="https://arxiv.org/abs/2602.01815v1"><img src="https://img.shields.io/badge/arXiv-2602.01815-b31b1b.svg" alt="arXiv" /></a> |
| **[ORCH: many analyses, one merge — a deterministic multi-agent orchestrator](https://arxiv.org/pdf/2602.01797v1)** - Multiple LLMs analyze a problem independently, then a merge agent picks the best answer. Deterministic and training-free — same input, same output every time. | <a href="https://arxiv.org/abs/2602.01797v1"><img src="https://img.shields.io/badge/arXiv-2602.01797-b31b1b.svg" alt="arXiv" /></a> |
| **[H-AdminSim: A Multi-Agent Simulator for Realistic Hospital Administrative Workflows](https://arxiv.org/pdf/2602.05407v1)** - Simulates end-to-end hospital admin workflows with multi-agent LLMs and FHIR integration. A sandbox for testing LLM-driven automation in healthcare. | <a href="https://arxiv.org/abs/2602.05407v1"><img src="https://img.shields.io/badge/arXiv-2602.05407-b31b1b.svg" alt="arXiv" /></a> |

</details>

<details>
<summary><strong>Eval & Observability</strong> (10)</summary>

<br>

| Paper | arXiv ID |
|---|:---:|
| **[From Features to Actions: Explainability in Traditional and Agentic AI Systems](https://arxiv.org/pdf/2602.06841v1)** - Standard feature-attribution explanations don't work for debugging agent failures. Trace-based diagnostics are far better at catching where multi-step agent runs break down. | <a href="https://arxiv.org/abs/2602.06841v1"><img src="https://img.shields.io/badge/arXiv-2602.06841-b31b1b.svg" alt="arXiv" /></a> |
| **[Agentic Uncertainty Reveals Agentic Overconfidence](https://arxiv.org/pdf/2602.06948v1)** - Tests whether agents can predict their own success. Agents that succeed only 22% of the time predict 77% success — a big gap between confidence and actual ability. | <a href="https://arxiv.org/abs/2602.06948v1"><img src="https://img.shields.io/badge/arXiv-2602.06948-b31b1b.svg" alt="arXiv" /></a> |
| **[AIRS-Bench: a Suite of Tasks for Frontier AI Research Science Agents](https://arxiv.org/pdf/2602.06855v1)** - 20 research tasks pulled from real ML papers — idea generation, running experiments, refining results — for benchmarking how well science agents handle end-to-end research. | <a href="https://arxiv.org/abs/2602.06855v1"><img src="https://img.shields.io/badge/arXiv-2602.06855-b31b1b.svg" alt="arXiv" /></a> |
| **[JADE: Expert-Grounded Dynamic Evaluation for Open-Ended Professional Tasks](https://arxiv.org/pdf/2602.06486v1)** - Instead of judging agent output as a whole, breaks it into individual claims and checks each against expert knowledge. Catches mistakes a single LLM judge would miss. | <a href="https://arxiv.org/abs/2602.06486v1"><img src="https://img.shields.io/badge/arXiv-2602.06486-b31b1b.svg" alt="arXiv" /></a> |
| **[Completing Missing Annotation: Multi-Agent Debate for Accurate Relevant Assessment](https://arxiv.org/pdf/2602.06526v1)** - IR benchmarks have missing labels, which makes evaluations unfair. Multi-agent debate fills the gaps at 95% accuracy with only 3.5% human involvement. | <a href="https://arxiv.org/abs/2602.06526v1"><img src="https://img.shields.io/badge/arXiv-2602.06526-b31b1b.svg" alt="arXiv" /></a> |
| **[TrajAD: Trajectory Anomaly Detection for Trustworthy LLM Agents](https://arxiv.org/pdf/2602.06443v1)** - Catches and pinpoints errors in agent runs as they happen, so developers can retry from the exact failure point instead of restarting the whole thing. | <a href="https://arxiv.org/abs/2602.06443v1"><img src="https://img.shields.io/badge/arXiv-2602.06443-b31b1b.svg" alt="arXiv" /></a> |
| **[Emulating Aggregate Human Choice Behavior and Biases with GPT Conversational Agents](https://arxiv.org/pdf/2602.05597v1)** - GPT-4/5 agents reproduce human cognitive biases with surprising precision in interactive decisions. Worth knowing if your agents make choices that affect people. | <a href="https://arxiv.org/abs/2602.05597v1"><img src="https://img.shields.io/badge/arXiv-2602.05597-b31b1b.svg" alt="arXiv" /></a> |
| **[Capture the Flags: Family-Based Evaluation of Agentic LLMs](https://arxiv.org/pdf/2602.05523v1)** - Creates families of equivalent CTF challenges through code transformations. Tests whether agents actually understand exploits or just memorize patterns. | <a href="https://arxiv.org/abs/2602.05523v1"><img src="https://img.shields.io/badge/arXiv-2602.05523-b31b1b.svg" alt="arXiv" /></a> |
| **[PieArena: Frontier Language Agents Achieve MBA-Level Negotiation](https://arxiv.org/pdf/2602.05302v1)** - A negotiation benchmark where frontier LLM agents match or beat MBA students. Also reveals cross-model differences in deception, accuracy, and trustworthiness that win-rate metrics miss. | <a href="https://arxiv.org/abs/2602.05302v1"><img src="https://img.shields.io/badge/arXiv-2602.05302-b31b1b.svg" alt="arXiv" /></a> |
| **[ES-MemEval: Benchmarking Conversational Agents on Personalized Long-Term Emotional Support](https://arxiv.org/pdf/2602.01885v1)** - Tests how well agents remember things over long conversations. Exposes memory weaknesses like forgetting past context or hallucinating outdated info. | <a href="https://arxiv.org/abs/2602.01885v1"><img src="https://img.shields.io/badge/arXiv-2602.01885-b31b1b.svg" alt="arXiv" /></a> |

</details>

<details>
<summary><strong>Security</strong> (12)</summary>

<br>

| Paper | arXiv ID |
|---|:---:|
| **[LLM Active Alignment: A Nash Equilibrium Perspective](https://arxiv.org/pdf/2602.06836v1)** - Models what happens when multiple LLMs compete for users. Finds that some user groups can get ignored entirely — relevant for thinking about alignment blind spots. | <a href="https://arxiv.org/abs/2602.06836v1"><img src="https://img.shields.io/badge/arXiv-2602.06836-b31b1b.svg" alt="arXiv" /></a> |
| **[Confundo: Learning to Generate Robust Poison for Practical RAG Systems](https://arxiv.org/pdf/2602.06616v1)** - Trains an LLM to generate RAG poison that survives real-world content processing and query variation. Useful for stress-testing RAG defenses against realistic attacks. | <a href="https://arxiv.org/abs/2602.06616v1"><img src="https://img.shields.io/badge/arXiv-2602.06616-b31b1b.svg" alt="arXiv" /></a> |
| **[Malicious Agent Skills in the Wild: A Large-Scale Security Empirical Study](https://arxiv.org/pdf/2602.06547v1)** - Scanned 98K agent skills from community registries and found 157 malicious ones, averaging 4 vulnerabilities each. Relevant if you use third-party agent plugins. | <a href="https://arxiv.org/abs/2602.06547v1"><img src="https://img.shields.io/badge/arXiv-2602.06547-b31b1b.svg" alt="arXiv" /></a> |
| **[Subgraph Reconstruction Attacks on Graph RAG Deployments with Practical Defenses](https://arxiv.org/pdf/2602.06495v1)** - Attackers can reconstruct your knowledge graph from Graph RAG outputs just by asking the right sequence of questions. Also covers practical defenses. | <a href="https://arxiv.org/abs/2602.06495v1"><img src="https://img.shields.io/badge/arXiv-2602.06495-b31b1b.svg" alt="arXiv" /></a> |
| **[Zero-Trust Runtime Verification for Agentic Payment Protocols](https://arxiv.org/pdf/2602.06345v1)** - Makes sure AI agents can only spend money exactly once per approval, blocking replay and redirect attacks in autonomous payments with barely any latency cost. | <a href="https://arxiv.org/abs/2602.06345v1"><img src="https://img.shields.io/badge/arXiv-2602.06345-b31b1b.svg" alt="arXiv" /></a> |
| **[Identifying Adversary Tactics and Techniques in Malware Binaries with an LLM Agent](https://arxiv.org/pdf/2602.06325v1)** - An LLM agent that reads stripped malware binaries and identifies the attack techniques inside them at 93% precision. Useful for automating threat analysis. | <a href="https://arxiv.org/abs/2602.06325v1"><img src="https://img.shields.io/badge/arXiv-2602.06325-b31b1b.svg" alt="arXiv" /></a> |
| **[Trustworthy AI Software Engineers](https://arxiv.org/pdf/2602.06310v1)** - Defines what "trustworthy" means for AI coding agents across technical quality, transparency, and self-awareness of limitations. Useful as an evaluation checklist. | <a href="https://arxiv.org/abs/2602.06310v1"><img src="https://img.shields.io/badge/arXiv-2602.06310-b31b1b.svg" alt="arXiv" /></a> |
| **[Agent2Agent Threats in Safety-Critical LLM Assistants: A Human-Centric Taxonomy](https://arxiv.org/pdf/2602.05877v1)** - Maps attack paths in agent-to-agent communication (like Google A2A) for automotive LLM assistants — from driver distraction to unauthorized vehicle control. | <a href="https://arxiv.org/abs/2602.05877v1"><img src="https://img.shields.io/badge/arXiv-2602.05877-b31b1b.svg" alt="arXiv" /></a> |
| **[Learning to Inject: Automated Prompt Injection via Reinforcement Learning](https://arxiv.org/pdf/2602.05746v1)** - Uses RL to auto-generate prompt injection attacks that transfer across GPT-5, Claude, and Gemini on AgentDojo. Useful for red-teaming agent defenses at scale. | <a href="https://arxiv.org/abs/2602.05746v1"><img src="https://img.shields.io/badge/arXiv-2602.05746-b31b1b.svg" alt="arXiv" /></a> |
| **[A Dual-Loop Agent Framework for Automated Vulnerability Reproduction](https://arxiv.org/pdf/2602.05721v1)** - Give it a CVE description and it writes a working exploit to reproduce the bug. Two feedback loops — one for strategy, one for code — hit 83% success on real vulnerabilities. | <a href="https://arxiv.org/abs/2602.05721v1"><img src="https://img.shields.io/badge/arXiv-2602.05721-b31b1b.svg" alt="arXiv" /></a> |
| **[Human Society-Inspired Approaches to Agentic AI Security: The 4C Framework](https://arxiv.org/pdf/2602.01942v1)** - Organizes agentic security risks into four layers — Core, Connection, Cognition, Compliance. Goes beyond prompt injection into broader trust and governance issues. | <a href="https://arxiv.org/abs/2602.01942v1"><img src="https://img.shields.io/badge/arXiv-2602.01942-b31b1b.svg" alt="arXiv" /></a> |
| **[MAGIC: A Co-Evolving Attacker-Defender Adversarial Game for Robust LLM Safety](https://arxiv.org/pdf/2602.01539v2)** - An attacker agent and a defender agent co-evolve through RL — the attacker keeps finding new tricks, the defender keeps adapting. Catches attack patterns that static datasets miss. | <a href="https://arxiv.org/abs/2602.01539v2"><img src="https://img.shields.io/badge/arXiv-2602.01539-b31b1b.svg" alt="arXiv" /></a> |

</details>

## Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

- Submit new papers via PR
- Suggest category improvements

## License

MIT License - see [LICENSE](LICENSE)

This is a curated list. Papers listed here are created and published by their respective authors, not by us. We curate papers relevant to the AI agent ecosystem and do not audit, endorse, or guarantee the correctness of listed research.

If you find an issue with a listed paper or want a paper removed, please [open an issue](https://github.com/VoltAgent/awesome-ai-agent-papers/issues) and we'll take care of it promptly.
