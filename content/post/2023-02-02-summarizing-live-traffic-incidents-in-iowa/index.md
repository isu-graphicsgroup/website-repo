---
title: Summarizing live traffic  incidents in Iowa
author: Guillermo Basulto, InTrans, Iowa State University
date: '2023-02-02'
slug: summarizing-live-traffic-incidents-in-iowa
categories:
  - category
tags:
  - shiny app
description: ''
draft: yes
images:
  - /2023/02/image.jpg
---

Traffic incidents in Iowa are constantly reported through the Advanced Traffic Management System (ATMS). On average, over 100 traffic incidents are daily incidents are reported in ATMS, from crashes and vehicle fires to slow traffic and stalled vehicles. In order to make understand the spatial component of them, trends, summaries and severity, we have developed an interactive dashboard in shiny.

I will describe the challenges and decisions I made to combine old information and up-to-date information; the tables and figures used to summarize the information; the additional sources of information to provide context to the incidents; and the upcoming and tentative changes to it. I will briefly talk about the technical aspects of the dashboard; it was developed in shiny using a wide variety of packages, like the whole tidyverse, sf, plotly, DT, and leaflet.

 

