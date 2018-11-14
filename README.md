# Talks
Talks at the graphics working group


- **16 Nov. 2018**:  
**Presenter**: Sam Tyner  
**Title**: "A survey of US Federal Government data sources"   
**Abstract**: Did you know that there are thirteen U.S. federal government agencies tasked with collecting statistics? Can you name any? (Besides the Census Bureau...) In addition to thirteen dedicated agencies, the federal government also has over one hundred other programs dedicated to collecting statistics on various goings-on in the United States. These programs range from the more intuitive, like the Agricultural Research Service (part of the USDA), to the quite niche, like the National Cemetery Administration (part of the VA). I'll briefly introduce these agencies and as many of the smaller programs as I can, and provide links to their data warehouse (if applicable). If there is time, I also hope to introduce everyone to some basics about using APIs (application program interface) responsibly to download some of this data from the web. A link with the presentation will be made available to the group on Friday.  




- **09 Nov. 2018**:  
**Presenter**: Ganesh Krishnan  
**Title**: "Diagnostics and Decisions in the Bullet Matching pipeline"   
**Abstract**: Forensic ballistic analysis comprises of identification of whether two bullets come from the same firearm (same-source) or not. This can be thought as an inverse problem to the actual process of firing a bullet, where we have an outcome first, and we then, try to find the source that generated the outcome. Therefore we need a framework of quantifiable steps that takes us from the questioned bullet to a firearm. In this talk I will first give a brief overview of this framework i.e. how different markings are made on the surface of a Bullet, the data we use in our framework, how these markings are identified, extracted and processed from the data, and methods used to come up with a comparison score.  After that I ll demonstrate how we can diagnose problems in the identification process through an interactive Shiny application, and how it can be useful in decision making.  



- **02 Nov. 2018**:  
**Presenter**: Ian Lyttle  
**Title**: "Introduction to Tidyeval"   
**Abstract**: Last year, a new version of dplyr was released. It handles non-standard evaluation using a new framework: tidyeval, developed by Hadley Wickham and Lionel Henry. Since then, tidyeval has been incorporated also into tidyr and ggplot2. Tidyeval will be useful if you write code that uses dplyr on data-frames with column names that you don’t know until runtime. This might be the case if you are writing package functions – this also might be the case if you are writing a shiny app that works on user-uploaded data-frames. If you have any experience using dplyr, you will have no problem to take your first steps into tidyeval. Please being your laptop, we will go through some interactive exercises that you can find here: https://ijlyttle.shinyapps.io/tidyeval/  




- **26 Oct. 2018**:  
**Presenter**: Kiegan Rice  
**Title**: "An interactive browser for US census data"   
**Abstract**: Census data provide an important snapshot of information about a country at different times throughout its history. The evolving and adapting nature of census questions creates a complicated data management problem, and this problem is exaggerated when the goal is to answer questions across several years simultaneously. However, recent developments in methods for data analysis and visualization provide a window for developing a more clean interface for census data exploration. I will present a web-based Shiny application that allows users to browse U.S. Census Data across multiple years simultaneously, create a visualization of variables of interest, and download chosen data, organized for further use.  




- **19 Oct. 2018**:  
**Presenter**: Heike Hofmann  
**Title**: "R Packages - DIY"   
**Abstract**: Almost everybody working in R is working with R packages. The package system in R is a convenient way to bundle your R functions and data and make it available to the wider community. In recent years the support for package development has increased. We will be discussing functionality of RStudio and the devtools package to support R development. We will work on a small R package together as an example. Bring your own code and laptop, and leave with your package! We will also talk about CRAN requirements and how to make sure packages are CRAN-ready.



- **12 Oct. 2018**:  
**Presenter**: Katherine Goode and Katie Rey    
**Title**: "Introducing ggResidpanel: An R Package for Easy Visualization of Residuals"   
**Abstract**: As consultants on a wide variety of projects across many majors, a common oversight we encounter is a failure to examine the residuals. This is particularly true when the client is performing the analysis in R. We were inspired by the residual panel in SAS to create an R package that easily provides users with a similar panel of plots. The ggResidpanel package in R is intended to give a single view of diagnostic plots for checking the key underlying assumptions of linear models. A variety of options gives the user the ability to choose from a selection of plots to display in a window. This includes SAS’s default residual panel as well as R’s default plots for linear models. Other options have been included to ensure that this package can also be applied to deviance or Pearson residuals if the user inputs a generalized linear model.  Cook’s D plots and interactive plots using Plotly are included to provide a straightforward process to identify outliers and influential points while connecting findings back to the data.  





