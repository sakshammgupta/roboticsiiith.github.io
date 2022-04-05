---
layout: project-page-new
title: "SROM: Simple Real-time Odometry and Mapping using LiDAR data for Autonomous Vehicles"
authors:
  - name: Nivedita Rufus
    sup: 1
  - name: Unni Krishnan R. Nair
    sup: 1
  - name: A.V.S Sai Bhargav Kumar
    sup: 1
  - name: Vashist Madiraju
    sup: 1
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
permalink: publications/2020/Rufus_SROM
abstract: "In this paper, we present SROM, a novel realtime Simultaneous Localization and Mapping (SLAM) system for autonomous vehicles. The keynote of the paper showcases SROM’s ability to maintain localization at low sampling rates or at high linear or angular velocities where most popular LiDAR based localization approaches get degraded fast. We also demonstrate SROM to be computationally efficient and capable of handling high-speed maneuvers. It also achieves low drifts without the need for any other sensors like IMU and/or GPS. Our method has a two-layer structure wherein first, an approximate estimate of the rotation angle and translation parameters are calculated using a Phase Only Correlation (POC) method. Next, we use this estimate as an initialization for a point-toplane ICP algorithm to obtain fine matching and registration. Another key feature of the proposed algorithm is the removal of dynamic objects before matching the scans. This improves the performance of our system as the dynamic objects can corrupt the matching scheme and derail localization. Our SLAM system can build reliable maps at the same time generating high-quality odometry. We exhaustively evaluated the proposed method in many challenging highways/country/urban sequences from the KITTI dataset and the results demonstrate better accuracy in comparisons to other state-of-the-art methods with reduced computational expense aiding in real-time realizations. We have also integrated our SROM system with our in-house autonomous vehicle and compared it with the state-of-the-art methods like LOAM and LeGO-LOAM."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/nivedita_etal_iv20.pdf
iframe: https://www.youtube.com/embed/hH9YdSmOOyE

---