# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![image](https://github.com/msingaram1/MechaCar_Statistical_Analysis/blob/main/resources/images/Deliverable%201.PNG)

![image](https://github.com/msingaram1/MechaCar_Statistical_Analysis/blob/main/resources/images/deliverable%201%202.PNG)

From the above output we can see that:

    1. The variables that are statisically likely to provide non-random amounts of variance to the model are vehicle length, and vehicle ground clearance. 
    
    2. The p-Value for this model, p-Value: 5.35e-11, is much smaller than the assumed significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis, which further indcates that the slope of this linear model is not zero.

    3. With an r-squared value of 0.7149 (Approximately 71% of all mpg predictions will be determined by this model). Relatively speaking, this multiple regression model does predict mpg of MechaCar prototypes effectively.


## Summary Statistics on Suspension Coils

![image](https://github.com/msingaram1/MechaCar_Statistical_Analysis/blob/main/resources/images/del21.PNG)
![image](https://github.com/msingaram1/MechaCar_Statistical_Analysis/blob/main/resources/images/del22.PNG)

For the entire production lot, the variance of the coils is 62.29 PSI, which is well within the 100 PSI variance requirement.

Lot 1 and Lot 2 are well within the 100 PSI variance requirement; with variances of 0.98 and 7.47 respectively. However, it is Lot 3 that is showing much larger variance in performance and consistency, with a variance of 170.29. Thus, Lot 3 that is disproportionately causing the variance at the full lot level.

## T-Tests on Suspension Coils
![image](https://github.com/msingaram1/MechaCar_Statistical_Analysis/blob/main/resources/images/deliverable%2031.PNG)
![image](https://github.com/msingaram1/MechaCar_Statistical_Analysis/blob/main/resources/images/del32.PNG)
![image](https://github.com/msingaram1/MechaCar_Statistical_Analysis/blob/main/resources/images/del33.PNG)

From the above t-tests, we can make the following conclusions:

For all lots, the mean of the sample is 1498.78 with a p-Value of 0.06, highter than signficance level of .05 so there is not enough evidence to reject the null hypothesis. 

For lot 1, the mean is 1500 with a p-value of 1 so we cannot reject the null.

For lot 2, the mean is 1500.02 and the p-value is .61 so the null can not be rejected

For lot 3, the mean is 1496.14 and the p-Value is .04 which is lower than the significance level of .05 so we can reject the null hypothesis which means the sample mean and the population mean are statistically the same.

## Study Design: MechaCar vs Competition 

Studying the metrics of safety feature rating, current price, drive package, engine, resale value, mpg, cost of ownership (maintenance) we can determine the MechaCar compares against competition. 

The null hypothesis would be: MechaCar is priced correctly based on its metrics
and the Alternative hypothesis would be: MechaCar is not priced correctly based on its metrics. 

To test this hypothosis we would use a multiple linear regressions determining which metrics have the highest correlation with the selling price and which combination has the greatest impact on price. The data to run this test would be all the aforementioned metrics. 
 
