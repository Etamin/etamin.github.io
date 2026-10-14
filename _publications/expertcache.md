---
title: "ExpertCache: GPU-Efficient MoE Inference through Reinforcement Learning-Guided Expert Selection"
collection: publications
category: conferences
permalink: /publication/expertcache
date: 2025-09-08
venue: 'The 41st International Conference on Software Maintenance and Evolution (ICSME 2025)'
paperurl: 'https://orbilu.uni.lu/handle/10993/65750'
citation: 'Xunzhu Tang, Tiezhu Sun, Yewei Song, Siyuan Ma, Jacques Klein, and Tegawendé F. Bissyandé. "ExpertCache: GPU-Efficient MoE Inference through Reinforcement Learning-Guided Expert Selection." In The 41st International Conference on Software Maintenance and Evolution (ICSME). 2025.'
---

Mixture-of-Experts (MoE) architectures have emerged as a promising approach for scaling large language models while maintaining computational efficiency. However, inference in these models remains challenging due to the substantial GPU memory requirements of storing all expert parameters. In this paper, we introduce ExpertCache, a novel two-phase reinforcement learning framework that optimizes both which experts to load into GPU memory and which loaded experts to activate during inference. Our approach consists of a pre-loading controller that selects a task-specific subset of experts to cache in GPU memory, and a runtime controller that dynamically activates the most relevant experts for each token. Both controllers are optimized through reinforcement learning with carefully designed reward functions that balance model quality, computational efficiency, and expert utilization. We evaluate ExpertCache on Qwen3-235B-A22B using BigCodeBench, demonstrating that our approach reduces GPU memory requirements by up to 85% while achieving superior performance compared to loading all experts. Our method enables deployment of large MoE models on consumer-grade hardware and significantly improves inference throughput in production environments. ExpertCache outperforms current expert selection methods on both memory efficiency and computational performance, establishing a new state-of-the-art for efficient MoE inference.
