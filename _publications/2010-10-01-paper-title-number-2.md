---
title: A Du-Octree based Cross-Attention Model for LiDAR Geometry Compression
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: ''
date: 2024-05-14
venue: '2024 IEEE International Conference on Robotics and Automation (ICRA)'
slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
citation: 'M. Cui, M. Feng, J. Long, D. Hu, S. Zhao, and K. Huang*. A Du-Octree based Cross-Attention Model for LiDAR Geometry Compression，2024 IEEE International Conference on Robotics and Automation (ICRA).'
---

Point cloud compression is an essential technology for efficient storage and transmission of 3D data. Previous methods usually use hierarchical tree data structures for encoding the spatial sparseness of point clouds. However, the node context within the tree is not fully discovered since the feature space among nodes varies significantly. To address this problem, we innovatively represent the LiDAR points in a two-octree structure instead of using traditional single-octree coding, and then design the cross-attention model to capture the hierarchical features between different octrees, of which each octree incorporates a transformer-based deep entropy model and an arithmetic encoder. Besides, we introduce the untied cross-aware position encoding with principal component analysis and different projection matrices, which enhances the correlations over two octrees’ attention feature embeddings. Experimental results show that our method outperforms the previous state-of-the-art works, achieving up to 8.2% Bpp savings on point cloud benchmark datasets with different lasers.
