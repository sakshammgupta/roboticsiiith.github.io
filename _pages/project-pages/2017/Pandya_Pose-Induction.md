---
layout: project-page-new
title: "Pose Induction for Visual Servoing to a Novel Object Instance"
authors:
  - name: Harit Pandya*
    sup: 1
  - name: Gourav Kumar*
    sup: 1
  - name: Ayush Gaud*
    sup: 1
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
permalink: /publications/2017/Pandya_Pose-Induction/
abstract: "Present visual servoing approaches are instance specific i.e. they control camera motion between two views of the same object. We address the problem of visual servoing to a novel instance of an object category: given a desired view of any instance (source) of an object category, the robot is required to servo to the corresponding view of another instance (target) from the same object category. We formulate visual servoing across instances as iterative pose induction and pose alignment problem. Here, the desired camera pose of the target (instance on which servoing is done) is induced from a desired view of a source instance (any instance from the same category). Once the desired camera pose is transferred through pose induction,the pose alignment step is solved by estimating the current pose using the semantic reconstruction of target followed by a pose based visual servoing (PBVS) iteration. To tackle large variation in appearance across object instances in a category, we employ visual features that uniquely correspond to locations of object’s parts in images. These part-aware keypoints are learned from annotated images using a convolutional neural network (CNN). Advantages of using such part-aware semantics are two-fold. Firstly, it conceals the illumination and textural variations from the visual servoing algorithm. Secondly, semantic keypoints result in more accurate matching compared to local appearance based descriptors like SIFT. We validate the efficacy of our approach through experiments in simulation as well as on a quadcopter. Our approach results in acceptable desired camera pose and smooth velocity profile. We also show results for large camera transformations with no overlap between current and desired pose for 3D objects, which is desirable in servoing context."
paper: https://robotics.iiit.ac.in/people/gourav.kumar/pose_induction_web/pose_induction.pdf
video: https://robotics.iiit.ac.in/people/gourav.kumar/pose_induction_web/pose_induction.mp4
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---