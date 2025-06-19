---
title: ""
collection: publications
category: conferences
permalink: /publication/linea
date: 2025-10-13
venue: 'IEEE International Conference on Image Processing 2025'
---
Line detection is a basic digital image processing operation used by higher-level processing methods. 
Recently, transformer-based methods for line detection have proven to be more accurate than methods based on CNNs, at the expense of significantly lower inference speeds. 
As a result, video analysis methods that require low latencies cannot benefit from current transformer-based methods for line detection. 
In addition, current transformer-based models require pretraining attention mechanisms on large datasets (e.g., COCO or Object360). 
This paper develops a new transformer-based method that is significantly faster without requiring pretraining the attention mechanism on large datasets. 
We eliminate the need to pre-train the attention mechanism using a new mechanism, Deformable Line Attention (DLA). 
We use the term LINEA to refer to our new transformer-based method based on DLA. 
Extensive experiments show that LINEA is significantly faster and outperforms previous models on sAP in out-of-distribution dataset testing.
