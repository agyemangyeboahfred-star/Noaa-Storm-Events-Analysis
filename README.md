# U.S. Storm Events Analysis (2025 NOAA Data)

[![RPubs](https://img.shields.io/badge/Report-RPubs-blue)](http://rpubs.com/Agyemanf/1427503)

Prepared for: Government / Emergency Management Stakeholders

---

## Project Overview
This project analyzes the NOAA Storm Events dataset for 2025 to understand the impact of severe weather across the United States.

The analysis focuses on:
- Public health impact (deaths and injuries)
- Geographic distribution of events
- Seasonal patterns
- Economic damage

---

## Research Questions
1. Which event types are most harmful to population health?
2. Which event types occur most frequently across states?
3. How do storm events vary by month?
4. Which events cause the greatest economic damage?

---

## Key Insights
- **Excessive Heat** is the most harmful event in terms of human impact  
- **Thunderstorm Wind** occurs most frequently across multiple states  
- Storm events show strong **seasonal patterns**  
- **Tornadoes** cause the highest economic damage (~$1.9B)  

---

## Tools Used
- R (dplyr, ggplot2, tidyr)
- NOAA Storm Events Dataset

---


---

```markdown
## Required R Packages

The project uses the following R packages:

```r
library(dplyr)
library(readr)
library(ggplot2)
library(stringr)
library(forcats)
library(scales)
library(knitr)
library(tidyr)

Install missing packages with:
install.packages(c("dplyr", "readr", "ggplot2", "stringr", "forcats", "scales", "knitr", "tidyr"))

## Output
- Data processing pipeline
- Visualizations (health impact, geography, seasonality, damage)
- Fully reproducible R Markdown report

## Live Report
[View RPubs Report](http://rpubs.com/Agyemanf/1427503)

## Files
- `NOAA_Storm_Events_Final_Project.Rmd` — full report
- `NOAA_Storm_Events_Final_Project.R` — script version
- CSV outputs — summarized analysis tables

## How to Run
1. Download the repository
2. Place NOAA CSV files in the same folder
3. Open the `.Rmd` file in RStudio
4. Click **Knit**

## Author
Fred Yeboah Agyemang  
MS Business Analytics | Canisius University
