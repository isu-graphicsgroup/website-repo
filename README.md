# Talks
Talks at the graphics working group

- **17 Sept 2020**  
**Presenter**: Emily Robinson and Susan Vanderplas    
**Title**: Comparing Containment Measures by Epidemiological Effects of COVID-19  
**Abstract**: Log scales are often used to display data over several orders of magnitude within one graph. During the COVID pandemic, we've seen both the benefits and the pitfalls of using log scales to display data. In this week's graphics group, we will test out an experiment designed to assess perceptual and cognitive biases in graphical displays of exponentially increasing data.  

- **10 Sept 2020**  
**Presenter**: Yumou Qiu    
**Title**: Comparing Containment Measures by Epidemiological Effects of COVID-19  
**Abstract**: We estimate and assess the effective reproduction numbers of COVID-19 for 25 countries using an extended SEIR model. By comparing the countries' reproduction curves over the first 4 weeks of the start of local transmission, we identify the successful strategies which may be useful for other countries to control the pandemic and the possible second wave. The study shows significant benefits in taking containment measures sooner with vigorous enforcement in reducing the effective reproduction number. An analysis on the weekly reduction rates in the reproduction number shows no positive correlation between the weekly reduction rates and the lead times since the outbreak in China. The absence of a lead-time advantage could be a key lesson for controlling future pandemics. Graphic tools have been developed to track the reproduction for each states in the US.

- **3 Sept 2020**  
**Presenter**: Ashirwad Barnwal  
**Title**: Crash Data Visualization Using Leaflet  
**Abstract**: In the recent years, RStudio has ported Leaflet, a widely used open-source JavaScript library for creating interactive maps, to R as a package called leaflet and has made it possible to create maps in R using the familiar ggplot2 style syntax. Additionally, a bunch of Leaflet plugins that extend Leaflet's functionalities have also been ported to R by the community members, enabling users to create a variety of maps with ease. In this talk, I will demonstrate the use of the leaflet R package for visualizing fatal crash data for the state of Iowa in many different ways, such as heat maps, choropleth maps, etc. Towards the end of the presentation, I will also introduce some data visualization software such as kepler.gl and deck.gl that support large scale data and provide an intuitive interface to creating geospatial visualizations without any coding.

- **27 Aug 2020**
**Presenter**: Yawei Ge    
**Title**: The ggpcp for Generalized Parallel Coordinate Plot  
**Abstract**: ggpcp is an R package developed for the generalized parallel coordinate plots which are a useful set of graphics for visualizing data with more than 2-dimensions. It is generalized in the sense of combining numeric and categorical variables together while keeping the ability to track each observation. It helps to see some interesting aspects of the "high"-dimensional data.

- **24 Apr. 2020**  
**Presenter**: Kiegan Rice  
**Title**: Managing Computational Reproducibility in a Shifting R Package Landscape  
**Abstract**: Most modern data analysis requires the use of statistical software. The results of data analysis then rely on the underlying software utilized and the actions applied to data. R, one of the most widely-used statistical softwares for data analysis, relies on user-developed "packages" for many data science and data analysis tasks. These packages are subject to change over time, which can impact computational reproducibility efforts, as well as frustrate users who are left to hunt down problems in broken code. We propose an adaptive approach to computational reproducibility in R that focuses on identifying changes in packages over time. In this talk, I will discuss some prior approaches to achieving computational reproducibility in R and present our proposed framework for managing computational reproducibility. I will also demonstrate the software tools we are developing to assist users as a part of the "manager" package through two R package case studies.  

