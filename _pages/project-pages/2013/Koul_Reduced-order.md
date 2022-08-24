---
layout: project-page-new
title: "Reduced-order Forward Dynamics of Multi-Closed-Loop Systems"
authors:
  - name: Majid Koul
    sup: #
  - name: Suril V Shah
    sup: #
  - name: S K Saha∗
    sup: #
  - name: M Manivannan
    sup: #
affiliations:
  - name: IIIT Hyderabad, India
    link: #
    sup: #
permalink: /publications/2013/Koul_Reduced-order/
abstract: "In this work, a reduced-order forward dynamics of multi-closed-loop systems is proposed by exploiting the associated inherent kinematic constraints at acceleration level. First, a closed-loop system is divided into an equivalent open architecture consisting of several serial and tree-type subsystems by introducing cuts at appropriate joints. The resulting cut joints are replaced by appropriate constraint forces also referred to as Lagrange multipliers. Next, for each subsystem, the governing equations of motion are derived in terms of the Lagrange multipliers which are based on the Newton-Euler formulation coupled with the concept of Decoupled Natural Orthogonal Complement (DeNOC) matrices, introduced elsewhere. In the proposed forward dynamics formulation, Lagrange multipliers are calculated sequentially at subsystem level and later treated as external forces to the resulting serial or tree-type systems of the original closed-loop system, for the recursive computation of joint accelerations. Note that such subsystem-level treatment allows one to use already existing algorithms for serial and tree-type systems. Hence, one can perform the dynamic analyses relatively quickly without re-writing the complete model of the closed-loop system at hand. The proposed methodology is in contrast to the conventional approaches, where the Lagrange 
multipliers are calculated together at system level or simultaneously along with the joint accelerations, both of which incur higher order computational complexities and thereby more number of arithmetic operations. Due to the smaller size of matrices involved in evaluating Lagrange multipliers in the proposed methodology, and the recursive computation of the joint accelerations, the overall numerical performances like computational efficiency, etc., are likely to improve. The proposed reduced-order forward dynamics formulation is illustrated with two multi-closed-loop systems, namely, a 7-bar carpet scrapping mechanism and a 3-RRR parallel manipulator."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/Shah_etal_JMSD_13.pdf
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---