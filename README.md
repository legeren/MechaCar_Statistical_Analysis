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
- In the test across all manufacturing lots,

![image](https://user-images.githubusercontent.com/100737452/173254698-8ce3acd2-f232-44df-9081-10c5b5f6afab.png)


- In Lot1,

![image](https://user-images.githubusercontent.com/100737452/173254713-20492032-9442-456f-9bd4-710c3434f54f.png)


- In Lot2,

![image](https://user-images.githubusercontent.com/100737452/173254717-5a6a9fc4-9f94-4093-b38e-11cfb9769d7e.png)


- In Lot3,

![image](https://user-images.githubusercontent.com/100737452/173254721-17e17ce2-0b01-4c62-8c50-31b641a5a1fb.png)



## Study Design: MechaCar vs Competition

