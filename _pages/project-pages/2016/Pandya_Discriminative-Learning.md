---
layout: project-page-new
title: "Discriminative Learning based Visual Servoing across Object Instances"
authors:
  - name: Harit Pandya
    sup: #
  - name: K. Madhava Krishna
    sup: #
  - name: C.V. Jawahar
    sup: #
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
permalink: /publications/2016/Pandya_Discriminative-Learning/
abstract: "Classical visual servoing approaches use visual features based on geometry of the object such as points, lines, region, etc. to attain the desired camera pose. However, geometrical features are not suited for visual servoing across different object instances due to large variations in appearance and shape. In this paper, we present a new framework for visual servoing across object instances. Our approach is based on a discriminative learning framework where the desired pose
is estimated using previously seen examples. Specifically, we learn a binary classifier that separates the desired pose from all other poses for that object category. The classification error
is then used to control the end-effector so that the desired pose is attained. We present controllers for linear, kernel and exemplar Support Vector Machine (SVM) and empirically discuss their performance in the visual servoing context. To address large intra-category variation in appearance, we propose a modified version of Histogram of Oriented Gradients (HOG) features
for visual servoing. We show effective servoing across diverse instances over 3 object categories with zero terminal velocity and acceptable camera pose error at termination."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/Harit_etal_ICRA_16.pdf
video: https://robotics.iiit.ac.in/videos/publications/Harit_etal_ICRA16.mp4
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---