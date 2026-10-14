---
title: "Are Small Language Models the Silver Bullet to Low-Resource Languages Machine Translation?"
collection: publications
category: conferences
permalink: /publication/loresmt26
date: 2026-03-27
venue: 'Proceedings of the Ninth Workshop on Technologies for Machine Translation of Low-Resource Languages (LoResMT 2026)'
paperurl: 'https://aclanthology.org/2026.loresmt-1.1'
citation: 'Yewei Song, L. Li, Cedric Lothritz, Saad Ezzini, L. Sleem, Tegawendé F. Bissyandé, and Jacques Klein. "Are Small Language Models the Silver Bullet to Low-Resource Languages Machine Translation?" In Proceedings of the Ninth Workshop on Technologies for Machine Translation of Low-Resource Languages. 2026.'
---

Low-resource languages (LRLs) lack sufficient linguistic resources and are underrepresented in benchmark datasets, resulting in persistently lower translation quality than high-resource languages, especially in privacy-sensitive and resource-limited contexts. Firstly, this study systematically evaluates state-of-the-art smaller Large Language Models in 200 languages using the FLORES-200 benchmark, highlighting persistent deficiencies and disparities in the translation of LRLs. To mitigate these limitations, we investigate knowledge distillation from large pre-trained teacher models to Small Language Models (SLMs) through supervised fine-tuning. The results show substantial improvements; for example, the translation performance of English to Luxembourgish (EN to LB), measured by the LLM-as-a-Judge score, increases from 0.36 to 0.89 in the validation set for Llama-3.2-3B. We further investigate various fine-tuning configurations and tasks to clarify the trade-offs between data scale and training efficiency, verify that the model retains its general capabilities without significant catastrophic forgetting after training, and explore the distillation benefits to other LRLs on SLMs (Khasi, Assamese, and Ukrainian). In general, this work exposes the limitations and fairness issues of current SLMs in LRL translation and systematically explores the potential of using the distillation of knowledge from large to small models, offering practical, empirically grounded recommendations to improve LRL translation systems.
