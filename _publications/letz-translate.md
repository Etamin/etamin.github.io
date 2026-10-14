---
title: "Letz Translate: Low-Resource Machine Translation for Luxembourgish"
collection: publications
category: conferences
permalink: /publication/icnlp23
date: 2023-03-24
venue: '2023 5th International Conference on Natural Language Processing (ICNLP)'
paperurl: 'https://arxiv.org/abs/2303.01347'
citation: 'Yewei Song, Saad Ezzini, Jacques Klein, Tegawendé Bissyandé, C. Lefebvre, and Anne Goujon. "Letz Translate: Low-Resource Machine Translation for Luxembourgish." In 2023 5th International Conference on Natural Language Processing (ICNLP). 2023.'
---

Natural language processing of Low-Resource Languages (LRL) is often challenged by the lack of data. Therefore, achieving accurate machine translation (MT) in a low-resource environment is a real problem that requires practical solutions. Research in multilingual models have shown that some LRLs can be handled with such models. However, their large size and computational needs make their use in constrained environments (e.g., mobile/IoT devices or limited/old servers) impractical. In this paper, we address this problem by leveraging the power of large multilingual MT models using knowledge distillation. Knowledge distillation can transfer knowledge from a large and complex teacher model to a simpler and smaller student model without losing much in performance. We also make use of high-resource languages that are related or share the same linguistic root as the target LRL. For our evaluation, we consider Luxembourgish as the LRL that shares some roots and properties with German. We build multiple resource-efficient models based on German, knowledge distillation from the multilingual No Language Left Behind (NLLB) model, and pseudo-translation. We find that our efficient models are more than 30% faster and perform only 4% lower compared to the large state-of-the-art NLLB model.
