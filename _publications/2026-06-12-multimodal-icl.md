---
title: "Dissecting Multimodal In-Context Learning: Modality Asymmetries and Circuit Dynamics in modern Transformers"
collection: publications
# permalink: /affscore_website
excerpt: '[Paper](https://arxiv.org/abs/2601.20796)'
date: 2026-06-12
venue: 'International Conference on Machine Learning (ICML)'
citation: 'Yiran Huang, Karsten Roth, <u>Quentin Bouniot</u>, Wenjia Xu, Zeynep Akata'
share: False
teaser: /images/publications/ICML2026-multimodal-icl-teaser.png
---

![Main Figure](/images/publications/ICML2026-multimodal-icl-teaser.png)

> **Spotlight**

## Abstract

Transformer-based multimodal large language models often exhibit in-context learning (ICL) abilities. Motivated by this phenomenon, we ask: how do transformers learn to associate information across modalities from in-context examples? We investigate this question through controlled experiments on small transformers trained on synthetic classification tasks, enabling precise manipulation of data statistics and model architecture. We begin by revisiting core principles of unimodal ICL in modern transformers. While several prior findings replicate, we find that Rotary Position Embeddings (RoPE) increases the data complexity threshold for ICL. Extending to the multimodal setting reveals a fundamental learning asymmetry: when pretrained on high-diversity data from a primary modality, surprisingly low data complexity in the secondary modality suffices for multimodal ICL to emerge. Mechanistic analysis shows that both settings rely on an induction-style mechanism that copies labels from matching in-context exemplars; multimodal training refines and extends these circuits across modalities. Our findings provide a mechanistic foundation for understanding multimodal ICL in modern transformers and introduce a controlled testbed for future investigation.

## Resources

- [Paper](https://arxiv.org/abs/2601.20796)
- [Code](https://github.com/YiranHuangIrene/multimodal-icl)

<!-- ## Bibtex

>```BibTex
>@article{huang2026dissecting,
>  title={Dissecting Multimodal In-Context Learning: Modality Asymmetries and Circuit Dynamics in modern Transformers},
>  author={Huang, Yiran and Roth, Karsten and Bouniot, Quentin and Xu, Wenjia and Akata, Zeynep},
>  journal={International Conference on Machine Learning (ICML)},
>  year={2026}
>}
>```  -->