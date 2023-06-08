---
title: "Cross Domain 2D-3D Descriptor Matching for Unconstrained 6- DOF Pose Estimation"
collection: publications
excerpt: 'Uzair Nadeem, Mohammed Bennamoun, Roberto Togneri, Ferdous Sohel, Aref Miri Rekavandi, Farid Boussaid'
date: 2023-04-01
venue: 'Pattern Reconition'
---
This paper presents a novel approach for cross-domain descriptor matching between 2D and 3D modalities. The 2D-3D matching is applied to localize 2D images in 3D point clouds. Direct cross-domain matching allows our technique to localize images in any type of 3D point cloud without any constraints on the nature or mechanism by which it is obtained. We propose a learning based framework, called Desc-Matcher, to directly match features between the two modalities. A dataset of 2D and 3D features with corresponding locations in images and point clouds is generated to train the Desc-Matcher. To estimate the pose of an image in any 3D cloud, keypoints and feature descriptors are extracted from the query image and the point cloud. The trained Desc-Matcher is then used to match the features from the image and the point cloud. A robust pose estimator is used to predict the location and orientation of the query image from the corresponding positions of the matched 2D and 3D features. We carried out an extensive evaluation of the proposed method for indoor and outdoor scenarios and with different types of point clouds to verify the feasibility of our approach. Experimental results show that the proposed approach can reliably estimate the 6-DOF poses of query cameras in any type of 3D point cloud with high precision. We achieved average median errors of 1.09cm/0.27deg and 19cm/0.39deg on the Stanford and Cambridge datasets, respectively.

[Paper](https://www.sciencedirect.com/science/article/pii/S0031320323003564)
