# SAGE: Semantic-aware Generation of Multi-view Portrait Drawings, IJCAI 2023 

comming soon...

## Abastract
Neural radiance fields (NeRF) based methods have shown amazing performance in synthesizing 3D-consistent photographic images, but fail to generate multi-view portrait drawings. The key is that the basic assumption of these methods -- *a surface point is consistent when rendered from different views* -- doesn't hold for drawings. In a portrait drawing, the appearance of a facial point may changes when viewed from different angles. Besides, portrait drawings usually present little 3D information and suffer from insufficient training data. To combat this challenge, in this paper, we propose a *Semantic-Aware GEnerator* (SAGE) for synthesizing multi-view portrait drawings. Our motivation is that facial semantic labels are view-consistent and correlate with drawing techniques. We therefore propose to collaboratively synthesize multi-view semantic maps and the corresponding portrait drawings. To facilitate training, we design a semantic-aware domain translator, which generates portrait drawings based on features of photographic faces. In addition, use data augmentation via synthesis to mitigate collapsed results.We apply SAGE to synthesize multi-view portrait drawings in diverse artistic styles. Experimental results show that SAGE achieves significantly superior or highly competitive performance, compared to existing 3D-aware image synthesis methods. The codes are available at https://github.com/AiArt-HDU/SAGE. 

## Paper Information

Biao Ma, Fei Gao, Chang Jiang, Nannan Wang, Gang Xu, "Semantic-aware Generation of Multi-view Portrait Drawings," the 32nd International Joint Conference on Artificial Intelligence (IJCAI), accepted, 2023.

## Pipeline

![](fig_pipeline.jpg)


## Synthesized Sketches

![](fig-sketch.jpg)


## Synthesized Oil-paintings (WikiArt)

![](fig-wikiart.jpg)
