# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  - The vehicle length and ground clearance provided a non-random amount of variance to the mpg values in the dataset.

2. Is the slope of the linear model considered to be zero? Why or why not?
  - The slope of the linear model is not considered to be zero.  The p-value for the model (5.35e-11) is smaller than the assumed significance level of 0.05%.

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  - This linear model predicts mpg of MechaCar prototypes effectively according to the Multiple R-squared of 0.7149.

![image](https://user-images.githubusercontent.com/100737452/173253768-a328a1d6-bc6f-47a5-8e1a-e9ecef2adf44.png)

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Looking at all lots in total, the manufacturing data meet the design spec as the overall variance at 62 PSI does not exceed 100 PSI.

![image](https://user-images.githubusercontent.com/100737452/173254218-baef4f89-1984-46b9-95c9-484965e38194.png)

However, looking at each lot individually, only Lot1 and Lot2 meet the design specification whereas Lot3 (with a variance of 170 PSI) does not meet the design specs.

![image](https://user-images.githubusercontent.com/100737452/173254269-d9f4d5f8-4635-4e9c-ac08-3b0fdce0531c.png)

## T-Tests on Suspension Coils
This deliverable is to determine if the PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch.

- In the test across all manufacturing lots, p-value is 0.06028.  Assuming our significance level was the common 0.05 percent, our p-value is above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis.

![image](https://user-images.githubusercontent.com/100737452/173254698-8ce3acd2-f232-44df-9081-10c5b5f6afab.png)


- In Lot1, the p-value is 1.  Using the same significance level of 0.05, our p-value is well above.  Thus, we don't have sufficient evidence to reject the null hypothesis.

![image](https://user-images.githubusercontent.com/100737452/173254713-20492032-9442-456f-9bd4-710c3434f54f.png)


- In Lot2, the p-value is 0.6072.  Using the same significance level of 0.05, our p-value is well above.  Thus, we don't have sufficient evidence to reject the null hypothesis.

![image](https://user-images.githubusercontent.com/100737452/173254717-5a6a9fc4-9f94-4093-b38e-11cfb9769d7e.png)


- In Lot3, the p-value is 0.04168.  Using the same significance level of 0.05, we do have sufficient evidence to reject the null hypothesis.

![image](https://user-images.githubusercontent.com/100737452/173254721-17e17ce2-0b01-4c62-8c50-31b641a5a1fb.png)



## Study Design: MechaCar vs Competition
A statistical study I will do to quantify how the MechaCar performs against the competition is to check if maintenance cost have a correlation against safety rating.

The null hypothesis will be *If maintenance cost is not related to safety rating, then MechaCar's maintenance cost of $1000 a year will show no affect against safety rating.*

The alternative hypthosis will be *If maintenance cost is related to safety rating, then MechaCar's maintenance cost of $1000 a year will show higher safety rating.*

I would first do a summary statistics of MechaCar and their competition to gather the mean, median, standard deviation of maintenance costs and safety ratings.  Then I would perform a t-test to make sure I am able to compare the different stats.  I would need a year's worth of maintenance cost and safety ratings data of different sets and makes of cars (Mazda, Honda, MechaCar) to perform this test.
