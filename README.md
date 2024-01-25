# Dine-Out-Patterns
Cpts475

This repository contains the code for a Data Science final project, focusing on analyzing movements and visit durations around restaurant locations. The project utilizes R and several libraries, including tidyverse, sf, sp, ggplot2, htmltools, and leaflet.

Data Sources
  The project uses two main datasets:
  
  Movements Data (movements.csv):
  
  Contains information about movements with coordinates (longitude and latitude) and timestamp.
  Restaurant Data (restaurants.csv):
  
  Includes details about various restaurants, such as Restaurant_ID, Name, Category, and coordinates.

How to Use:
  Ensure movements.csv and restaurants.csv are in the script's directory.
  Run the R script in an R environment or RStudio.
  Explore visualizations and filtered data.

You need a movements.csv to run this code. The one I used is too large to upload to github.
Line 133, Change 1:1000 to 1:nrow(movements_within) if you want capture the entire data file.
