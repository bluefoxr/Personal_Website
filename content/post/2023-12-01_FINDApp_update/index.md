---
authors:
- admin
categories: []
date: "2023-12-01"
draft: false
featured: false
image:
  caption: ''
  focal_point: ""
  preview_only: false
projects: []
summary: "Wrapping up the composite indicators app project for release."
tags:
- Composite indicators
- Software
title: "Updates on the FIND composite indicators app"
---

The [Foundation for Innovative New Diagnostics (FIND)](https://www.finddx.org/) is a non-profit organisation which “seeks to ensure equitable access to reliable (medical) diagnosis around the world. Early in 2023 I began working with them to develop a Shiny app which can build composite indicators to help them identify in which countries to direct their resources.

After much hard work and collaboration with talented people, we are nearly ready to release the app. Although the app was developed as a tool for use within FIND, we should be able to release an open-source version of it, which can be installed as an R package, but run as an app.

The app is essentially a front end for the [COINr package](https://bluefoxr.github.io/COINr/), but also has a number of modifications and tries to strike a balance between flexibility and not overwhelming the user with too many options. Its features include:

- Upload of any data set and index structure
- Screening units by data availability
- Imputation of missing data
- Outlier treatment
- Normalisation and aggregation
- Stats, maps, bar and bubble charts
- Unit profiles
- Global sensitivity analysis and reweighting

I leave a couple of screenshots here, and hopefully the app will be made freely available in the near future!
