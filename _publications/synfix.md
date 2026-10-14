---
title: "SynFix: Dependency-Aware Program Repair via RelationGraph Analysis"
collection: publications
category: conferences
permalink: /publication/synfix
date: 2025-07-27
venue: 'Findings of the Association for Computational Linguistics: ACL 2025'
paperurl: 'https://aclanthology.org/2025.findings-acl.252/'
citation: 'Xunzhu Tang, J. Gao, J. Xu, Tiezhu Sun, Yewei Song, Saad Ezzini, Wendkuuni C. Ouedraogo, Jacques Klein, et al. "SynFix: Dependency-aware program repair via RelationGraph analysis." In Findings of the Association for Computational Linguistics: ACL 2025, pp. 4878-4894. 2025.'
---

Recent advancements in large language models (LLMs) have significantly improved software development automation, including bug localization, code synthesis, program repair, and test generation. However, most prior work on program repair focuses on isolated elements, such as classes or functions, neglecting their interdependencies, which limits repair accuracy. We present SynFix, a RelationGraph-based approach that integrates LLMs with structural search and synchronization techniques for coordinated program repair across codebases. SynFix constructs a RelationGraph to capture relationships among classes, functions, variables, and their interactions (e.g., imports, inheritance, dependencies). Each RelationGraph node includes detailed code descriptions to help LLMs understand root causes and retrieve relevant contexts. By analyzing one-hop nodes in the RelationGraph, SynFix ensures repairs account for dependent updates across components. Patch validation is conducted using regression tests from the SWE-bench benchmark suite. Evaluated on SWE-bench datasets, SynFix resolves 52.33% of issues in SWE-bench-lite (300 GitHub issues), 55.8% in SWE-bench-verified (500 issues), and 29.86% in SWE-bench-full (2,294 issues), outperforming baselines such as Swe-Agent, Agentless and AutoCodeRover.
