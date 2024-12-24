---
title: "DT-LSD: Deformable Transformer-based Line Segment Detection"
collection: publications
category: conferences
permalink: /publication/dtlsd
date: 2025-02-28
venue: Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) 2025''
paperurl: 'https://arxiv.org/abs/2411.13005'
---

Line segment detection is a fundamental low-level task in computer vision, and improvements in this task can impact more advanced methods that depend on it. Most new methods developed for line segment detection are based on Convolutional Neural Networks (CNNs). Our paper seeks to address challenges that prevent the wider adoption of transformer-based methods for line segment detection. More specifically, we introduce a new model called Deformable Transformer-based Line Segment Detection (DT-LSD) that supports cross-scale interactions and can be trained quickly. This work proposes a novel Deformable Transformer-based Line Segment Detector (DT-LSD) that addresses LETR's drawbacks. For faster training, we introduce Line Contrastive DeNoising (LCDN), a technique that stabilizes the one-to-one matching process and speeds up training by 34×. We show that DT-LSD is faster and more accurate than its predecessor transformer-based model (LETR) and outperforms all CNN-based models in terms of accuracy. In the Wireframe dataset, DT-LSD achieves 71.7 for sAP10 and 73.9 for sAP15; while 33.2 for sAP10 and 35.1 for sAP15 in the YorkUrban dataset. The code is available at [https://github.com/SebastianJanampa/DT-LSD](https://github.com/SebastianJanampa/DT-LSD)
