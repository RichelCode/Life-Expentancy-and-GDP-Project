# Life Expectancy and GDP Project

## Overview
This project explores the relationship between **GDP** and **Life Expectancy** using **data visualization and statistical analysis**. The goal is to understand the distribution of these variables and their correlation.

## Key Analyses Performed
### 1. **Univariate Analysis**
- **Histograms & Boxplots** to visualize the distribution of GDP and Life Expectancy.
- **Summary Statistics** (mean, median, standard deviation) to describe data trends.
- **Detection of Skewness** in GDP and Life Expectancy distributions.

### 2. **Log Transformation of GDP**
- Since GDP was highly **right-skewed**, applying `log10` transformation improved its distribution.
- Boxplots and histograms confirmed **reduced skewness** after transformation.

### 3. **Visualizations**
- **Histograms for Life Expectancy and GDP** (before and after log transformation).
- **Boxplots highlighting outliers** in GDP and Life Expectancy.

## Findings
- **Life Expectancy Distribution**: Most countries have high life expectancy, but some exhibit significantly lower values.
- **GDP Distribution**: Highly right-skewed, indicating a few countries dominate global GDP.
- **Log Transformation Impact**: Improved GDP distribution, making comparisons more meaningful.

## How to Run the Notebook
### Prerequisites
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib seaborn
```
### Run the Notebook
1. Open Jupyter Notebook and navigate to `life_expectancy_gdp.ipynb`.
2. Execute the cells sequentially to generate visualizations and insights.

## Acknowledgments & References
- Libraries Used: Pandas, NumPy, Seaborn, Matplotlib


