# World-Happiness-Report

[View the Tableau Dashboard](https://public.tableau.com/app/profile/nimrat.kaur2103/viz/WorldHappinessReport_17670313651560/WorldHappinessReport?publish=yes)

# Executive Summary

This project analyzes global happiness data from 2005 to 2023 to understand how happiness varies across countries and to identify the key factors associated with higher life satisfaction. Using exploratory analysis, linear regression, and cluster analysis, the study finds that economic stability and social support together are strongly linked to higher happiness levels. While income plays an important role, social factors significantly influence how happy people feel across different regions of the world.

# Business Problem

Governments, international organizations, and policymakers aim to improve citizens’ well-being, but happiness is influenced by multiple interconnected factors. Relying on economic growth alone may not fully explain or improve life satisfaction.

# Key questions addressed:

- How does happiness vary across countries and regions?

- What factors are most strongly associated with higher happiness?

- Can countries be grouped into meaningful segments based on economic and social conditions?

- How can these insights support better policy decisions?

# Methodology

The analysis follows a structured, step-by-step approach:

1. Exploratory Data Analysis (EDA)

- Visualized global happiness using a choropleth map

- Examined distributions and trends over time

- Explored relationships between happiness and key variables such as GDP per capita and social support

2. Linear Regression

- Built regression models to test whether GDP per capita and social support predict happiness scores

- Evaluated model performance using trend lines and R² values

- Assessed the strength and direction of relationships

3. Cluster Analysis

- Applied clustering techniques to group countries based on:

- GDP per capita

- Happiness score

- Social support

- Identified three distinct clusters representing different happiness profiles

- Compared clusters to understand economic and social differences

# Visualizations

<img width="3224" height="2553" alt="heatmap_world_happiness_report" src="https://github.com/user-attachments/assets/aebe55e3-2099-41e7-bbdf-ad1bd360436f" />

<img width="700" height="500" alt="scat2_world_happiness_report" src="https://github.com/user-attachments/assets/999802d9-aa56-4c73-8291-e9cee4a85dff" />

<img width="700" height="500" alt="scat3_world_happiness_report" src="https://github.com/user-attachments/assets/4d57e54a-2f90-4c30-b9d0-89b0c5128358" />

<img width="640" height="480" alt="scat5_world_happiness_report" src="https://github.com/user-attachments/assets/e1f6c5c6-b3e9-41f1-a257-fd0b209a6c71" />


# Tools Used

- Tableau Public – data visualization and storytelling

- Python – data preparation and analysis

- Pandas, Matplotlib, Scikit-learn – statistical analysis and modeling

# Results & Key Insights

- Countries with higher GDP per capita generally report higher happiness, but income alone does not fully explain happiness.

- Social support shows a strong positive relationship with happiness across countries.

Cluster analysis reveals:

- Cluster 1: Lower income, lower social support, lowest happiness levels

- Cluster 2: High income and strong social support, highest happiness levels

- Cluster 3: Moderate income and social support, mid-range happiness

- The findings suggest that economic and social factors work together to shape happiness outcomes.

# Recommendations

- Policymakers should focus not only on economic growth, but also on strengthening social support systems, community well-being, and social safety nets.

- Investments in healthcare, education, work-life balance, and social trust may significantly improve happiness outcomes.

- Countries in transitional stages can benefit from balanced strategies that address both economic and social development.

# Next Steps

- Incorporate additional variables such as inequality, mental health indicators, governance quality, and freedom of choice.

- Perform time-series analysis to examine how happiness changes before and after major global events.

- Test non-linear or multivariate models to capture more complex relationships.

- Expand clustering with additional features to refine country segmentation.

# Limitations

- Happiness scores are self-reported, which may introduce cultural and personal bias.

- Data availability varies by country and year, leading to potential gaps.

- The analysis identifies associations, not causation.
