---
layout: project-page-new
title: "3D Region Proposals For Selective Object Search"
authors:
  - name: Sheetal Reddy
    sup: 1
  - name: Vineet Gandhi
    sup: 1
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
permalink: /publications/2017/Reddy_3D-Region/
abstract: "The advent of indoor personal mobile robots has clearly demonstrated their utility in assisting humans at various places such as workshops, offices, homes, etc. One of the most important cases in such autonomous scenarios is where the robot has to search for certain objects in large rooms. Exploring the whole room would prove to be extremely expensive in terms of both computing power and time. To address this issue,we demonstrate a fast algorithm to reduce the search space by identifying possible object locations as two classes, namely - Support Structures and Clutter. Support Structures are plausible object containers in a scene such as tables, chairs, sofas, etc. Clutter refers to places where there seem to be several objects but cannot be clearly distinguished. It can also be identified as unorganized regions which can be of interest for tasks such as robot grasping, fetching and placing objects. The primary contribution of this paper is to quickly identify potential object locations using a Support Vector Machine(SVM) learnt over the features extracted from the depth map and the RGB image of the scene, which further culminates into a densely connected Conditional Random Field(CRF) formulated over the image of the scene. The inference over the CRF leads to assignment of the labels - support structure, clutter, others to each pixel.There have been reliable outcomes even during challenging scenarios such as the support structures being far from the robot. The experiments demonstrate the efficacy and speed of the algorithm irrespective of alterations to camera angles, modifications to appearance change, lighting and distance from locations etc."
paper: https://robotics.iiit.ac.in/people/sheetal.reddy/RPSelectiveObjectSearch/visapp.pdf
video: https://robotics.iiit.ac.in/people/sheetal.reddy/RPSelectiveObjectSearch/visapp.mp4
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---