# README
## hw06 - Daniel Buonauro

# Analyzing Baseball Statistics with R: A Short Report
In this report, I used the Lahman library to analyze three aspects of baseball in R. 

In Part 1, I looked at ways to visualize homeruns. This includes the homerun leaders of the 21st century, the top homerun leaders of all time, and the relationship between homeruns and strikeouts.

In Part 2, I examined pitching data to visualize the top season ERA leaders in modern baseball history, strikeout to walk ratio, and the top strikeout leaders of all time.

In the 3rd and final part, I examined the relationship between run differential and winning percentage. 

Throughout the report, I put each statistic in the context of baseball history, to provide perspective and background information. This also aided in explaining why certain relationships occur. 

# Directory

## Useful Libraries
The main library used for this project is the Lahman library, an open-source collection of baseball statistics.

This can be installed as a package directly in your R console. If you've never installed this package before, the very first thing you'll want to do is run:
install.packages("Lahman"). Once this is installed, you can load the libraries, which in this project, are:

library(Lahman)
library(tidyverse)
library(dplyr)

The data files can be accessed directly from R once everything is installed and loaded. They can also be downloaded in full [Here](http://www.seanlahman.com/baseball-archive/statistics/)
At the above website, you can download all of the csv files in the database, if you prefer that method.

## Useful Files
The main data files I focused on from the Lahman library were:
Batting, Pitching, Teams, and Master. 

Assuming you installed the package and loaded the library, they can be accessed directly within R, without reading in a csv file. A full breakdown of the package can be found here:
[Lahman Library in R](https://cran.r-project.org/web/packages/Lahman/Lahman.pdf)

Files in Project:
[Baseball Short Report](baseball-short-report.Rmd) - R markdown file of a short report on baseball
[Rendered Markdown File](baseball-short-report.md) - Knitted markdown file of final report
[Figures](baseball-short-report-files/figure-gfm) - Folder with all visualizations

