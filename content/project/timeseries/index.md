---
title: Time Series Analysis Framework
summary: "This framework is aimed to provide analytical tools and operations on time series from any domain and allows plugins to be written to import time series from custom sources and visualize them in custom ways. Written in Java with GUI constructed with 
Java Swing."
tags:
- Java
- GUI
- Analysis
- TimeSeries
- Framework
date: "2020-04-10T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: A screenshot of the framework used to analyze and visualize stock prices
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

# TimeSeries Data Analysis Framework

A Time Series is a series of data points indexed in time order. It is usually comprised of data points taken at successive equally spaced points in time and it is thus discrete-time data. Time Series can be used in a massive number of domains (just to name a few, statistics, signal processing, econometrics, math finance, weather forecasting) that time series itself has become a domain of study.

This framework is aimed to provide analytical tools and operations on time series from any domain and allows plugins to be written to import time series from custom sources and visualize them in custom ways. For the time matter of this phase, we have implemented basic operations including time series arithmetic, growth rate, simple moving average, and time point extraction. Further analysis, such as curve fitting, prediction, classification and segmentation, could be supported by the framework in the future.