- **17 Apr. 2020**  
**Presenter**: Susan Vanderplas  
**Title**: Computer Vision, Machine Learning, and… Jellybeans?  
**Abstract**: While eating jellybeans isn’t as hazardous in the real world as in the Harry Potter universe, it can still be unexpectedly interesting: you think you have a few raspberry flavored beans, but how do you know one of them isn’t actually cinnamon? In an effort to combat this anxiety-inducing problem, we collected several sets of image data. I’ll talk about how we applied computer vision techniques to isolate the beans and extract useful features from the images (as well as the associated challenges). I’ll also show the results from the predictive models we developed, which have a classification accuracy of ~92% and significantly improve on my classification accuracy, which is about 10%. Note: My original plan was to give this talk in person and bring the jelly beans as a snack. While I can’t do a live demo, because my specimens are stranded on campus, you may still find it entertaining to acquire some jellybeans to munch. 🙂  

- **10 Apr. 2020**  
**Presenter**: Katherine Goode  
**Title**: An Overview of Visualization Techniques for Explainable Machine Learning    
**Abstract**: Machine learning models are excellent predictors, but it is impractical to interpret many of these models. Despite this impracticality, it is important to be able to explain predictions to assess and validate models. As a result, a field of research has recently developed in the explainability of machine learning models. In this talk, I will provide an overview of explainable machine learning with a focus on visualization methods. I will discuss philosophies of "explainability", model agnostic and model specific visualization methods, and code for creating some of the visualizations in R. I hope that this talk will provide listeners with an introduction to explainable machine learning and resources to learn more if desired.

