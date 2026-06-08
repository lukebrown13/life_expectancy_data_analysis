Life Expectancy Data Analysis
Overview

This project explores global life expectancy data using Python. It applies statistical hypothesis testing, exploratory data analysis (EDA), and data visualization techniques to understand relationships between key health indicators such as adult mortality and life expectancy across different regions.

The goal is to identify meaningful patterns in the data that can help explain how health factors vary globally.

Objectives
Perform statistical hypothesis testing on sample data
Analyze global life expectancy trends
Explore relationships between health indicators
Visualize key patterns in the dataset
Prepare data for potential predictive modeling
Dataset

The dataset used in this project contains global health and demographic indicators, including:

Country
Region
Life expectancy
Adult mortality
Additional health-related variables

The dataset was loaded from a public Google Drive source.

Tools & Technologies
Python
Pandas
NumPy
SciPy (statistical analysis)
Matplotlib
Google Colab
Key Analysis Performed
1. Hypothesis Testing

A one-sample t-test was performed to evaluate whether the sample mean differs significantly from a hypothesized population mean.

2. Exploratory Data Analysis (EDA)
Data structure inspection (shape, info, describe)
Grouping and aggregation by region
Duplicate removal and data cleaning
3. Data Visualization
Scatter plot analyzing the relationship between adult mortality and life expectancy
Regional comparisons of average life expectancy
4. Feature Preparation

Independent and dependent variables were defined in preparation for potential predictive modeling.

Key Insights
Life expectancy varies significantly across regions
Higher adult mortality is associated with lower life expectancy
Regional grouping reveals meaningful differences in health outcomes
Data shows strong potential for predictive modeling applications
How to Run This Project
Open the notebook in Google Colab or Jupyter Notebook

Ensure required libraries are installed:

pip install pandas numpy scipy matplotlib
Run cells sequentially from top to bottom
Future Improvements
Build a regression model to predict life expectancy
Expand dataset with additional socioeconomic indicators
Add more advanced visualizations (heatmaps, correlation matrices)
Automate data preprocessing pipeline
Author

Created by a Computer Science student with interests in data analysis, machine learning, and real-world applications of Python in healthcare and economic data.
