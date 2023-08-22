---
title: "Adaptive subspace detector in high dimensional space with insufficient training data"
collection: publications
excerpt: 'Aref Miri Rekavandi, Abd-Krim Seghouane, and Robin Evans'
date: 2019-05-01
venue: 'IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)'
---
[Paper](https://ieeexplore.ieee.org/abstract/document/8683677)

Adaptive subspace detectors (ASD) generalize matched subspace detectors (MSD) by accounting for possible correlation. Both ASD and MSD are derived using the generalized likelihood ratio test (GLRT). While MSD assumes there is no correlation between observations, ASD estimates a sample covariance matrix of possibly correlated samples using signal-free observations. In this paper, we address the performance of the ASD when the number of secondary data is insufficient and the observed signal lies in higher dimensional space. Such high dimensional spaces are frequently encountered in functional magnetic resonance imaging (fMRI) data for the analysis of brain activation detection. We propose a methodology that works based on the latent variables in a lower dimensional space. A low-rank decomposition of the sample covariance matrix is derived based on the singular value decomposition (SVD) and an adaptive basis selection method is used to decide which eigen-vectors are useful in data projection. Performing detection in the lower dimensional subspace has the benefit of reducing the number of parameters which need to be estimated. Simulation results show superiority of our proposed adaptive reduced subspace detector (ARSD) over conventional ASD in term of probability of detection.


