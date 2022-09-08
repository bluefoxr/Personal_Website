---
abstract: "Sensitivity analysis allows one to investigate how changes in input parameters to a system affect the output. When computational expense is a concern, metamodels such as Gaussian processes can offer considerable computational savings over Monte Carlo methods, albeit at the expense of introducing a data modelling problem. In particular, Gaussian processes assume a smooth, non-bifurcating response surface. This work highlights a recent extension to Gaussian processes which uses a decision tree to partition the input space into homogeneous regions, and then fits separate Gaussian processes to each region. In this way, bifurcations can be modelled at region boundaries and different regions can have different covariance properties. To test this method, both the treed and standard methods were applied to the bifurcating response of a Duffing oscillator and a bifurcating FE model of a heart valve. It was found that the treed Gaussian process provides a practical way of performing uncertainty and sensitivity analysis on large, potentially-bifurcating models, which cannot be dealt with by using a single GP, although an open problem remains how to manage bifurcation boundaries that are not parallel to coordinate axes."
authors:
- admin
- Keith Worden
- Jennifer Rowson
date: "2013-01-01"
doi: "10.1016/j.ymssp.2012.05.010"
featured: false
image:
  caption: ''
  focal_point: ""
  preview_only: false
links: null
projects: null
publication: In *Mechanical Systems and Signal Processing*
publication_types:
- "2"
publishDate: "2013-01-01"
summary: Sensitivity analysis of bifurcating models using treed Gaussian processes.
tags:
- Machine learning
- Sensitivity analysis
- Engineering
- Biomechanics
title: "Bayesian sensitivity analysis of bifurcating nonlinear models"
---