- **03 Apr. 2020**  
**Presenter**: Anabelle Laurent and Xiaodan Lyu  
**Title**: Create a personal website with Blogdown like what we did  
**Abstract**: A personal website is an incomparable platform for building your online profile and showcasing your amazing work (research or other interesting stuff). Blogdown is a popular R package developed for producing a static website from R Markdown documents. Even if you are currently using GitHub pages for your personal website, you might be interested in this talk after reading [this post](https://yihui.org/en/2017/06/netlify-instead-of-github-pages/) by Yihui. In this talk, we’ll introduce some tips and tricks for building a personal website with Blogdown based on our own experience. This talk is expected to be a hands-on workshop (something fun and meaningful to do during quarantine). Participants would have a chance to build their own “baby” website and deploy the website online with Netlify!
 
    Preparation: It would be helpful if you register a [Netlify](https://www.netlify.com/) account and master some basics about GitHub and Markdown in advance. You can be even more prepared and start to work on your own website now by following [this tutorial](https://annielyu.com/2020/01/12/blogdown-website/) written by Annie. That’s how Anabelle created [her own website](https://www.anabellelaurent.com/)!

- **27 Mar. 2020**  
**Presenter**: Eryn Blagg  
**Title**: Detecting Wear Among 3D Shoe Objects  
**Abstract**: Shoe analysis is frequently used as part of forensic analysis. However, dealing with time, the wear of the sole and its features can be difficult. Here we present a method for extracting the wear between two 3D scans of a single shoe after some amount of use, using an iterative alignment process, in order to discover matching methods after a large amount of wear. Initial processing transforms a Standard Triangle Language (stl) 3D object, into a triangle mesh before alignment. Alignment between the two meshes is accomplished using, principal component analysis to initially align the mesh objects onto the same plane, followed by an iterative closest point comparison. After alignment, surface differences are measured and compared, in order to define wear. This method has been used to successfully compare wear in a variety of brands including Nike, Adidas, and Sony for wear patterns from new up to 8 months old. The methods presented here allows for more accurate wear analysis which can help the forensic community match shoe print analysis, even after wear.  

- **12 Mar. 2020**  
**Presenter**: Di Cook  
**Title**: A slice tour for finding hollowness in high-dimensional data  
**Abstract**: Taking projections of high-dimensional data is a common analytical and visualisation technique in statistics for working with high-dimensional problems. Sectioning, or slicing, through high dimensions is less common, but can be useful for visualising data with concavities, or non-linear structure. It is associated with conditional distributions in statistics, and also linked brushing between plots in interactive data visualisation. This talk will describe the simple approach for  slicing in the orthogonal space of projections obtained when running a tour, thus presenting the viewer with an interpolated sequence of sliced projections. The method has been implemented in R as an extension to the tourr package, and can be used to explore for concave and non-linear structures in multivariate distributions.

    If you want to follow along with the talk and run demos yourself, install the tourr package from github:

    remotes::install_github("ggobi/tourr")

    and the geozoo package from CRAN.

    This is joint work with Ursula Laa, German Valencia, Andreas Buja  

- **06 Mar. 2020**:  
**Presenter**: Heike Hofmann  
**Title**: Historical Firsts and Some Classics (II)   
**Abstract**: In this talk we are going to re-visit some of the historical firsts as well as some of the classical graphics. William Playfair - Scottish engineer and British secret agent gave us a few of those firsts: line charts, barcharts, and also, alas, pie charts. Looking at graphics created at a time when visualizing out-of-the-box was the only way to go, hopefully also allows us to break through our box and inspires us to visualize things a little differently.

- **28 Feb. 2020**:  
**Presenter**: Kiegan Rice  
**Title**: Political Data Journalism: A History of Election Graphics in the U.S.   
**Abstract**: In today's day and age, U.S. society is inundated with information about politics and elections from all around the world. Particularly in a U.S. Presidential election year, the news is full of predictions, results, and stories about the primary and Presidential elections. The key to effectively communicating a message about election data lies in graphical presentation of statistical information. In this talk, I will present a history of innovation in election graphics including results, predictions, voter turnout, and campaigns and advertising. Slides can be found here (with lots of links to news articles).  

- **21 Feb. 2020**:  
**Presenter**: Ganesh Krishnan  
**Title**: Interactive graphical diagnostics as visual model explanations for forensic toolmark examination  
**Abstract**: Forensic firearms examiners subjectively compare two bullets, using visual examination to make a determination about whether the bullets are similar enough to have originated from the same weapon. Recently, there has been increased demand for quantitative, objective similarity assessment methods for many types of forensic evidence, including bullets. In this talk, we discuss visualizations for a machine learning algorithm capable of matching striation marks on fired bullets. We describe the steps of the algorithm and summary visualizations used at each stage of the data science pipeline, and present an application which wraps the visualizations into an interactive exploration tool. This application can be used to explain and interpret results from the machine learning algorithm, but it is also an effective tool for analysis of the model’s strengths and weaknesses when examining new (and sometimes messy) data. Using a sequence of case studies originating from a set of 5 fired bullets, we describe the effectiveness of the application for model exploration. Finally, we evaluate the tool’s design with respect to its ability to bridge the gap between experts in data science and experts in firearms examination.

- **14 Feb. 2020**:  
**Presenter**: Kiegan Rice and STATCOM  
**Title**: STATCOM x Graphics Group: A Data Viz-a-thon  
**Abstract**: National Student Exchange (NSE) is a non-profit consortium of 165 colleges and universities throughout the United States, Canada, Guam, Puerto Rico, and the U.S. Virgin Islands. NSE provides opportunities for collegiate study away and student exchange among member campuses. NSE recently reached out to Iowa State's STATCOM chapter for help visualizing survey data. We are hoping to leverage the awesome graphical minds of ISU's Graphics Group to accomplish two things: (1) have a discussion about visualizing "feedback" survey data, including Likert scale data and qualitative text response data, and (2) have the group spend some time with the data, making visualizations! The (mostly) cleaned data and a description file can be found in the CyBox linked here. You are welcome to look at the description and data and work on visualizations ahead of time. However, there is no need to do so before the meeting if you don't have time.

- **7 Feb. 2020**:  
**Presenter**: Ian Lyttle  
**Title**: Conference Roundup  
**Abstract**: This will presentation be a grab-bag of three topics:
 
    1. A re-enactment of my rstudio::conf() talk “Small Team, Big Value: Using R to Design Visualizations”.

    2. Discussion on rstudio::conf() itself.

    3. A preview of what I plan to submit to UseR! (St. Louis), as a lightning talk – the package I worked on at Uncoast Unconf 2019: {steward}, to help you to document datasets.  I’d like to see what the group might find useful for this package, as I work on it between now and July.  https://uncoast-unconf.github.io/steward/

- **24 Jan. 2020**:  
**Presenter**: Heike Hofmann  
**Title**: Historical Firsts and Some of the Classics  
**Abstract**: In the time of abundant and sometimes questionable charts by software products we shall not name, it is easy to forget that not too long ago data could not be summarized readily and shown in charts produced with a mere click of a mouse or a few lines of instructions. In this talk we are going to re-visit some of the historical firsts as well as some of the classical graphics. William Playfair - Scottish engineer and British secret agent gave us a few of those firsts: line charts, barcharts, and also, alas, pie charts. By looking at graphics created at a time when visualizing out-of-the-box was the only way to go, hopefully also allows us to break through our box and inspires us to visualize things a little differently. There might be cookies … but if not, there will be cake :)   

- **5 Dec. 2019**:  
**Presenter**: Eryn Blagg   
**Title**: Dealing with 3D  
**Abstract**: Dealing with 3D data adds a whole new complexity to the simplest of projects, now there is another plane to deal with. Now that 3D scanners and imaging are even more available, the need to work with 3D data is even more relevant. In this talk, we will discuss different ways to not align 3D data, and some possible ways to align them. And maybe some fun pictures along the way.  

- **21 Nov. 2019**:  
**Presenter**: Susan VanderPlas and Heike Hofmann  
**Title**: Can you trust your eyes?'  
**Abstract**: We use phrases all the time - "plain as day", "right in front of you" - that suggest our visual system is infallible. When creating graphics, it is important to know when that assumption does not hold. In this talk, we'll discuss different pitfalls, optical illusions, and bugs that affect the visual system. 

- **14 Nov. 2019**:  
**Presenter**: Eric Hare and Lawrence Mosley  
**Title**: 'Modern Dimension Reduction and Visualization Techniques using UMAP'   
**Abstract**: One of our fundamental tasks as data scientists, especially given our focus on statistical graphics, is to take a potentially large and messy dataset, and extract meaningful relationships and patterns from it. One such approach to this is dimension reduction, the task of reducing the number of variables in a dataset to a much smaller number that still captures the structure of the original data well. A commonly used technique for dimension reduction is PCA, or Principal Component Analysis, where transformations of the variables are made in order to extract a set of uncorrelated principal components from the data. However, since PCA focuses of deriving latent linear features, when applied to data sets with global non-linear relationships, the 2-D projections produced will fail to capture salient aspects of the variance-covariance structure.

    In this talk, we will cover a newer dimension reduction technique called UMAP, or Uniform Manifold Approximation and Projection. Compared to PCA, UMAP is significantly more flexible, and compared to other visualization techniques like t-SNE, UMAP is significantly faster and more optimized. UMAP also produces a reduced-dimension dataset that has been shown to perform extremely well in statistical models. We will illustrate this by showing initial work on building a deep learning model that can read clock faces in order to tell time!

- **07 Nov. 2019**:  
**Presenter**: Haley Jeppson and Ian Lyttle  
**Title**: 'ggvega: A ggplot2 to Vega-Lite translator'   
**Abstract**: The ggvega package was created to translate from ggplot2 to Vega-Lite, inspired by the capability the R package plotly provides to translate from ggplot2 to plotly. In this talk, we will discuss the motivation and design philosophy behind ggvega as well as some of the roadblocks we encountered along the way. We will conclude with a demonstration of some fun use-cases.  

- **31 Oct. 2019**:  
**Presenter**: Katherine Goode  
**Title**: 'gganimate (with a spooky twist)'   
**Abstract**: gganimate allows for the animation of ggplot2 graphics. The package has been around for a while, but it has been updated to allow for easier transitions from static ggplot2 graphic to animated versions. This talk is meant to be an interactive tutorial on how to use the updated version of gganimate. You are encouraged to bring a laptop to follow along. Since the talk will be given on Halloween, spooky datasets will be used to demonstrate the functionality of gganimate.  

- **24 Oct. 2019**:  
**Presenter**: Xiaodan Lyu  
**Title**: 'Interactive Data Visualization in Production'   
**Abstract**:  Interactive data visualization (dashboards) are often used to show important measures or key performance indicators (KPI) at a comprehensible level of aggregation and are continuously updated as new data are added to the database. In this talk, I'll present a full procedure of developing a dashboard from data engineering to data visualization taken from my summer internship as a visualization analyst at Autodesk. Some recommended practices such as choosing appropriate charts and designing effective dashboards will be discussed. I'll also share my experience in communicating statistical models with non-tech decision-makers.  

- **17 Oct. 2019**:  
**Presenter**: Fan Dai  
**Title**: 'Three-dimensional Radial Visualization of High-dimensional Continuous or Discrete Datasets'   
**Abstract**: We develop methodologies for 3D radial visualization of high-dimensional datasets. Our display engine is called RadViz3D and extends the classic RadViz that visualizes  multivariate data in the 2D plane by mapping every record to a point inside the unit circle. The classic RadViz display has equally-spaced anchor points on the unit circle, with each of them associated with an attribute or feature of the dataset. RadViz3D obtains equi-spaced anchor points exactly for the five Platonic solids and approximately for the other cases via a  Fibonacci grid. We show that distributing anchor points at least approximately uniformly on the 3D unit sphere provides a better visualization %with less effects of ordering than in 2D. We also propose a Max-Ratio Projection (MRP) method that utilizes the group information in high dimensions to provide distinctive lower-dimensional projections that are then displayed using Radviz3D. Our methodology is extended to datasets with discrete and mixed features where a generalized distributional transform is used in conjunction with copula models before applying MRP and RadViz3D visualization.

- **10 Oct. 2019**:  
**Presenter**: Yihui Xie  
**Title**: 'The fun with CSS and JavaScript, joined by the simplicity of Markdown'      
**Abstract**: I briefly talked about pagedown at rstudio::conf 2019 (https://resources.rstudio.com/rstudio-conf-2019/pagedown-creating-beautiful-pdfs-with-r-markdown-and-css) but did not explain the details due to the length of the talk. This time I will talk about it in depth. I will also demonstrate my last R package rolldown for storytelling with R Markdown (https://github.com/yihui/rolldown).  

- **3 Oct. 2019**:  
**Presenter**: Adam Loy  
**Title**: 'Exploring automatic evaluation of statistical graphics'    
**Abstract**: We live in a world where both statistical learning models and computer visions models allow many tasks to be automated, ranging from detecting fraudulent credit card transactions to self-driving cars. Based on these advances, it seems reasonable to ask whether we can automate the evaluation of common statistical graphics, such as residual plots.

    Statistical graphics are commonly used for exploratory data analysis and model checking, however,  they are often criticized due to the subjectivity involved in their interpretation. Seasoned analysts have built up their intuition over years to be able to interpret single statistics graphics and express their uncertainty related to their decisions. Less seasoned analysts may struggle with interpretations or face increased skepticism.  Recently, a protocol that puts graphics into an inferential framework has been developed, allowing analysts to understand the extent to  which perceived structure in a plot occurs by chance. This inferential framework treats plots as statistics, which casts graphics in a framework amenable to automatic evaluation.

    This talk will review  the development and implementation of the lineup protocol for visual inference, discuss its applications, and explore how statistical learning models and computer vision models might be used to automatically assess plots.

- **26 Sep. 2019**:  
**Presenter**: Yawei Ge  
**Title**: 'Generalized Parallel Coordinate Plot with ggpcp'    
**Abstract**: Parallel coordinate plot is well used to show data with dimensions more than three, which provides an elegant way of displaying data with such many dimensions by representing each variable by an axis. Parallel coordinate plot works well with continuous variables but not categorical variables. Some improved versions of parallel coordinate plots were introduced to show categorical variables in a similar way as in numeric variable cases, such as parallel set plots, hammock plots and common angle plots. But these kinds of parallel coordinate plots don't provide a good way to combine numerical and categorical variables in a single plot. We introduce the generalized parallel coordinate plot to include both types of variables in a single plot and provide a set of solutions to the problems coming in the process. We also introduce the package ggpcp to implement the generalized parallel coordinate plot, which is built under the ggplot2 framework.

    See the GitHub repo for ggpcp: https://github.com/yaweige/ggpcp

- **19 Sep. 2019**:  
**Presenter**: Kiegan Rice  
**Title**: 'Visualizing Variability in Bullet Scans'    
**Abstract**: The field of forensic firearms analysis involves the visual comparison of patterns engraved on bullets by the barrel of a gun. In recent years, computer vision techniques have been developed to complete these visual comparisons in an automated fashion. These methods, such as the one developed by Heike Hofmann and Eric Hare, are based on high-resolution images of bullet lands. We collected repeated scans of a small set of bullets in order to study the variability introduced by human involvement in the scanning process. Visualizing the variability in these data has proven to be a very interesting challenge! I will briefly detail the bullet matching process and our variability study, and share some ongoing attempts to effectively visualize variability in the data.

- **12 Sep. 2019**:  
**Presenter**: Heike Hofmann  
**Title**: 'Boxes and Pies - The Statistical Atlas of 1870'    
**Abstract**: The Statistical Atlases of 1870 to 1890 are wonderful sources of statistical graphics, created in a time when conventions for statistical graphics were still very much in flux. We will be looking at some examples of visualizations from the 1870s - some of which will look very familiar, discuss the charts from their cognitive perspective, and look into re-designs based on available Census data.

    There will be cake - at the point of writing, the baker is not certain about pie versus box shape.

- **05 Sep. 2019**:  
**Presenter**: Susan Vanderplas  
**Title**: 'The Power of Visual Inference'    
**Abstract**: I will talk about visual hypothesis testing using lineups, including how we model the process of choosing  a plot from a lineup, different types of lineups, and how we estimate a lineup's difficulty. There will also be a lot of pictures of puppies!

- **29 Aug. 2019**:  
**Presenter**: Everyone  
**Title**: 'Graphics Group on "Vacation"'    
**Abstract**: While summer may be a time to relax and enjoy the sun, it is also a time to enjoy working on research without the stress of classes (possibly while also sitting outside and basking in the sun). In this talk, returning graphics group participants will tell about summer research projects, conferences and workshops attended, and internship experiences. We hope this will allow everyone to learn about the work done by others, provide some inspiration going into the fall semester, and allow new attendees to get an idea of the breadth of work done by individuals in the graphics group.

- **12 Apr. 2019**:  
**Presenter**: Eric Hare    
**Title**: "Building a Trivia Bot that Outperforms Humans with Google’s BERT"       
**Abstract**: One of the first things we need when we build statistical models is a rich set of training data. Creating a labeled training dataset is feasible when the dataset has hundreds, or maybe even thousands of rows. But the top-performing models on many machine learning tasks do best with millions or even billions of examples. How do we automatically build a large training set with billions of examples? Enter BERT, Google’s new Natural Language Processing (NLP) language model. BERT exploits the key fact that the internet is home to massive amounts of unstructured text data that we can easily incorporate into an NLP model. But it goes a step further: BERT automatically masks particular words in sentences, and uses this to create a training dataset automatically. For example:  
Input: The woman went to the [MASK1]. She bought a [MASK2] of milk.  
Labels: [MASK1] = store; [MASK]2 = gallon  

    In this talk, I will describe at a high level the BERT language representation model, and how it can be used to train state-of-the-art NLP models. I will then demo the question-answering (trivia) bot that we’ve trained with BERT which, by some metrics, can out perform humans on particular question-answering challenges.   

- **5 Apr. 2019**:  
**Presenter**: Chance Johnstone    
**Title**: "Data Visualization in Sports: A Case Study with NCAA Women’s Hockey Goaltending"       
**Abstract**: One of the more recognizable terms associated with analysis in sports is “sabermetrics”. Made famous in part by Bill James in the 1970s, and executed with some success by Billie Beane and the 2001 Oakland Athletics, it has changed the way people view sports. Sports are no longer just about intuition. Following this paradigm shift, the use of analytics has grown tremendously within Baseball, and has even made its way into other sports, most prominently with Football and Basketball. Ideas like “win-shares”, “plus-minus”, “expected goals” have permeated sports culture.
During this session we will focus our discussion on analysis within a Hockey scope. We will begin by identifying and discussing current literature on statistics as it relates to the sport, and follow that with the introduction of a tool that utilizes the googlesheets() and shiny() packages, among others, to provide visualizations and metrics related to NCAA Women’s Hockey. Specifically, the tool provides training insight, and game-to-game decision support related to the goaltender position.   

- **15 Mar. 2019**:  
**Presenter**: Samantha Tyner    
**Title**: "What happens at an unconf should not stay at an unconf"       
**Abstract**: Last weekend, I attended the Chicago R Unconference, a two day "hackathon" style event for R users and developers. In this talk, I'll discuss the structure and function of an R unconf, and I'll present my project with Angela Li and many others, the Unconf Toolbox, a Github organization providing structure and guidance so that future organizers have a guide for organizing an unconf.    

- **08 Mar. 2019**:  
**Presenter**: Discussion    
**Title**: "The Re-Emergence of Emotional Appeals in Interactive Data Visualization"
**Abstract**: This week we will be discussing "The Re-Emergence of Emotional Appeals in Interactive Data Visualization" by Charles Kostelnick. The purpose statement of the article follows. "I argue that emotional appeals, prevalent in charts and graphs during the later nineteenth century but largely dormant since then, have rapidly re-emerged in contemporary data visualization. Changing the relationship between designer and user, this new form of data design has intensified the affective impact of data displays by eliciting emotions ranging from excitement and empathy to anxiety and fear."  

- **01 Mar. 2019**:  
**Presenter**: Katherine Goode    
**Title**: "An Application of LIME to a Random Forest Model"       
**Abstract**: Random forests are known for their accurate predictive abilities, but they are a part of the family of machine learning models that lack interpretability. A technique called LIME was developed to provide local interpretations for black-box predictive models. In this talk, I will explain the LIME procedure and show an application of LIME to predictions from a random forest model fit to a bullet matching dataset. I will present a Shiny app I created to view the LIME explanations. Additionally, I will discuss the issues that I have encountered while working with LIME, some of the attempts at a solution, and future directions for my research.  
**Slides**: https://goodekat.github.io/presentations/graphics_group/03-applying_lime_to_random_forest/slides.html  

- **15 Feb. 2019**:  
**Presenter**: Susan VanderPlas    
**Title**: "Truthiness: Going with your gut"       
**Abstract**: Graphics are incredibly useful information conduits, but what effects do extraneous graphics have on someone's ability to evaluate factual statements? In this talk, I'll discuss the "truthiness effect" and talk about what pictures and charts have to do with Stephen Colbert and science communication. I'll discuss results from two cognitive psychology studies detailing the truthiness effect and some initial data from a study I'm conducting to explore whether this effect extends to statistical charts and graphics.  

    Slide link: http://srvanderplas.github.io/Presentations/GraphicsGroup/201902-Truthiness/slides.html#1  

    Papers:  
    McCabe, D. P., & Castel, A. D. (2008). Seeing is believing: The effect of brain images on judgments of scientific reasoning. Cognition, 107(1), 343–352.  
    Newman, E. J., Garry, M., Bernstein, D. M., Kantner, J., & Lindsay, D. S. (2012). Nonprobative photographs (or words) inflate truthiness. Psychonomic Bulletin & Review, 19(5), 969–974.  

- **08 Feb. 2019**:  
**Presenter**: Ian Lyttle and Haley Jeppson    
**Title**: "rstudio::conf(2019L) %>% filter(favorites)"       
**Abstract**: We were very fortunate to attend rstudio::conf() last month in Austin; this will be a presentation of our highlights. We will each describe three of our favorite talks (narrowing down to three each was the *most* difficult part). We were not the only graphics-group members there, so we will also invite extemporaneous contributions from our colleagues, as they see fit.

    tl;dr: It was super-useful and inclusive.    

- **01 Feb. 2019**:  
**Presenter**: Sam Tyner, Kiegan Rice, Haley Jeppson, Katherine Goode, and Miranda Tilton    
**Title**: "Graphics for the LAS Status of Women Report"       
**Abstract**: In this presentation, Sam Tyner, Kiegan Rice, Haley Jeppson, Katherine Goode, and Miranda Tilton will show off their ggplot2 skills and demonstrate how good statistical graphics can help the Iowa State community. As a member of the ISU UCW committee, Sam saw an early draft of the "LAS Status of Women Report." The professor heading the report, Maggie LaWare, asked for input on the graphs in the report, as the current figures were her first foray into making figures in Excel. As a ggplot2 aficionado, Sam volunteered to help out, and thought it would be fun to recruit some others onto the project. Upon seeing the graphics, Kiegan, Haley, Kat, and Miranda jumped at the opportunity to help with the project. We'll each walk through the graphs (or tables) we were tasked with beautifying, and describe how we used our visualization skills acquired in Graphics Group and elsewhere to create striking graphics that accurately represent the status of women in LAS at ISU.  

- **25 Jan. 2019**:  
**Presenter**: Heike Hofmann    
**Title**: "Colors like a Grey Sky WinterR"       
**Abstract**: To kick off graphics group this semester, we will start with colors and some color themes. Gretchen Albrecht is a New Zealand painter famous for her use of color. Ben Marwick and Di Cook initiated an R package "gretchenalbrecht" as a way to collect and disseminate color palettes based on Gretchen Albrecht's paintings. We will investigate and discuss the package with a graphical twist. We will also discuss an avenue to create color schemes automatically.

    There will be baked goods! 

- **07 Dec. 2018**:  
**Presenter**: Eric Hare    
**Title**: "It’s like magick! Automating image processing and graphics design in R"
**Abstract**: Most of us are quite familiar with the advantages of automating an analysis using R - If we change the data or tweak some parameters, we need only rerun the script in order to produce new results. But one task that we don’t often think of automating is graphics design and image processing. Maybe we need to combine two images side-by-side, or manipulate the dimensions of a set of images to fit some journal convention. We might choose to open Photoshop or some other image editing software in order to accomplish this. As it turns out, the magick package makes many of these tasks both simple and easy to automate.

    In this talk, we will introduce the magick package and its capabilities, and use it to modify, transform, and add effects to images. We will then discuss one of its specific capabilities, OCR (Optical Character Recognition) and play a game we’ve created in Shiny using OCR. You may wish to install magick in advance by following the steps at the beginning of the Vignette here: https://cran.r-project.org/web/packages/magick/vignettes/intro.html  
    
    Slides available at: https://omnianalytics.io/isu-graphics/magick/

- **30 Nov. 2018**:  
**Presenter**: Miranda Tilton   
**Title**: "CoNNOR: Convolutional Neural Network for Outsole Recognition"     
**Abstract**: A convolutional neural network (CNN) is a tool for deep learning that uses hierarchical networks of hidden layers to learn patterns in a set of training images and detect the presence of similar features in new images. Shoe outsoles are well-suited to classification with CNNs as they often contain distinct and well-defined shapes, such as circles and quadrilaterals, as well as text and textures. Automatic classification of outsole features can be used to identify the make and model of a shoe, speed up database searches, or determine the relative frequency of a particular outsole or set of features within specific populations. This talk will give an overview of how CNNs classify images, explain how pre-trained CNNs can improve performance on new classification tasks, and discuss the challenges of applying these techniques to approximately 2,000 images of shoe outsoles of various types, brands, and sizes.  

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
