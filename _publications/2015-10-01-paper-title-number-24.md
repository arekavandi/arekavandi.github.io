---
title: "Faster Image2Video Generation: A Closer Look at CLIP Image Embedding's Impact on Spatio-Temporal Cross-Attentions"
collection: publications
excerpt: 'Ashkan Taghipour, Morteza Ghahremani, Mohammed Bennamoun, Aref Miri Rekavandi, Zinuo Li, Hamid Laga, Farid Boussaid'
date: 2025-07-25
venue: 'IEEE ACCESS'
---
[Paper](https://ieeexplore.ieee.org/abstract/document/11114950) [Code](https://github.com/anonymous-coderrs/VCUT/blob/main/README.md)

This paper explores the effectiveness—specifically in improving video consistency—and the computational burden of Contrastive Language-Image Pre-Training (CLIP) embeddings in video generation. The investigation is conducted using the Stable Video Diffusion (SVD) framework, a state-of-the-art method for generating high-quality videos from image inputs. The diffusion process in SVD generates videos by iteratively denoising noisy inputs over multiple steps. Our analysis reveals that employing CLIP in the cross-attention mechanism at every step of this denoising process has limited impact on maintaining subject and background consistency while imposing a significant computational burden on the video generation network. To address this, we propose Video Computation Cut (VCUT), a novel, training-free optimization method that significantly reduces computational demands without compromising output quality. VCUT replaces the computationally intensive temporal cross-attention with a one-time computed linear layer, cached and reused across inference steps. This innovation reduces up to 322T MACs per 25-frame video, decreases model parameters by 50M, and cuts latency by 20% compared to baseline methods. By streamlining the SVD architecture, our approach makes high-quality video generation more accessible, cost-effective, and eco-friendly, paving the way for real-time applications in telemedicine, remote learning, and automated content creation.



