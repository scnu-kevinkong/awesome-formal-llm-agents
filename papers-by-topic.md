# Papers by Topic

This page reorganizes papers from the main list by technical topic. It is meant for researchers who already know the mechanism they care about and want to jump directly into the relevant literature.

## Temporal Logic and Runtime Monitoring

- [RvLLM: LLM Runtime Verification with Domain Knowledge](https://openreview.net/forum?id=XdwPWKbxd9&noteId=ZzUTHYqdwG)  
  Runtime verification for LLM outputs with a lightweight domain specification language.
- [Formally Specifying the High-Level Behavior of LLM-Based Agents](https://arxiv.org/abs/2310.08535)  
  Declarative specifications, including temporal logic, for high-level agent behavior.
- [LogicGuard: Improving Embodied LLM Agents through Temporal Logic Based Critics](https://arxiv.org/abs/2507.03293)  
  Temporal-logic critics for embodied agents.
- [NL2TL: Transforming Natural Languages to Temporal Logics using Large Language Models](https://arxiv.org/abs/2305.07766)  
  Natural-language-to-temporal-logic translation.
- [Automatic Generation of Safety-compliant Linear Temporal Logic via Large Language Model: A Self-supervised Framework](https://openreview.net/forum?id=fp51nxr5B1)  
  LLM-assisted LTL generation for safety constraints.
- [Verifiable Natural Language to Linear Temporal Logic Translation: A Benchmark Dataset and Evaluation Suite](https://openreview.net/forum?id=RUs4KC34yT)  
  Benchmarking NL-to-LTL translation with verification-aware evaluation.

## Contracts and Tool Use

- [ToolGate: Contract-Grounded and Verified Tool Execution for LLMs](https://arxiv.org/abs/2601.04688)  
  Hoare-style contracts and symbolic state for verified tool execution.
- [Agent Behavioral Contracts: Formal Specification and Runtime Enforcement for Reliable Autonomous AI Agents](https://arxiv.org/abs/2602.22302)  
  Design-by-contract for autonomous agents under LLM non-determinism.
- [Position: Trustworthy AI Agents Require the Integration of Large Language Models and Formal Methods](https://openreview.net/forum?id=wkisIZbntD)  
  Position paper on formal methods for trustworthy agents.
- [SpecMAS: A Multi-Agent System for Self-Verifying System Generation via Formal Model Checking](https://github.com/Idsl-group/SpecMAS)  
  Multi-agent self-verification with formal model checking.

## Constrained Decoding and Structured Generation

- [Prompting Is Programming: A Query Language for Large Language Models](https://arxiv.org/abs/2212.06094)  
  LMQL as a language-model programming and constrained generation framework.
- [Grammar-Constrained Decoding for Structured NLP Tasks without Finetuning](https://aclanthology.org/2023.emnlp-main.674/)  
  Grammar-constrained decoding for structured NLP tasks.
- [NeuroLogic Decoding: (Un)supervised Neural Text Generation with Predicate Logic Constraints](https://aclanthology.org/2021.naacl-main.339/)  
  Predicate-logic constraints for neural text generation.
- [PICARD: Parsing Incrementally for Constrained Auto-Regressive Decoding from Language Models](https://aclanthology.org/2021.emnlp-main.779/)  
  Incremental parsing for constrained semantic parsing.
- [Constrained Language Models Yield Few-Shot Semantic Parsers](https://aclanthology.org/2022.emnlp-main.608/)  
  Constrained decoding for few-shot semantic parsing.
- [Logically Constrained Decoding](https://aclanthology.org/2025.mathnlp-main.11/)  
  Logic-aware constrained decoding.
- [Flexible and Efficient Grammar-Constrained Decoding](https://arxiv.org/abs/2502.05111)  
  Efficient algorithms for grammar-constrained decoding.
- [Automata-based Constraints for Language Model Decoding](https://arxiv.org/abs/2407.08103)  
  Automata constraints for language model decoding.

## Symbolic Solving and Formalization

- [Logic-LM: Empowering Large Language Models with Symbolic Solvers for Faithful Logical Reasoning](https://aclanthology.org/2023.findings-emnlp.248/)  
  LLM-to-solver pipelines for logical reasoning.
- [Large Language Models Can Solve Real-World Planning Rigorously with Formal Verification Tools](https://aclanthology.org/2025.naacl-long.176/)  
  Natural language to formal constraints, then solver-backed planning.
- [Formal-LLM: Integrating Formal Language and Natural Language for Controllable LLM-based Agents](https://arxiv.org/abs/2402.00798)  
  Automata-supervised agent planning and execution.

## Transformer and Neural Network Verification

- [Robustness Verification for Transformers](https://arxiv.org/abs/2002.06622)  
  Certified robustness verification for transformer models.
- [Towards Formally Verifying LLMs: Taming the Nonlinearity of the Transformer](https://openreview.net/forum?id=evDSvZBFRP)  
  Verification methods targeting softmax and attention nonlinearity.
- [Certifying LLM Safety against Adversarial Prompting](https://openreview.net/forum?id=wNere1lelo)  
  Safety certification against adversarial prompting.
- [Fast and Precise Certification of Transformers](https://dl.acm.org/doi/10.1145/3453483.3454056)  
  Certification algorithms for transformer models.
- [Vertex-Softmax: Tight Transformer Verification via Exact Softmax Objective Optimization](https://arxiv.org/abs/2605.10974)  
  Transformer verification through softmax objective optimization.
- [Reluplex: An Efficient SMT Solver for Verifying Deep Neural Networks](https://link.springer.com/chapter/10.1007/978-3-319-63387-9_42)  
  Foundational SMT approach for neural network verification.
- [Marabou: A Framework for Verification and Analysis of Deep Neural Networks](https://link.springer.com/chapter/10.1007/978-3-030-25540-4_26)  
  Neural network verification framework.
- [CROWN: A General Framework for Certifying and Boosting the Robustness of Neural Networks](https://arxiv.org/abs/1811.00866)  
  Bound-propagation framework for robustness certification.
- [Beta-CROWN: Efficient Bound Propagation with Per-neuron Split Constraints for Complete and Incomplete Neural Network Verification](https://arxiv.org/abs/2103.06624)  
  Bound propagation with split constraints.

## Planning and Embodied Agents

- [Grounding Generative Planners in Verifiable Logic: A Hybrid Architecture for Trustworthy Embodied AI](https://openreview.net/forum?id=wb05ver1k8)  
  Verifier-in-the-loop embodied planning.
- [SENTINEL: A Multi-Level Formal Framework for Safety Evaluation of LLM-based Embodied Agents](https://openreview.net/forum?id=vCyxemIKLL)  
  Multi-level formal safety evaluation for embodied agents.
- [LogicGuard: Improving Embodied LLM Agents through Temporal Logic Based Critics](https://arxiv.org/abs/2507.03293)  
  LTL critics for embodied decision making.
- [PlanBench: An Extensible Benchmark for Evaluating Large Language Models on Planning and Reasoning about Change](https://arxiv.org/abs/2206.10498)  
  Planning and reasoning about change.
- [TCP: a Benchmark for Temporal Constraint-Based Planning](https://aclanthology.org/2025.emnlp-main.1142.pdf)  
  Temporal constraints in planning-style dialogue.
- [TravelPlanner](https://github.com/OSU-NLP-Group/TravelPlanner)  
  Travel planning benchmark with constraints.
- [ALFWorld](https://alfworld.github.io/)  
  Text-based embodied household tasks.
- [BEHAVIOR](https://behavior.stanford.edu/)  
  Embodied AI benchmark for household activities.

## Formal Reasoning Benchmarks

- [Evaluating the Formal Reasoning Capabilities of Large Language Models through Chomsky Hierarchy](https://arxiv.org/abs/2604.02709)  
  Formal language hierarchy as a lens on LLM reasoning.
- [Can LLMs Reason About Program Semantics? A Comprehensive Evaluation of LLMs on Formal Specification Inference](https://aclanthology.org/2025.acl-long.1068/)  
  Program semantics and formal specification inference.
- [ProofWriter](https://allenai.org/data/proofwriter)  
  Natural-language proof and rule reasoning.
- [FOLIO: Natural Language Reasoning with First-Order Logic](https://github.com/Yale-LILY/FOLIO)  
  First-order logic reasoning from natural language.
- [BIG-Bench Hard](https://arxiv.org/abs/2210.09261)  
  Hard reasoning tasks selected from BIG-Bench.
- [AgentBench](https://arxiv.org/abs/2308.03688)  
  Broad agent evaluation benchmark.
- [WebArena](https://webarena.dev/)  
  Web-based agent task benchmark.
