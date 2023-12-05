---
date: "2022-12-01"
external_link: ""
image:
  caption: "Image by [Jan from Pixabay](https://pixabay.com/vectors/interface-internet-program-browser-3614766/)"
  focal_point: Smart
summary: A web app for composite indicator construction
tags:
- Software
- Indicators
title: "Composite indicator app"
---

The open-source COINr package is now used worldwide for building and analysing composite indicators. However, for those people who don't use R, it is hard to access.

The [Foundation for Innovative New Diagnostics (FIND)](https://www.finddx.org/) is a non-profit organisation which “seeks to ensure equitable access to reliable (medical) diagnosis around the world. Early in 2023 I began working with them to develop a Shiny app which can build composite indicators to help them identify in which countries to direct their resources.

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