- **05 Oct. 2018**:  
**Presenter**: Susan VanderPlas    
**Title**: "Clusters Beat Trend? Testing Feature Hierarchy in Statistical Graphics"   
**Abstract**: Graphics are very effective for communicating numerical information quickly and efficiently, but many of the design choices we make are based on subjective measures, such as personal taste or conventions of the discipline rather than objective criteria. We'll talk briefly about perceptual principles such as preattentive features and gestalt heuristics, and then discuss the design and results of a factorial experiment examining the effect of plot aesthetics such as color and trend lines on participants' assessment of ambiguous data displays. The quantitative and qualitative experimental results strongly suggest that plot aesthetics have a significant impact on the perception of important features in statistical graphics.
 




- **28 Sept. 2018**:  
**Presenter**: Sam Tyner    
**Title**: "An interactive crash course in bookdown" 
**Abstract**: The bookdown package makes creating a book within RStudio shockingly easy. However, if you're used to writing in LaTeX, there are some humps and bumps that need to be smoothed out before working with bookdown is as easy as it purports to be. In this talk, we will walk through the knowledge bookdown assumes you have before starting,  its little idiosyncrasies, how it compares to LaTeX, and how to use it to make a highly customized book (e.g. a thesis  *nudge nudge, wink wink*). Come prepared by: bringing your laptop, which has the latest release of RStudio, the bookdown package, a LaTeX distribution, and git installed (install.packages("bookdown"), install.packages('tinytex'); tinytex::install_tinytex()). You should also have a Github account. (Not required but VERY helpful. See happygitwithr.com for help installing/configuring git/github/rstudio for your system.)


- **21 Sept. 2018**:  
**Presenter**: Heike Hofmann    
**Title**: "Is what we see really there? - A discussion of visual inference"   
**Abstract**: Often times, when we are 'looking' at data in plots, we find a set of interesting points or identify a pattern that is interesting. 
What is the significance of a finding like that? 
Visual inference gives us protocols that help us to quantify the strength of a visual finding in a framework similar to 
to confirmatory statistical hypothesis testing. Visual inference helps analysts determine if structure is real or
spurious.  In this framework, plots take on the role of test statistics, and human cognition the role of statistical tests.
Statistical significance of visual "discoveries" is measured by having the human viewer compare the plot of the real dataset with collections of plots of simulated or null datasets.
We will discuss some applications of visual inference and aspects of visual tests, such as determining the power of competing designs.   




- **14 Sept. 2018**:  
**Presenter**: Susan VanderPlas   
**Title**: "Eye, Brain, and Mind: Perception and Statistical Graphics"   
**Abstract**: "A picture is worth 1000 words" is as true in scientific communication as it is in other domains, but why are pictures such an effective way to communicate numerical information? In this talk, I'll give an overview of the human visual system, focusing on the areas which influence our perception of graphics. We'll discuss the hardware and "software" of human vision, and then I'll give a brief overview of some of the research on the perception of statistical charts and graphs. If you've ever wondered why pie charts and rainbow color schemes are bad, or how optical illusions impact statistical graphics, this talk is for you!   
**Links**:  http://srvanderplas.github.io/Presentations/GraphicsGroup/EyeBrainMind.html#1   


- **7 Sept. 2018**:  
**Presenter**: Ian Lyttle   
**Title**: Using vegawidget to render Vega-Lite specifications from R   
**Abstract**: The Vega-Lite framework offers the traditional grammar of graphics, rendered in the browser. It also offers a first implementation (at least within Vega-Lite) of a grammar of interactive graphics. The vegawidget package (not yet available on CRAN) provides a means to create and render Vega-Lite specifications using R. In this presentation, we will go through a tutorial overview of vegawidget. To participate, you will need only a laptop with a modern browser (such as Chrome or Firefox), and an internet connection. This overview will cover scatterplots, bar charts, layered charts, time-indexed charts, faceted charts, repeated charts, interactive charts, and tooltips (time-permitting). Anything we do not finish during the presentation can be left as an exercise to the reader.  
**Links**:  Vega-Lite documentation: https://vega.github.io/vega-lite  
Vega-Lite InfoVis paper: https://idl.cs.washington.edu/files/2017-VegaLite-InfoVis.pdf  
vegawidget documentation: https://vegawidget.github.io/vegawidget  
vegawidget tutorial:  https://ijlyttle.shinyapps.io/vegawidget-overview  

