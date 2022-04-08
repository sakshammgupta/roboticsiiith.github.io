---
layout: project-page-new
title: "Hierarchical Structured Learning for Indoor Autonomous Navigation of Quadcopter"
authors:
  - name: Vishakh Duggal
    sup: 1
  - name: Utsav Shah
    sup: 1
  - name: Kumar Bipin
    sup: 1
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
permalink: publications/2016/Duggal_Hierarchical-Structured-Learning
abstract: "Autonomous navigation of generic monocular quadcopter in the indoor environment requires sophisticated approaches for perception, planning and control. This paper presents a system which enables a miniature quadcopter with a frontal monocular camera to autonomously navigate and explore the unknown indoor environment. Initially, the system estimates dense depth map of the environment from a single video frame using our proposed novel supervised Hierarchical Structured Learning (HSL) technique, which yields both high accuracy levels and better generalization. The proposed HSL approach discretizes the overall depth range into multiple sets. It structures these sets hierarchically and recursively through partitioning the set of classes into two subsets with subsets representing apportioned depth range of the parent set, forming a binary tree. The binary classification method is applied to each internal node of binary tree separately using Support Vector Machine(SVM). Whereas, the depth estimation of each pixel of the image starts from the root node in top-down approach, classifying repetitively till it reaches any of the leaf node representing its estimated depth. The generated depth map is provided as an input to Convolutional Neural Network (CNN), which generates flight planning commands. Finally, trajectory planning and control module employs a convex programming technique to generate collision-free minimum time trajectory which follows these flight planning commands and produces appropriate control inputs for the quadcopter. The results convey unequivocally the advantages of depth perception by HSL, while repeatable flights of successful nature in typical indoor corridors confirm the efficacy of the pipeline."
paper: https://robotics.iiit.ac.in/people/utsav.shah/project_page/hsl/Vishakh.pdf
video: https://robotics.iiit.ac.in/people/utsav.shah/project_page/hsl/Vishakh.mp4
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---