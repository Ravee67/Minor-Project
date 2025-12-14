# Minor-Project
Corizo Minor project about Exploratory Data Analysis
NHANES Body Measurements Analysis – Task Specification
Objective

This project analyses adult male and female body measurement data from the NHANES 2020 survey using NumPy and Matplotlib. The purpose of this repository is to complete and document the tasks specified in the assignment instructions.

Data Files

The following datasets are used:

nhanes_adult_male_bmx_2020.csv

nhanes_adult_female_bmx_2020.csv

Source repository:
https://github.com/gagolews/teaching-data/tree/master/marek

Dataset Structure

Each dataset contains seven columns representing:

Weight (kg)

Standing height (cm)

Upper arm length (cm)

Upper leg length (cm)

Arm circumference (cm)

Hip circumference (cm)

Waist circumference (cm)

Tasks Performed
Task 1: Data Loading

Downloaded the male and female NHANES datasets.

Read both CSV files as NumPy matrices named:

male

female

Task 2: Weight Histograms

Created a single figure with two subplots:

Top subplot: Histogram of female weights

Bottom subplot: Histogram of male weights

Used identical x-axis limits for both histograms using matplotlib.pyplot.xlim.

Task 3: Box-and-Whisker Plot

Generated a box-and-whisker plot using matplotlib.pyplot.boxplot.

Plotted female and male weights side by side for comparison.

Task 4: Numerical Summary Statistics

Computed basic numerical aggregates of male and female weights, including:

Measures of location

Measures of dispersion

Measures of distribution shape

Compared the statistical characteristics of the two weight distributions.

Task 5: Body Mass Index (BMI)

Computed Body Mass Index (BMI) for all female participants.

Added BMI as an eighth column to the female data matrix.

Task 6: Standardisation of Female Dataset

Created a new matrix named zfemale.

Standardised all columns of the female dataset by computing z-scores for each variable.

Task 7: Scatterplot Matrix and Correlation Analysis

Drew a scatterplot matrix (pairplot) for the standardised female variables:

Height

Weight

Waist circumference

Hip circumference

BMI

Computed Pearson’s and Spearman’s correlation coefficients for all pairs of these variables.

Interpreted the observed relationships and correlation strengths.

Task 8: Waist-Based Ratio Calculations

Computed the following ratios for both male and female participants:

Waist-to-height ratio

Waist-to-hip ratio

Added these ratios as two additional columns to the male and female matrices.

Task 9: Ratio Comparison Using Boxplots

Created a box-and-whisker plot with four boxes side by side:

Female waist-to-height ratio

Male waist-to-height ratio

Female waist-to-hip ratio

Male waist-to-hip ratio

Compared the distributions and explained the observed differences.

Task 10: Comparison of Anthropometric Indicators

Listed advantages and disadvantages of the following body composition measures:

Body Mass Index (BMI)

Waist-to-height ratio

Waist-to-hip ratio

Task 11: Extreme BMI Analysis

Identified the 5 female participants with the lowest BMI and the 5 with the highest BMI.

Printed the standardised body measurements for these 10 participants using numpy.argsort on BMI values.

Interpreted the differences in body proportions based on standardised measurements.

Notebook Requirements

The notebook is divided into clearly labeled sections.

Each code cell is preceded by a brief explanation of its purpose.

Each code cell is followed by a short summary discussing the results.

Markdown formatting is used for readability.

Formal language, correct grammar, and clear structure are maintained throughout.

Tools and Libraries

Python 3

NumPy

Matplotlib

Jupyter Notebook

Execution

Run the notebook sequentially to reproduce all tasks and outputs described above.
