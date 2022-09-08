---
abstract: Comparison studies of global sensitivity analysis (GSA) approaches are limited in that they are performed on a single model or a small set of test functions, with a limited set of sample sizes and dimensionalities. This work introduces a flexible ‘metafunction’ framework to benchmarking which randomly generates test problems of varying dimensionality and functional form using random combinations of plausible basis functions, and a range of sample sizes. The metafunction is tuned to mimic the characteristics of real models, in terms of the type of model response and the proportion of active model inputs. To demonstrate the framework, a comprehensive comparison of ten GSA approaches is performed in the screening setting, considering functions with up to 100 dimensions and up to 1000 model runs. The methods examined range from recent metamodelling approaches to elementary effects and Monte Carlo estimators of the Sobol’ total effect index. The results give a comparison in unprecedented depth, and show that on average and in the setting investigated, Monte Carlo estimators, particularly the VARS estimator, outperform metamodels. Indicatively, metamodels become competitive at around 10–20 runs per model input, but at lower ratios sampling-based approaches are more effective as a screening tool.
authors:
- admin
date: "2020-12-01"
doi: "10.1016/j.ress.2020.107189"
featured: true
image:
  caption: ''
  focal_point: ""
  preview_only: false
projects: []
publication: '*Reliability Engineering & System Safety*'
publication_short: ""
publication_types:
- "2"
publishDate: 2020-12-01"
summary: A novel approach to benchmarking sensitivity analysis approaches using highly flexible "metafunctions".
tags:
- Sensitivity analysis
- Machine learning
title: Metafunctions for benchmarking in sensitivity analysis
---

Supporting code is found [here](http://dx.doi.org/10.13140/RG.2.2.15667.66081), and the metafunction is integrated into the [sobolsens package](https://cran.r-project.org/package=sensobol) in R.
