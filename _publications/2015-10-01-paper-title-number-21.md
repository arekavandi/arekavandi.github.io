---
title: "RS-Reg: Probabilistic and Robust Certified Regression through Randomized Smoothing"
collection: publications
excerpt: 'Aref Miri Rekavandi, Olga Ohrimenko and Benjamin IP Rubinstein'
date: 2025-04-05
venue: 'Transactions on Machine Learning Research'
---
[Paper](https://openreview.net/forum?id=AcLlg4J52H&referrer=%5Bthe%20profile%20of%20Aref%20Miri%20Rekavandi%5D(%2Fprofile%3Fid%3D~Aref_Miri_Rekavandi1) [Code](https://github.com/arekavandi/Certified_Robust_Regression)

Randomized smoothing has shown promising certified robustness against adversaries in classification tasks. Despite such success with only zeroth-order access to base models, randomized smoothing has not been extended to a general form of regression. By defining robustness in regression tasks flexibly through probabilities, we demonstrate how to establish upper bounds on input data point perturbation (using the $\ell_2$ norm) for a user-specified probability of observing valid outputs. Furthermore, we showcase the asymptotic property of a basic averaging function in scenarios where the regression model operates without any constraint. We then derive a certified upper bound of the input perturbations when dealing with a family of regression models where the outputs are bounded. Our simulations verify the validity of the theoretical results and reveal the advantages and limitations of simple smoothing functions, i.e., averaging, in regression tasks. The code is publicly available at \url{https://github.com/arekavandi/Certified_Robust_Regression}.


