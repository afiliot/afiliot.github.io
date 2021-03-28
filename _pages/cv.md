---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

### **MSc in Statistics and Computer Science, 2017-2019** - ENSAE Paris
### **MSc in Machine Learning and Computer Vision, 2018-2019** - ENS Paris-Saclay
### **Engineering school, 2015-2017** - Ecole Centrale de Marseille
### **Prep school, Maths & Physipcs, 2013-2015** - Lycée Henri Wallon


Work experience
======
### **Data scientist, Nov. 2019-now** - Lille University Hospital
Statistical-learning-based<sup>1</sup> medical research projects as part of the INCLUDE team (INtegration Center of the Lille University hospital for Data Exploration, GitHub [here](https://github.com/include-project))
- Statistical support for clinical research projects (data mining and method design, implementation, results sharing and clinical feedbacks, publication if relevant)
- Histological image analysis using deep learning techniques applied to classification and survival estimation 
- POCs on the applicability of federated learning to medical research in close collaboration with the Inria Magnet team, IT engineers, DPOs, etc.

Supervising of internships and another data scientist for a 1-year project on histology.

Writing of research protocols, calls for applications and applications to calls. 

<sup>1</sup> Let's be honest : statistical learning ⊂ AI. 

![xkcd #1897](/images/ikcd1.png "XKCD #1897")


### **Research intern, Jun-Nov. 2019** - Guerbet
- *GANs*: virtual contrast enhancement applied on brain MRIs using deep generative networks.
- *3DCNN*: gliomas segmentation on Brats data set using 3D convolution networks.

### **Data scientist intern, Jun-Sep. 2018** - Banque de France 
- *Credit scoring*: statistical modelling and 3 year-prediction of the European Fractional Default Risk.
- *Natural Language Processing*: analysis of companies' financial reports to evaluate the semantic risk of credit default.



Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  