---
title: "Correctness isn't Efficiency: Runtime Memory Divergence in LLM-Generated Code"
collection: publications
category: conferences
permalink: /publication/icse26-memory
date: 2026-04-12
venue: 'Proceedings of the IEEE/ACM 48th International Conference on Software Engineering (ICSE 2026)'
paperurl: 'https://arxiv.org/abs/2601.01215'
citation: 'P. K. Rajput, Yewei Song, A. A. Bonkoungou, I. E. Olatunji, A. K. Kabore, Jacques Klein, et al. "Correctness isn''t Efficiency: Runtime Memory Divergence in LLM-Generated Code." In Proceedings of the IEEE/ACM 48th International Conference on Software Engineering. 2026.'
---

Large language models (LLMs) can generate programs that pass unit tests, but passing tests does not guarantee reliable runtime behavior. We find that different correct solutions to the same task can show very different memory and performance patterns, which can lead to hidden operational risks. We present a framework to measure execution-time memory stability across multiple correct generations. At the solution level, we introduce Dynamic Mean Pairwise Distance (DMPD), which uses Dynamic Time Warping to compare the shapes of memory-usage traces after converting them into Monotonic Peak Profiles (MPPs) to reduce transient noise. Aggregating DMPD across tasks yields a model-level Model Instability Score (MIS). Experiments on BigOBench and CodeContests show substantial runtime divergence among correct solutions. Instability often increases with higher sampling temperature even when pass@1 improves. We also observe correlations between our stability measures and software engineering indicators such as cognitive and cyclomatic complexity, suggesting links between operational behavior and maintainability. Our results support stability-aware selection among passing candidates in CI/CD to reduce operational risk without sacrificing correctness.
