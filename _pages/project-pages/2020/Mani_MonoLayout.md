---
layout: project-page-new
title: "MonoLayout: Amodal Scene Layout from a single image"
authors:
  - name: Kaustubh Mani
    sup: 1
  - name: Swapnil Daga
    sup: 1
  - name: Shubhika Garg
    sup: 3
  - name: N. Sai Shankar
    sup: 1
  - name: J. Krishna Murthy
    sup: 1
  - name: K.Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
  - name: IIT Kharagpur, India
    link: #
    sup: 2
  - name: Mila - Quebec AI Institute, Montreal
    link: #
    sup: 3
permalink: publications/2020/Mani_MonoLayout
abstract: "In this paper, we address the novel, highly challenging problem of estimating the layout of a complex urban driving scenario. Given a single color image captured from a driving platform, we aim to predict the bird’s-eye view layout of the road and other traffic participants. The estimated layout should reason beyond what is visible in the image, and compensate for the loss of 3D information due to projection. We dub this problem amodal scene layout estimation, which involves “hallucinating” scene layout for even parts of the world that are occluded in the image. To this end, we present MonoLayout, a deep neural network for real-time amodal scene layout estimation from a single image. We represent scene layout as a multi-channel semantic occupancy grid, and leverage adversarial feature learning to hallucinate plausible completions for occluded image parts. Due to the lack of fair baseline methods, we extend several state-of-the-art approaches for road-layout estimation and vehicle occupancy estimation in bird’s-eye view to the amodal setup for rigorous evaluation. By leveraging temporal sensor fusion to generate training labels, we significantly outperform current art over a number of datasets. On the KITTI and Argoverse datasets, we outperform all baselines by a significant margin. We also make all our annotations, and code publicly available"
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/kaustubh_etal_wacv20.pdf
iframe: https://www.youtube.com/embed/uLQMSNJSPZs

---