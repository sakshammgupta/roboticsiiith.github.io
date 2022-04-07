---
layout: project-page-new
title: "Time Scaled Collision Cone based Trajectory Optimization Approach for Reactive Planning in Dynamic Environments"
authors:
  - name: Bharath Gopalakrishnan
    sup: 1
  - name: Arun Kumar Singh
    sup: 1
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
permalink: publications/2014/Gopalakrishnan_Time-Scaled-Collision
abstract: "The current paper proposes a trajectory optimization approach for navigating a non-holonomic wheeled mobile robot in dynamic environments. The dynamic obstacle’s motion is not known and hence is represented by a band of predicted trajectories . The trajectory optimization can account for large number of predicted obstacle trajectories and seeks to avoid each predicted trajectory of every obstacle in the sensing range of the robot. The two primary contributions of
the proposed trajectory optimization are (1): A computationally efficient method for computing the intersection space of collision avoidance constraints of large number of predicted obstacle
trajectories. (2): A optimization framework to connect the current state to the solution space in time optimal fashion. The intersection/solution space computation is build on our earlier proposed concept of time scaled collision cone, which can be solved in closed form to obtain a set of formulae. These formulae describe how much and in what manner the temporal specification of a trajectory needs to be changed to avoid a given set of dynamic obstacles. This allows us to quickly
evaluate solution space of time scaled collision cone over various candidate trajectories, thus reducing the problem of computing the intersection space to that of generating multiple homotopic
trajectories. The optimization framework used to connect the current state to the solution space in time optimal fashion is based on the concept of non-linear time scaling, which induces a difference of convex form structure. Thus, on the theoretical side, we show that the various components of the proposed framework are computationally simple and involves solving sets of linear equations and using state of the art convex programming techniques. On the practical side we show that
the proposed planner performs better than sampling based planners which treat dynamic obstacles as static over a short duration of time"
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/Bharath_etal_IROS_14.pdf
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---
