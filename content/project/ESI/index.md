---
date: "2023-10-01"
external_link: ""
image:
  caption: "Credit: [Cedefop](https://www.cedefop.europa.eu/en)"
  focal_point: Smart
summary: Updating and improving the European Skills Index for Cedefop.
tags:
- Skills
- Policy
- Indicators
title: "European Skills Index"
---

The [European Skills Index](https://www.cedefop.europa.eu/en/tools/european-skills-index) (ESI) is a well-established composite indicator that is produced by [Cedefop](https://www.cedefop.europa.eu/en/about-cedefop/who-we-are), the European agency which promotes vocational and education training. It aims to measure skills systems at the national level in European countries.

As of 2023 I was part of a consortium that successfully won the bid to update and potentially tweak/improve the ESI for the next few years.

The next iteration of the ESI will be launched in 2024, and I am in charge of the main ESI index calculations. Naturally, I am using the [COINr package](https://bluefoxr.github.io/COINr/) which is (even though I am mega-biased) the best tool out there for building reproducible composite indicators! Some particular improvements that I am making are:

- Fully-reproducible data pipeline based on APIs as much as possible
- Programmatic data and methodology validation
- Results calculated using COINr in Quarto documents: fully transparent and easily portable.

The idea here is to modernise the ESI calculation and make it super easy to come back in future years for updates.

At the time of writing we are about to calculate the final results. Of course there will be plenty to do afterwards in reporting, but for now we are on track.
