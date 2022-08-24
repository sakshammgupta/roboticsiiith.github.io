---
layout: project-page-new
title: "Monocular Reconstruction of Vehicles: Combining SLAM with Shape Priors"
authors:
  - name: Falak Chhaya
    sup: 1
  - name: Dinesh Reddy
    sup: 1
  - name: Sarthak Upadhyay
    sup: 1
  - name: Visesh Chari
    sup: 1
  - name: M. Zeeshan Zia
    sup: 2
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
  - name: Retrocausal, Inc
    link: #
    sup: 2
permalink: /publications/2016/Chhaya_Monocular-Reconstruction/
abstract: "Reasoning about objects in images and videos using 3D representations is re-emerging as a popular paradigm in computer vision. Specifically, in the context of scene understanding for roads, 3D vehicle detection and tracking from monocular videos still needs a lot of attention to enable practical applications. Current approaches leverage two kinds of information to deal with the vehicle detection and tracking problem: (1) 3D representations (eg. wireframe models or voxel based or CAD models) for diverse vehicle skeletal structures learnt from data, and (2) classifiers trained to detect vehicles or vehicle parts in single images built on top of a basic feature extraction step.
In this paper, we propose to extend current approaches in two ways. First, we extend detection to a multiple view setting. We show that leveraging information given by feature or part detectors in multiple images can lead to more accurate detection results than single image detection. Secondly, we show that given multiple images of a vehicle, we can also leverage 3D information from the scene generated using a unique structure from motion algorithm. This helps us localize the vehicle in 3D,
and constrain the parameters of optimization for fitting the 3D model to image data. We show results on the KITTI dataset, and demonstrate superior results compared with recent state-of-theart methods, with upto 14.64 % improvement in localization error."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/Falak_etal_ICRA16.pdf
video: https://robotics.iiit.ac.in/videos/publications/Falak_etal_ICRA16.mp4
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---