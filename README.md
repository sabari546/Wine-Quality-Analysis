# Project Description: Wine Quality Analysis

## Goal of the Project
The primary goal of this project is to explore and analyze the factors that influence wine quality ratings, specifically focusing on the differences between red and white wines. The analysis aims to determine how attributes such as alcohol content, acidity, and other chemical properties relate to wine ratings, as well as to investigate the relationships between sweetness and quality. Ultimately, this project seeks to provide insights that could be beneficial for winemakers and consumers in understanding wine quality.

## Process
1. **Data Loading and Exploration**:
   - The project begins with loading the dataset and displaying the data for both white and red wines.
   - Initial exploration includes obtaining the size of each wine type and checking for null values.

2. **Data Cleaning**:
   - Duplicate entries are identified and removed from both datasets to ensure data integrity.
   - The number of unique values in all features is calculated and displayed.
   - Null values are removed to maintain a clean dataset.
   - Outliers are detected and removed using statistical methods to prevent skewed results in analysis.

3. **Descriptive Statistics**:
   - The mean density of both wine types is calculated for comparison.
   - A new column is created based on acidity levels derived from pH values, categorizing wines into different acidity levels.

4. **Statistical Analysis**:
   - Correlation analysis is performed to examine the relationship between citric acid content and pH levels.
   - Regression analysis is conducted to determine the influence of citric acid on pH.
   - The project assesses how wines with higher alcohol content correlate with quality ratings.
   - A group-by operation is utilized to find the mean quality ratings for each acidity level.

5. **Hypothesis Testing**:
   - The analysis investigates whether certain types of wine (red or white) are associated with higher quality ratings.
   - Confidence intervals are calculated to analyze differences in proportions of wines with a specific quality rating.

6. **Data Visualization and Summary**:
   - Visual representations are generated to illustrate key findings and relationships.
   - The project summarizes the insights gained from the analysis, particularly focusing on sweetness and its impact on quality ratings.

## Features
- **Quality Ratings**: The dependent variable representing the quality of the wine, with possible ratings from 0 to 10.
- **Wine Type**: A categorical variable indicating the type of wine, either red or white.
- **pH Levels**: A continuous variable used to infer the acidity and sweetness of the wine.
- **Alcohol Content**: A continuous variable indicating the percentage of alcohol present in the wine.
- **Citric Acid**: A continuous variable representing the citric acid content in the wine, which may influence its taste and quality.
- **Density**: A continuous variable reflecting the density of the wine, which can provide insight into its composition.
- **Acidity Level**: A new categorical variable derived from pH levels, divided into five groups: `High`, `Moderately_High`, `Medium`, `Low`, and `Very_Acidic`.

## Expected Outcomes
- Insights into the differences in wine quality ratings between red and white wines.
- Statistical evidence regarding the relationship between alcohol content and quality ratings.
- A clearer understanding of how citric acid and pH levels correlate and affect wine quality.
- Conclusions on whether sweeter wines receive better ratings and how acidity influences perceived quality.

