# Bike-Sharing-Assignment

A bike-sharing system provides bicycles for short-term use, either for a fee or free, often through computer-controlled "docks" where users enter payment information to unlock bikes, which can be returned to any other dock in the system.

BoomBikes, a US-based bike-sharing provider, has faced significant revenue declines due to the COVID-19 pandemic and is struggling to stay afloat. To address this, they plan to develop a business strategy to boost revenue once the lockdown ends and the economy recovers.

To do this, BoomBikes aims to understand the post-quarantine demand for shared bikes. They have hired a consulting firm to identify key factors affecting bike demand in the American market. This firm has gathered extensive data on daily bike demand, considering various factors.

# Business Goal:

Need to model the demand for shared bikes using the provided variables. This model will help management understand how demand varies with different features, allowing them to adjust their business strategy to meet customer needs and explore new market dynamics.

# General Information

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

### The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Technologies Used

- numpy - version 1.20.3
- pandas - version 1.3.4
- matplotlib - version 3.4.3
- plotly - version 5.6.0
- seaborn - version 0.11.2
- statsmodels - version 0.12.2
- sklearn - version 0.24.2

## Conclusion

- For the variable season, we can clearly see that the category 3 : Fall, has the highest median, which shows that the demand was high during this season. It is least for 1: spring .
- The year 2019 had a higher count of users as compared to the year 2018
- The bike demand is almost constant throughout the week. there seems no trend in the weekday dataset thus we can leave this variable for the prediction.
- The count of total users is in between 4000 to 6000 (~5500) during clear weather
- From the "Mnth" boxplot we can see that the months are following a trend and could be a good predictor variable. The bookings in the mid-month are above 4000.
- The count is highest in the month of October
- The count of users is less during the holidays
- From the "Workingday" boxplot we can see that maximum bookings happening between 4000 and 6000. There is not much of difference in booking whether its working day or not.  


## Contact

Created by [@rupali1013] - feel free to contact me!
