# Remuneration Across Races and Regions

A statistical analysis of wage disparities using data from the **1988 Current Population Survey (CPS)**. This project investigates how wages differ between Black and non-Black male workers across U.S. geographic regions while controlling for education and work experience.

## Project Overview

This analysis uses multiple linear regression to estimate wage differences across racial groups and regions while accounting for important socioeconomic factors. The project demonstrates statistical modeling, exploratory data analysis, data cleaning, model diagnostics, and interpretation of regression results in R.

## Research Questions

* What is the wage gap between Black and non-Black male workers across U.S. regions?
* Does the magnitude of the wage gap differ by geographic region?
* How do education and years of work experience influence wages after controlling for race and region?

## Data

The analysis uses the **1988 Current Population Survey (CPS)** sample available in the **Sleuth2** R package.

```r
library(Sleuth2)
CPS_1988_wages <- Sleuth2::ex1029
```

The dataset includes information on wages, race, education, work experience, and geographic region for U.S. workers.

## Methods

* Data cleaning and preparation
* Exploratory data analysis
* Multiple linear regression
* Interaction effects between race and region
* Model assumption diagnostics
* Confidence intervals and hypothesis testing

## Technologies

* R
* Quarto (.qmd)
* tidyverse
* ggplot2
* Sleuth2

## Repository Structure

```
├── README.md
├── remuneration-race-region.qmd
├── remuneration-race-region.html
└── figures/
```

## Key Skills Demonstrated

* Statistical Modeling
* Multiple Linear Regression
* Data Wrangling
* Exploratory Data Analysis
* Data Visualization
* Model Diagnostics
* Statistical Inference
* Scientific Communication

## Author

**Hadiya Cabdi**

Statistics & Data Science | Economics

Smith College

