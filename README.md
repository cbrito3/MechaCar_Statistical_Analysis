# MechaCar_Statistical_Analysis

# Deliverable 1: Linear Regression to Predict MPG 
## Linear Regression to Predict MPG

Output from the linear regression 

!['Visual%20Data/Linear%20Regression](https://github.com/cbrito3/MechaCar_Statistical_Analysis/blob/main/Visual%20Data/Linear%20Regression.png?raw=true)

Summary of the model

!['Visual%20Data/Summary%20Statistics](https://github.com/cbrito3/MechaCar_Statistical_Analysis/blob/main/Visual%20Data/Summary%20Statistics.png?raw=true)


* Based on the data above, we can address the following questions:

  1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

In the summary output, each Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model. According to our results, the vehicle length and ground clearance variables represent non-random amounts of variance as applied to the mpg value (the intercept). 

  2. Is the slope of the linear model considered to be zero? Why or why not?

Based on the results from the linear regression model, the y intercept (Intercept) and slope coefficients. coefficients the slope is not zero. This is because the slope coefficients are non zero variables.

  3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
 
This linear model predict mpg of MechaCar prototypes effectively because the r-squared value is 0.715 which means that it has a strong correlation for the dataset. 
 
 
# Deliverable 2: Create Visualizations for the Trip Analysis
## Summary Statistics on Suspension Coils

The MechaCar dataset contains the results from multiple production lots. In this dataset, the weight capacities of multiple suspension coils were tested to determine if the manufacturing process is consistent across production lots.
First I created a total_summary dataframe as in the first graph and then a lot_summary dataframe as seen in the second graph.

* Below is the total_summary dataframe that has the mean, median, variance, and standard deviation of the PSI for all manufacturing lots 
!['Visual%20Data/Total%20Summary](https://user-images.githubusercontent.com/107222716/191886267-2d76f2fb-4752-4fbc-8f83-fa9293bb160e.png)

* Below is a lot_summary dataframe that has the mean, median, variance, and standard deviation for each manufacturing lot 
!['Visual%20Data/Lot%20Summary](https://user-images.githubusercontent.com/107222716/191886364-45d37042-7c1d-4e08-9bbe-9c2e57a290fc.png)

* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

  * In the first result from the total_summary gives us a variance of approximately 62.29 PSI, this does meet the design specification of not exceeding 100  pounds per square inch. When looking at the lot_summary results, the variances for Lot1 and Lot2, approximately 0.98 PSI and 7.47 PSI respectively, meet the design specification of not exceeding 100  pounds per square inch; however, Lot3 at apprimately 170.29 PSI does not. 


# Deliverable 3: T-Tests on Suspension Coils
## T-Tests on Suspension Coils

* Below is the t-test that compares all manufacturing lots against mean PSI of the population
!['Visual%20Data/t.test()%20function](https://user-images.githubusercontent.com/107222716/191886528-4ffc0fa6-713a-4ab7-aa93-806d0c065a82.png)

* Below is the three t-tests that compare each manufacturing lot against mean PSI of the population 
!['Visual%20Data/t.test()%20functions%20and%20subset()s](https://user-images.githubusercontent.com/107222716/191886571-37f3f81f-a32f-42f6-a68a-f9335bd7539d.png)

# Deliverable 4: Design a Study Comparing the MechaCar to the Competition
## Study Design: MechaCar vs Competition

* Below are 4 questions that can answer the statistical study that can quantify how the MechaCar performs against the competition. In this study design, I think about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

* For this statistical study I address the following questions:
  
  1. What metric or metrics are you going to test?
  
    * the metrics I would use for this study design that can quantify how the MechaCar performs against the competition and that would be of interest to a consumer qouls be: safety rating, highway fuel efficiency, horse power, and maintenance cots. 
  
  2. What is the null hypothesis or alternative hypothesis?

   * The null hypothesis is would be that mean for the safety rating is zero
   * The alternative hypothesis would be that the mean for the safety rating is not zero.

  3. What statistical test would you use to test the hypothesis? And why?
  
   * The statistical test that I would use to test the hypothesis would be a multiple linear regression model to get the the statistical summary for Mechacar and their competition, this would allow me to compary the results for stafety rating. 
  
  4.  What data is needed to run the statistical test?
  
  * To run the statistical test we would need to run a random sample for MechaCar and their competition using RStudio using the variables we selected, safety rating, highway fuel efficiency, horse power, and maintenance cots.
  
