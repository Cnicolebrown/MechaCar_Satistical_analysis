# MechaCar_Satistical_analysis

## Linear Regression to Predict MPG
 ![image](https://user-images.githubusercontent.com/103790879/182505932-ae359329-7767-499f-aa34-84bfe0b7b63f.png)

•	Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset? 
o	MPG, Vehicle length, ground clearance all have values that are greater than 0.05 meaning they acre at a 95% confidence level. This indicates that these are the nonrandom and are statistically significant. 
•	Is the slope of the linear model considered to be zero? Why or why not?
o	The slope is not considered 0 because the values of the coefficients do not equal zero.
•	Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
o	The R squared values is equal to 0.7119, this is indicative of the data being a good predictor for MPG of the MechaCar. 

## Summary Statistics on Suspension Coils
# Total Summary
 
![image](https://user-images.githubusercontent.com/103790879/182506055-feaa8dd2-aa0e-4f32-9fc1-a6e6c32ba85d.png)
# Summary by lot number
*Note: this is the mean, median, variance, SD separated by lot. 
 ![image](https://user-images.githubusercontent.com/103790879/182505970-e045b5a7-53f6-4aa2-8837-bee7ab6de5ca.png)

•	The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
All cars meet the requirements with the exception of lot 3 which exceeds the design specifications. Lot 3 is greater than 100 due to its variance being 170.28.  
## T-Tests on Suspension Coils
 ![image](https://user-images.githubusercontent.com/103790879/182506000-cee620e6-5ff9-49a0-8a78-a14226c23de0.png)

Based on the above T test, all the lots appear to display normal distribution. This means they are all statistically significant and the null hypothesis can be rejected. 

## Study Design: MechaCar vs Competition. 
•	What metric or metrics are you going to test?
o	The metrics being tested in the new competition is safety rating vs that of the competition. 
•	What is the null hypothesis or alternative hypothesis?
o	the null bypothesis is that the car will not perform as well as the compition in terms of safety. This would result in a mean of 0 for MechaCar. 
o	The alternative is that the car will outperform the competition which would result in a mean higher than 0.
•	What statistical test would you use to test the hypothesis? And why?
o	Linear regression because this would give the resulting information required like the mean. 
•	What data is needed to run the statistical test?
o	Data representing safety of the MechaCar vs various competitors. One safety rating would be crash test data, brake time reaction, and airbag deployment efficiency. 

