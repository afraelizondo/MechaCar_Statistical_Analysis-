# MechaCar Statistical Analysis 


## Linear Regression to Predict MPG

The slope of the linear model is not considered to be zero, this is due to the fact that the p-value is 5.35 x 10-11, so much smaller than the assumed level of significance, which means there is sufficient evidence to reject the null hypothesis, coming to the conclusion that the slope of the lineal model is not zero. 

This linear model predicts mpg of MechaCar prototypes decently, because the value of the residual standard error is 0.7149. Since it is not 0, it is more likely that it can predict some of the outcomes, but not the complete diagnostic for this model. 

The coefficients that provided non-random amount of variance to the mpg values in the dataset are:
- Vehicle length
- Ground clearance

If this model is performed without these two coefficients, it would get a bad fit.

<img width="378" alt="Screen Shot 2023-01-30 at 7 41 32 PM" src="https://user-images.githubusercontent.com/113856917/215639019-7bccf4fa-42ae-4288-a61d-4c39776993a0.png">


## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

<img width="248" alt="Screen Shot 2023-01-30 at 7 50 31 PM" src="https://user-images.githubusercontent.com/113856917/215639212-bfeef2d5-b9b2-447f-9a41-46f0904cd60c.png">

<img width="369" alt="Screen Shot 2023-01-30 at 7 50 40 PM" src="https://user-images.githubusercontent.com/113856917/215639225-926bed98-c0c2-4556-ae2b-9cc1c82bf72d.png">

## T-Tests on Suspension Coils

The value of t-test statistic is -1.8931, while p-value is 0.06. The p-value is above the assumed significance level. Therefore, we would state that there is not enough evidence to reject the null hypothesis and we can confirm the mean of the population and samples are not statistically different.

With these two values, we can assume that th=he alternative hypothesis is false, as it is stating "True mean is not equal to 1500".

<img width="328" alt="Screen Shot 2023-01-30 at 7 52 44 PM" src="https://user-images.githubusercontent.com/113856917/215639481-ee63f6a7-2ff6-442f-bbf9-72564f8dbd81.png">

<img width="451" alt="Screen Shot 2023-01-30 at 7 54 01 PM" src="https://user-images.githubusercontent.com/113856917/215639637-f5d31897-774d-46ba-99cc-eab0a9fbba19.png">

<img width="458" alt="Screen Shot 2023-01-30 at 7 54 34 PM" src="https://user-images.githubusercontent.com/113856917/215639709-376c413d-bd14-4466-a9ea-90e2926625da.png">

<img width="452" alt="Screen Shot 2023-01-30 at 7 57 06 PM" src="https://user-images.githubusercontent.com/113856917/215640217-826df454-dc91-4f5c-94be-db49cf901917.png">


## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

In your description, address the following questions:

What metric or metrics are you going to test?

What is the null hypothesis or alternative hypothesis?

What statistical test would you use to test the hypothesis? And why?

What data is needed to run the statistical test?
