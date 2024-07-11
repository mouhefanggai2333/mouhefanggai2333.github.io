---
title: "OctFormer: Efficient Octree-Based Transformer for Point Cloud Compression with Local Enhancement"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-10-1
venue: 'Proceedings of the 2023 AAAI Conference on Artificial Intelligence (AAAI)'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'M. Cui, J. Long, M. Feng, B. Li, and K Huang*, OctFormer: Efficient Octree-Based Transformer for Point Cloud Compression with Local Enhancement. Proceedings of the 2023 AAAI Conference on Artificial Intelligence (AAAI).'
---

Point cloud compression with a higher compression ratio and tiny loss is essential for efficient data transportation. However, previous methods that depend on 3D convolution or frequent multi-head self-attention operations bring huge computations. 
To address this problem, we propose an octree-based Transformer compression method called OctFormer, which does not rely on the occupancy information of sibling nodes.
Our method uses non-overlapped context windows to construct octree node sequences and share the result of a multi-head self-attention operation among a sequence of nodes. %them.
Besides, we introduce a locally-enhance module for exploiting the sibling features and a positional encoding generator for enhancing the translation invariance of the octree node sequence.
Compared to the previous state-of-the-art works, our method obtains up to 17\% Bpp savings compared to the voxel-context-based baseline and saves an overall 99\% coding time compared to the attention-based baseline.
