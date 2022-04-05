---
layout: project-page-new
title: "Reactive Navigation under Uncertainty through Hilbert Space Embedding of Probabilistic Velocity Obstacles"
authors:
  - name: SriSai Naga Jyotish Poonganam*
    sup: 1
  - name: Bharath Gopalakrishnan*
    sup: 1
  - name: Venkata Seetharama Sai Bhargav Kumar Avula
    sup: 1
  - name: Arun Kumar Singh
    sup: 2
  - name: K. Madhava Krishna
    sup: 1
  - name: Dinesh Manocha
    sup: 3
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in/
    sup: 1
  - name: University of Tartu
    link: https://www.ut.ee/en
    sup: 2
  - name: University of Maryland
    link: https://www.umd.edu/
    sup: 3
permalink: publications/2020/Poonganam_Reactive-Navigation
abstract: "The probabilistic velocity obstacle (PVO) extends the concept of velocity obstacle (VO) to work in uncertain dynamic environments. In this paper, we show how a robust model predictive control (MPC) with PVO constraints under non-parametric uncertainty can be made computationally tractable. At the core of our formulation is a novel yet simple interpretation of our robust MPC as a problem of matching the distribution of PVO with a certain desired distribution. To this end, we propose two methods. Our first baseline method is based on approximating the distribution of PVO with a Gaussian Mixture Model (GMM) and subsequently performing distribution matching using Kullback Leibler (KL) divergence metric. Our second formulation is based on the possibility of representing arbitrary distributions as functions in Reproducing Kernel Hilbert Space (RKHS). We use this foundation to interpret our robust MPC as a problem of minimizing the distance between the desired distribution and the distribution of the PVO in the RKHS. Both the RKHS and GMM based formulation can work with any uncertainty distribution and thus allowing us to relax the prevalent Gaussian assumption in the existing works. We validate our formulation by taking an example of 2D navigation of quadrotors with a realistic noise model for perception and ego-motion uncertainty. In particular, we present a systematic comparison between the GMM and the RKHS approach and show that while both approaches can produce safe trajectories, the former is highly conservative and leads to poor tracking and control costs. Furthermore, RKHS based approach gives better computational times that are up to one order of magnitude lesser than the computation time of the GMM based approach."
paper: https://arxiv.org/pdf/2001.09007.pdf
iframe: https://www.youtube.com/embed/jHz7qyB8nyU

---