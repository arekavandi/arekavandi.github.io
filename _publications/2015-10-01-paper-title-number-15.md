---
title: "B-Pose: Bayesian Deep Network for Camera 6-DoF Pose Estimation from RGB Images"
collection: publications
excerpt: 'Aref Miri Rekavandi, Farid Boussaid, Abd-Krim Seghouane, and Mohammed Bennamoun'
date: 2023-09-07
venue: 'IEEE Robotics and Automation Letters'
---
[Paper](https://ieeexplore.ieee.org/abstract/document/10242363) [Code](https://github.com/arekavandi/BPose)

Camera pose estimation has long relied on geometry-based approaches and sparse 2D-3D keypoint correspondences. With the advent of deep learning methods, the estimation of camera pose parameters, i.e., the six parameters that describe position and rotation denoted by 6 Degrees of Freedom (6-DoF), has decreased from tens of meters to a few centimeters in median error for indoor applications. For outdoor applications, errors can be quite large and highly dependent on the variations in occlusion, contrast, brightness, repetitive structures, or blur introduced by camera motion. To address these limitations, we introduce, B-Pose, a Bayesian Convolutional deep network capable of not only automatically estimating the camera's pose parameters from a single RGB image but also provides a measure of uncertainty in the parameter estimation. Reported experiments on outdoor and indoor datasets demonstrate that B-Pose outperforms SOTA techniques and generalizes better to unseen RGB images. A strong correlation is shown between the prediction error and the model's uncertainty, indicating that the prediction is almost always incorrect whenever the model's uncertainty is high. 


