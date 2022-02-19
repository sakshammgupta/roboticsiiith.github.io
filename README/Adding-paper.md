# Adding a new paper to RRC website



To add a new paper to the RRC website, we will create a new markdown file. Create a markdown file in `_pages/project-pages/<year>/`. Name this file as `<surname_first_author>_<Paper-separated-by-hyphen>.md`. For instance, for the paper `DeepMPCVS: Deep Model Predictive Control for Visual Servoing` of `Pushkal Katara` (2020), the name of the file will be `_pages/project-pages/2020/Katara_DeepMPCVS-Deep-Model-Predictive-Control-for-Visual-Servoing.md`



### Content

Copy the content from  `_pages/project-pages/2020/Katara_DeepMPCVS-Deep-Model-Predictive-Control-for-Visual-Servoing.md` to your file. Edit the authors, paper title, superscripts, abstract, and additional links according to your use. Example is given below

```yaml
---
layout: project-page-new
title: "DeepMPCVS: Deep Model Predictive Control for Visual Servoing"
authors:
  - name: Pushkal Katara
    sup: 1
  - name: YVS Harish
    sup: 1
  - name: Harit Pandya
    sup: 3
  - name: Abhinav Gupta
    sup: 1
  - name: AadilMehdi Sanchawala
    sup: 1
  - name: Gourav Kumar
    sup: 2
  - name: K. Madhava Krishna
    sup: 1
  - name: Brojeshwar Bhowmick
    sup: 2
affiliations:
  - name: IIIT Hyderabad, India
    link: https://robotics.iiit.ac.in
    sup: 1
  - name: TCS Research and Innovation Labs, Kolkata, India
    link: #
    sup: 2
  - name: University of Lincoln, UK
    link: #
    sup: 3
permalink: publications/2020/DeepMPCVS
abstract: "The simplicity of the visual servoing approach makes it an attractive option for tasks dealing with vision-based control of robots in many real-world applications. However, attaining precise alignment for unseen environments pose a challenge to existing visual servoing approaches. While classical approaches assume a perfect world, the recent data-driven approaches face issues when generalizing to novel environments. In this paper, we aim to combine the best of both worlds. We present a deep model predictive visual servoing framework that can achieve precise alignment with optimal trajectories and can generalize to novel environments. Our framework consists of a deep network for optical flow predictions, which are used along with a predictive model to forecast future optical flow. For generating an optimal set of velocities we present a control network that can be trained on-the-fly without any supervision. Through extensive simulations on photo-realistic indoor settings of the popular Habitat framework, we show significant performance gain due to the proposed formulation vis-a-vis recent state of the art methods. Specifically, we show a faster convergence and an improved performance in trajectory length over recent approaches."
paper: https://robotics.iiit.ac.in/publications/2020/deep-mpc-for-visual-servoing/preprint.pdf
supplement: https://robotics.iiit.ac.in/publications/2020/deep-mpc-for-visual-servoing/supplementary.pdf
video: https://robotics.iiit.ac.in/publications/2020/deep-mpc-for-visual-servoing/video.mp4
# iframe: https://www.youtube.com/embed/jhjskX4FQwA

---
```



**Note:** if you are embedding a youtube video, please use iframe tag (commented in the file). If you are using drive files then use the video tag (as done above)

### Adding paper to configuration file

Add the paper to the config file in `_data/pubs/<year>.yml`. For `_pages/project-pages/2020/Katara_DeepMPCVS-Deep-Model-Predictive-Control-for-Visual-Servoing.md`, we have added the following in `_data/pubs/2020.yml`

```yaml
- title: "DeepMPCVS: Deep Model Predictive Control for Visual Servoing"
  authors: Pushkal Katara, YVS Harish, Harit Pandya, Abhinav Gupta, AadilMehdi Sanchawala, Gourav Kumar, 
           Brojeshwar Bhowmick and K. Madhava Krishna

  venue: Conference on Robot Learning (CoRL), 2020
  link:
    url: publications/2020/DeepMPCVS
    display: Project Page
```
**Note:** Make sure the url in the configuration file matches the permalink of your markdown.

