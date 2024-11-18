---
title: "Preprint: Distillation-Based Model Compression Framework for Swin Transformer"
collection: publications
category: conferences
permalink: /publication/2024-11-23-distillation-based-framework-vit
excerpt: ''
date: 2024-11-16
venue: 'IEEE International Conference on Future Machine Learning and Data Science (FMLDS)'
paperurl: 'https://easychair.org/publications/preprint/fgwP'
slidesurl: 'https://easychair.org/smart-slide/slide/XWFSm'
---

_Preprint for our accepted paper at 2024 IEEE International Conference on Future Machine Learning and Data Science (FMLDS) that's taking place on the 23rd of November 2024._

Vision Transformers (ViTs) have gained significant attention in computer vision due to their exceptional model capabilities. However, most ViT models suffer from high complexity, with a large number of parameters that demand considerable memory and inference time, limiting their applicability on resource-constrained devices. To address this issue, we propose a distillation-based framework for compressing large models for smaller datasets. The framework leverages fine-tuning and knowledge distillation to accelerate the training process of compressed models. To evaluate its effectiveness, two compressed Swin Transformer models, Swin-N and Swin-M, were introduced and tested on the CIFAR-100 dataset. Experimental results demonstrate that when trained using the proposed framework, both Swin-N and Swin-M exhibit significant improvements in accuracy compared to their counterparts trained from scratch, with Swin-N achieving an 18.89% increase and Swin-M showing a 20.10% improvement. Additionally, Swin-M closely approximates the accuracy of the Swin-T teacher model, further validating the effectiveness of the framework.
