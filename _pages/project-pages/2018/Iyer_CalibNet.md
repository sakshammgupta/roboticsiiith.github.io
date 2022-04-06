---
layout: project-page-new
title: "CalibNet: Geometrically Supervised Extrinsic Calibration using 3D Spatial Transformer Networks"
authors:
  - name: Ganesh Iyer
    sup: 1
  - name: R. Karnik Ram
    sup: 1
  - name: J. Krishna Murthy
    sup: 2
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
  - name: Mila, Universite de Montreal  
    link: https://mila.quebec/
    sup: 2
permalink: publications/2018/Iyer_CalibNet
abstract: "3D LiDARs and 2D cameras are increasingly being used alongside each other in sensor rigs for perception tasks. Before these sensors can be used to gather meaningful data, however, their extrinsics (and intrinsics) need to be accurately calibrated, as the performance of the sensor rig is extremely sensitive to these calibration parameters. A vast majority of existing calibration techniques require significant amounts of data and/or calibration targets and human effort, severely impacting their applicability in large-scale production systems. We address this gap with CalibNet: a geometrically supervised deep network capable of automatically estimating the 6-DoF rigid body transformation between a 3D LiDAR and a 2D camera in real-time. CalibNet alleviates the need for calibration targets, thereby resulting in significant savings in calibration efforts. During training, the network only takes as input a LiDAR point cloud, the corresponding monocular image, and the camera calibration matrix K. At train time, we do not impose direct supervision (i.e., we do not directly regress to the calibration parameters, for example). Instead, we train the network to predict calibration parameters that maximize the geometric and photometric consistency of the input images and point clouds. CalibNet learns to iteratively solve the underlying geometric problem and accurately predicts extrinsic calibration parameters for a wide range of mis-calibrations, without requiring retraining or domain adaptation"
paper: https://arxiv.org/pdf/1803.08181.pdf
iframe: https://www.youtube.com/embed/WyW9T2dSbec

---