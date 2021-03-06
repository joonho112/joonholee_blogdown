---
title: Modeling heterogenous treatment effects across sites

date: 2020-01-26T00:00:00

authors: [JoonHo Lee, Sophia Rabe-Hesketh]

summary: "Understanding treatment effect heterogeneity in multi-site trials: A full Bayesian approach"

external_link: ""

image:
  caption: ''
  focal_point: "Center"
  preview_only: true

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
- methods

tags: [method, R, causal inference, Bayesian methods, Stan]

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

## Abstract 

Educational researchers and policymakers are increasingly asking questions such as “To what extent does the treatment effect vary across schools?” and “Why is a treatment more effective in some schools than others?” These questions are closely related to understanding how a treatment might differentially operate in different school contexts. Bayesian hierarchical models (BHMs) provide a framework to separate genuine underlying heterogeneity across sites from sampling error and simultaneously use this variation to inform the uncertainty on the average treatment effect. Full Bayesian models often perform better relative to frequentist counterparts, particularly with a small number of sites.

The core challenge is how to model the distribution of site-level effects. A convenient, often implicit, modeling assumption is that the distribution is normal, but this could be problematic when the true distribution is multi-modal or heavy-tailed, for instance. In this project, we explore the use of flexible alternatives for modeling the site-level effects distribution and investigate ways to incorporate site-level covariates. The main motivating example is a multi-site randomized evaluation of conditional cash transfer programs in two of the poorest school districts in Bogota, Colombia. We find that standard results relying on normality assumptions mask interesting and important results of this study.



## Research notes

### Simulation design

- [Data generating models: Gaussian, T, and a mixture of two Gaussians](/html/01_Simulation-data-generation.html)


### Modeling choices

1. [Gaussian](/html/02_Modeling-choices_01_Gaussian.html) 

2. [T (df = 5)](/html/02_Modeling-choices_02_T5.html)

3. Dirichlet Process #1 - bumpy, multi-modal G distribution

4. Dirichlet Process #2 - smoother G distribution

5. Empirical Bayes deconvolution estimator (Efron prior)

6. Smoothing by roughening (SBR)      



### Summary of posterior samples

1. Posterior means

2. Triple-goal estimator

3. Constrained Bayes estimator



### Results

1. A small illustrative simulation

2. Efficiency of nonparametric data analysis choices for G

3. Robustness of G

4. Estimating ranks



