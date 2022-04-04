---
layout: project-page-new
title: "Talk to the Vehicle: Language Conditioned Autonomous Navigation of Self Driving Cars"
authors:
  - name: Sriram N. N.
    sup: 1
  - name: Tirth Maniar
    sup: 1
  - name: Jayaganesh Kalyanasundaram
    sup: 1
  - name: Vineet Gandhi
    sup: 1
  - name: Brojeshwar Bhowmick
    sup: 2
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
  - name: TCS Research and Innovation Labs, Kolkata, India
    link: #
    sup: 2
permalink: publications/2019/N_Talk-to-the-Vehicle
abstract: "We propose a novel pipeline that blends encodings from natural language and 3D semantic maps obtained from computer vision data to generate local trajectories that are executed by a low-level controller. The pipeline precludes the need for a prior registered map through a local waypoint generator neural network. The waypoint generator network (WGN) maps semantics and natural language encodings (NLE) to local waypoints. A local planner then generates a trajectory from the ego location of the vehicle (an outdoor car in this case) to these locally generated waypoints while a low-level controller executes these plans faithfully. The efficacy of the pipeline is verified in the CARLA simulator environment as well as on local semantic maps built from real-world KITTI dataset. In both these environments (simulated and real-world) we show the ability of the WGN to generate waypoints accurately by mapping NLE of varying sequence lengths and levels of complexity. We compare with baseline approaches and show significant performance gain over them. And finally, we show real implementations on our electric car verifying that the pipeline lends itself to practical and tangible realizations in uncontrolled outdoor settings. In loop execution of the proposed pipeline that involves repetitive invocations of the network is critical for any such language-based navigation framework. This effort successfully accomplishes this thereby bypassing the need for prior metric maps or strategies for metric level localization during traversal."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/sriram_et_al_iros19/talk_to_the_vehicle.pdf
video: https://robotics.iiit.ac.in/uploads/Main/Publications/sriram_et_al_iros19/video.mp4
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---