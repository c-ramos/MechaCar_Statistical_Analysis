# MechaCar Statistical Analysis
The goal of this Analysis is to use historical data to perform analytics verification and validation of automotive features and design for future testing. Visualization of statistical tests using R and interpretation of the results will be provided to management.

## Deliverable 1: Linear Regression to Predict MPG

![Imgs/2.png](https://github.com/c-ramos/MechaCar_Statistical_Analysis/blob/cd156b340c72ef6d126412176590dbe812b2adbb/Imgs/2.png)
- The variables in the dataset which should a non-random amount of variance to MPG are the vehicle_length and ground_clearance. 
- The slope if the linear model is not considered to be zero because neither R nor Stdev is zero. The P-value 5.35e-11, indicating a relationship between the dependent and independent variables.
- The model predicts MPFG because of the R-squared of 71%. 


## Deliverable 2: Summary Statistics on Suspension Coils

![Imgs/total_summary.png](https://github.com/c-ramos/MechaCar_Statistical_Analysis/blob/cd156b340c72ef6d126412176590dbe812b2adbb/Imgs/total_summary.png)
![Imgs/lot_summary.png](https://github.com/c-ramos/MechaCar_Statistical_Analysis/blob/cd156b340c72ef6d126412176590dbe812b2adbb/Imgs/lot_summary.png)

The first table indicates that overall variance is under 100 psi and meets design specifications; however, in the Lot Summary table the variance for Lot 3 is over the design specs at 170. 

## Deliverable 3: T-Tests on Suspension Coils
![Imgs/deliverable 3.png](https://github.com/c-ramos/MechaCar_Statistical_Analysis/blob/cd156b340c72ef6d126412176590dbe812b2adbb/Imgs/deliverable%203.png)

The T-Test findings for Lots 1 and 2 show that the p-values for both are not low enough to reject the null hypothesis. The T-Test results for the suspension coils for Lot 3 shows that there is not sufficient evidence, with a p-value of 0.041, to reject the null hypothesis.

## Deliverable 4: Study Design: MechaCar vs Competition

As electric vehicle technology develops, MechaCar should start considering market changes in consumer behavior. With rising fuel prices, consumers will be looking to purchase vehicles with lower running costs. 

### Metrics
maintenance cost, city fuel efficiency, highway fuel efficiency, fuel/alternative fuel type

### Null hypothesis or alternative hypothesis
H0: Mechacar's average running cost is the similar to competitor vehicles in the same class.
Ha: MechaCar's average running cost is statistically above or below that of competitor vehicles.

### Statistical Test 
I would conduct a multiple linear regression to determine which metrics have the most significant correlation with fuel efficiency and its impact on total running cost.  total running cost, including maintenance and the price paid for fuel over time.

### Data 
Data from competitor vehicles in the same class. 

