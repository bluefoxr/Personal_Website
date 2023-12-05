---
authors:
- admin
categories: []
date: "2023-09-28"
draft: false
featured: false
image:
  caption: ''
  focal_point: ""
  preview_only: false
projects: []
summary: "My lectures on robustness in composite indicators and the COINr package."
tags:
- Composite indicators
- Software
- Training
title: "COIN training on composite indicators"
---

So on the 28th of September I gave a couple of invited talks at the [2023 JRC Week on Composite Indicators and Scoreboards](https://knowledge4policy.ec.europa.eu/composite-indicators/2023-jrc-week-composite-indicators-scoreboards_en), whic is spread over a few days and delves into all the technical and non-technical intricacies of building and analysing composite indicators.

I have helped with this training course for some years, particularly when I worked full time in the JRC's [Competence Centre for Composite Indicators and Scoreboards](https://knowledge4policy.ec.europa.eu/composite-indicators_en). In this case I gave two lectures:

- Quality control and robustness, in which I explain the main concepts for testing robustness (sensitivity analysis) and give some tips for building high-quality composite indicators.
- A lecture on building and auditing composite indicators with R

For the first lecture you can find the slides [here](https://knowledge4policy.ec.europa.eu/file/coin-week-2023-step-8-quality-control-robustness_en), and the video you can find [here](https://webcast.ec.europa.eu/2023-jrc-week-on-composite-indicators-and-scoreboards-2023-09-28) (the lecture starts about 14:35).

In the second lecture I built a code demo which is available as an HTML page on GitHub [here](https://bluefoxr.github.io/COINr-Demo-2023/COINr_demo.html). In this notebook, I show how to:

- Download data from the Eurostat API in R
- Pass the data and structure into COINr
- Analyse the data and calculate the results
- Map the data interactively using Leaflet
- Explore some methodological variations
- Export everything to Excel

This encapsulates many of the points that I think go in to making a good composite indicator. If you want to hear more about it, check out the [recording](https://webcast.ec.europa.eu/2023-jrc-week-on-composite-indicators-and-scoreboards-2023-09-28) and skip to approximately 16:28. Unfortunately there were a few technical problems throughout the lecture so you may need to skip ahead on occasions!
