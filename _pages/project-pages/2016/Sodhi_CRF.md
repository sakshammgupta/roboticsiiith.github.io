---
layout: project-page-new
title: "CRF based method for Curb Detection using semantic cues and stereo depth"
authors:
  - name: Danish Sodhi∗
    sup: #
  - name: Sarthak Upadhyay†
    sup: #
  - name: Dhaivat Bhatt‡
    sup: #
  - name: K Madhava Krishna
    sup: #
  - name: Shanti Swarup
    sup: #
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: #
  - name: Uurmi Systems
    link: #
    sup: #
permalink: publications/2016/Sodhi_CRF
abstract: "Curb detection is a critical component of driver assistance and autonomous driving systems. In this paper, we present a discriminative approach to the problem of curb detection
under diverse road conditions. We define curbs as the intersection of drivable and non-drivable area which are classified using dense Conditional random fields(CRF). In our method, we fuse output of a neural network used for pixelwise semantic segmentation with depth and color information from stereo cameras. CRF fuses the output of a deep model and height information available in stereo data and
provides improved segmentation. Further we introduce temporal smoothness using a weighted average of Segnet output and output from a probabilistic voxel grid as our unary potential. Finally, we show improvements over the current state of the art neural networks. Our proposed method shows accurate results over large range of variations in curb curvature and appearance, without the need of retraining the model for the specific dataset."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/Danish_etal_ICVGIP16.pdf
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---