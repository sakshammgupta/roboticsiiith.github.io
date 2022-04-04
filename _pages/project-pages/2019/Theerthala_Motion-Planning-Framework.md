---
layout: project-page-new
title: "Motion Planning Framework for Autonomous Vehicles: A Time Scaled Collision Cone Interleaved Model Predictive Control Approach"
authors:
  - name: Raghu Ram Theerthala
    sup: 1
  - name: A. V. S. Sai Bhargav Kumar
    sup: 1
  - name: Mithun Babu
    sup: 1
  - name: Phaniteja S.
    sup: 1
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
permalink: publications/2019/Theerthala_Motion-Planning-Framework
abstract: "This paper proposes a hierarchical model to offload the local planner onto a Velocity optimization scheme with Time scaled collision cone(TSCC) constraint. This trajectory otpimization is done by the first layer and the velocities are passed to the velocity optimization scheme. Now the appropriate scale is calculated to modify the velocity profile which provides a significant improvement in the computational efficiency. The non-myopic hierarchical planner interleaves between the TSCC layer and MPC layer maintaining the continuity in velocties. This framework is tested to handle unpredictable scenarios like jaywalking pedestrians, Multi-obstacle avoidance and lane changing scenarios. The runtime advantage obtained by this framework is shown in this paper by comparing it to the joint optimization framework. One more contribution includes simplistic implementation of road boundaries by approximating the road boundaries with cubic splines and formulating the constraints with the tangents at each location of the ego-vehicle. Thus this framework works has repeatability and fidelity even while abiding to the complex constraints as well"
paper: https://iiitaphyd-my.sharepoint.com/:b:/g/personal/robotics_iiit_ac_in/EQxtyXHxhuNFtA7Ri1dtqc8BDJvXJR2MH2lb6EMpCiQLBA?download=1
video: https://iiitaphyd-my.sharepoint.com/:v:/g/personal/robotics_iiit_ac_in/EUNVkV3Tk7tBt4JO2YusSWgBKtgTy-PKIY9nSbUtoeImGA?download=1
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---
