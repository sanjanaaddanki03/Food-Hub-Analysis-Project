# FoodHub Data Analysis for Business Growth

This project analyzes ordering data from FoodHub with the goal of understanding customer behavior, cuisine preferences, delivery performance, and ratings in order to improve operational efficiency, customer satisfaction, and overall business growth. The analysis focuses on identifying meaningful patterns and answering strategic questions using exploratory data techniques.

## Business Context

FoodHub wants to determine which restaurants and cuisines generate the most orders, analyze factors influencing ratings, and identify where improvements can be made in speed, quality, and customer retention. The findings are intended to guide marketing strategy, staffing optimization, and customer loyalty programs.

## Dataset Overview

- 1898 total orders  
- 9 features (categorical and numerical)  
- No missing values, though “Not rated” accounted for 736 entries  
- Food preparation time ranged from 20 to 35 minutes, with a mean of 27  


## Key Findings

### Customer Demand and Ordering Patterns
- There are 14 cuisine categories, with American as the most frequently ordered, followed by Japanese and Italian.  
- Weekend order volume is significantly higher than weekday volume.  
- Approximately 29.24% of orders cost above $20 (555 orders).  
- A small number of customers account for the highest order volume, with the top customer placing 13 orders.  


### Restaurant Performance
Top restaurants by number of orders:
- Shake Shack (219)
- The Meatball Shop (132)
- Blue Ribbon Sushi (119)
- Blue Ribbon Fried Chicken (96)
- Parm (68)


Restaurants suitable for promotional offers based on high volume and high ratings:
- The Meatball Shop (4.51)
- Blue Ribbon Fried Chicken (4.32)
- Shake Shack (4.28)
- Blue Ribbon Sushi (4.22)


### Pricing, Delivery, and Ratings
- Mid-priced orders tend to receive higher ratings.  
- There is a strong positive correlation between preparation time and delivery time, meaning operational delays at the kitchen level affect total delivery duration.  
- Shorter delivery times are associated with higher ratings.  
- Mean delivery time:
  - Weekends: 22 minutes  
  - Weekdays: 28 minutes  


## Recommendations

- Reduce delivery times for restaurants with lower ratings to increase customer satisfaction.
- Focus weekend marketing on popular cuisines such as American.
- Offer loyalty incentives for frequent returning customers.
- Optimize staffing and delivery resources on weekdays to reduce longer delivery times.


## Approach

- Conducted univariate and multivariate exploratory data analysis.
- Compared cuisines with cost, prep time, delivery time, and ratings.
- Examined delivery trends by day of week.
- Identified correlations to determine operational improvement areas.


## Author

Sanjana Addanki  
FoodHub Data Analysis Project  
