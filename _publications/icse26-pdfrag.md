---
title: "Empirical Evaluation of PDF Parsing and Chunking for Financial Question Answering with RAG"
collection: publications
category: conferences
permalink: /publication/icse26-pdfrag
date: 2026-04-13
venue: 'Proceedings of the IEEE/ACM 48th International Conference on Software Engineering (ICSE 2026)'
paperurl: 'https://arxiv.org/abs/2604.12047'
citation: 'O. El Bachyr, Yewei Song, Saad Ezzini, Jacques Klein, Tegawendé F. Bissyandé, A. Zilali, Ulrick Ble, et al. "Empirical Evaluation of PDF Parsing and Chunking for Financial Question Answering with RAG." In Proceedings of the IEEE/ACM 48th International Conference on Software Engineering. 2026.'
---

PDF files are primarily intended for human reading rather than automated processing. In addition, the heterogeneous content of PDFs, such as text, tables, and images, poses significant challenges for parsing and information extraction. To address these difficulties, both practitioners and researchers are increasingly developing new methods, including the promising Retrieval-Augmented Generation (RAG) systems to automated PDF processing. However, there is no comprehensive study investigating how different components and design choices affect the performance of a RAG system for understanding PDFs. In this paper, we propose such a study (1) by focusing on Question Answering, a specific language understanding task, and (2) by leveraging two benchmarks from the financial domain, including TableQuest, our newly generated, publicly available benchmark. We systematically examine multiple PDF parsers and chunking strategies (with varied overlap), along with their potential synergies in preserving document structure and ensuring answer correctness. Overall, our results offer practical guidelines for building robust RAG pipelines for PDF understanding.
