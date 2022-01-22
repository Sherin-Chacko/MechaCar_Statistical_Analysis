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


### DELIVERABLE 3 : T-TESTS ON SUSPENSION COILS
A) Summary of the t-test results across all manufacturing lots:

<img width="503" alt="Screen Shot 2022-01-21 at 3 09 06 PM" src="https://user-images.githubusercontent.com/91294352/150594149-77749a73-b7e0-4b52-b308-114321c80986.png">

We can see above that the mean of the sample is 1498.78. With a p-Value of 0.06, which is higher than the common significance level of 0.05, there is NOT enough evidence to support rejecting the null hypothesis. 

B) SUMMARY OF T-TESTS FOR EACH INDIVIDUAL LOTS:

1. Lot 1 sample actually has the true sample mean of 1500, again as we saw in the summary statistics above. With a p-Value of 1, clearly we cannot reject (i.e. accept) the null hypothesis that there is no statistical difference between the observed sample mean and the presumed population mean (1500).

<img width="548" alt="Screen Shot 2022-01-21 at 3 13 18 PM" src="https://user-images.githubusercontent.com/91294352/150594840-9e96f627-96ef-4c85-9b92-079fdfe324b9.png">

2. Lot 2 has essentially the same outcome with a sample mean of 1500.02, a p-Value of 0.61; the null hypothesis cannot be rejected, and the sample mean and the population mean of 1500 are statistically similar.

<img width="548" alt="Screen Shot 2022-01-21 at 3 13 18 PM" src="https://user-images.githubusercontent.com/91294352/150594840-9e96f627-96ef-4c85-9b92-079fdfe324b9.png">


3. However, Lot 3 has an different scenario. Here the sample mean is 1496.14 and the p-Value is 0.04, which is lower than the common significance level of 0.05. This indicates to reject the null hypothesis that this sample mean and the presumed population mean are not statistically different.

The production cycle of Lot 3 is improper. The process needs to be checked for system failure and the suspension coils from this lot need to be inspected to remove those not meeting quality criteria.  

<img width="430" alt="Screen Shot 2022-01-21 at 3 14 16 PM" src="https://user-images.githubusercontent.com/91294352/150595175-85b0274b-7035-49d5-8026-e2a8a3bc3452.png">

### DELIVERABLE 4 : STUDY DESIGN MechaCar vs COMPETITION

### Metrics
The following metrics can be considered:

Current Price: Dependent Variable

Safety Feature Rating: Independent Variable

Engine (Electric, Hybrid, Gasoline / Conventional): Independent Variable

MPG (Gasoline Efficiency): Independent Variable

Selling price: Dependent varaible

### Hypothesis: Null and Alternative
After determining which factors are key for the MechaCar's category:

Null Hypothesis (Ho): MechaCar is priced correctly based on its performance of key factors for its category.

Alternative Hypothesis (Ha): MechaCar is not priced correctly based on performance of key factors for its category.

### Statistical Tests
A multiple linear regression would be used to determine the factors that have the predictability with the list selling price (dependent variable), which combination has the greatest impact on price.






