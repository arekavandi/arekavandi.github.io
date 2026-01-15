---
title: "Towards Adaptive Subspace Detection in Heterogeneous Environments"
collection: publications
excerpt: 'Aref Miri Rekavandi'
date: 2025-09-02
venue: 'IEEE Journal of Selected Topics in Signal Processing'
---
[Paper](https://ieeexplore.ieee.org/abstract/document/11153026) [Code](https://github.com/arekavandi/Heterogeneous_Detector)

This paper takes a step towards addressing the challenge of adaptive subspace detection in non-stationary environments. While non-stationary conditions are more representative of real-world scenarios, most existing studies in detection theory are built on homogeneous or partially homogeneous assumptions. In these models, the covariance matrices of the primary and secondary datasets are either assumed to be identical or differ only up to a scaling factor. In contrast, this study relaxes this constraint by allowing the secondary dataset to share only partial covariance information with the primary dataset. Crucially, the primary dataset’s covariance matrix can differ significantly in structure. This situation commonly arises in applications such as radar and brain imaging, where the primary and secondary data may be collected at different times, in varying spatial regions, or with differing resolutions. To address this challenge, a twostep Generalized Likelihood Ratio Test (GLRT)-based detector inspired by the Adaptive Matched Filter (AMF) framework is proposed. The model assumes multivariate Gaussian noise and a known interference subspace. Simulation results demonstrate that the proposed method outperforms conventional detectors under these more general and realistic conditions.



