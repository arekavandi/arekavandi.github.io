---
title: "Certified Adversarial Robustness via Randomized α-Smoothing for Regression Models"
collection: publications
excerpt: 'Aref Miri Rekavandi, Farhad Farokhi, Olga Ohrimenko and Benjamin IP Rubinstein'
date: 2024-12-05
venue: 'NeurIPS'
---
[Paper](https://openreview.net/forum?id=jLUbLxa4XV) [Code](https://github.com/arekavandi/Certified_adv_RRegression)

Certified adversarial robustness of large-scale deep networks has progressed substantially after the introduction of randomized smoothing. Deep net classifiers are now provably robust in their predictions against a large class of threat models, including $\ell_1$, $\ell_2$, and $\ell_\infty$ norm-bounded attacks. Certified robustness analysis by randomized smoothing has not been performed for deep regression networks where the output variable is continuous and unbounded. In this paper, we extend the existing results for randomized smoothing into regression models using powerful tools from robust statistics, in particular, $\alpha$-trimming filter as the smoothing function. Adjusting the hyperparameter $\alpha$ achieves a smooth trade-off between desired certified robustness and utility. For the first time, we propose a benchmark for certified robust regression in visual positioning systems using the Cambridge Landmarks dataset where robustness analysis is essential for autonomous navigation of AI agents and self-driving cars. Code is publicly available at \url{https://github.com/arekavandi/Certified_adv_RRegression/}.


