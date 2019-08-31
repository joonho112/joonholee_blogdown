---
title: Bayesian Causal Inference
date: 2019-08-30T00:00:00
authors: [JoonHo Lee, Avi Feller, Sophia Rabe-Hesketh]
summary: Case studies for the implementation of Bayesian model-based inference for causal effects in Stan.
abstract: Taking advantage of fully Bayesian posterior predictive inference for multiply-imputing the missing potential outcomes
external_link: ""
image:
  focal_point: Smart

categories:
- software
- workshop

tags:
- causal inference
- Bayesian methods
- missing data

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

links:
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/apreshill/labhub
---

In this document, we discuss the implementation of Bayesian model-based inference for causal effects in Stan. The Bayesian inferential framework introduced by Rubin (1978) defines causal effects as a comparison of the potential outcomes of the same units and clearly separates the true underlying model of the potential outcomes from the treatment assignment mechanism. Then the framework takes advantage of fully Bayesian posterior predictive inference for multiply-imputing the missing potential outcomes.

We start by providing an introduction to the Bayesian inferential framework by analyzing a simulated dataset generated under unconfounded treatment assignment. Then we analyze an example dataset obtained from a completely randomized experiment focusing on the specification of the joint distribution of the potential outcomes. All of the source code for this case study is available on GitHub at [joonho112/Bayesian-causal-inference/Case_study_1](https://github.com/joonho112/Bayesian-causal-inference/tree/master/Case_study_1).