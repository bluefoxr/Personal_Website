---
date: "2023-01-05"
external_link: ""
image:
  caption: "Credit: UNHCR"
  focal_point: Smart
summary: "Measuring migrant and refugee vulnerability in Guatemala."
tags:
- Indicators
- Sustainable development
- Policy
title: Community based protection in Guatemala
---

The [United Nations High Commissioner for Refugees (UNHCR)](https://www.unhcr.org/) is a UN agency that helps to protect the rights and wellbeing of people who have been forced to flee from their homes. In Guatemala, there are many such refugees and forcibly displaced people, typically moving from southern countries (such as Honduras, El Salvador) northwards. One of the activities of the UNHCR in Guatemala is to provide community-based protection (CBP) for these people, however due to the complexity of the situation more information is need to understand where CBP should be directed.

My work for the UNHCR is to build a web app to measure the vulnerability of populations at the municipal level in Guatemala by bringing together indicators measuring threats, socioeconomic circumstances, and response capacities to give a summary measure which helps to identify the municipalities that are in most need of CBP.

The resulting app, which is called the [Admin-2 Severity Index Tool (A2SIT)](https://rstudio.unhcr.org/SeverityIndex/) is a fairly complex Shiny app which runs on an R server. It is encapsulated in an R package that I also built called A2SIT [which is available on GitHub](https://github.com/UNHCR-Guatemala/A2SIT). I should mention that although I built the app and package, a huge amount of work was done in collecting the data, helping guide the app and designing the index, as well as many other things during the project.

In the app you can:

-   Upload your own data set which should be at the Admin 2 level for one of the supported countries
-   Obtain a statistical analysis of your data and flagged issues for indicators
-   Calculate index results and plot them on a map, and as tables and bar charts
-   Play with composite indicator settings
-   View and compare profiles of municipalities
-   Compare scenarios

There is also fairly comprehensive documentation which is available in an [online book](https://unhcr-guatemala.github.io/A2SIT/book/index.html)!

This has been a big project and I have learned a lot. But it has also been very rewarding. The app has been successful in testing with users, and should be rolled out to other countries in Central and South America. There is also a [Medium article](https://medium.com/unhcr-innovation-service/everything-all-at-the-same-time-6f554c74f586) on the app.

![Data analysis](screenshot_2.png)

![Mapping and results](screenshot_3.png)

![Region profiles](screenshot_4.png)
