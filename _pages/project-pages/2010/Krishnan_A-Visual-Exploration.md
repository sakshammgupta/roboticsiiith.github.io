---
layout: project-page-new
title: "A Visual Exploration Algorithm using Semantic Cues that Constructs Image based Hybrid Maps"
authors:
  - name: Aravindhan K Krishnan
    sup: #
  - name: K. Madhava Krishna
    sup: #
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: #
permalink: /publications/2010/Krishnan_A-Visual-Exploration/
abstract: "A vision based exploration algorithm that invokes semantic cues for constructing a hybrid map of images - a combination of semantic and topological maps is presented in this paper. At the top level the map is a graph of semantic constructs. Each node in the graph is a semantic construct
or label such as a room or a corridor, the edge represented by a transition region such as a doorway that links the two semantic constructs. Each semantic node embeds within it a topological graph that constitutes the map at the middle level. The topological graph is a set of nodes, each node representing an image of the higher semantic construct. At the low level the topological graph embeds metric values and relations, where each node embeds the pose of the robot from which the image
was taken and any two nodes in the graph are related by a transformation consisting of a rotation and translation. The exploration algorithm explores a semantic construct completely before moving or branching onto a new construct. Within each semantic construct it uses a local feature based exploration algorithm that uses a combination of local and global decisions to decide the next best place to move. During the process of exploring a semantic construct it identifies transition regions
that serve as gateways to move from that construct to another. The exploration is deemed complete when all transition regions are marked visited. Loop detection happens at transition regions and graph relaxation techniques are used to close loops when detected to obtain a consistent metric embedding of the robot poses. Semantic constructs are labeled using a visual bag of words(VBOW) representation with a probabilistic SVM classifier."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/aravindhan_etal_iros2010.pdf
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---