---
layout: project-page-new
title: "Fast Randomized Planner for SLAM Automation"
authors:
  - name: Amey Parulkar*
    sup: #
  - name: Piyush Shukla*
    sup: #
  - name: K Madhava Krishna+
    sup: #
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: #
permalink: publications/2012/Parulkar_Fast-Randomized-Planner
abstract: "In this paper, we automate the traditional problem of Simultaneous Localization and Mapping (SLAM) by interleaving planning for exploring unknown environments by a mobile robot. We denote such planned SLAM systems as SPLAM (Simultaneous Planning Localization and Mapping).
The main aim of SPLAM is to plan paths for the SLAM process such that the robot and map uncertainty upon execution of the path remains minimum and tractable. The planning is interleaved with SLAM and hence the terminology SPLAM. While typical SPLAM routines find paths when the robot traverses amidst known regions of the constructed map, herein we use the SPLAM formulation for an exploration like
situation. Exploration is carried out through a frontier based approach where we identify multiple frontiers in the known map. Using Randomized Planning techniques we calculate various possible trajectories to all the known frontiers. We introduce a novel strategy for selecting frontiers which mimics Fast SLAM, selects a trajectory for robot motion that will minimize the map and robot state covariance. By using a Fast SLAM like approach for selecting frontiers we are able to decouple the robot and landmark covariance resulting in a faster selection of next best location, while maintaining the same kind of robustness of an EKF based SPLAM framework. We then compare our results with Shortest Path Algorithm and EKF based Planning. We show significant reduction in covariance when compared with shortest frontier first approach, while the uncertainties are comparable to EKFSPLAM albeit at much faster planning times. "
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/Parulkar_etal_case2012.pdf
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---