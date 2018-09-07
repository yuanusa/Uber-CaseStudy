# Uber Churn prediction
Churn prediction
Uber is interested in predicting rider retention.

## Project overview
Uber is interested in predicting rider retention. To help explore this question, they have provided a sample dataset of a cohort of users who signed up for an account in January 2014. The data was pulled several months later.
## Dataset description
city: city this user signed up in

phone: primary device for this user

signup_date: date of account registration; in the form ‘YYYY­MM­DD’

last_trip_date: the last time this user completed a trip; in the form ‘YYYY­MM­DD’

avg_dist: the average distance *(in miles) per trip taken in the first 30 days after signup

avg_rating_by_driver: the rider’s average rating over all of their trips

avg_rating_of_driver: the rider’s average rating of their drivers over all of their trips

surge_pct: the percent of trips taken with surge multiplier > 1

avg_surge: The average surge multiplier over all of this user’s trips

trips_in_first_30_days: the number of trips this user took in the first 30 days after signing up

luxury_car_user: True if the user took an luxury car in their first 30 days; False otherwise

weekday_pct: the percent of the user’s trips occurring during a weekday

## Define a Churn
Add churn indicator. 
Considered to churn if have not taken a trip in the last 30 days. 
In practice, you will often have to figure out how to generate a reasonable label to train your dataset. 

Is the cutoff of 30 days reasonable? You may want to test this... Sometimes, the correct label is even less obvious; your ability to make a sensible (and defensible) decision in these cases is important.

keep working
