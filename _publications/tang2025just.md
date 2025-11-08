---
title: "Just-in-time detection of silent security patches."
collection: publications
category: manuscripts
permalink: /publication/tang2025
date: 2025-07-29
venue: 'ACM Transactions on Software Engineering and Methodology'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3749370'
citation: 'Tang, Xunzhu, Kisub Kim, Saad Ezzini, Yewei Song, Haoye Tian, Jacques Klein, and Tegawende Bissyande. "Just-in-time detection of silent security patches." ACM Transactions on Software Engineering and Methodology (2025).'
---

Open-source code is pervasive. In this setting, embedded vulnerabilities are spreading to downstream software at an alarming rate. Although such vulnerabilities are generally identified and addressed rapidly, inconsistent maintenance policies can cause security patches to go unnoticed. Indeed, security patches can be silent, i.e., they do not always come with comprehensive advisories such as CVEs. This lack of transparency leaves users oblivious to available security updates, providing ample opportunity for attackers to exploit unpatched vulnerabilities. Consequently, identifying silent security patches just in time when they are released is essential for preventing n-day attacks and for ensuring robust and secure maintenance practices. With llmda we propose to (1) leverage large language models (LLMs) to augment patch information with generated code change explanations, (2) design a representation learning approach that explores code-text alignment methodologies for feature combination, (3) implement a label-wise training with labeled instructions for guiding the embedding based on security relevance, and (4) rely on a probabilistic batch contrastive learning mechanism for building a high-precision identifier of security patches. We evaluate llmda on the PatchDB and SPI-DB literature datasets and show that our approach substantially improves over the state-of-the-art, notably GraphSPD by 20% in terms of F-Measure on the SPI-DB benchmark.