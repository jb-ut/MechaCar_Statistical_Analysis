# MechaCar_Statistical_Analysis

## Overview

Jeremy has been asked to help analyze production data for the MechaCar, which has been suffering from production delays. Management is looking for insights that can help them figure out what to do.

Jeremy will peform the following:

- Multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings

## Results

### Predicting MPG With Linear Regression

1. Vehicle weight and AWD provided a non-random amount of variance. The two variables that had the most amount of random variance are ground_clearance and vehicle_length.
2. R-squared value is 71%, which means roughly ~71% of the time the model will predict mpg values correctly.

### Suspension Coil Analysis
The current manufacturing data meets the 100 pounds per square inch variance limitation based on thhe overall variance for the entire dataset. It appears that a third lot demonstrates a much higher variance. Since lots are chosen randomly it is a possible that a third of the lot does not meet the necessary suspension coils requirement.

## Study Design: MechaCar vs Competition

We could also review fuel effiency against competition both for city and highway.

Dependent variable: City and highway fuel efficiency
Independent variable: vehicle weight: 
Independent variable: AWD capabilities 
Independent variable: MPG
