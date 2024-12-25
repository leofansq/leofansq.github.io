---
title:          "EMIFF: Enhanced Multi-scale Image Feature Fusion for Vehicle-Infrastructure Cooperative 3D Object Detection"
date:           2024-02-23 00:01:00 +0800
selected:       false
pub:            "IEEE International Conference on Robotics and Automation (ICRA)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"
abstract: >-
  In autonomous driving, cooperative perception makes use of multi-view cameras from both vehicles and infrastructure, providing a global vantage point with rich semantic context of road conditions beyond a single vehicle viewpoint. Currently, two major challenges persist in vehicle-infrastructure cooperative 3D (VIC3D) object detection: 1) inherent pose errors when fusing multi-view images, caused by time asynchrony across cameras; 2) information loss in transmission process resulted from limited communication bandwidth. To address these issues, we propose a novel camera-based 3D detection framework for VIC3D task, Enhanced Multi-scale Image Feature Fusion (EMIFF). To fully exploit holistic perspectives from both vehicles and infrastructure, we propose Multi-scale Cross Attention (MCA) and Camera-aware Channel Masking (CCM) modules to enhance infrastructure and vehicle features at scale, spatial, and channel levels to correct the pose error introduced by camera asynchrony. We also introduce a Feature Compression (FC) module with channel and spatial compression blocks for transmission efficiency. Experiments show that EMIFF achieves SOTA on DAIR-V2X-C datasets, significantly outperforming previous early-fusion and late-fusion methods with comparable transmission costs.
cover:          /assets/images/covers_researches/EMIFF.png
authors:
  - Zhe Wang
  - Siqi Fan
  - Xiaoliang Huo
  - Tongda Xu
  - Yan Wang
  - Jingjing Liu
  - Yilun Chen
  - Ya-Qin Zhang
links:
  Paper: https://arxiv.org/pdf/2402.15272
  Code: https://github.com/Bosszhe/EMIFF
  第三方中文解读: https://mp.weixin.qq.com/s/ydCbijfb4l74Jxu2Gv5rkg
---