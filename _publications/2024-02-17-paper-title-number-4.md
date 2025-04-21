---
title: "GAEM: Graph-driven Attention-based Entropy Model for LiDAR Point Cloud Compression"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: ''
date: 2025-03-17
venue: 'IEEE Transactions on Circuits and Systems for Video Technolog'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'M. Cui, Y. Zhong, M. Feng, J. Long, Y. Ling, J. Xu, and K Huang*, GAEM: Graph-driven Attention-based Entropy Model for LiDAR Point Cloud Compression, IEEE Transactions on Circuits and Systems for Video Technology'
---

High-quality LiDAR point cloud  (LPC) coding is essential for efficiently transmitting and storing the vast amounts of data required for accurate 3D environmental representation.
The Octree-based entropy coding framework has emerged as the predominant method, however, previous study usually overly relies on large-scale attention-based context prediction to encode Octree nodes, overlooking the inherent correlational properties of this structure. In this paper, we propose a novel Graph-driven Attention-based Entropy Model (GAEM), which adopts partitioned graph attention mechanisms to uncover contextual dependencies among neighboring nodes. Different from the Cartesian coordinate-based coding mode with higher redundancy, GAEM uses the multi-level spherical Octree to organize point clouds, improving the quality of LPC reconstruction.
GAEM combines graph convolution for node feature embedding and grouped-graph attention for exploiting dependency among contexts, which preserves performance in low-computation using localized nodes. Besides, to further increase the receptive field, we design a high-resolution cross-attention module introducing sibling nodes.
Experimental results show that our method achieves state-of-the-art performance on the LiDAR benchmark SemanticKITTI and MPEG-specified dataset Ford, compared to all baselines.
Compared to the benchmark GPCC, our method achieves gains of up to 53.9% and 53.6% on SemanticKITTI and Ford while compared to the sibling-introduced methods, we achieve up to 42.3% and 44.7% savings in encoding/decoding time. In particular, our GAEM allows for extension to downstream tasks (i.e., vehicle detection and semantic segmentation), further demonstrating the practicality of the method. 
