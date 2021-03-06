--- 
title: "Introduction to Data Science with R for Biochemists"
author: "Jannik Buhr"
date: "2020-11-22"
site: bookdown::bookdown_site
documentclass: book
colorlinks: yes
github-repo: jannikbuhr/dataIntro19Master
bibliography: ["references.bib", "book.bib", "packages.bib"]
csl: chicago-author-date-de.csl
link-citations: true
description: "Introduction to Data Science with R for Biochemists"
editor_options: 
  chunk_output_type: console
---



# Prologue {-}

## Preparation for the Course

The course for master students will be held in English,
as the concepts covered will directly transfer to the
research you do and the papers you will most likely write
with the working language in this domain being English.

Before the course starts, please install both R and RStudio
from the following links and bring your laptops to class:

- [R: https://cran.r-project.org/](https://cran.r-project.org/)
- [RStudio: https://www.rstudio.com/products/rstudio/download/#download](https://www.rstudio.com/products/rstudio/download/#download)

Alternatively, if you can not install anything on your machine
or would like to use the computers (Mac) provided in our
classroom, sign up for [RStudio Cloud](https://rstudio.cloud/).
This way we are not dependent on the IT department
for the correct installation of R, RStudio and additional packages.

## Structure of the Course

- From January 10, 2020 to February 14 (6 fridays)
- Morning session from 10 ct to about 12:00.
- Afternoon session from 13:00 to about 15:00,
  but I will be there for further questions until max 17:00.

## Content

- Einleitung
  - Was ist dieses R?
  - R und RStudio
  - R als Taschenrechner
    - .R-Dateien (Skripte)
    - Variablen und arithmetische Operationen
  - Wir machen es uns gemütlich in RStudio
    - Einstellungen, Themes, etc.
    - Project-based Workflow
    - R Markdown
  - Das Tidyverse (und andere Packages)
  - Hilfe finden
    - Die Community
    - StackOverflow, GitHub, R4DS, Slack, Advanced R
- Arten von Daten
  - Daten in der Wildnis
  - Data in R
    - Vector, matrix, array, list, data.frame (tibble)
  - Data formats, Getting data into R
- Mein erster Plot
  - Das letzte Kuchendiagramm
  - Barplots
    - Base R vs ggplot2
    - The grammar of graphics
  - Scatterplots
- Tidy data
  - Prinzip
  - Daten importieren
  - Data-Wrangling mit dplyr and tidyr
- Funktionale Programmierung (vs OOP)
  - Funktionen schreiben
  - FP vs. OOP
  - Pure functions und Functional Programming
- Statistik
  - Basics: sd, var, mean, median, correlation
  - Histogramme, Verteilungen
  - p-values
    - t.test, Wilcoxon rank sum test, quisquared (ANOVA)
- Modelling and data fitting
  - Lineare Regression
  - Analyse
    - modelr, broom
    - $R^2$, rmse, residuals, plots,
  - non-linear regression
- Many models
  - nested datframes, list colums
  - map Funktionen

This table of content is structured thematically, not chronologically.

## Resources

### Tidyverse

- [R for Data Science](https://r4ds.had.co.nz/) [@wickhamDataScienceImport2017]
- [R4DS online Community](https://www.rfordatasci.com/)
- [RStudio Cheat Sheets!](https://www.rstudio.com/resources/cheatsheets/)
- [The Modern Dive](https://moderndive.com/) [@kim2019]
- [RStudio Education](https://education.rstudio.com/)

### R in general

- [Advanced R](https://adv-r.hadley.nz/) [@wickham2019]
- [Hands on Programming with R](https://rstudio-education.github.io/hopr/) [@grolemund2014]
- [R Packages](http://r-pkgs.had.co.nz/) [@wickham2015]
- [Data Visualization: A Practical Introduction](https://socviz.co/index.html) [@healy2018]
- [Graph Cookbook](http://www.cookbook-r.com/Graphs/) [@chang2013]

### Statistics

- [Intuitive Biostatistics](http://www.intuitivebiostatistics.com/) [@motulsky2017]
- [Statistics Done Wrong](https://www.statisticsdonewrong.com/) [@reinhart2015]

### Talks, Podcasts, Blogs

- [David Robinson, YouTube](https://www.youtube.com/user/safe4democracy)

### Misc

- [Unglaublich niedliche Illustrationen](https://github.com/allisonhorst/stats-illustrations) [@horst2019]
- [Happy Git with R](https://happygitwithr.com/)

## Other Resources

- [Tidytuesday](https://github.com/rfordatascience/tidytuesday)
- [Tips for Working with Images in Rmarkdown](http://zevross.com/blog/2017/06/19/tips-and-tricks-for-working-with-images-and-figures-in-r-markdown-documents/)

Made with the help of these amazing packages (plus documentation):
@R-base; @R-bookdown; @R-knitr; @R-rmarkdown; @xie2015

