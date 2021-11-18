# Predicting King County Housing Prices

**Authors**: Adonis McQueen, Colin Pelzer, Zach Hanly

## Overview
This project takes the data for houses in King County Washington in order to predict home prices based upon various features. We use linear regression modeling on various features in order to predict these prices. 

## Business and Data Understanding
Ding Dong Real Estate wants to purchase homes in the Seattle area. They have tasked us with determining how much to spend on a home, on average, and areas to purchase homes in. 

Our data set contains information of houses sold such as price, square footage, grade of the house and the locations in both cooridinates and zipcode. This is all thanks to King County's effort to make data more accessible. 
From the King County site:
<blockquote cite="https://kingcounty.gov/about/website/Transparency.aspx">
"King County is committed to making data open, accessible and transparent. The following data resources are designed to increase public access to high value, machine readable datasets from various departments in King County government."</blockquote>

For more King County data go to [King County Public Data](https://kingcounty.gov/services/data.aspx)

## Explain your stakeholder audience here
The stakeholder for this project is a commercial real estate company looking to purchase homes in a given area. They are primarily interested in: what zipcodes have the lowest prices, predicted prices of homes in the area, and any relevant differences between the real prices and our model's predicted price.

## Modeling
### Correlation Heatmap
<img src="images/corr_heatmap.png" width="1500" height="1000" />

## Regression Results
### Price vs. Square Footage per Zip Code
![Zipcode Regression plot](images/zipcode_regression.png)

### Residual Error for Price vs. Square Footage per Zip Code
![Zipcode Map](images/map.png)

## Conclusion
*

*

* Strongest feature, square footage,  performs best in suburbs outside of Seattle.

## For More Information

Please review our full analysis in [our Jupyter Notebook](./main_notebook.ipynb) or our [presentation](./presentation.pdf).

## Repository Structure

```
├── README.md                 <- The top-level README for reviewers of this project
├── master_notebook.ipynb     <- Narrative documentation of analysis in Jupyter notebook
├── presentation.pdf          <- PDF version of project 
├── data                      <- Sourced externally
└── images                    <- Generated from code
├── adonis                    <- conntributions from adonis
└── colin                     <- conntributions from colin
├── zach                      <- conntributions from zach
```# Predicting King County Housing Prices
