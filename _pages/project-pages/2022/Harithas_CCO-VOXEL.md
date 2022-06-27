---
layout: project-page-new
title: "CCO-VOXEL: Chance Constrained Optimization over Uncertain Voxel-Grid Representation for Safe Trajectory Planning"
authors:
  - name: Sudarshan S Harithas
    sup: 1
  - name: Rishabh Dev Yadav
    sup: 1
  - name: Deepak Singh
    sup: 1
  - name: Arun Kumar Singh
    sup: 2
  - name: K Madhava Krishna 
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
  - name: University of Tartu, Estonia
    link: #
    sup: 2
permalink: /publications/2022/Harithas_CCO-VOXEL/
abstract: "We present CCO-VOXEL: the very first chance-constrained optimization (CCO) algorithm that can compute trajectory plans with probabilistic safety guarantees in real-time directly on the voxel-grid representation of the world. CCO-VOXEL maps the distribution over the distance to the closest obstacle to a distribution over collision-constraint violation and computes an optimal trajectory that minimizes the violation probability. Importantly, unlike existing works, we never assume the nature of the sensor uncertainty or the probability distribution of the resulting collision-constraint violations. We leverage the notion of Hilbert Space embedding of distributions and Maximum Mean Discrepancy (MMD) to compute a tractable surrogate for the original chance-constrained optimization problem and employ a combination of A* based graph-search and Cross-Entropy Method for obtaining its minimum. We show tangible performance gain in terms of collision avoidance and trajectory smoothness as a consequence of our probabilistic formulation vis a vis state-of-the-art planning methods that do not account for such nonparametric noise. Finally, we also show how a combination of low-dimensional feature embedding and pre-caching of Kernel Matrices of MMD allows us to achieve real-time performance in simulations as well as in implementations on on-board commodity hardware that controls the quadrotor flight"
paper: https://arxiv.org/abs/2110.02904
code: https://github.com/sudarshan-s-harithas/CCO-VOXEL 
#supplement: https://iiitaphyd-my.sharepoint.com/personal/avneesh_mishra_research_iiit_ac_in/Documents/Forms/All.aspx?RootFolder=%2Fpersonal%2Favneesh%5Fmishra%5Fresearch%5Fiiit%5Fac%5Fin%2FDocuments%2FRRC%2FOpposing%20View%20Loop%20Closure%2FE2CNN%2FPresented%20Material%2FReF%20Paper&FolderCTID=0x012000A1AB309DA2EB7542856220193D0C0808
#video: https://robotics.iiit.ac.in/publications/2020/deep-mpc-for-visual-servoing/video.mp4
iframe: https://www.youtube.com/embed/qNAqAlb7m3E # https://www.youtube.com/embed/jhjskX4FQwA

---