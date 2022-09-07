# Ford GoBike System Data Exploration
## by Chukwudi Chidubem


## Dataset

> The dataset was made up of 183412 rows representing the number of trips and 16 columns representing variables but after some data wrangling was applied the data is now made up of 174952 rows and 16 columns. Also, the dataypes of some columns have been changed and some feature engineering has been applied to the dataset. The variables presented in the dataset are:
- duration_sec (int dtype)
- start_time (datetime dtype)
- end_time (datetime dtype)
- start_station_id (float dtype)
- start_station_name (object dtype)
- start_station_latitude (float dtype)
- start_station_longitude (float dtype)
- end_station_id (float dtype)
- end_station_name (object dtype)
- end_station_latitude (float dtype)
- end_station_longitude (float dtype)
- bike_id (int dtype)
- user_type (object dtype)
- member_birth_year (int dtype)
- member_gender (category dtype)
- bike_share_for_all_trip (object dtype)

## Summary of Findings

> In the exploration, I found that most of the users were male, between the ages of 25 - 45 years old and subscribers. I also found out that the most common start stations where also the most common end stations. I had to perfrom logarithmic transformation when plotting the distribution of the Trip duration in which I discovered that most users spend a moderate amount of time with the bikes. I also discovered there's a strong relationship between the duration and the user type, But before I could discover that I had to perform another logarithmic transformation to get a clear visualization of the relationship. There was strong relationship between the duration and the genders too.

>Outside of the main variables of interest, I verified that there were no relationships between the other features. Including during the Multivariate section, the relationships between the main feature and the other features were not strengthened  by including another feature.


## Key Insights for Presentation

> For the presentation, I focus on the influence of Age, User Type and Gender on the Trip duration and will leave out other features. I start by introducing the Trip duration variable, followed by the pattern in Age distribution, then plot the transformed age distribution.

> Then, I introduce each categorical variables one by one. To start, I use a subplot with a barplot and a transformed box plot to sure a very picture of the relationship between User Type and Duration. The other categortical variable (gender) using barplots. I have made sure to use different color palettes for each quality variable to make sure it is clear.