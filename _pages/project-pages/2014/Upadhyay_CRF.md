---
layout: project-page-new
title: "CRF Based Frontier Detection using Monocular Camera"
authors:
  - name: Sarthak Upadhyay
    sup: #
  - name: Suryansh Kumar
    sup: #
  - name: K. Madhava Krishna
    sup: #
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: #
permalink: publications/2014/Upadhyay_CRF
abstract: "Frontier detection is a critical component in indoor mobile robot exploration, wherein the robot decides the next best location to move in order to continue with its mapping process. All frontier detection algorithms to the best of our knowledge require 3D locations of occupied regions as its input. In a monocular setting this entails a backend VSLAM algorithm that reconstructs the scene as the robot moves. Most monocular SLAM algorithms however provide sparse scene reconstruction from which frontiers cannot be reliably detected and estimated. In this effort we provide an alternate method of detecting frontiers during the course of robot motion that circumvents the requirement of dense mapping. Based on the observation that frontiers typically occur around vertical edges of walls, doors or tables we propose a novel linear chain CRF formulation that is able
to detect the presence or absence of such frontier regions around such vertical edges. We used cues like increase in number of ground plane pixels and change in the spreading of optical flow vector, around those vertical edges. We also demonstrate that this method gives us more relevant frontiers as compared to methods based on reconstructing the scene through state-of-the art such SLAM algorithms such as PTAM. Finally, we present results in indoor scenes wherein frontiers are reliably detected around wall edges leading to new corridors, door edges leading to new rooms or corridors
and table edges that opens up to a new space in rooms."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/Sarthak_etal_ICVGIP_14.pdf
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---