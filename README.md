# AB-Testing
# A/B Test Analysis

This project consists of a Jupyter Notebook designed for analyzing the outcomes of an A/B test. Python is used for statistical analysis and data visualization.

## Getting Started

To run this project on your local system, follow these steps:

1. Set up a Python environment and install the necessary dependencies using `pip` or `conda`.

2. Clone this GitHub repository to your local directory or download the project files.

3. Open the Jupyter Notebook `AB_Test_Analysis.ipynb` using Jupyter Notebook or Jupyter Lab.

## Project Overview

This project involves the analysis of an A/B test, where two groups (control and test) were exposed to different conditions or changes, and the results are compared to determine the effectiveness of the changes.

## Data Preparation

The project uses two datasets: `dataframe_control` and `dataframe_test`. These datasets are loaded from an Excel file, and initial data exploration is performed to understand the structure and content.

## Statistical Analysis

Several statistical tests are conducted to analyze the results of the A/B test:

- **Shapiro-Wilk Test**: Used to check the normality of the data distribution.
- **Levene's Test**: Used to check the homogeneity of variances between groups.
- **Independent Samples T-Test**: Used to compare means between the control and test groups.

## Results

The results of the statistical tests are presented, including test statistics and p-values. Interpretations of these results are provided to draw conclusions about the A/B test outcomes.

## Conclusion

In conclusion, this project demonstrates the process of analyzing A/B test results using Python. The statistical analysis helps determine whether the changes implemented in the test group have a significant impact compared to the control group.
