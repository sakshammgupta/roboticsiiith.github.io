---
layout: project-page-new
title: "Incorporating Prediction in Control Barrier Function Based Distributive Multi-Robot Collision Avoidance"
authors:
  - name: Pravin Mali
    sup: 1
  - name: K. Harikumar
    sup: 1
  - name: Arun Kumar Singh
    sup: 2
  - name: K. Madhava Krishna
    sup: 1
  - name: P.B. Sujit
    sup: 3
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
  - name: BGU, Bio Medical Robotics Lab, Israel
    link: #
    sup: 2
  - name: Indian Institute of Science Education and Research Bhopal
    link: #
    sup: 3
permalink: publications/2021/Mali_Incorporating-Prediction
abstract: "Control barrier function (CBF) constraints provide a rigorous characterization of the space of control inputs that ensure the satisfaction of state constraints, such as collision
avoidance, at all time instants. However, CBFs are highly nonlinear and non-convex and thus, when incorporated within an optimization-based algorithm such as Model Predictive Control (MPC), leads to a computationally challenging problem. Existing works by-pass the computational intractability by
collapsing the horizon of the MPC to a single step, although this comes at the cost of severe degradation of performance. In this paper, we present two contributions to ensure the real-time performance of CBFs based MPC over long horizons in the context of multi-robot collision avoidance. First, we propose a customized Project Gradient Descent Method that incurs minimal computational overhead over existing one-step approaches but leads to a substantial improvement in trajectory
smoothness, time to reach the goal, etc. Our second contribution lies in applying the proposed MPC to both quadrotors and fixed-wing aerial aircrafts (FWA). In particular, we show that the formulation for the quadrotors can be readily extended to the latter by deriving additional CBFs for the curvature and forward velocity constraints. We validate our algorithm with an extensive simulation of up to 10 robots in challenging benchmark scenarios."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/Mali_etal_ECC_2021.pdf
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---