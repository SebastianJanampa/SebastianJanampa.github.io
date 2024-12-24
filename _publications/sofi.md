---
title: "SOFI: Multi-Scale Deformable Transformer for Camera Calibration with Enhanced Line Queries"
collection: publications
category: conferences
permalink: /publication/sofi
date: 2024-11-28
venue: 'The 35th British Machine Vision Conference 2024'
paperurl: 'https://bmvc2024.org/proceedings/528'
---

Camera calibration consists of estimating camera parameters such as the zenith vanishing point and horizon line. Estimating the camera parameters allows other tasks like 3D rendering, artificial reality effects, and object insertion in an image. Transformer-based models have provided promising results; however, they lack cross-scale interaction. In this work, we introduce multi-Scale defOrmable transFormer for camera
calibratIon with enhanced line queries, SOFI. SOFI improves the line queries used in CTRL-C and MSCC by using both line content and line geometric features. Moreover, SOFI’s line queries allow transformer models to adopt the multi-scale deformable attention mechanism to promote cross-scale interaction between the feature maps produced by the backbone. SOFI outperforms existing methods on the Google Street View, Horizon Line in the Wild, and Holicity datasets while keeping a competitive inference speed.
Code is available at: https://github.com/SebastianJanampa/SOFI
