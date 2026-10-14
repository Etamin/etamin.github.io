---
title: "RAML: Toward Retrieval-Augmented Localization of Malicious Payloads in Android Apps"
collection: publications
category: conferences
permalink: /publication/raml
date: 2025-11-16
venue: '40th IEEE/ACM International Conference on Automated Software Engineering, ASE 2025'
paperurl: 'https://doi.org/10.1109/ASE63991.2025.00351'
citation: 'Tiezhu Sun, M. Alecci, Yewei Song, Xunzhu Tang, Kisub Kim, J. Samhi, Tegawendé F. Bissyandé, and Jacques Klein. "RAML: Toward Retrieval-Augmented Localization of Malicious Payloads in Android Apps." In 2025 40th IEEE/ACM International Conference on Automated Software Engineering (ASE). 2025.'
---

Android malware detection and family classification have been extensively studied, yet localizing the exact malicious payloads within a detected sample remains a challenging and labor-intensive task. We propose RAML, a novel Retrieval-Augmented Malicious payload Localization pipeline inspired by retrieval-augmented generation (RAG), which leverages large language models (LLMs) to bridge high-level behavior descriptions and low-level Smali code. RAML generates class-level descriptions from Smali code, embeds them into a vector database, and performs semantic retrieval via similarity search. Matched candidates are re-ranked with LLM assistance, followed by method-level LLM analysis to precisely identify malicious methods and provide insightful role explanations. Preliminary results show that RAML effectively localizes corresponding malicious payloads based on behavioral descriptions, narrows the analysis scope, and reduces manual effort, offering a promising direction for automated malware forensics.
