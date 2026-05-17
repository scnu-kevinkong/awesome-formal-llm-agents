# Resources

This page collects tools, libraries, benchmarks, and background material useful for work at the intersection of formal methods, LLMs, and agents.

## Solver and Verification Backends

- [Z3](https://github.com/Z3Prover/z3) - SMT solver from Microsoft Research.
- [cvc5](https://cvc5.github.io/) - SMT solver with broad theory support.
- [MiniZinc](https://www.minizinc.org/) - Constraint modeling language for CP, SAT, and MIP backends.
- [OR-Tools](https://developers.google.com/optimization) - Optimization toolkit for routing, scheduling, CP-SAT, and planning-style constraints.
- [SPIN](https://spinroot.com/spin/whatispin.html) - Model checker for distributed software systems.
- [NuSMV](https://nusmv.fbk.eu/) - Symbolic model checker.
- [PRISM](https://www.prismmodelchecker.org/) - Probabilistic model checker.
- [UPPAAL](https://uppaal.org/) - Modeling, simulation, and verification for timed automata.
- [TLA+](https://lamport.azurewebsites.net/tla/tla.html) - Specification language for concurrent and distributed systems.
- [Alloy](https://alloytools.org/) - Lightweight formal modeling language and analyzer.
- [Coq](https://coq.inria.fr/) - Interactive theorem prover.
- [Lean](https://lean-lang.org/) - Interactive theorem prover and programming language.
- [Isabelle](https://isabelle.in.tum.de/) - Generic proof assistant.

## Automata and Temporal Logic

- [Spot](https://spot.lre.epita.fr/) - Automata manipulation and LTL model checking library.
- [ltl3ba](https://sourceforge.net/projects/ltl3ba/) - LTL-to-Buchi automata translator.
- [MONA](https://www.brics.dk/mona/) - Decision procedures for monadic second-order logic on finite strings and trees.
- [omega](https://github.com/tulip-control/omega) - Symbolic algorithms for omega-regular specifications.
- [TuLiP](https://tulip-control.sourceforge.io/) - Temporal logic planning and synthesis.

## Neural Network Verification

- [Marabou](https://github.com/NeuralNetworkVerification/Marabou) - Verification and analysis of deep neural networks.
- [alpha-beta-CROWN](https://github.com/Verified-Intelligence/alpha-beta-CROWN) - Neural network verifier based on bound propagation and branch-and-bound.
- [ERAN](https://github.com/eth-sri/eran) - ETH Robustness Analyzer for neural networks.
- [VNN-COMP](https://sites.google.com/view/vnn2024) - Annual neural network verification competition.

## LLM Programming and Constrained Generation

- [LMQL](https://github.com/eth-sri/lmql) - Language model query language with constraints.
- [Outlines](https://github.com/dottxt-ai/outlines) - Structured generation for LLMs.
- [Guidance](https://github.com/guidance-ai/guidance) - Guidance language for controlling language model generation.
- [jsonformer](https://github.com/1rgs/jsonformer) - Constrained JSON generation.
- [SGLang](https://github.com/sgl-project/sglang) - Runtime for structured language model programs.
- [DSPy](https://github.com/stanfordnlp/dspy) - Declarative language model pipelines.

## Planning, PDDL, and Agent Environments

- [Fast Downward](https://www.fast-downward.org/) - Classical planning system.
- [Planning.Domains](https://planning.domains/) - PDDL editor, solver interface, and planning resources.
- [VAL](https://github.com/KCL-Planning/VAL) - Plan validation tools for PDDL.
- [PlanBench](https://github.com/karthikv792/LLMs-Planning) - Planning benchmark for LLMs.
- [TravelPlanner](https://github.com/OSU-NLP-Group/TravelPlanner) - Constraint-heavy travel planning benchmark.
- [ALFWorld](https://alfworld.github.io/) - Interactive embodied agent benchmark.
- [BEHAVIOR](https://behavior.stanford.edu/) - Embodied AI benchmark.
- [WebArena](https://webarena.dev/) - Web task benchmark for autonomous agents.
- [AgentBench](https://github.com/THUDM/AgentBench) - Multi-environment benchmark for LLM agents.

## Formal Reasoning Datasets

- [ProofWriter](https://allenai.org/data/proofwriter) - Natural language reasoning with proofs.
- [FOLIO](https://github.com/Yale-LILY/FOLIO) - First-order logic reasoning benchmark.
- [BIG-Bench Hard](https://arxiv.org/abs/2210.09261) - Hard reasoning tasks from BIG-Bench.

## Conferences and Venues to Watch

- Formal methods and verification: CAV, TACAS, FMCAD, FM, VMCAI, ATVA, POPL, PLDI, OOPSLA.
- NLP and LLM systems: ACL, EMNLP, NAACL, EACL, COLM, ICLR, NeurIPS, ICML.
- Agents, robotics, and planning: AAMAS, IROS, ICRA, RSS, ICAPS, IJCAI, AAAI.
- Security and safety: IEEE S&P, USENIX Security, CCS, NDSS, Safe and Trustworthy AI workshops.

## Contribution Format

For new papers, include:

- Title and link
- Authors
- Year
- Venue or status
- Topic category
- Short summary
- Code or project link, when available
- DOI, when available
