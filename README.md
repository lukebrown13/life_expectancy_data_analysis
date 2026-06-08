# Life Expectancy Data Analysis

## Overview
This project analyzes global life expectancy data using Python. It explores relationships between key health indicators such as adult mortality and life expectancy across different regions using statistical testing, data visualization, and exploratory data analysis (EDA).

The goal is to identify meaningful patterns in the data that help explain differences in health outcomes across the world.

---

## Objectives
- Perform statistical hypothesis testing on sample data
- Explore global life expectancy trends
- Identify relationships between health indicators
- Visualize patterns using graphs
- Prepare data for potential predictive modeling

---

## Dataset
The dataset contains global health and demographic indicators, including:

- Country
- Region
- Life expectancy
- Adult mortality
- Additional health-related variables

The data was loaded from a publicly available Google Drive source.

---

## Tools and Technologies
- Python
- Pandas
- NumPy
- SciPy (statistical analysis)
- Matplotlib (visualization)
- Google Colab

---

## Analysis Workflow

### 1. Hypothesis Testing
A one-sample t-test was performed to compare sample data against a known population mean and evaluate statistical significance.

### 2. Exploratory Data Analysis (EDA)
- Inspected dataset structure using shape, info, and describe
- Removed duplicate entries
- Grouped data by region for comparison

### 3. Data Visualization
- Scatter plot of Adult Mortality vs Life Expectancy
- Regional comparison of average life expectancy

### 4. Feature Preparation
Defined independent variables (X) and dependent variable (y: Life Expectancy) for potential predictive modeling.

---

## Key Insights
- Life expectancy varies significantly across regions
- Higher adult mortality is strongly associated with lower life expectancy
- Regional grouping reveals meaningful global disparities in health outcomes
- The dataset can be used for predictive modeling tasks

---

## How to Run This Project
1. Open the notebook in Google Colab or Jupyter Notebook
2. Install required libraries:
   pip install pandas numpy scipy matplotlib
3. Run all cells sequentially from top to bottom

---

## Future Improvements
- Build regression models to predict life expectancy
- Add correlation heatmaps and advanced visualizations
- Include socioeconomic indicators such as GDP and education
- Automate data preprocessing pipeline

---

## Author
Computer Science student focused on data analysis, machine learning, and real-world applications of Python in health and socioeconomic datasets.
