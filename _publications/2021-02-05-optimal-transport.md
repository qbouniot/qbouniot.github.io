---
title: "Optimal Transport as a Defense Against Adversarial Attacks"
collection: publications
permalink: /publication/2021-02-05-optimal-transport
excerpt: '[Paper link](https://arxiv.org/abs/2102.03156)'
date: 2021-02-05
venue: 'ICPR'
# paperurl: 'https://arxiv.org/abs/2102.03156'
citation: ' &quot;Optimal Transport as a Defense Against Adversarial Attacks.&quot; Quentin Bouniot, Romaric Audigier, Angélique Loesch (2021). <i>IEEE International Conference on Pattern Recognition (ICPR) 2020</i>.'
---

## Abstract

Deep learning classifiers are now known to have flaws in the representations of their class. Adversarial attacks can find a human-imperceptible perturbation for a given image that will mislead a trained model. The most effective methods to defend against such attacks trains on generated adversarial examples to learn their distribution. Previous work aimed to align original and adversarial image representations in the same way as domain adaptation to improve robustness. Yet, they partially align the representations using approaches that do not reflect the geometry of space and distribution. In addition, it is difficult to accurately compare robustness between defended models. Until now, they have been evaluated using a fixed perturbation size. However, defended models may react differently to variations of this perturbation size. In this paper, the analogy of domain adaptation is taken a step further by exploiting optimal transport theory. We propose to use a loss between distributions that faithfully reflect the ground distance. This leads to SAT (Sinkhorn Adversarial Training), a more robust defense against adversarial attacks. Then, we propose to quantify more precisely the robustness of a model to adversarial attacks over a wide range of perturbation sizes using a different metric, the Area Under the Accuracy Curve (AUAC). We perform extensive experiments on both CIFAR-10 and CIFAR-100 datasets and show that our defense is globally more robust than the state-of-the-art.

## Resources

- [Paper link](https://arxiv.org/abs/2102.03156)
- [Video](https://crossminds.ai/video/optimal-transport-as-a-defense-against-adversarial-attacks-6035a52dc390863d8e9c1b1f/)
- [Slides]({{ site.url }}/files/slides_ICPR2020_QB.pdf)
- [Poster]({{ site.url }}/files/poster_ICPR2020_QB.pdf)

>**For attribution in academic contexts, please cite this work as**
>
>"Optimal transport as a defense against adversarial attacks."
 **Quentin Bouniot**, Romaric Audigier, Angelique Loesch. *2020 25th International Conference on Pattern Recognition (ICPR).* IEEE, 2021.

>```BibTex
>@inproceedings{bouniot2021optimal,
>  title={Optimal transport as a defense against adversarial attacks},
>  author={Bouniot, Quentin and Audigier, Romaric and Loesch, Angelique},
>  booktitle={2020 25th International Conference on Pattern Recognition (ICPR)},
>  pages={5044--5051},
>  year={2021},
>  organization={IEEE}
>}
>```