---
title:          "SpiderMesh: Spatial-aware Demand-guided Recursive Meshing for RGB-T Semantic Segmentation"
date:           2023-03-15 00:01:00 +0800
selected:       true
pub:            "[TechReport'2023] SOTA on RGB-T segmentation benchmarks"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2023"
abstract: >-
  <p>
  We proposed a systematic multimodal learning approach for practical RGB-T (thermal) segmentation, termed Spatial-aware Demand-guided Recursive Meshing (SpiderMesh), to leverage the additional thermal signals in a proactive manner. SpiderMesh (1) proactively compensates inadequate contextual semantics in optically-impaired regions via a demand-guided target masking algorithm and (2) refines multimodal semantic features with recursive meshing to improve pixel-level semantic analysis performance. We further introduce an asymmetric data augmentation technique M-CutOut, and enable semi-supervised learning to fully utilize RGB-T labels only sparsely available in practical use. It is evaluated on <em> MFNet</em> and <em> PST900</em> datasets, and achieves SOTA performance on standard RGB-T segmentation benchmarks.
  </p>
cover:          /assets/images/covers_researches/SpiderMesh.png
authors:
  - Siqi Fan
  - Zhe Wang
  - Yan Wang
  - Jingjing Liu
links:
  Paper: https://arxiv.org/pdf/2303.08692.pdf
  Code: https://github.com/leofansq/SpiderMesh
---