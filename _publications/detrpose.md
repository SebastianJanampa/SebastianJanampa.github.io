---
title: "DETRPose: Real-time end-to-end transformer model for multi-person pose estimation"
collection: publications
category: conferences
permalink: /publication/detrpose
date: 2025-06-16
venue: 'under review'
paperurl: 'https://arxiv.org/abs/2506.13027'
---
Multi-person pose estimation (MPPE) estimates keypoints for all individuals present in an image. 
MPPE is a fundamental task for several applications in computer vision and virtual reality. 
Unfortunately, there are currently no transformer-based models that can perform MPPE in real time. 
The paper presents a family of transformer-based models capable of performing multi-person 2D pose estimation in real-time. 
Our approach utilizes a modified decoder architecture and keypoint similarity metrics to generate both positive and negative queries, thereby enhancing the quality of the selected queries within the architecture. 
Compared to state-of-the-art models, our proposed models train much faster, using 5 to 10 times fewer epochs, with competitive inference times without requiring quantization libraries to speed up the model. 
Furthermore, our proposed models provide competitive results or outperform alternative models, often using significantly fewer parameters.
The code is available at https://github.com/SebastianJanampa/DETRPose
