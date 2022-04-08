---
layout: project-page-new
title: "SLAM Pose-graph Robustification via Multi-scale Heat-Kernel Analysis"
authors:
  - name: Sayantan Datta
    sup: #
  - name: Siddharth Tourani
    sup: #
  - name: Avinash Sharma
    sup: #
  - name: K. Madhava Krishna
    sup: #
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: #
permalink: publications/2016/Datta_SLAM
abstract: "The Simultaneous Localization and Mapping problem (SLAM) in robotics is typically modeled as a dyadic graph of relative pose measurements taken by the robot. The graph nodes store the values representing the absolute pose of the robot at a given point of time. An edge connecting two nodes
represents robot movement and it stores the measurements taken by the robot sensor while moving between two nodes. The objective of the SLAM problem is to find the optimal global measurements best satisfying the noisy relative measurements [12]. This problem of optimal estimation on a graph given
relative measurements is a well-studied problem within the control community, for which several results and algorithms are known [3, 4]. SLAM is generally solved as a least squares problem. Robust kernels which are less sensitive to outliers are used to deal with noise and outlier measurements. However, robust kernels tend to be dependent on initialization and can fail as the number of outliers increase. Therefore, it’s important to identify and prune the outlier (noisy) measurements represented by incorrect loop closure edges for an accurate pose estimate. In this paper we propose a multi-scale Heat-Kernel analysis based loop closure edge pruning algorithm for the SLAM graph. We show that compared to other pruning algorithms, our algorithm has a substantially higher precision and recall when compared and is able to handle a large amount of outlier measurements. We have corroborated results on several publicly available datasets and several types of noise. Our algorithm is not restricted to SLAM graphs only, but has a much wider applicability to other types of geometric graphs."
paper: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7798703
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---