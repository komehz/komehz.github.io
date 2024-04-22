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
* Ph.D. in Transportation Engineering, Coventry University, 2023
* M.Sc. in Control Engineering, Coventry University, 2017
* B.Sc. in Electrical/Electronics Engineering, University of Lagos, 2015

Work experience
======
* **Research Fellow** \| Birmingham City University \| Apr. 2024 - Current
  * Provide AI consultancy and assistance to MedTech companies in the West Midlands.

* **Postgraduate Researcher** \| Coventry University \| Sep. 2019 - Sep. 2023
  * Developed advanced deep-learning-based models, data preprocessing techniques and evaluation methods for traffic flow forecasting.
  * Python libraries used: NumPy, Pandas, Matplotlib, TensorFlow/Keras. 

* **Research Assistant** \| Coventry University \| Jul. 2022 - Dec. 2022
  * Annotated road-marking images and managed the preprocessing and augmentation of 150,000 images.
  * Trained a highly effective road-marking detection model in Detectron2.

* **Research Assistant** \| Coventry University \| Nov. 2017 - Nov. 2018
  * Developed advanced traffic simulation models for the iVMS (Intelligent Variable Message Systems) and UKCITE (UK Connected Intelligent Transport Environment) projects.
  * Simulated sophisticated driver assistance features in VISSIM and AIMSUN.
  
Skills
======
* **Programming Languages:** Python, SQL
* **Programming Toolset:** Tensorflow/Keras, PyTorch, NumPy, Pandas, Matplotlib, OpenCV, LangChain
* **Technology Stack:** Deep Learning, Natural Language Processing, Time Series Forecasting, Computer Vision. 
* **Platform Proficiency:** Amazon SageMaker, Docker, Git

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!--
Talks
 ======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
-->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!--
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
