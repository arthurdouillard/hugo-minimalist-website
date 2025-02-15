---
title: "Papers"
description: "Papers."
---

I tend to work on one thing at the time, and always getting my hands dirty implementing, debugging, and scaling myself the models.

I've started my journey with **continual learning**, and did my PhD on this. In hindsight, I was focused on academic benchmarks (*e.g.* learning incrementally new classes on ImageNet) that were not realistic enough.

When joining DeepMind in late 2022 to work on continual learning, I've realized that current deep learning needs more **modularity**: to learn & unlearn specific knowledge skills but also to scale massively the model without also increasing its inference cost. In order to train massive modular system, I've developped DiLoCo: a new way to distribute training of LLMs across the world with two orders of magnitude less bandwidth. Several startups are now based on that technology. Using DiLoCo, I've made DiPaCo, a new kind of modular architecture with its weights are world-wide distributed and trained semi-independetly.

I'm still working on distributed training, regularly pushing futher the limits of what was thought to be possible. My dream is to do **compute arbitrage on all the GPUs and TPUs across the world**. No devices should be ever iddle, everthing must be used towards training better AIs. 

# Distributed Training

* **2025**:
    * **Streaming DiLoCo** with overlapping quantized communication: [streaming diloco](https://arxiv.org/abs/2501.18512) and covered in [Import AI #398](https://importai.substack.com/p/import-ai-398-deepmind-makes-distributed)
    * Coverage by [The Economist](https://www.economist.com/science-and-technology/2025/01/08/training-ai-models-might-not-need-enormous-data-centres) of my research on distributed training
* **2024**: 
    * **Async DiLoCo** with heterogenous devices: [arxiv](https://arxiv.org/abs/2401.09135) `[ICML Workshop 2024]`
    * **DiPaCo**, distributed modular system: [arxiv](https://arxiv.org/abs/2403.10616) and covered in [Import AI #367](https://importai.substack.com/p/import-ai-367-googles-world-spanning)
* **2023**: 
    * **DiLoCo**: large-scale distributed training of LLMs: [arxiv](https://arxiv.org/abs/2311.08105) `[ICML Workshop 2024]`
    * It has kickstarted the startup PrimeIntellect with their first projects [OpenDiLoCo](https://arxiv.org/abs/2407.07852) and [Intellect-1](https://arxiv.org/abs/2412.01152) and FlowerLabs with [FlowerLM](https://arxiv.org/abs/2405.10853)
    * Covered in [Import AI #349](https://importai.substack.com/p/import-ai-349-distributed-training)

# Continual Learning

Work mosly during my PhD thesis (2019-2022).

* **2024**: Interview in the french newspaper ActuIA
* **2022**:
    * **DyTox**: Quick adaptation to new tasks with learns tokens for vision transformer: [arxiv](https://arxiv.org/abs/2111.11326) `[CVPR 2022]`
    * **MuHDi** Unsupervised continual domain adaptation: [arxiv](https://arxiv.org/abs/2204.11667) `[CVPR Workshop 2022]`
    * Latent replay for foundation models: [arxiv](https://arxiv.org/abs/2205.00329) `[CoLLas 2023]`
    * My PhD thesis: [thesis](https://theses.hal.science/tel-03872534v1/file/DOUILLARD_Arthur_these_2022.pdf)
    * **CoNFormer**: panoptic segmentation: [arxiv](https://arxiv.org/abs/2211.13999) `[CVPR 2023]`
    * Compute-optimal transfer learning: [arxiv](https://arxiv.org/abs/2304.13164) `[ICLR Workshop 2023]`
* **2020**:
    * **PLOP** Multi-scale features distillation for segmentation: [arxiv](https://arxiv.org/abs/2011.11390) `[CVPR 2021]`
    * **Ghost** Zero-shot learning using ghost features: [arxiv](https://arxiv.org/abs/2006.13748) `[CVPR Workshop 2021]`
    * **Continumm**: a data framework for continual learning: [arxiv](https://arxiv.org/abs/2102.06253) `[CVPR Workshop 2021]`
    * Synthetic visual data for rehearsal learning: [synthetic data](https://arxiv.org/abs/2106.15287) `[TPAMI 2021]`
* **2019**: **PODNet**: features distillation to reduce catastrophic forgetting with extremely large number of tasks: [PODNet](https://arxiv.org/abs/2004.13513) `[ECCV 2020]`

# Miscellaneous

* **2024**:
    * RLHF: [WARP: On the Benefits of Weight Averaged Rewarded Policies](https://arxiv.org/abs/2406.16768)
    * AI Ethics: [A Mechanism-Based Approach to Mitigating Harms from Persuasive Generative AI](https://arxiv.org/abs/2404.15058)
* **2019**: **Core**: [Fashion garments color detection](https://www.researchgate.net/profile/Arthur-Douillard/publication/344505647_CORE_Color_Regression_for_Multiple_Colors_Fashion_Garments/links/5faa9cf3299bf15bae0637d3/CORE-Color-Regression-for-Multiple-Colors-Fashion-Garments.pdf) `[CVPR Workshop 2020]`
* **2018**: Won the NATO challenge with an aerial object detection method based on RetinaNet while at Dataiku: [post](https://blog.dataiku.com/object-detection-with-deep-learning-on-aerial-imagery)

