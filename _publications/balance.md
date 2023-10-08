---
title: "Scalable Batch-Mode Deep Bayesian Active Learning via Equivalence Class Annealing"
collection: publications
permalink: 'https://arxiv.org/abs/2112.13737'
excerpt: 'Deep Bayesian Active Learning'
venue: 'The 12th International Conference on Learning Representations (ICLR)'
date: 2023-1-20
paperurl: 'https://arxiv.org/abs/2112.13737'
citation: 'Zhang, Renyu, et al. "Scalable Batch-Mode Deep Bayesian Active Learning via Equivalence Class Annealing." arXiv preprint arXiv:2112.13737 (2021).'

---
Active learning has demonstrated data efficiency in many fields. Existing active learning algorithms, especially in the context of batch-mode deep Bayesian active models, rely heavily on the quality of uncertainty estimations of the model, and are often challenging to scale to large batches. In this paper, we propose Batch-BALanCe, a scalable batch-mode active learning algorithm, which combines insights from decision-theoretic active learning, combinatorial information measure, and diversity sampling. At its core, Batch-BALanCe relies on a novel decision-theoretic acquisition function that facilitates differentiation among different equivalence classes. Intuitively, each equivalence class consists of hypotheses (e.g., posterior samples of deep neural networks) with similar predictions, and Batch-BALanCe adaptively adjusts the size of the equivalence classes as learning progresses. To scale up the computation of queries to large batches, we further propose an efficient batch-mode acquisition procedure, which aims to maximize a novel information measure defined through the acquisition function. We show that our algorithm can effectively handle realistic multi-class classification tasks, and achieves compelling performance on several benchmark datasets for active learning under both low- and large-batch regimes. Reference code is released at [link](https://github.com/zhangrenyuuchicago/BALanCe).

