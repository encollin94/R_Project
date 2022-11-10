# R_Project

## Linear Regression to Predict MPG
![pIC](https://github.com/encollin94/R_Project/blob/main/MechaCarcHALLENGE_sNIPPET.png)
Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Ground Clearance and Vehicle Length, all of these are showing less than 0.05 for Pr
Is the slope of the linear model considered to be zero? Why or why not?
No, there is a coefficient in each variable.
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
This model overall has a value that is less than p<0.05m, which mean it is significant.

## Summary Statistics on Suspension Coils
![image]((https://github.com/encollin94/R_Project/blob/main/Suspension_lot_summary.png)
![image](https://github.com/encollin94/R_Project/blob/main/Suspension_total_summary.png)
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not? LOT1 and LOT2 meet these specifications as both of their variance are under 100psi. However, lot3 does not meet these expectation as their variance is at 170 psi. The average of all the variance of the lots is under 100 psi, coming in at about 60 psi.


## T-Tests on Suspension Coils
Overall T-TEST
![image](https://github.com/encollin94/R_Project/blob/main/Overal_Suspension_tttest.png) 
3Lot Ttest
![image](https://github.com/encollin94/R_Project/blob/main/Suspension_3lots_ttest.png)

The overall t-test is statistically significant so we can affirm the alternative hypothesis that the true mean is not equal to 1500. The LOT1 t-test is statistically significant so we can affirm the alternative hypothesis that the true mean is not equal to 1500. The LOT2 t-test is statistically significant so we can affirm the alternative hypothesis that the true mean is not equal to 1500. The LOT3 t-test is statistically significant so we can affirm the alternative hypothesis that the true mean is not equal to 1500. 

## Study Design: MechaCar vs Competition

What metric or metrics are you going to test? I think a good study would be to test safety. The metric to test would be safety ourcomes in a car crash based on vehicle weight. 
What is the null hypothesis or alternative hypothesis? The null hypothesis could be that the vehical weight does not impact safety outcomes. Th alternative is that the vehicle weight does impact safety outcomes
What statistical test would you use to test the hypothesis? And why?
You could run 2 samplet-test against the vehicle weight and the number of people injured in car crashes. This would show if their is a statisical signficance between the two metrics
What data is needed to run the statistical test? Number of accidents, vehicle weight and number of persons injured
