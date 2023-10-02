# San Francisco Real Estate Analysis

## Overview

This project analyzes the San Francisco real estate market, focusing on housing rental data between 2011-2016. The goal is to provide insights and visualizations to support a potential one-click, buy-and-rent strategy in the San Francisco market. I  used data analysis techniques, interactive visualizations, and geospatial analysis to uncover trends and opportunities within the market.

## Project Structure

The analysis is divided into several key steps, each addressing a specific aspect of the real estate market:

1. **Data Preparation**: In this phase, I loaded and cleaned the necessary data from CSV files, including housing per year, neighborhood coordinates, and census data. We merge these datasets to create a comprehensive dataset for analysis.

2. **Housing Units per Year**: I calculated and visualized the number of housing units per year using a bar chart. This step helps us understand the overall trend in housing units over the analyzed period.

3. **Average Sale Prices per Square Foot**: I calculated the average sale price per square foot and the lowest reported gross rent over the years. Using a line plot, I visualized how these prices change over time and explored relationships between sale prices and gross rent.

4. **Average Sale Prices by Neighborhood**: This step involves analyzing the average sale price per square foot by neighborhood using interactive visualizations. I created an interactive line plot that allows users to explore different neighborhoods and their pricing trends.

5. **Interactive Neighborhood Map**: I used geospatial analysis to build an interactive neighborhood map. The map displays the relationship between sale price per square foot (represented by point size) and gross rent (characterized by color density) across neighborhoods.

6. **Data Story**: In this final section, I summarized the trends observed in rental income growth and sales prices. I discussed whether these trends hold true for all neighborhoods or if there are variations. Insights are provided to support potential investment strategies, and specific areas are recommended based on the analysis.

## Usage

To replicate this analysis, follow these steps:

1. Clone the GitHub repository to your local machine.
2. Ensure you have Jupyter Notebook installed.
3. Open the Jupyter Notebook file `san_francisco_housing.ipynb` in your Jupyter environment.
4. Execute the code cells sequentially to reproduce the analysis.
5. Explore the interactive visualizations to gain insights into the San Francisco real estate market.

## Findings

Based on the analysis, here are some key findings:

- The San Francisco housing market has shown steady growth in housing units over the analyzed period.
- Average sale prices per square foot have generally increased, with occasional drops in specific years.
- Neighborhoods exhibit varying pricing trends, making some neighborhoods more attractive for investment.
- An interactive map helps identify neighborhoods with the highest gross rent and sale prices per square foot, providing valuable insights for potential investors.

**Note: The hvplot() outputs can be viewed when you run it in the Jupyter kernels**
