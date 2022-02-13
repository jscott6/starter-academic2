---
title: epidemia
summary: Hierarchical Bayesian Modeling of Epidemics with Point Processes
tags:
- Epidemiology
date: "2020-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: epidemia logo
  focal_point: Smart

links:
- icon: github-alt
  icon_pack: fab
  name: Source Code
  url: https://github.com/ImperialCollegeLondon/epidemia
- name: Website
  url: https://imperialcollegelondon.github.io/epidemia/index.html
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

Flexibly specify and fit Bayesian statistical models for epidemics. epidemia leverages R’s formula interface to paramaterize the time-varying reproduction rate as a function of covariates. Multiple regions can be modeled simultaneously with multilevel models. The design of the package has been inspired by, and has borrowed from, rstanarm. epidemia uses rstan as the backend for fitting models.