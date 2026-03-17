U.S. House Election Data Analysis (2012–2022)
Overview
This project analyzes U.S. House election data from 2012 to 2022 to explore the relationship between district competitiveness and political ideology. Using R and the tidyverse suite, I cleaned and merged multiple large datasets, engineered key variables such as two-party vote share and ideological extremity (DW-NOMINATE scores), and conducted exploratory and statistical analyses. The project also includes simulation modeling to evaluate sampling variability and regression analysis to identify predictors of ideological extremity.

Key Features
-Data cleaning and merging of multi-cycle election and ideology datasets
-Variable engineering: vote share, district competitiveness, ideological extremity
-Statistical analysis including regression models
-Simulation modeling (1,000+ iterations) for confidence interval estimation
-Visualization of political trends across congressional cycles

Data sources: U.S. House election results, DW-NOMINATE scores

How to Use
-Clone this repository
-Open the R Markdown file (DATA3100_FINALEXAM_MANNS.Rmd) in RStudio
-Run the code chunks sequentially to reproduce the analysis and visualizations
-Knit to a HTML or PDF file

Insights
Districts with higher electoral safety (large vote margins) tend to elect representatives with more extreme political ideologies.
More competitive districts tend to elect more moderate representatives.
These findings emphasize the complex relationship between competitiveness and ideological polarization.
