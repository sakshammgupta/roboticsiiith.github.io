---
layout: project-page-new
title: "Model Predictive Control for Autonomous Driving Based on Time Scaled Collision Cone"
authors:
  - name: Mithun Babu
    sup: 1
  - name: Yash Oza
    sup: 1
  - name: Arun Kumar Singh
    sup: 2
  - name: K. Madhava Krishna
    sup: 1
  - name: Shanti Medasani
    sup: 3
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
  - name: AUT, Tampere University of Technology, Finland
    link: http://www.tut.fi/en/research/research-fields/automation-and-hydraulic-engineering/index.htm
    sup: 2
  - name: Mathworks Inc.
    link: https://in.mathworks.com/
    sup: 3
permalink: /publications/2018/Babu_Model-Predictive-Control/
abstract: "In this paper, we present a Model Predictive Control (MPC) framework based on path velocity decomposition paradigm for autonomous driving. The optimization underlying the MPC has a two layer structure wherein first, an appropriate path is computed for the vehicle followed by the computation of optimal forward velocity along it. The very nature of the proposed path velocity decomposition allows for seamless compatibility between the two layers of the optimization. A key feature of the proposed work is that it offloads most of the responsibility of collision avoidance to velocity optimization layer for which computationally efficient formulations can be derived. In particular, we extend our previously developed concept of time scaled collision cone (TSCC) constraints and formulate the forward velocity optimization layer as a convex quadratic programming problem. We perform validation on autonomous driving scenarios wherein proposed MPC repeatedly solves both the optimization layers in receding horizon manner to compute lane change, overtaking and merging maneuvers among multiple dynamic obstacles."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/resources/Mithun_et_al_ecc18/ecc_2018.pdf
iframe: https://www.youtube.com/embed/8re0I9z0LEk

---