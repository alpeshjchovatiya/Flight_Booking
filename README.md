### Title:Flight Booking Price Prediction  
### Author: Alpesh Chovatiya

### Problem Statement:
Flight ticket prices fluctuate due to a variety of factors, such as the airline, the time until departure, the route, and more. For travelers, predicting the price of a flight is crucial for planning and saving costs. The goal is to analyze various factors that influence the price of flight bookings and develop a predictive model to forecast flight prices.

### Objective:
To build a machine learning model that predicts the price of flight tickets based on features such as airline, flight route, time of day, duration, number of stops, and the number of days left before departure. This model will help customers make informed decisions on when to book flights and at what price.

### Dataset Overview:
This dataset contains  300153 records with following 11 columns.  

**1. airline:** The airline offering the flight.  
**2. flight:** Flight number or identifier.  
**3. source_city:** The city of departure.   
**4. departure_time:** The time of day of the departure (e.g., Morning, Evening).   
**5. stops:** Number of stops during the flight.   
**6. arrival_time:** Time of arrival at the destination.   
**7. destination_city:** The destination city.    
**8. class:** The class of the flight (e.g., Economy).     
**9. duration:** Duration of the flight (in hours).  
**10. days_left:** The number of days left before departure.   
**11. price:** The price of the flight ticket (target variable).        

### Summary of Results:
**Random Forest:** 0.98     
**Decision Tree:** 0.97   
**XGB:** 0.97    
**K-Nearest Neighbors:** 0.97  
**Adaboost:** 0.93    
**Lasso:** 0.90   
**Ridge:** 0.90  
**Linear Regression:** 0.90   

#### Best performing model for current dataset is Random Forest  with accuracy of 98%.
