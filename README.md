# Used-Car-Market-Analysis
This repository contains a collaborative research paper as well as its R code that analyzes car performance data from a [Corgis dataset](https://corgis-edu.github.io/corgis/csv/cars/). Our team looked at how various automotive specifications influence consumer preferences. Using data analysis and visualizations in R, we sought to help consumers make informed decisions based on their needs. 

Contributors:
Shane Fitzpatrick, Jacob Spano, Joseph Cicero, Leo Morifuji, Christian Cuevas

My Contributions: I focused primarily on data preparation, visualization, and statistical analysis regarding car specifications.

1. Data Preparation and Cleaning:
Imported the dataset and eliminated unnecessary columns.
Examined dataset structure and verified data quality.
2. Feature Engineering:
Utilized the stringr package in R to extract numeric cylinder count from the "Engine.Information.Engine.Type" column.
Converted extracted cylinder counts to numeric format, facilitating further analysis.
3. Statistical Analysis and Visualization:
Computed the average horsepower for each cylinder count.
Created visualizations in ggplot2 showing a clear relationship between cylinder count and horsepower.
Conducted correlation analyses between cylinders and horsepower, providing insights into vehicle performance.
The R Notebook (Fitzpatrick_Cars.Rmd) includes detailed code demonstrating these contributions, which directly supported key findings presented in our research paper (see Appendix 4: Visualization + Code).

