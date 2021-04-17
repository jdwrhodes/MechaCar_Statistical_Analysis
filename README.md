# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

The picture below shows the results of a multi-linear regression analysis for the variables impacting the mpg of multiple vehicle prototypes.

![Multiple-Linear Regression Result](https://raw.githubusercontent.com/jdwrhodes/MechaCar_Statistical_Analysis/main/resources/mpg_multilinear_regression.png 'Multiple-Linear Regression Result')

- In this analysis, the vehicle_length and ground_clearance provided a p-value of 2.60e-12 and 5.21e-08 respectively. As they are both less than 0.05, this indicates that those variables provided a non-random amount of variance to the dataset. 
- The final p-value of 5.35e-11 is below the 0.05 threshhold, meaning we can reject the null-hypothesis that the slope is zero.
- Whether or not this model could accurately predict the mpg of the prototypes is difficult to say. With an r-squared of 0.7149, it could be used to accurately predict the mpg over 70% of the time. However, with an intercept of 5.08e-08, there is strong indication of other variables that may not be in the dataset that need to be accounted for.

## Summary Statistics on Suspension Coils

The pictures below are the testing results for 3 lots of suspension coils. 

The first picture shows the total results across all three lots. Combined they satisfy the requirement that the variance not exceed 100 PSI. Digging deeper though shows some different results.

![Total Summary](https://raw.githubusercontent.com/jdwrhodes/MechaCar_Statistical_Analysis/main/resources/total_summary.png 'Total Summary')

This picture shows the results by lot. The first and second lot easily satisfy the variance requirement. The third lot does not, by quite the margin as well. It is 70% higher, at 170 PSI, than the requirement allows. This batch should be rejected and remanufactured to meet the variance requirement.

![Lot Summary](https://raw.githubusercontent.com/jdwrhodes/MechaCar_Statistical_Analysis/main/resources/lot_summary.png 'Lot Summary')

## T-Tests on Suspension Coils
