
## Introduction to R

Welcome to the Introduction to R class! 

To visit the site, go to [https://christopherdavisw.github.io/intro-to-r/](https://christopherdavisw.github.io/intro-to-r/). 

Note that this site is an abridged version of the full 6 course class taught at a government agency. It has been modified for public display.

The repository is laid out as follows: 

-  `/exercises/`: the R script (.R) and Quarto (.qmd) exercises that we will be working with throughout the course
-  `/lesson_code/`: the Quarto (.qmd) documents that are used to generate the html documents
-  `/_site/`: the html documents of the tutorials. Open up the `index.html` file to view the website and corresponding materials.  

### Prerequisites 

No prior R experience is assumed to take this course. Before attending, please remember to ensure that R and R Studio have been downloaded. 

Consider changing some options in RStudio before the class. Under the `Tools` -\> `Global Options` menu items, you can customize multiple options to your preferences. 

I recommend to: 

-  In `General`
  - Uncheck `Restore .Rdata into workspace at startup`\
  - Assign `Never` to `Save workspace to .Rdata on exit`\
- In `Appearance`
  - Play around with the Editor theme and decide on what you like
- In `R Markdown`
  - Show output preview in `View Pane`
  - Uncheck `Show output inline for RMarkdown documents`
  
### What is R? 

R is a free, open source programming language for statistical computing and graphics. It is known for robust visualization capabilities and a growing library of statistical and analytic methods. 

R has an exensive user base that benefit from the libraries that others have created through the Comprehensive R Archive Network (CRAN). CRAN is a network of FTP and web servers that store versions of code and documentation for R. 

R is maintained by the [R Foundation](https://www.r-project.org/foundation/), a non-profit organization that supports the continued development of R for satistical and computational research. 

### What is RStudio? 

RStudio is a free integrated development entironment (IDE) for R, created by the private organization Posit (formally RStudio). An IDE is a graphical user interface that consolidates different features helpful for writing code into one application. Other examples of IDEs include SAS Enterprise Guide, VSCode, Jupyter, or Spyder. 

Which IDE you might choose might depend on the programming language and personal preference. However, I recommend using RStudio forR - it has the most built out features for programming in R. 

### Why R? 

- **Open Source**: R is made freely available and may be redistributed and modified by anyone. 
- **Popular**: R is one of the most popular statistical tools for data analysis. Given its growing popularity over paid softwares like SAS or Stata, future employees will likely know R or have some experience with it. 
- **Excellent visualization tools**: R excels at data manipulation, statistical analysis, machine learning, and reproduciability, but it is probably best known for its graphics. R visualizations are the gold standard for reproducible data visualizations. 
- **Flexibility**: Given its open source nature, R makes it easy to build off of work that others have already done. Over the past three decades, users have been contributing to the R ecosystem, which has allowed for the expansion of libraries and functions to do nearly any kind of data analysis task. If you have a data analysis need, it is likely that someone else has had a similar need and written code already to complete it. 
- **Reproducible**: Like most programming languages, R is fully reproducible and encourages workflows to be entirely reproducible. This means that you are able to run through the entire workflow, start to finish, and achieve the same results. 

### Other Resources

- [R for Data Science](https://r4ds.hadley.nz/) by Garret Grolemund and Hadley Wickham. This books is the gold standard for R programming. Co-written by the creator of `tidyverse` and `ggplot2`, this free book goes over the core concept of `tidy` data and how to work with tidy data in R. 
- [ggplot2: Elegant Graphics for Data Analysis](https://ggplot2-book.org/) by Hadley Wickham. This book provides a more theoretical and comprehensive understanding of the decisions underlying the construction of ggplot2. 
- [Text Mining with R: A Tidy Approach](https://www.tidytextmining.com/) by Julia Silge and David Robinson. This book provides a comprehensive overview of text mining in R. 
- [Geocomputation with R](https://r.geocompx.org/adv-map) by Robin Lovelace, Jakub Nowosad, and James Muenchow. This book provides tutorials for how to do various spatial operations in R, including analyzing and modeling geographic data, mapping (both static and interactive), and statistical operations. 
- [Hands-On Machine Learning with R](https://bradleyboehmke.github.io/HOML) by Bradley Boehmke and Brandon Greenwell. This book provides an overview of machine learning in R. 
- [Cheat Sheets](https://posit.co/resources/cheatsheets/) by Posit (formally RStudio). These cheat sheets are a great resource to provide an overview of relevant functions in many commonly-used packages. 
- [HarvardX: Data Science: Visualization](https://www.edx.org/learn/data-visualization/harvard-unisverity-data-science-visualization). This is an online course that goes over basic data visualization principles and how to apply them using ggplot2. 
