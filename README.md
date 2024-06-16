# EPL-xG-Analysis

### Summary 

A deep dive into the performance metrics of Premier League attackers using the powerful tools of R and python. I collected the data from FBref. [Football Reference](https://fbref.com/en/)

In this project, I've transformed data into dynamic visualizations that reveal more than just numbers. By examining the relationship between expected goals (xG) and actual goals scored, I've uncovered insights into who is outperforming their expected metrics and who isn't living up to them. 
 
Some of the key discoveries:

- Aston Villa's season shines through the data, with two players ranking in the top 10% for exceeding their expected goals. Interestingly, these aren't the players grabbing the daily headlines.
  
- Patterns emerged among players who are consistently underperforming against their xG, offering a unique lens through which coaches might reassess strategies and player utilization.

## Files Included

- `fbref_scraping.ipynb`: The Jupyter Notebook file containing the code for web scraping, data extraction, and preliminary analysis.
- 'FBred.Rmd': The R studio file containing the code for visualization
  
## Prerequisites

- **Required Packages for python**:
  - `pandas`
    
- **Required Packages for R**:
  - 'reader'
  - 'dplyr'
  - 'ggplot2'
  - 'ggrepel'
  - 'cowplot'
    
- ## Running the Analysis

1. **Setup**: Ensure all required packages are installed and loaded in your R environment.

2. **Data Loading**: Load the EPL data using the `readr` package.

3. **Data Filtering**: Extract and filter the data for attackers.

4. **Data Transformation**: Calculate goal differences and categorize players into top performers, bottom performers, and others.

5. **Visualization**: Create a scatter plot to compare npxG per 90 minutes with g_pk per 90 minutes and highlight the significant players. 
