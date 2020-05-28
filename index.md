---
title       : Brazilian PV Market App 
subtitle    : A closer look into brazilian photovoltaic market with interactive plots and maps
author      : Lucas Teixeira
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : prettify  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github:
        user: lucassilvat
        repo: slidifyPVMarket
---

## Executive summary

The main goal of Brazilian PV Market App is to provide an interactive set of maps and plots that can be customized by some inputs in order to generate insights.

The user can:  
> 1. Make comparisons over states (UFs) and cities  
> 2. Set a specific time period
> 3. Change the unit of summarization (power or count)  
> 4. Show animation over time  


--- .class2 #id

## Data

All computations were based on a public dataset containing information of **all** PV systems installed in brazilian territory.

Data can be found in [ANEEL's site](https://www.aneel.gov.br/outorgas/geracao/-/asset_publisher/mJhnKIi7qcJG/content/registro-de-central-geradora-de-capacidade-reduzida/655808?inheritRedirect=false&redirect=http%3A%2F%2Fwww.aneel.gov.br%2Foutorgas%2Fgeracao%3Fp_p_id%3D101_INSTANCE_mJhnKIi7qcJG%26p_p_lifecycle%3D0%26p_p_state%3Dnormal%26p_p_mode%3Dview%26p_p_col_id%3Dcolumn-2%26p_p_col_pos%3D1%26p_p_col_count%3D2). One can find a lot of summarized tables, which were scraped into a single dataset.

There are over 230.000 observations.

--- .class #id

## Brazilian PV Market App

There is already a [PowerBI based application at ANEEL's webpage](https://app.powerbi.com/view?r=eyJrIjoiZjM4NjM0OWYtN2IwZS00YjViLTllMjItN2E5MzBkN2ZlMzVkIiwidCI6IjQwZDZmOWI4LWVjYTctNDZhMi05MmQ0LWVhNGU5YzAxNzBlMSIsImMiOjR9).  

However, using this app for inference is quite hard, since a huge set of information is crushed together.

The motivation then is to make a simpler app that can be used to make basic inference about the actual status of the brazilian PV market.

[Here](lucassilvat.shinyapps.io/PV-brazil/) you can find my app. It is still in development, so if you are interested, there will be updates!

--- .class #id

## Example

1) Set *Whole country*, *default* time period, *Power* and show map.

<iframe src="map.html" width=100% height=100% allowtransparency="true"> </iframe>

In case of questions or suggestions, send e-mail to lucassilvat@gmail.com

**Cheers!**
--- .class #id