- **31 Aug. 2018**:  
**Presenter:** Earo Wang  
**Title**: Tidy your time series analysis with tsibble  
**Abstract:** Mining temporal-context data for information is often inhibited by a multitude of time formats: irregular or multiple time intervals, multiple observational units or repeated measurements on multiple individuals, heterogeneous data types, nested and crossed factors indicating hierarchical sub-groups. Time series models, in particular, the software supporting time series forecasting makes strict assumptions on data that needs to be provided, typically a matrix of numeric data with an implicit time index. Going from raw data to model-ready data is painful. This work presents a cohesive and conceptual framework for organizing and manipulating temporal data, which in turn flows into visualization and forecasting routines. Tidy data principles are applied, and extended to temporal data: (1) mapping the semantics of a dataset into its physical layout, (2) including an explicitly declared index variable representing time, (3) incorporating a "key" comprised of single or multiple variables to uniquely identify units over time, using a syntax-based and user-oriented approach in which it imposes nested or crossed structures on the data. This tidy data representation most naturally supports thinking of operations on the data as building blocks, forming part of a "data pipeline" in time-based context. A sound data pipeline facilitates a fluent and transparent workflow for analyzing temporal data. Applications are included to illustrate tidy temporal data structure, data pipeline structure and usage. The infrastructure of tidy temporal data has been implemented in the R package `tsibble`. 



- **20 Aug. 2018**:  
**Presenter:** All of us
**Title:** "What I did this summer".  
**Abstract:** We are talking about things graphics we did this summer and/or at the Joint Statistical Meetings in Vancouver.
We will also discuss plans for the rest of the semester.  

- **18 Apr. 2018**:  
**Presenter:** Susan VanderPlas  
**Title:** "Graphical Perception- Theory, Experimentation, and Application to the Development of Graphical Methods".  
**Abstract:** Cleveland and McGill's examination of the accuracy of perception of different graphical objects underlies the conventional wisdom that guides our selection of plot types and choices. If you've ever wondered why, exactly, pie charts are bad, this paper is the place to start! The paper breaks down graphical perception into a series of elementary tasks which we use while reading charts. We'll discuss the paper and its implications for creating the most effective plots. The paper can be accessed here: https://www.jstor.org/stable/pdf/2288400.pdf.  

- **11 Apr. 2018**:  
**Presenter:** Lindsay Rutter  
**Title:** Visual inference in RNA-sequencing data  
**Abstract:** In a visual lineup, actual data is plotted among null data, and humans are asked to judge the plot that is different. Creating visual lineups of datasets allows us to assess statistical significance of visual findings, while connecting exploratory data analysis with inferential statistics. We will discuss some of these concepts. I will also present visual lineups for soybean and honeybee RNA-sequencing datasets. This is a work in progress, and so I would be happy to hear any of your advice and input. The paper can be accessed here: https://www.tandfonline.com/doi/abs/10.1080/01621459.2013.808157.  

- **4 Apr. 2018**:  
**Presenter:** Ian Lyttle  
**Title:** Using the altair package to create Vega-Lite visualizations from R  
**Abstract:** Using R to create browser-rendered interactive visualizations has long been an interest for Graphics Group, and for the larger R community. One of the most-promising efforts out there is the Vega-Lite library: https://vega.github.io/vega-lite/. Bob Rudis is coordinating an effort to provide a native R-interface to the Vega-Lite library: https://github.com/hrbrmstr/vegalite. In the Python world, Jake Vanderplas and coworkers offer an API to the latest version of Vega-Lite, the Altair library: https://altair-viz.github.io. In late March, RStudio released to CRAN a package called reticulate: https://github.com/rstudio/reticulate. Its purpose is to make it easy to use a Python library from R. It is the underpinning to their packages to access Tensorflow and Keras. Given the availability of these tools, it seemed possible to make the Altair Python library available to R users, by using the reticulate package. This is what is done with the R-package altair: https://ijlyttle.github.io/altair/index.html; it uses reticulate to connect R to the Altiar Python library. At the moment, the altair package provides a minimal interface to create and render Vega-Lite visualizations. In this presentation-workshop, we will go through an installation process, a few first examples including linked-brushing, and I’ll share a few thoughts about where this package might go. Of course, your feedback will be essential to this presentation. 

