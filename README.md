# IMDB-DATA-VISUALIZATION PROJECT
---
### Data set consits of top 100 performing movies from the year 2010 to 2016
## Major Objectives
* Performed **data manipulation, analysis, and visualisation** to get various insights about the data
* Finding most **popular and unpopular genre** among the top 1000 Voters
* Analysis on **US vs non-US** voters responses
* Finding the most popular trio interms of certain important features
* visualisation of results using different inbuilt packages 
## Code and Resources Used
---
**Python Version:** 3.7 <br>
**Packages:** pandas, numpy, seaborn, matplotlib

## Data Manipulation
---
After reading the data and inspecting further we found that there are certain columns which needs data manipulation so we did the following steps.
* Numeric columns like budget and gross are too big compromising its readability, converting **$ to million $**
* creating `profit` column with dufference from `gross` and `budget` column

## Data visualization
---
* plotting the results obtained by categorizing different `genres` to  `CNT`
* Using **heatmaps** to find the correlation between different gender votes aftecting the rating
* Outlier Analysis using **box plots** to find the votes casted by under 18 age group for R- rated movies
