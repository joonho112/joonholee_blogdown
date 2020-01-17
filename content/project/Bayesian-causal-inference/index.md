---
title: Bayesian Causal Inference
date: 2018-06-24T00:00:00
authors: [JoonHo Lee, Avi Feller, Sophia Rabe-Hesketh]
summary: Developing a series of Stan case studies demonstrating important concepts in Bayesian causal inference
external_link: ""
image:
  caption: '[Photo by Chris Liverani on Unsplash](https://unsplash.com/photos/dBI_My696Rk)'
  focal_point: Smart

links:
- icon: images
  icon_pack: fas
  name: materials
  url: /html/Case-Study01_Model-Based_Inference_for_RCT.html
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/joonho112/Bayesian-causal-inference/tree/master

categories:
- workshop

tags: [R, causal inference, Bayesian methods, Stan]

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

In this project, we develop a series of case studies demonstrating the implementation of Bayesian model-based inference for causal effects in [Stan](http://mc-stan.org). 

The Bayesian inferential framework introduced by Rubin (1978) defines causal effects as a comparison of the potential outcomes of the same units and clearly separates the true underlying model of the potential outcomes from the treatment assignment mechanism. Then the framework takes advantage of fully Bayesian posterior predictive inference for multiply-imputing the missing potential outcomes.


## Stan Case Studies

- [Model-based Inference for Causal Effects in Completely Randomized Experments](/html/Case-Study01_Model-Based_Inference_for_RCT.html)   

- Instrumental Variabls Analysis of Randomized Experiments with One-Sided Noncompliance

- Instrumental Variabls Analysis of Randomized Experiments with Two-Sided Noncompliance

- Treament Effect Variations in Multi-Site Trials
