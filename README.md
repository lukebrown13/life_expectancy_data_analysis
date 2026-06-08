  Life Expectancy Data Analysis
  Overview

This project analyzes global life expectancy data using Python. It explores relationships between key health indicators such as adult mortality and life expectancy across different regions using statistical testing, data visualization, and exploratory data analysis (EDA).

The goal is to uncover meaningful patterns that help explain differences in health outcomes across the world.

  Objectives
Perform statistical hypothesis testing on sample data
Explore global life expectancy trends
Identify relationships between health indicators
Visualize patterns using graphs
Prepare data for potential predictive modeling
  Dataset

The dataset contains global health and demographic indicators, including:

Country
Region
Life expectancy
Adult mortality
Additional health-related variables

Data was loaded from a publicly hosted Google Drive file.

  Tools & Technologies
Python
Pandas
NumPy
SciPy (statistical analysis)
Matplotlib (visualization)
Google Colab
  Analysis Workflow
1. Hypothesis Testing

A one-sample t-test was conducted to compare sample data against a known population mean, helping evaluate statistical significance.

2. Exploratory Data Analysis (EDA)
Inspected dataset structure (shape, info, describe)
Checked for and removed duplicate entries
Grouped data by region for comparison
3. Data Visualization
Scatter plot: Adult Mortality vs Life Expectancy
Regional comparison of average life expectancy
4. Feature Preparation

Defined:

Independent variables (X)
Dependent variable (y: Life Expectancy)

This prepares the dataset for future predictive modeling.

  Key Insights
Life expectancy varies significantly across regions
Higher adult mortality is strongly associated with lower life expectancy
Regional grouping reveals meaningful global disparities in health outcomes
The dataset is suitable for predictive modeling of life expectancy
  How to Run
Open the notebook in Google Colab or Jupyter Notebook

Install required libraries:

pip install pandas numpy scipy matplotlib
Run all cells sequentially from top to bottom
  Future Improvements
Build regression models to predict life expectancy
Add correlation heatmaps and advanced visualizations
Include socioeconomic indicators (GDP, education, etc.)
Automate data cleaning pipeline
  Author

Computer Science student focused on data analysis, machine learning, and real-world applications of Python in health and socioeconomic data.
