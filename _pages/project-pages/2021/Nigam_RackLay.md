---
layout: project-page-new
title: "RackLay: Monocular Multi-Layered Layout Estimation for Warehouses with Sim2Real Transfer"
authors:
  - name: Meher Shashwat Nigam*
    sup: 1
  - name: Avinash Prabhu*
    sup: 1
  - name: Anurag Sahu*
    sup: 1
  - name: Tanvi Karandikar
    sup: 1
  - name: Puru Gupta
    sup: 1
  - name: N. Sai Shankar
    sup: 1
  - name: Ravi Kiran Sarvadevabhatla
    sup: 1
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
permalink: /publications/2021/Nigam_RackLay
abstract: "Given a monocular color image of a warehouse rack, we aim to predict the bird's-eye view layout for each shelf in the rack, which we term as 'multi-layer' layout prediction. To this end, we present RackLay, a deep neural network for real-time shelf layout estimation from a single image. Unlike previous layout estimation methods which provide a single layout for the dominant ground plane alone, RackLay estimates the top-view <u>and</u> front-view layout for each shelf in the considered rack populated with objects. RackLay's architecture and its variants are versatile and estimate accurate layouts for diverse scenes characterized by varying number of visible shelves in an image, large range in shelf occupancy factor and varied background clutter. Given the extreme paucity of datasets in this space and the difficulty involved in acquiring real data from warehouses, we additionally release a flexible synthetic dataset generation pipeline WareSynth which allows users to control the generation process and tailor the dataset according to the contingent application. The ablations across architectural variants and comparison with strong prior baselines vindicate the efficacy of RackLay as an apt architecture for the novel problem of multi-layered layout estimation. We also show that fusing the top-view and front-view enables 3D reasoning applications such as metric free space estimation for the considered rack."
paper: https://dl.acm.org/doi/10.1145/3490035.3490263
code: https://github.com/Avinash2468/RackLay
supplement: # https://robotics.iiit.ac.in/publications/2020/deep-mpc-for-visual-servoing/supplementary.pdf
# video: https://youtu.be/9m5brJTAz50
iframe: https://www.youtube.com/embed/9m5brJTAz50 # https://www.youtube.com/embed/jhjskX4FQwA
project_page: https://avinash2468.github.io/RackLay/
---

