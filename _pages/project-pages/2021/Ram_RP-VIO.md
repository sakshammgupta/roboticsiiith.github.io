---
layout: project-page-new
title: "RP-VIO: Robust Plane-based Visual-Inertial Odometry for Dynamic Environments"
authors:
  - name: Karnik Ram*
    sup: 1
  - name: Chaitanya Kharyal
    sup: 1
  - name: Sudarshan S. Harithas
    sup: 1
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: Robotics Research Center, KCIS, IIIT Hyderabad
    link: https://robotics.iiit.ac.in
    sup: 1
permalink: /publications/2021/Ram_RP-VIO/
abstract: "Modern visual-inertial navigation systems (VINS) are faced with a critical challenge in real-world deployment: they need to operate reliably and robustly in highly dynamic environments. Current best solutions merely filter dynamic objects as outliers based on the semantics of the object category. Such an approach does not scale as it requires semantic classifiers to encompass all possibly-moving object classes; this is hard to define, let alone deploy. On the other hand, many real-world environments exhibit strong structural regularities in the form of planes such as walls and ground surfaces, which are also crucially static. We present RP-VIO, a monocular visual-inertial odometry system that leverages the simple geometry of these planes for improved robustness and accuracy in challenging dynamic environments. Since existing datasets have a limited number of dynamic elements, we also present a highly-dynamic, photorealistic synthetic dataset for a more effective evaluation of the capabilities of modern VINS systems. We evaluate our approach on this dataset, and three diverse sequences from standard datasets including two real-world dynamic sequences and show a significant improvement in robustness and accuracy over a state-of-the-art monocular visual-inertial odometry system. We also show in simulation an improvement over a simple dynamic-features masking approach. Our code and dataset are publicly available."
paper: https://arxiv.org/pdf/2103.10400.pdf
iframe: https://www.youtube.com/embed/2GMoUJEDO0U

---