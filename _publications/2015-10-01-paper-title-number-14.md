---
title: "TRPAST: A tunable and robust projection approximation subspace tracking method"
collection: publications
excerpt: 'Aref Miri Rekavandi, Abd-Krim Seghouane, and Karim Abed-Meraim'
date: 2023-06-20
venue: 'IEEE Transactions on Signal Processing'
---
[Paper](https://ieeexplore.ieee.org/abstract/document/10164018) [Code](https://github.com/arekavandi/TRPAST)

In this article, the problem of estimating and tracking a subspace signal in the presence of non-Gaussian noise is addressed. In contrast to non-robust methods such as PAST, NIC, and NP3, which are based on restrictive noise models, we use the popular ϵ− contamination noise model employed in robust statistics with Gaussian density as the nominal model to estimate the subspace that the target signal lives in. Adopting a new robust measure borrowed from the information geometry, i.e., the parametric family of α− divergence, two subspace tracking methods are proposed. The first one tolerates deviations over the entire observed vector signal whereas the second method is robust to sparsely distributed deviations in entries of the observed signal vector and efficiently uses the information in clean entries to perform the subspace estimation task. Both variants are implemented recursively, and are fit for adaptive real time processing. Simulation results reveal the superiority of the proposed methods in some metrics such as subspace estimation performance (SEP) and orthonormal error (OE) in several synthetic and real world problems.


