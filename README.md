# Evaluating-Fuel-Efficiency
Evaluating Fuel Efficiency (MPG): A Comparative Study of Manual and Automatic Transmissions

## Executive summary:

This project analyzed the relationship between transmission type (manual or automatic) and miles per gallon (MPG). The project set out to determine which transmission type produces a higher MPG. The mtcars dataset was used for this analysis. A t-test between automatic and manual transmission vehicles shows that manual transmission vehicles have a 7.245 greater MPG than automatic transmission vehicles.

After fitting multiple linear regressions, the analysis showed that the manual transmission contributed less significantly to MPG, with only an improvement of 1.81 MPG. Other variables, weight, horsepower, and number of cylinders contributed more significantly to the overall MPG of vehicles.

## Usage:
The mtcars dataset was used for this analysis. The only library needed is ggplot2.

## Data description:
The mtcars dataset has 11 columns featuring variables such as MPG, Cylinders, horsepower, weight, etc. First, we change the type of the factorial variables into factors.

## Methodology

### Statistical Analysis
- **T-Test**: Used to compare the MPG of manual vs. automatic transmissions. The test showed a significant difference in favour of manual transmissions.

### Regression Modeling
- **Initial Model**: Included all variables from the mtcars dataset. No varialbe's p-value was less than 0.05.
- **Backward Selection**: Identified the most statistically significant variables affecting MPG. 
- **Final Model**: Consisted of four key variables: cylinders, horsepower, weight, and transmission type. The model explained around 87% of the variables in MPG.

### Residual Analysis
- Conducted to ensure the reliability of the regression model. No significant outliers were detected, confirming the model's validity.

## Visualizations

![Box plot](https://github.com/Beh-naz/Evaluating-Fuel-Efficiency/blob/main/my_boxplot.png)

![Residuals plots](https://github.com/Beh-naz/Evaluating-Fuel-Efficiency/blob/main/my_residual_plot.png)


## Conclusion:
MPG is affected by transmission, however, not as significantly as it is affected by weight, horsepower, and cylinders.

Find my complete report of this project in the project.pdf uploaded to this repository.