- **21 Mar. 2018**:  
**Presenter:** Kanak Choudhury  
**Title:** Parallel and Distributed computing in R  
**Abstract:** Parallel and Distributed computing is very helpful for Big
Data analysis and cloud computing. Besides, for bootstrap, simulation
and machine learning model estimation, this technique is extremely
helpful to reduce computation time. In this talk, I will briefly
discuss about how parallel and distributed computing works and then
demonstrate some R packages ('parallel', 'doRedis'. 'doParallel') that
can be used to parallelize computation.

- **29 Feb. 2018**:  
**Presenter:** Nick Berry  
**Title:** Information Extraction for Handwritten Text  
**Abstract:** In forensic handwriting applications practitioners are interested in matching a document with an unknown author with a particular person's writing style. In order for this to be done computationally it is necessary to first process the documents and try to isolate information in the messy documents. Starting with just blobs of ink, we will isolate important characteristics and start to make steps towards having something usable for performing analyses. This talk will introduce a Shiny app that shows off some of the handwriting processing, and will delve into the Rcpp code that makes it go. Additionally, I’ll briefly run through how some of the more interesting aspects of information extraction work in the handwriting application. GitHub Repo: https://github.com/CSAFE-ISU/handwriter. Shiny App: https://berryni.shinyapps.io/ViewHW/

- **21 Feb. 2018**:  
**Presenter:** Weicheng Zhu  
**Title:** Blogdown quick tutorial  
**Abstract:** In this talk, I will show you how to create a professional academic homepage (or blog) from scratch using the R package 'blogdown'. I will first introduce some basic concepts of web construction and some essential tools ('rmarkdown' and 'git/github') that will be used in building websites with 'blogdown'. Then I will illustrate how to build a website step by step. By the end of the meeting, you are expected to have your own homepage created!

- **14 Feb. 2018**:  
**Presenters:** Eric Hare, Lawrence Mosley, and Nadia Antony  
**Title:** Creating Stylized Valentine's Day Pictures with Neural Art  
**Abstract:** In this special Valentine's Day addition of Graphics Group, we will begin by briefly discussing the formation of our data science non-profit called Omni Analytics Innovative Technologies Initiative (OAITI), consisting of some former members of Graphics Group. After this overview, we will learn the basics of how Neural Art and Stylized Transfer algorithms operate, and use a Shiny app we created to generate Valentine's Day images of us! Please bring your laptops so you can participate. Organization Link: https://oaiti.org/

- **8 Feb. 2018**:  
**Presenter:** Earo Wang  
**Title:** Calendar-based graphics for visualizing people's daily schedules  
**Abstract:** Calendars are broadly used in society to display temporal information, and events. This paper describes a new R package with functionality to organize and display temporal data, collected on sub-daily resolution, into a calendar layout. The function frame_calendar uses linear algebra on the date variable to restructure data into a format lending itself to calendar layouts. The user can apply the grammar of graphics to create plots inside each calendar cell, and thus the displays synchronize neatly with ggplot2 graphics. The motivating application is studying pedestrian behavior in Melbourne, Australia, based on counts which are captured at hourly intervals by sensors scattered around the city. Faceting by the usual features such as day and month, was insufficient to examine the behavior. Making displays on a monthly calendar format helps to understand pedestrian patterns relative to events such as work days, weekends, holidays, and special events. The layout algorithm has several format options and variations. It is implemented in the R package sugrrants. Paper: http://pub.earo.me/calendar-vis.pdf

- **31 Jan. 2018**:  
**Presenter:** Sam Tyner  
**Title:** "Recreating Historical Graphics with `ggplot2`".  
**Abstract:** At the turn of the 19th century, there seemed to have been a sudden interest in the United States in visualizing census data. There are some pretty amazing plots from this time in "The Statistical Atlas of the United States" and in the collection "African American Photographs Assembled for 1900 Paris Exposition" by W.E.B.  Du Bois. In this talk, I'll walk through the process of recreating a small sample of these visualizations using the NHGIS data finder and modern statistical computing tools. Slides [here](https://sctyner.github.io/historical-graphics-ggplot2.html). 

- **17 Jan. 2018**:  
**Presenter:** Heike Hofmann  
**Title:** "Colors like a Grey Sky Winter"  
**Abstract:** Gretchen Albrecht is a New Zealand painter famous for her use of color. Ben Marwick and Di Cook recently initiated an R package "gretchenalbrecht" as a way to collect and disseminate color palettes based on Gretchen Albrecht's paintings. We will investigate and discuss the package with a graphical twist. We will also discuss an avenue to create color schemes automatically.
