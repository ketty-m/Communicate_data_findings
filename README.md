# (Ford GoBike Trip data Visualization)
## by (Ketty Muwowo)


## Dataset

> In this project, the dataset selected for exploratory and explanatory data visualization is the Ford GoBike Trip data. The following link can be used to assess this dataset https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv. It includes information about the rides made in a bike-sharing system covering the greater San-Francisco Bay area. The dataset contains trip data for the month of February 2019 and consists of 183,412 trips with 16 features. Some of which include:


- duration_sec : The duration of the trip in seconds.


- member_gender : The gender of the members, whether Male or Female.

- member_birth_year : The date of birth for each user.

- start_time : The start time for each trip.

- user_type : The type of bike user whether Customer or Subscriber.


- age : The age of the bike users which will be derived from the member_birth_year variable.

  
- period_ofday : The period of time in a day, such as morining, afternoon and evening. Derived from the start_time variable.

- duration_min : The trip duration in minutes.

This dataset contains the object, int64 and float64 datatypes. Upon carrying a bit of data wrangling steps, we found some issues to do with inappropriate data types and missing values. This issues were fixed before any exploration was undertaken.






## Summary of Findings

> Upon data exploration, the following points are a summary of the findings:



- The distribution of member age right skewed and spread mostly between 20-40 years with the presence of some outliers.

- The Majority of bike users are subscibers.

- Male gender type are in majority.

- Most trips are taken in the afternoon and morning periods of the day.

- The top 5 most famous start stations are :


     * Market St at 10th St

     * San Francisco Caltrain Station 2 (Townsend St at 4th St)
 
     * Berry St at 4th St

     * Montgomery St BART Station (Market St at 2nd St)

     * Powell St BART Station (Market St at 4th St)
     

- The Male gender has a slightly shorter trip duration time compared to the Females.

- Subscribers tend to have a shorter trip duration than customers.

- For the both user types, the male gender are in majority.

- The customer user type tend to use the bike services more in the afternoon and have a higher trip duration time compared to subscriber user type.

- The subscriber user type has a higher mean age across all gender types compared to the customer user type.

- There is a strong correlation between start station longitude and end station longitude.



## Key Insights for Presentation


> The following are the key insights that I had choosen to add in the presentation as these convey the main important relationships, patterns and factors that may influence the decision of selecting and  determing a better marketing plan or strategy for the bike sharing company.


> The key insights selected are:


- The top 5 famous start stations are :


     * Market St at 10th St

     * San Francisco Caltrain Station 2 (Townsend St at 4th St)
 
     * Berry St at 4th St

     * Montgomery St BART Station (Market St at 2nd St)

     * Powell St BART Station (Market St at 4th St)
 
 - The most prominent user type is the subsciber.
 
 - On average most trips do not last longer than 60 minutes.
 
 - Afternoon and morning periods of the day are the peak periods when most trips are taken.
 
 -  For both user types, the male gender are in majority.
 