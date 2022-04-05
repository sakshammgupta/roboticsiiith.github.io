---
layout: project-page-new
title: "LiDAR Guided Small Obstacle Segmentation"
authors:
  - name: Aasheesh Singh
    sup: 1
  - name: Aditya Kamireddypalli
    sup: 1
  - name: Vineet Gandhi
    sup: 1
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
permalink: publications/2020/Singh_LiDAR
abstract: "Detecting small obstacles on the road is critical for autonomous driving. In this paper, we present a method to reliably detect such obstacles through a multi-modal framework of sparse LiDAR(VLP-16) and Monocular vision. LiDAR is employed to provide additional context in the form of confidence maps to monocular segmentation networks. We show significant performance gains when the context is fed as an additional input to monocular semantic segmentation frameworks. We further present a new semantic segmentation dataset to the community, comprising of over 3000 image frames with corresponding LiDAR observations. The images come with pixel-wise annotations of three classes off-road, road, and small obstacle. We stress that precise calibration between LiDAR and camera is crucial for this task and thus propose a novel Hausdorff distance based calibration refinement method over extrinsic parameters. As a first benchmark over this dataset, we report our results with 73 % instance detection up to a distance of 50 meters on challenging scenarios. Qualitatively by showcasing accurate segmentation of obstacles less than 15 cms at 50m depth and quantitatively through favourable comparisons vis a vis prior art, we vindicate the method’s efficacy."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/aasheesh_etal_iros20.pdf
iframe: https://www.youtube.com/embed/PZ_lpwmFUSA

---