---
title: "IT-RUDA: Information Theory Assisted Robust Unsupervised Domain Adaptation"
collection: publications
excerpt: 'Shima Rashidi, Ruwan Tennakoon, Aref Miri Rekavandi, Papangkorn Jessadatavornwong, Amanda Freis, Garret Huff, Mark Easton, Adrian Mouritz, Reza Hoseinnezhad and Alireza Bab-Hadiashar'
date: 2025-02-25
venue: 'ACM Transactions on Intelligent Systems and Technology'
---
[Paper](https://dl.acm.org/doi/abs/10.1145/3716853) [Code](https://github.com/rashidis/IT-RUDA)

Domain adaptation is a well-studied field in machine learning. Distribution shift between train (source) and test (target) datasets is a common problem encountered in machine learning applications. One approach to resolve this issue is to use the Unsupervised Domain Adaptation (UDA) technique that carries out knowledge transfer from a label-rich source domain to an unlabeled target domain. Outliers that exist in either source or target datasets can introduce additional challenges when using UDA in practice. In this paper, 
$\alpha$-divergence is used as a measure to minimize the discrepancy between the source and target distributions while inheriting robustness, adjustable with a single parameter $\alpha$, as the prominent feature of this measure. Here, it is shown that the other well-known divergence-based UDA techniques can be derived as special cases of the proposed method. Furthermore, a theoretical upper bound is derived for the loss in the target domain in terms of the source loss and the 
$\alpha$-divergence between the joint distributions in the two domains. The robustness of the proposed method is validated through testing on several benchmarked datasets in open-set and partial UDA setups where extra classes existing in target and source datasets are considered as outliers. Code is publicly available at https://github.com/rashidis/IT-RUDA.


