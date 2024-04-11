# STIF Shiny App

## Description

The aim of this R project is to visualize and compare the number of Navigo validations on the Ile-de-France network, and thus determine the standards for the various comparisons. A shiny application is deployed to visualize all this.

## Running the STIF Shiny App:

### 1. Execute the `clean_and_process.R` Script:
   - Run the `clean_and_process.R` script first to clean the data.
   - This script handles tasks such as removing NaN values, eliminating duplicates, and addressing outliers.

### 2. Run the `EDA.R` Script:
   - Execute the `EDA.R` script to perform Exploratory Data Analysis.
   - This step involves identifying general trends, exploring seasonality, and detecting potential outliers affecting the data.

### 3. Launch the Shiny App for Initial Comparison (`ShinyTB.R`):
   - Run the `ShinyTB.R` script to perform an initial comparison of the number of validations from 2017 to 2023.
   - The app provides insights on a daily and weekly basis.

### 4. Run the Final Shiny App for User Interaction:
   - Execute the final Shiny app (`App shiny final`) to interactively compare periods.
   - Select a reference date and the period for comparison to analyze and visualize trends.
   - Enjoy exploring the data!