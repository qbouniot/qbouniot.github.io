---
title: "Rethinking Concept Bottleneck Models: From Pitfalls to Solutions"
collection: publications
# permalink: /affscore_website
excerpt: '[Paper](http://arxiv.org/abs/2603.05629)'
date: 2026-03-27
venue: 'CVPR'
# paperurl: 'https://arxiv.org/abs/2010.01992'
citation: 'Merve Tapli, <u>Quentin Bouniot</u>, Wolfgang Stammer, Zeynep Akata, Emre Akbas'
share: False
teaser: /images/publications/CVPR2026_cbm_main.png
---

![Main Figure](/images/publications/CVPR2026_cbm_main.png)

## Abstract

Concept Bottleneck Models (CBMs) ground predictions in human-understandable concepts but face fundamental limitations: the absence of a metric to pre-evaluate concept relevance, the "linearity problem" causing recent CBMs to bypass the concept bottleneck entirely, an accuracy gap compared to opaque models, and finally the lack of systematic study on the impact of different visual backbones and VLMs. We introduce CBM-Suite, a methodological framework to systematically addresses these challenges. First, we propose an entropy-based metric to quantify the intrinsic suitability of a concept set for a given dataset. Second, we resolve the linearity problem by inserting a non-linear layer between concept activations and the classifier, which ensures that model accuracy faithfully reflects concept relevance. Third, we narrow the accuracy gap by leveraging a distillation loss guided by a linear teacher probe. Finally, we provide comprehensive analyses on how different vision encoders, vision-language models, and concept sets interact to influence accuracy and interpretability in CBMs. Extensive evaluations show that CBM-Suite yields more accurate models and provides insights for improving concept-based interpretability.

## Resources

- [Paper](http://arxiv.org/abs/2603.05629)
- [Code](https://github.com/mervetapli/CBMSuite)


## Bibtex

>```BibTex
>@article{tapli2026rethinking,
>  title={Rethinking Concept Bottleneck Models: From Pitfalls to Solutions}, 
>  author={Tapli, Merve and Bouniot, Quentin and Stammer, Wolfgang and Akata, Zeynep and Akbas, Emre},
>  journal={CVPR},
>  year={2026}
>}
>``` 