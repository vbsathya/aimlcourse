# AI/ML Course
## Practical Application Assignment 5.1: Will the Customer Accept the Coupon?
### Based on the observations on exploring acceptance for the "Bar" coupon type
- Drivers who go to bar atleast once a month and aged below 30 years has the most acceptance rate for Bar coupons.
- The following User Attributes predict the probability of accepting Bar coupon
    - Age less than 30
    - Visiting the bar at least once a month
- The following Contextual Attributes predict the probability of accepting Bar coupon
    - Not having kids as passengers

### Some observations based on the exploration of acceptance of "Restaurant coupon that is less than $20"
- Income is not a big predictor of coupon acceptane
- Acceptance rate is high when people are travelling to a not so urgent place
- Acceptance rate is high when the weather is sunny compared to snowy or rainy
- Drivers travelling alone has lowest acceptance rate
- Below in their 20s or in their 40 has higher acceptance rate
- Coupon that has longer expiration date has higher acceptance rate
- Coupon has highest acceptance rate in the evening around 6 PM

## Practical Application Assignment 11.1: What Drives the Price of a Car?
### Based on the data exploration, model building and evaluation, below are my observations
- I used different linear regression algorithms and different methods for feature engineering and hyperparameter tuning. Based on the observation, it's difficult to predict what used car drivers are looking for in a car because our dataset has different type of cars. However, we can use these models to predict price of used cars. We can see that 'number of cylinders', 'odometer', 'age of the car', 'condition of the car', 'size','type' features influence the price more. As expected the higher the cylinder, the higher the price. Odometer and age features have negative correlation to price.

## Practical Application Assignment 17.1: Will a customer subscribe or not for CD in a bank?
 After analyzing and preparing the data, I used various classification algorithms to build the models. Based on my observation, K-Nearest Neighbors algorithm performed slightly better than others and Decision tree algorithm performed the worst.
