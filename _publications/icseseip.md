---
title: "Enhancing Text-to-SQL Translation for Financial System Design"
collection: publications
category: conferences
permalink: /publication/icse24
date: 2024-05-31
venue: 'In Proceedings of the 46th International Conference on Software Engineering: Software Engineering in Practice'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3639477.3639732'
citation: 'Song, Yewei, Saad Ezzini, Xunzhu Tang, Cedric Lothritz, Jacques Klein, Tegawendé Bissyandé, Andrey Boytsov, Ulrick Ble, and Anne Goujon. "Enhancing text-to-sql translation for financial system design." In Proceedings of the 46th International Conference on Software Engineering: Software Engineering in Practice, pp. 252-262. 2024.'
---

Text-to-SQL, the task of translating natural language questions into SQL queries, is part of various business processes. Its automation, which is an emerging challenge, will empower software practitioners to seamlessly interact with relational databases using natural language, thereby bridging the gap between business needs and software capabilities.
In this paper, we consider Large Language Models (LLMs), which have achieved state of the art for various NLP tasks. Specifically, we benchmark Text-to-SQL performance, the evaluation methodologies, as well as input optimization (e.g., prompting). In light of the empirical observations that we have made, we propose two novel metrics that were designed to adequately measure the similarity between SQL queries.
Overall, we share with the community various findings, notably on how to select the right LLM on Text-to-SQL tasks. We further demonstrate that a tree-based edit distance constitutes a reliable metric for assessing the similarity between generated SQL queries and the oracle for benchmarking Text2SQL approaches. This metric is important as it relieves researchers from the need to perform computationally expensive experiments such as executing generated queries as done in prior works. Our work implements financial domain use cases and, therefore contributes to the advancement of Text2SQL systems and their practical adoption in this domain.