---
layout: project-page-new
title: "Overtaking Maneuvers in Simulated Highway Driving using Deep Reinforcement Learning"
authors:
  - name: Meha Kaushik
    sup: 1
  - name: Vignesh Prasad
    sup: 2
  - name: K. Madhava Krishna
    sup: 1
  - name: Balaraman Ravindran
    sup: 3
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
  - name: TCS Innovation Labs, Kolkata
    link: #
    sup: 2
  - name: Indian Institute of Technology, Madras
    link: #
    sup: 3
permalink: /publications/2018/Kaushik_Overtaking-Maneuvers/
abstract: "Most methods that attempt to tackle the problem of Autonomous Driving and overtaking usually try to either directly minimize an objective function or iteratively in a Reinforcement Learning like framework to generate motor actions given a set of inputs. We follow a similar trend but train the agent in a way similar to a curriculum learning approach where the agent is first given an easier problem to solve, followed by a harder problem. We use Deep Deterministic Policy Gradients to learn overtaking maneuvers for a car, in presence of multiple other cars, in a simulated highway scenario. The novelty of our approach lies in the training strategy used where we teach the agent to drive in a manner similar to the way humans learn to drive and the fact that our reward function uses only the raw sensor data at the current time step. This method, which resembles a curriculum learning approach is able to learn smooth maneuvers, largely collision free, wherein the agent overtakes all other cars, independent of the track and number of cars in the scene."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/resources/Meha_et_al_iv18/IV2018_0542_FI.pdf
video: https://robotics.iiit.ac.in/uploads/Main/Publications/resources/Meha_et_al_iv18/IV2018_0542_VD_fi.mp4
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---