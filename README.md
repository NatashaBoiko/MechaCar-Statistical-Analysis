# MechaCar-Statistical-Analysis
## Overview
This new assignment consists of three technical analysis parts and a proposal for further statistical study. 

Part 1: Linear Regression to Predict MPG
Part 2: Summary Statistics on Suspension Coils
Part 3: T-Test on Suspension Coils
Part 4: Design a Study Comparing the MechaCar to the Competition

### Linear Regression to Predict MPG
In this dataset, we are using the independent variables such as vehicle length, vehicle weight, spoiler angle, ground clearance, and All Wheel Drive (AWD), to predict the dependent variable Miles per Gallon (MPG).
![image](https://github.com/NatashaBoiko/MechaCar-Statistical-Analysis/assets/119450584/8780ea89-f6db-4edd-9624-43d8795c6373)

### Summary Statistics on Suspension Coils
The Suspension coil dataset examines all vehicles in 3 different lots. When analyzing all manufacturing lots, we found that the mean PSI is 1498.78, the median PSI is 1500, the count of coils in 150, and the PSI differentiates by 7.89 on average. 

All Lots: The data summary states that the variance of PSI is 62.29, which is less than the stated 100 PSI max, so the entire population does meet the design specification.
![image](https://github.com/NatashaBoiko/MechaCar-Statistical-Analysis/assets/119450584/453be902-9d05-42f5-a692-785f0d79046c)
All manufacturing lots when examined all together, meet the design specifications. However, when analyzing lots separately, only lots 1 and 2 fit the design, and lot 3 does not. With this information, lot 3 is what is causing most of the variation within the model.

### T-Tests on Suspension Coils
![image](https://github.com/NatashaBoiko/MechaCar-Statistical-Analysis/assets/119450584/4d7b3e6c-3499-4e27-bd7f-f15b6c027c85)

### Design a Study Comparing the MechaCar to the Competition
What metric or metrics are you going to test? To examine MechaCar against competition, the metrics will be Price of vehicles.
What is the null hypothesis or alternative hypothesis? Null hypothesis: The Price of the vehicles within the MechaCar have an impact on the MPG. Alternative hypothesis: The Price of the vehicles within the MechaCar does not have an impact on the MPG.
What statistical test would you use to test the hypothesis? And why? I would use a t-test since we are comparing two groups. The t-test would allow us to find the p-value and determine if the prove of the vehicle has a significant impact on the MPG.
What data is needed to run the statistical test? The price for all MechaCar vehicles is needed to run this t-test.

