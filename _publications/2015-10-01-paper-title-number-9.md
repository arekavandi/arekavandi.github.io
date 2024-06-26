---
title: "Adaptive Brain Activity Detection in Structured Interference and Partially Homogeneous Locally Correlated Disturbance"
collection: publications
excerpt: 'Aref Miri Rekavandi, Abd-Krim Seghouane, and Robin Evans'
date: 2022-03-23
venue: 'IEEE Transactions on Biomedical Engineering'
---
[Paper](https://ieeexplore.ieee.org/abstract/document/9740406) [Code](https://github.com/arekavandi/Banded_Detection)

Objective: In this paper, we aim to address the problem of subspace detection in the presence of locally-correlated complex Gaussian noise and interference. For applications like brain activity detection using functional magnetic resonance imaging (fMRI) data where the noise is possibly locally correlated, using the sample covariance estimator is not a suitable choice due to significant dependency of its accuracy on the number of observations. Methods: In this study, we take advantage of an assumed banded structure in the covariance matrix to model the local dependence in the noise and propose a new covariance estimation approach. In particular, we use the idea of factorizing the joint likelihood function into a few conditional likelihood terms and maximizing each term independently of the others. This process leads to an explicit estimator for banded covariance matrices which requires fewer observations to achieve the same accuracy as the sample covariance. This estimate is then fed into an adaptive matched filter, two-step Rao and two-step Wald tests for detection. Results: Simulation results reveal the superiority of the proposed methods over well known classical detectors. Finally, the proposed methods are applied to functional magnetic resonance imaging (fMRI) data to localize neural activities in the brain. Conclusion: The proposed method can offer better activation maps in terms of accuracy and spatial smoothness. Significance: The proposed methods can be seen as alternatives for standard detection approaches which are not perfectly aligned with the properties of fMRI data.


