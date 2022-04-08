---
layout: project-page-new
title: "DeepFly: Towards Complete Autonomous Navigation of MAVs with Monocular Camera"
authors:
  - name: Utsav Shah
    sup: 1
  - name: Rishabh Khawad
    sup: 1
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
permalink: publications/2016/Shah_DeepFly
abstract: "Recently, the interest in Micro Aerial Vehicles (MAVs) and their autonomous flights has increased tremendously and significant advances have been made. The monocular camera has turned out to be most popular sensing modality for MAVs as it is light-weight, does not consume more power, and encodes rich information about the environment around. In this paper, we present DeepFly, our framework for autonomous navigation of a quadcopter equipped with monocular camera. The navigable space detection and waypoint selection are fundamental components of autonomous navigation system. They have broader meaning than just detecting and avoiding immediate obstacles. Finding the navigable space emphasizes equally on avoiding obstacles and detecting ideal regions to move next to. The ideal region can be defined by two properties: 1) All the points in the region have approximately same high depth value and 2) The area covered by the points of the region in the disparity map is considerably large. The waypoints selected from these navigable spaces assure collision-free path which is safer than path obtained from other waypoint selection methods which do not consider neighboring information. In our approach, we obtain a dense disparity map by performing a translation maneuver. This disparity map is input to a deep neural network which predicts bounding boxes for multiple navigable regions. Our deep convolutional neural network with shortcut connections regresses variable number of outputs without any complex architectural add on. Our autonomous navigation approach has been successfully tested in both indoors and outdoors environment and in range of lighting conditions."
paper: https://robotics.iiit.ac.in/people/utsav.shah/project_page/deepfly/deepfly.pdf
video: https://robotics.iiit.ac.in/people/utsav.shah/project_page/deepfly/deepfly.mp4
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---