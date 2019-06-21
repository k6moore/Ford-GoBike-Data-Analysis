# Ford GoBike Bay Wheels Data Exploration

This project explores a dataset containing Bay Wheels's bike trip data for 2018.

## The Dataset
The data consists of information for 1,863,721 bike trips including duration, start time, end time, user type, member birth year, member gender and other bike trip features.
The data for each month can be found at [here]https://s3.amazonaws.com/baywheels-data/index.html with 

## Main Findings
During my exploration, I found majority of the bikers were male between the age of 31-40 and that there were way more Subscribers than Customers.

I found The age group category had the most effect on month of travel, day of the week of travel and hour of travel.
As expected, the two younger age groups bike more than older age groups. 
But interestingly, between Januray and June, most bikers range between ages 31-40, while July to December, most bikers range between ages 18-30. 
Another intersting observation, is that during the week, most bikers range between age 31-40, while on the weekends most bikers range between ages 18-30.
We could also see most bikers travel at 8:00 AM and 5:00 PM no matter tha age group. 


## Key Insights for Presentation
For the presentation I focused on the effects of age groups and gender on month of travel, day of the week of travel and hour of travel. 
First, I start by introducing each categorical variable of interest one by one. 
I then show their relationship to each other using clustered bar charts, box plots and violin plots by comparing biker categories (age and gender) against time categories (month of travel, day of the week of travel and hour of travel).