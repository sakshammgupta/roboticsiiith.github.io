---
layout: project-page-new
title: "On Measurement Models for Line Segments and Point Based SLAM"
authors:
  - name: Satish Pedduri
    sup: #
  - name: Gururaj Kosuru
    sup: #
  - name: K Madhava Krishna
    sup: #
  - name: Amit K Pandey∗
    sup: #
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: #
permalink: publications/2009/Pedduri_On-Measurement-Models
abstract: "We present efficient measurement models for localization in a feature based EKF SLAM framework. Both points and segments form the features, points include corners formed by intersection of wall like segments. The point features are described by its coordinates, while the segment
feature is represented by the angle made by the normal to the segment from the global origin with the abscissa called the normal angle or N-angle for short. The measurement equation involves measuring the distance and bearing to the point feature and only bearing to the line feature. The
distance measurement to the segment is intentionally kept out of the measurement equation due to its inefficacy in correcting the robot and landmarks state. This arises due to very large differences in the predicted and observed distances even for modest measurement errors when the robot is not very near the segment. Hence for this reason the segment feature is represented only by its N-angle  devoid of distance since such a representation results in better state correction. The number of computations resulting from the covariance matrix updates is also less than a representation that includes both N-distance and N-angle."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/2009_5.pdf
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---