---
authors:
- admin
categories: []
date: "2023-09-08"
draft: false
featured: false
image:
  caption: ''
  focal_point: ""
  preview_only: false
projects: []
summary: "We published the JRC's annual report on greenhouse gas emissions of all countries in the world."
tags:
- Emissions
- Sustainable development
- Publications
title: "Global emissions data set published"
---

In September 2023, as part of my work as a data scientist at the Joint Research Centre, I contributed to the [GHG emissions of all world countries booklet](https://publications.jrc.ec.europa.eu/repository/handle/JRC134504).

The booklet is an annual output of the EDGAR database team (of which I am a member) and provides emissions time series from 1970 until 2022 for GHGs for all countries and for all anthropogenic sectors. EDGAR is used around the world as a highly-detailed, consistent and high-quality data source for research and policy making.

My particular role in this endeavour was calculating uncertainties on emissions estimates. This is a fairly complex procedure given the size and complexity of the database, and also due to issues such as skewed distributions and correlations. To do this I built a custom R package which is live-linked to the EDGAR database using SQL drivers. Uncertainties can be explored, visualised and exported internally via a Shiny app.

I'm quite proud of my contributions so far to the EDGAR project (although these are mostly internal), and pleased to be a part of a team that contributes significantly to climate change research and policy.
