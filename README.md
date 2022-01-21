## MechaCar_Statistical_Analysis
Module 15 / R and Statistics

### DELIVERABLE 1 : LINEAR REGRESSION TO PREDICT MPG

A) OUTPUT OF THE LINEAR MODEL-

<img width="671" alt="Screen Shot 2022-01-21 at 12 57 47 PM" src="https://user-images.githubusercontent.com/91294352/150577600-72abb759-f1aa-4004-9203-2dee8a24524b.png">

B) STATISTICAL SUMMARY-

From the output shown above, we can summarize the following:

1. The vehicle length and vehicle ground clearance have non-random impact on miles per gallon on the MechaCar prototype. Other variables such as the vehicle weight, spoiler angle, and All Wheel Drive (AWD) have p-Values that indicate a random amount of variance with the dataset.

2. The p-Value: 5.35e-11 for this model is much smaller than the assumed significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis, which further indicates that the slope of this linear model is not zero.

3. This linear model has an r-squared value of 0.7149, which means that 71% of all mpg predictions will be determined by this model. This linear regression model does predict mpg of MechaCar prototypes effectively.

### DELIVERABLE 2 : SUMMARY STATISTICS ON SUSPENSION COILS

<img width="499" alt="Screen Shot 2022-01-21 at 1 53 55 PM" src="https://user-images.githubusercontent.com/91294352/150585466-656ae495-99f4-4dc3-928c-c9cb2cfc5b56.png">

<img width="650" alt="Screen Shot 2022-01-21 at 1 54 46 PM" src="https://user-images.githubusercontent.com/91294352/150585688-e53efbc8-590c-4adb-af56-89d66c7bcbb9.png">

1. When looking at the entire set of the production lot, the variance of the coils is 62.29 PSI, which is well within the 100 PSI variance requirement.

2. Individually, Lot 1 and Lot 2 are well within the 100 PSI variance requirement; with variances of 0.98 and 7.47 respectively. However, it is Lot 3 that is showing much larger variance in performance and consistency, with a variance of 170.29. Therefore, the current manufacturing data does not meet the design specification for Lot 3 as observed in the table above.




