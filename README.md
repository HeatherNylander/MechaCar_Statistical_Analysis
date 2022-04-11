# MechaCar Statistical Analysis

## Linear Regression to Predict MPG

![linear_regression](https://github.com/HeatherNylander/MechaCar_Statistical_Analysis/blob/main/images/linear_reg_output.png)

#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- Vehicle Weight
- All Wheel Drive
- Spoiler Angle
##### Is the slope of the linear model considered to be zero? Why or why not?
- No, the relationship between the independent and dependent variables would have to be insignificant for the slope to be zero, which is not the case.
##### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- The model predicts at about 71% which means the r value is approximately .84 which is considered a strong strength of correlation.


## Summary Statistics on Suspension Coils
#### Total Summary
![total_summary](https://github.com/HeatherNylander/MechaCar_Statistical_Analysis/blob/main/images/total_summary.png)

#### Lot Summary
![lot_summary](https://github.com/HeatherNylander/MechaCar_Statistical_Analysis/blob/main/images/lot_summary.png)

##### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
- The overall variance is about 62 which does not exceed the design specifications: however, the variance on Lot 3 is over 170 which means that only Lot 1 & Lot 2 meet the requirement. 

## T-Tests on Suspension Coils

![t-tests](https://github.com/HeatherNylander/MechaCar_Statistical_Analysis/blob/main/images/t-tests.png)
#### Summarize your interpretation and findings for the t-test results.
- Lot 1 & Lot 2 do not have sample means that are statistically different from the population mean.
- Lot 3 has a mean that is statistically different from the population mean. 
- This means that we cannot reject the null hypothesis for Lots 1 & 2.
- But, the p-value for Lot 3 is low enough to reject the null hypothesis. 


## Study Design: MechaCar vs Competition
##### What metric or metrics are you going to test?
- We should gather car weight, car length, mpg and AWD metrics from the competition.
##### What is the null hypothesis or alternative hypothesis?
- The null hypothesis is that car length, car weight, and AWD does not impact the mpg of a car.
##### What statistical test would you use to test the hypothesis? And why?
- Summary statistics and a t-test should be conducted so that we can observe variance and p-value. 
##### What data is needed to run the statistical test?
- We would need to gather mileage performance data as well as the physical car stats.
