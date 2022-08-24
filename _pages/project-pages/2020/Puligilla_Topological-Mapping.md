---
layout: project-page-new
title: "Topological Mapping for Manhattan-like Repetitive Environments"
authors:
  - name: Sai Shubodh Puligilla
    sup: 1
  - name: Satyajit Tourani*
    sup: 1
  - name: Tushar Vaidya*
    sup: 1
  - name: Udit Singh Parihar
    sup: 1
  - name: Ravi Kiran Sarvadevabhatla
    sup: 1
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
permalink: /publications/2020/Puligilla_Topological-Mapping/
abstract: "We showcase a topological mapping framework for a challenging indoor warehouse setting. At the most abstract level, the warehouse is represented as a Topological Graph where the nodes of the graph represent a particular warehouse topological construct (e.g. rackspace, corridor) and the edges denote the existence of a path between two neighbouring nodes or topologies. At the intermediate level, the map is represented as a Manhattan Graph where the nodes and edges are characterized by Manhattan properties and as a Pose Graph at the lower-most level of detail. The topological constructs are learned via a Deep Convolutional Network while the relational properties between topological instances are learnt via a Siamese-style Neural Network. In the paper, we show that maintaining abstractions such as Topological Graph and Manhattan Graph help in recovering an accurate Pose Graph starting from a highly erroneous and unoptimized Pose Graph. We show how this is achieved by embedding topological and Manhattan relations as well as Manhattan Graph aided loop closure relations as constraints in the backend Pose Graph optimization framework. The recovery of near ground-truth Pose Graph on real-world indoor warehouse scenes vindicate the efficacy of the proposed framework."
paper: https://arxiv.org/pdf/2002.06575
iframe: https://www.youtube.com/embed/QTnmc52DB5I

---