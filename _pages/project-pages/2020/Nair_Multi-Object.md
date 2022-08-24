---
layout: project-page-new
title: "Multi-Object Monocular SLAM for Dynamic Environments"
authors:
  - name: Gokul B Nair
    sup: 1
  - name: Swapnil Daga
    sup: 1
  - name: Rahul Sajnani
    sup: 1
  - name: Anirudha Ramesh
    sup: 1
  - name: Junaid Ahmed Ansari
    sup: 2
  - name: J. Krishna Murthy
    sup: 3
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
  - name: TCS Research and Innovation Labs, Kolkata, India
    link: #
    sup: 2
  - name: Mila - Quebec AI Institute, Montreal, Canada
    link: #
    sup: 3
permalink: /publications/2020/Nair_Multi-Object/
abstract: "In this paper, we tackle the problem of multibody SLAM from a monocular camera. The term multibody, implies that we track the motion of the camera, as well as that of other dynamic participants in the scene. The quintessential challenge in dynamic scenes is unobservability: it is not possible to unambiguously triangulate a moving object from a moving monocular camera. Existing approaches solve restricted variants of the problem, but the solutions suffer relative scale ambiguity (i.e., a family of infinitely many solutions exist for each pair of motions in the scene). We solve this rather intractable problem by leveraging single-view metrology, advances in deep learning, and category-level shape estimation. We propose a multi pose-graph optimization formulation, to resolve the relative and absolute scale factor ambiguities involved. This optimization helps us reduce the average error in trajectories of multiple bodies over real-world datasets, such as KITTI. To the best of our knowledge, our method is the first practical monocular multi-body SLAM system to perform dynamic multi-object and ego localization in a unified framework in metric scale."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/gokul_etal_iv20.pdf
iframe: https://www.youtube.com/embed/fMGj0U9QuBw

---