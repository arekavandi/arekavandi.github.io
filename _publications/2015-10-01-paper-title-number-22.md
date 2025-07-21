---
title: "Box It to Bind It: Unified Layout Control and Attribute Binding in T2I Diffusion Models"
collection: publications
excerpt: 'Ashkan Taghipour, Morteza Ghahremani, Mohammed Bennamoun, Aref Miri Rekavandi, Hamid Laga and Farid Boussaid'
date: 2025-04-20
venue: 'IEEE Transactions on Multimedia'
---
[Paper](https://arxiv.org/abs/2402.17910) [Code](https://github.com/nextaistudio/BoxIt2BindIt)

While latent diffusion models (LDMs) excel at creating imaginative images, they often lack precision in semantic fidelity and spatial control over where objects are generated. To address these deficiencies, we introduce the Box-it-to-Bind-it (B2B) module - a novel, training-free approach for improving spatial control and semantic accuracy in text-to-image (T2I) diffusion models. B2B targets three key challenges in T2I: catastrophic neglect, attribute binding, and layout guidance. The process encompasses two main steps: i) Object generation, which adjusts the latent encoding to guarantee object generation and directs it within specified bounding boxes, and ii) attribute binding, guaranteeing that generated objects adhere to their specified attributes in the prompt. B2B is designed as a compatible plug-and-play module for existing T2I models, markedly enhancing model performance in addressing the key challenges. We evaluate our technique using the established CompBench and TIFA score benchmarks, demonstrating significant performance improvements compared to existing methods. The source code will be made publicly available at this https URL.


