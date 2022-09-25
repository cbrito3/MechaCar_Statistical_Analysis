# MechaCar_Statistical_Analysis

# Deliverable 1: Linear Regression to Predict MPG 
## Linear Regression to Predict MPG

Output from the linear regression 

!['Visual%20Data/Linear%20Regression](https://github.com/cbrito3/MechaCar_Statistical_Analysis/blob/main/Visual%20Data/Linear%20Regression.png?raw=true)

Summary of the model

!['Visual%20Data/Summary%20Statistics](https://github.com/cbrito3/MechaCar_Statistical_Analysis/blob/main/Visual%20Data/Summary%20Statistics.png?raw=true)


* Based on the data above, we can address the following questions:

  * Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

In the summary output, each Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model. According to our results, the vehicle length and ground clearance variables represent non-random amounts of variance as applied to the mpg value (the intercept). 


  * Is the slope of the linear model considered to be zero? Why or why not?

Based on the results from the linear regression model, the y intercept (Intercept) and slope coefficients. coefficients the slope is not zero. This is because the slope coefficients are non zero variables.


  * Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
 

 This linear model predict mpg of MechaCar prototypes effectively because the r-squared value is 0.715 which means that it has a strong correlation for the dataset. 
 
# Deliverable 2: Create Visualizations for the Trip Analysis
## Summary Statistics on Suspension Coils

* Below is the total summary dataframe that has the mean, median, variance, and standard deviation of the PSI for all manufacturing lots 
!['Visual%20Data/Total%20Summary](https://user-images.githubusercontent.com/107222716/191886267-2d76f2fb-4752-4fbc-8f83-fa9293bb160e.png)

* Below is a lot summary dataframe that has the mean, median, variance, and standard deviation for each manufacturing lot 
!['Visual%20Data/Lot%20Summary](https://user-images.githubusercontent.com/107222716/191886364-45d37042-7c1d-4e08-9bbe-9c2e57a290fc.png)


# Deliverable 3: T-Tests on Suspension Coils
## T-Tests on Suspension Coils

* Below is the t-test that compares all manufacturing lots against mean PSI of the population
!['Visual%20Data/t.test()%20function](https://user-images.githubusercontent.com/107222716/191886528-4ffc0fa6-713a-4ab7-aa93-806d0c065a82.png)

* Below is the three t-tests that compare each manufacturing lot against mean PSI of the population 
!['Visual%20Data/t.test()%20functions%20and%20subset()s](https://user-images.githubusercontent.com/107222716/191886571-37f3f81f-a32f-42f6-a68a-f9335bd7539d.png)

# Deliverable 4: Design a Study Comparing the MechaCar to the Competition
## Study Design: MechaCar vs Competition

* Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

* For this statistical study I address the following questions:
  * What metric or metrics are you going to test?
  
  * What is the null hypothesis or alternative hypothesis?
  
  * What statistical test would you use to test the hypothesis? And why?
  
  * What data is needed to run the statistical test?
