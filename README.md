Library Preparation
The script begins by loading three essential R libraries:

readr: For efficient CSV file reading
ggplot2: For creating professional data visualizations
broom: For transforming statistical model outputs into clean, readable formats


Data Loading
The code reads a CSV file named "study_data.csv" into a data frame called study_data. It then prints the first few rows to verify the data has been loaded correctly.
Initial Data Exploration
A summary function is used to generate descriptive statistics about the dataset, providing an overview of the variables' characteristics.
Visualization of Raw Data
The first visualization is a scatter plot showing the relationship between Days and Time Study. Key features include:


Each data point is plotted
X-axis labeled with all days from 1 to 20
Minimal, clean design for easy interpretation


Linear Regression Analysis
A linear regression model is created with:


Dependent variable: Time Study
Independent variable: Days
The script generates multiple outputs:
Detailed model summary
Tidy, clean version of model coefficients
Advanced Visualization
A second plot is created with a polynomial (quadratic) regression curve, which helps identify potential non-linear relationships in the data.
Model Diagnostics
Four diagnostic plots are generated to check regression assumptions:


Residuals vs. Fitted values
Quantile-Quantile (Q-Q) plot of residuals
Scale-Location plot
Residuals vs. Leverage plot

These help assess the validity and reliability of the regression model.

Prediction Preparation
The script creates a sequence of days and generates predictions using the regression model, including confidence intervals.
Final Analysis and Reporting
The last section includes:


Another visualization of the data with a polynomial trend
Printing of the R-squared value (indicating model fit)
Displaying the regression equation
