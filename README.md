## Overview

The goal of this project was to create a multiple linear regression and random forest model to predict high rider gratuity or not. This project utilized 
yellow taxi trips taken in New York City during 2017. The final random forest model performed with an F<sub>1 </sub> score of 72% which represent the precision and 68% accuracy, this model help determine what features were most important in separating low tippers from high tippers. Based on the model, the duration, distance, and fare amount were most influential in determining a generous tipper (>20%) vs a non-generous one (<20%). 

## Business Understanding

According to salary.com the average salary for a New York Taxi Driver is around $46,000 - $60,000 per year. From apartments.com, as of October 2024, the average rent in New York, NY is $3,863 per month. This is 147% higher than the national average rent price of $1,564/month, making New York one of the most expensive cities to rent an apartment in the US. Therefore, it is important to understand what factors encourage riders to leave tips in order to help drivers obtain a livable wage. 

## Data Understanding

The NYC Taxi and Limousine Commission data are provide from the google advance data analytics certificate courses. The data consisted of approximately 408k unique trips and 18 features. The features included information on trip duration and destination, vendor used, toll information, and payment type. The bar chart below shows the breakdown of how many generous tippers (1) versus non-generous (0) tippers that exist in the data set. 

![oie_3WFNsOARdxtm](https://github.com/user-attachments/assets/3f6271de-d748-4df6-bebe-54c3d84dfe7e)

## Model and Evaluation

A random forest model comprising 300 decision trees was used to determine feature importance in who would tip generously or not. The below plot shows that 
trip duration, distance, fare cost, and vendor_ID were the top most important factors in determining a generous tipper from a non-generous one. The overall model performed with 68% accuracy and 72% precision.

![Feature importances](https://github.com/user-attachments/assets/34d47abb-13dc-4991-b496-764f0c5adc47)

## Conclusion

This model can benefit Taxi Drivers in knowing if they will be tipped generously or not; however, running a parametric model to determine how much each 
variable will influence the actual price of the tip. In the future, adding more information on a rider’s past tipping behavior may also be beneficial in 
helping the stakeholder address their business problem. This model is recommend since it performs acceptably. Precision score was 72% and it had an overall accuracy of 68%. It correctly identified ~78% of the actual responders in the test set, which is 48% better than a random guess. It may be worthwhile to test the model with a select group of taxi drivers to get feedback.


