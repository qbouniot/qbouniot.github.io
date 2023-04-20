---
title: "Proposal-Contrastive Pretraining for Object Detection from Fewer Data"
collection: publications
permalink: /publication/2023-03-01-selfsup-od
excerpt: '[Paper link](https://openreview.net/forum?id=gm0VZ-h-hPy)'
date: 2023-03-01
venue: 'ICLR'
citation: '"Proposal-Contrastive Pretraining for Object Detection from Fewer Data" Quentin Bouniot,Romaric Audigier, Angelique Loesch, Amaury Habrard; The Eleventh International Conference on Learning Representations, 2023 '
---

> **Notable Top-25%**


## Abstract

The use of pretrained deep neural networks represents an attractive way to achieve strong results with few data available. When specialized in dense problems such as object detection, learning local rather than global information in images has proven to be more efficient. However, for unsupervised pretraining, the popular contrastive learning requires a large batch size and, therefore, a lot of resources. To address this problem, we are interested in transformer-based object detectors that have recently gained traction in the community with good performance and with the particularity of generating many diverse object proposals. 
In this work, we present Proposal Selection Contrast (ProSeCo), a novel unsupervised overall pretraining approach that leverages this property. ProSeCo uses the large number of object proposals generated by the detector for contrastive learning, which allows the use of a smaller batch size, combined with object-level features to learn local information in the images. To improve the effectiveness of the contrastive loss, we introduce the object location information in the selection of positive examples to take into account multiple overlapping object proposals. When reusing pretrained backbone, we advocate for consistency in learning local information between the backbone and the detection head. 
We show that our method outperforms state of the art in unsupervised pretraining for object detection on standard and novel benchmarks in learning with fewer data. 

## Resources

> [Paper link](https://openreview.net/forum?id=gm0VZ-h-hPy)

>**For attribution in academic contexts, please cite this work as**
>
>"Proposal-Contrastive Pretraining for Object Detection from Fewer Data" **Quentin Bouniot**, Romaric Audigier, Angelique Loesch, Amaury Habrard; The Eleventh International Conference on Learning Representations, 2023 


>```BibTex
>@inproceedings{
>bouniot2023proposalcontrastive,
>title={Proposal-Contrastive Pretraining for Object Detection from Fewer Data},
>author={Quentin Bouniot and Romaric Audigier and Angelique Loesch and Amaury Habrard},
>booktitle={The Eleventh International Conference on Learning Representations },
>year={2023},
>url={https://openreview.net/forum?id=gm0VZ-h-hPy}
>}
>``` 