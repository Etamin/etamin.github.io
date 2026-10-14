---
title: "Semantic Patch Embedding for Security Detection: A Fine-to-Coarse Grained Approach"
collection: publications
category: conferences
permalink: /publication/iclr24-tiny
date: 2024-05-11
venue: 'The Second Tiny Papers Track at ICLR 2024'
paperurl: 'https://orbilu.uni.lu/handle/10993/65670'
citation: 'Xunzhu Tang, Yewei Song, Haoye Tian, Z. Chen, Jacques Klein, and Tegawendé F. Bissyandé. "Semantic Patch Embedding for Security Detection: A Fine-to-Coarse Grained Approach." In The Second Tiny Papers Track at ICLR 2024. 2024.'
---

The growth of open-source software has increased the risk of hidden vulnerabilities that can affect downstream software applications. This concern is further exacerbated by software vendors' practice of silently releasing security patches without explicit warnings or common vulnerability and exposure (CVE) notifications. This lack of transparency leaves users unaware of potential security threats, giving attackers an opportunity to take advantage of these vulnerabilities. In the complex landscape of software patches, grasping the nuanced semantics of a patch is vital for ensuring secure software maintenance. To address this challenge, we introduce a multilevel Semantic Embedder for security patch detection, termed MultiSEM. This model harnesses word-centric vectors at a fine-grained level, emphasizing the significance of individual words, while the coarse-grained layer adopts entire code lines for vector representation, capturing the essence and interrelation of added or removed lines. We further enrich this representation by assimilating patch descriptions to obtain a holistic semantic portrait. This combination of multi-layered embeddings offers a robust representation, balancing word complexity, understanding code-line insights, and patch descriptions. Evaluating MultiSEM for detecting patch security, our results demonstrate its superiority, outperforming state-of-the-art models with promising margins: a 22.46% improvement on PatchDB and a 9.21% on SPI-DB in terms of the F1 metric.
