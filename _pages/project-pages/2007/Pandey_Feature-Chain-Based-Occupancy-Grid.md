---
layout: project-page-new
title: "Feature Chain Based Occupancy Grid SLAM for Robots Equipped with Sonar Sensors "
authors:
  - name: Amit Kumar Pandey*
    sup: #
  - name: K. Madhava Krishna*
    sup: #
  - name: Henry Hexmoor+
    sup: #
affiliations:
  - name: Robotics Research Center, IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: #
  - name: Computer Science Dept, Southern Illinois University, Carbondale, IL, 62901, USA
    link: #
    sup: #
permalink: /publications/2007/Pandey_Feature-Chain-Based-Occupancy-Grid/
abstract: "This paper presents a methodology for achieving SLAM onto the occupancy grid framework with the data only from sonar sensors. Sonar data are highly noisy and unpredictable. Sonar does not give the consistent readings for a point from two different positions, so the approaches which
rely on correspondence reading matching will prone to fail without exhaustive mathematical calculations of sonar modeling and environment modeling. Also, if features are being use to localize then the robot needs to revisit those features exactly, to localize, which itself will not be accurate because robot will not be at the exact position from where that feature has been detected. Hence it will not get back those feature readings using sonar. Here we are presenting a hybrid
approach based on feature chain. Instead of relying completely on feature mapping and point matching, it finds the links between features to localize. It will drastically reduce the need
of revisiting a feature to localize and hence reducing the exploration overhead, while handling other issues of problems with point or feature matching. We map features onto Occupancy Grid (OG) framework taking advantage of its dense representation of the world. Combining features onto
OG overcomes many of its limitations such as the independence assumption between cells and provides for better modeling of the sonar implicitly providing more accurate maps."
paper: https://robotics.iiit.ac.in/uploads/Main/Publications/2007_10.pdf
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---