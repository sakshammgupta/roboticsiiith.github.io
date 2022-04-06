---
layout: project-page-new
title: "Constructing Category-Specific Models for Monocular Object-SLAM"
authors:
  - name: Parv Parkhiya
    sup: 1
  - name: Rishabh Khawad
    sup: 1
  - name: J. Krishna Murthy
    sup: 1
  - name: Brojeshwar Bhowmick
    sup: 2
  - name: K. Madhava Krishna
    sup: 1
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
  - name: Tata Consultancy Services, Kolkata, India
    link: http://www.tata.com/innovation/articlesinside/TCS-innovation-labs
    sup: 2
permalink: publications/2018/Parkhiya_Constructing-Category-Specific-Models
abstract: "We present a new paradigm for real-time object- oriented SLAM with a monocular camera. Contrary to previous approaches, that rely on object-level models, we construct category-level models from CAD collections which are now widely available. To alleviate the need for huge amounts of labeled data, we develop a rendering pipeline that enables synthesis of large datasets from a limited amount of manually labeled data. Using data thus synthesized, we learn category- level models for object deformations in 3D, as well as dis- criminative object features in 2D. These category models are instance-independent and aid in the design of object landmark observations that can be incorporated into a generic monocular SLAM framework. Where typical object-SLAM approaches usually solve only for object and camera poses, we also estimate object shape on-the-fly, allowing for a wide range of objects from the category to be present in the scene. Moreover, since our 2D object features are learned discriminatively, the proposed object-SLAM system succeeds in several scenarios where sparse feature-based monocular SLAM fails due to insufficient features or parallax. Also, the proposed category- models help in object instance retrieval, useful for Augmented Reality (AR) applications. We evaluate the proposed framework on multiple challenging real-world scenes and show — to the best of our knowledge — first results of an instance-independent monocular object-SLAM system and the benefits it enjoys over feature-based SLAM methods."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/resources/Parv_et_al_icra18/ICRA18_1571_FI.pdf
iframe: https://www.youtube.com/embed/30Isrpn10uE

---