# House Price Prediction Analysis Project

## Project Link
https://rpubs.com/Suhani/1261520

## Overview

This project presents a comprehensive analysis of house prices using R and various visualization techniques. Created by Suhani M Swamy, it includes interactive visualizations, statistical analysis, and a presentation of findings using R Markdown.

## Project Structure


house-price-analysis/
├── house_price_presentation.Rmd   # Main R Markdown presentation file
├── README.md                      # Project documentation
└── data/                         # Data directory (if using external datasets)


## Features

- Interactive visualizations using Plotly
- Statistical analysis of house prices
- Multiple visualization types:
  - Scatter plots
  - Box plots
  - Histograms
  - Bar charts
- Linear regression model for price prediction
- Comprehensive statistical summaries

## Dependencies

- R (version 4.4 or higher)
- RStudio
- Required R packages:
  R
  install.packages(c(
    "rmarkdown",
    "shiny",
    "ggplot2",
    "plotly",
    "dplyr"
  ))
  

## Installation

1. Install R and RStudio
   - Download R from [CRAN](https://cran.r-project.org/)
   - Download RStudio from [Posit](https://posit.co/downloads/)

2. Install Rtools (for Windows users)
   - Download from [Rtools](https://cran.rstudio.com/bin/windows/Rtools/)
   - Follow installation instructions

3. Clone the repository or download the files
   bash
   git clone [repository-url]
   cd house-price-analysis
   

4. Open the R Markdown file in RStudio
   
   house_price_presentation.Rmd
   

## Usage

1. Open RStudio
2. Open the house_price_presentation.Rmd file
3. Install required packages if not already installed
4. Click 'Knit' to generate the presentation
5. Use the presentation controls to navigate through the slides

## Data Description

The project uses a synthetic dataset with the following variables:
- Location: Urban, Suburban, Rural
- YearBuilt: Year of construction
- SquareFeet: House area in square feet
- Bedrooms: Number of bedrooms
- Price: House price in USD

## Visualizations

The presentation includes:
1. Square Footage vs Price Analysis
2. Year Built vs Price Trends
3. Location-based Price Distribution
4. Bedroom Count Impact on Price
5. Price Distribution Analysis

## Statistical Analysis

- Linear regression model
- Summary statistics by location
- Price distribution analysis
- Correlation analysis between variables

## Future Enhancements

- Add more predictive models
- Include more variables
- Expand the dataset
- Add interactive filtering options
- Include time series analysis

## Contributing

If you'd like to contribute:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## Author

*Suhani M Swamy*
- Created: January 2025
- Project: House Price Prediction Analysis




