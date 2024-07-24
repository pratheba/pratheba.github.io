---
title: "FORA: Fast-Forward Caching in Diffusion Transformer Acceleration"
collection: publications
permalink: /publication/FORA
excerpt: 'Fast-Forward Caching in Diffusion Transformer Acceleration.'
date: 2024-07-01
venue: 'arXiv'
citation: 'Pratheba Selvaraju,Tianyu Ding, Tianyi Chen, Ilya Zharkov, Luming Liang. &quot; FORA: Fast-Forward Caching in Diffusion Transformer Acceleration.&quot; <i>arXiv</i>.'
---
<img src = '../images/FORA_teaser.png'>
<div style="text-align: justify">
<h3>Abstract</h3> 
Diffusion transformers (DiT) have become the de facto choice for generating high-quality images and videos, largely due to their scalability, which enables the construction of larger models for enhanced performance. However, the increased size of these models leads to higher inference costs, making them less attractive for real-time applications. We present Fast-FORward CAching (FORA), a simple yet effective approach designed to accelerate DiT by exploiting the repetitive nature of the diffusion process. FORA implements a caching mechanism that stores and reuses intermediate outputs from the attention and MLP layers across denoising steps, thereby reducing computational overhead. This approach does not require model retraining and seamlessly integrates with existing transformer-based diffusion models. Experiments show that FORA can speed up diffusion transformers several times over while only minimally affecting performance metrics such as the IS Score and FID. By enabling faster processing with minimal trade-offs in quality, FORA represents a significant advancement in deploying diffusion transformers for real-time applications.
</div>
[Download paper here](https://arxiv.org/abs/2407.01425)
