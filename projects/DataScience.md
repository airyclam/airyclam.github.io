---
layout: project
type: project
image: images/datareport.png
title: Cytokine Analysis
permalink: projects/cytokines
# All dates must be YYYY-MM-DD format!
date: 2019-08-20
labels:
  - Data Science
  - Machine Learning
  - Biology
  
  
summary: An initial exploratory analysis I conducted on inflammatory cytokine markers related to aging. 
---
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I've been working as a research assistant for the Allsopp lab at John A. Burns School of Medicine for the past few years. At a high level overview, the Allsopp lab does <ins>research into longevity</ins> and the biological pathways connected to the FOXO3a gene and telomerase enzyme. Under the lab, I've been predominately involved in a project examining blood samples from Okinawan hospitals for various aging indicators. <ins>The sample size is around 200, with over 15 different measured variables.</ins>  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Although most of my work for the lab has revolved around conducting experiments and data collection, I've recently become more involved in the data processing and analysis pipeline. Last summer, my supervisor became interested in doing an exploratory analysis on the inflammatory cytokine data we collected. There have been previous studies on ["inflammaging"](https://www.nature.com/articles/s41574-018-0059-4) and we wanted to see if the cytokine levels we collected could be used as a predictor for age/genotype with machine learning. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; I started this project with no real computer science knowledge and not much direction from my supervisors. Experimenting on my own and fiddling around with a few different machine learning algorithms, I eventually obtained a model which could predict age with an <ins> accuracy of 85% </ins> using a random forest algorithm. However, a major issue with this project is the lack of reproducibility because I made a lot of direct changes to both the dataset and learning models. As an initial exploratory analysis, however, it has done its job. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Currently, I'm in the process of working with my supervisor to obtain access to a 1000+ dataset from a local hospital to explore the relationship between these variables further. To prepare for this, I will be using some of the new skills I've picked up this year to build a more <ins>scalable framework</ins> that can produce <ins>clean, consistent results.</ins>

<img class="ui medium right floated rounded image" src="../images/datatrend.svg">
Link to the initial analysis: <a href="https://github.com/airyclam/Cytokines"><i class="large github icon"></i>airyclam/Cytokines</a>


