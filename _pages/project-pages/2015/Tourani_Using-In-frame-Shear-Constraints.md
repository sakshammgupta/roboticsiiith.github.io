---
layout: project-page-new
title: "Using In-frame Shear Constraints for Monocular Motion Segmentation of Rigid Bodies"
authors:
  - name: Siddharth Tourani
    sup: #
  - name: K Madhava Krishna
    sup: #
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: #
permalink: publications/2015/Tourani_Using-In-frame-Shear-Constraints
abstract: "It is a well known result in the vision literature that the motion of independently moving objects viewed by an affine camera lie on affine subspaces of dimension four or less. As a result a large number of the recently proposed motion segmentation algorithms model the problem as one of clustering the trajectory data to its corresponding affine subspace. While these algorithms are elegant in formulation and achieve near perfect results on benchmark datasets, they fail
to address certain very key real-world challenges, including perspective effects and motion degeneracies. Within a robotics and autonomous vehicle setting, the relative configuration of the robot and moving object will frequently be degenerate leading to a failure of subspace clustering algorithms. On the other hand, while gestalt-inspired motion similarity algorithms have been used for motion segmentation, in the moving camera case, they tend to oversegment or under-segment the scene based on their parameter values. In this paper we present a principled approach that incorporates the strengths of both approaches into a cohesive motion segmentation algorithm capable of dealing with the degenerate cases, where camera motion follows that of the moving object. We first generate a set of prospective motion models for the various moving and stationary objects in the video sequence by a RANSAC-like procedure. Then, we incorporate affine and long-term
gestalt-inspired motion similarity constraints, into a multi-label Markov Random Field (MRF). Its inference leads to an over-segmentation, where each label belongs to a particular moving object or the background. This is followed by a model selection step where we merge clusters based on a novel motion coherence constraint, we call in-frame shear, that tracks the in-frame change in orientation and distance between the clusters, leading to the final segmentation. This oversegmentation is deliberate and necessary, allowing us to assess the relative motion between the motion models which we believe to be essential in dealing with degenerate motion scenarios.We present results on the Hopkins-155 benchmark motion segmentation dataset (Tron and Vidal 2007), as well as several on-road scenes where camera and object motion are near identical. We show that our algorithm is competitive with the state-of-the-art algorithms on Tron and Vidal (2007) and exceeds them substantially on the more realistic on-road sequences"
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/SKT_etal_JIRS_15.pdf
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---