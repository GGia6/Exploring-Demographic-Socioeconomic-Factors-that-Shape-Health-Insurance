# Exploring-Demographic-Socioeconomic-Factors-that-Shape-Health-Insurance


## Project Overview
This project explores how demographic and economic factors are associated with health insurance coverage in New York and New Jersey counties. Using interactive dashboards and statistical analysis, the project examines relationships between variables such as income, social demographics, and insurance outcomes to better understand disparities in health insurance access.

The analysis is presented through a combination of Shiny applications, Tableau visualizations, and a comprehensive RPubs report.

---

## Data & Methods
The project uses publicly available demographic and economic data related to health insurance coverage, found on the US Census website.

Statistical methods applied include:
- Correlation analysis to assess relationships between key variables
- Linear regression models to examine how economic and demographic factors predict insurance coverage rates

These methods are implemented within interactive Shiny applications to allow users to explore results dynamically.

---

## Tools & Technologies
- **R** (tidyverse, Shiny, ggplot2, gganimate, gifski)
- **Statistical methods:** correlation, linear regression
- **Tableau** (interactive dashboards)
- **RPubs** (published report)
- **GitHub** (code and project documentation)

---

## Project Components

### Shiny Applications
- **Shiny App 1:** Two interactive complementary views, allowing users to investigate the rates at which people are uninsured in neighboring counties.
  Live app:  https://giannnag.shinyapps.io/NYNJ_InsuranceModeling/
- **Shiny App 2:** Regression-based analysis allowing users to examine unique predictors of insurance outcomes
  Live app:  https://giannnag.shinyapps.io/CountyComparison/

### Tableau Visualizations
- Multiple Tableau dashboards visualizing trends and disparities in health insurance coverage across demographic and economic groups

### RPubs Report
- Full written analysis combining results from the Shiny apps and Tableau dashboards  
- Includes interpretation of statistical findings and visual summaries

**RPubs link:**  
[http://rpubs.com/GGianna/1375326]

---

## How to Run the Shiny Apps Locally
1. Clone this repository
2. Open the project in RStudio
3. Install required packages:
   ```r
   install.packages(c("shiny", "tidyverse", "ggplot2"))
