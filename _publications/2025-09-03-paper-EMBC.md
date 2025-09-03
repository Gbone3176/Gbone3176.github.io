---
title: "Prototype-Driven Class-Conditional Synthesis for High-Quality Chest X-ray Image Generation"
collection: publications
category: conferences
permalink: /publication/2025-09-03-paper-EMBC
excerpt: '提出类别原型驱动的扩散模型（CPDM），通过构造类别原型库和类别与类别的隐空间特征之间的交叉注意力机制，解决医学影像生成中的类别不平衡问题，同时提升图像质量和多样性'
date: 2025-09-03
venue: 'EMBC'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/Prototype-Driven Class-Conditional Synthesis for High-Quality Chest X-ray Image Generation.pdf'
citation: 'updating...'
---

As an advanced image argumentation approach, image generation technology offers a novel solution to the challenges of data scarcity and distribution imbalance in the medical field. However, the severe imbalance in the class distribution causes the networks to overfit to the head classes, while failing to adequately model the distribution of the tail class data during image generation, ultimately compromising the quality of the generated images. To solve this problem, we propose a Class Prototype-Driven Diffusion Model (CPDM) to improve class-conditional image synthesis on long-tailed chest X-ray images datasets. To fully extract the features of limited tail classes while avoiding overfitting to head classes, we introduce a Class Prototype Bank, which stores representative feature vectors of each class. Furthermore, by integrating cross-attention mechanisms between image features and class-specific prototypes, CPDM effectively captures fine-grained class features, enhancing both the realism and diversity of the generated images. Experiments show that our CPDM achieves the lowest FID=31.600 and highest IS=2.842, highlighting the effectiveness of CPDM in mitigating class imbalance and data scarcity in chest X-ray imaging. In downstream experiments, the classifier achieves a 17.22% improvement on the mAUC for 14 thoracic diseases when trained on a mixed dataset containing only 1% real images.