# info550_hw

For my project, I will analyze the movies and ratings data. The csv files are stored in [Data Directory](https://github.com/stchen1128/info550_hw/tree/master/Data)
Please download these files for running the analysis. 

To start the analysis you will need to install some R packages. The requaired packages ccan be installed using R commands. 
```
library(readr)
library(tidyverse)
library(ggplot2)
library(data.table)
library(reshape2)
library(table1)
```
# Execute the analysis

To execute the analysis, from the project folder you can run 
title: "Simple example"
output:
```
Rscript -e "rmarkdown::render('Info550_project.Rmd')"
```
This will create a file called report.html output in your directory that contains the results.
