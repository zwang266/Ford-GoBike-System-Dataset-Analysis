# Ford-GoBike-System-Dataset-Analysis
## by Zhiyu Wang


## Dataset

> The dataset describes information about 183,000 rides in the Ford GoBike System covering the greater San Francisco Bay area, with user behavior as well as user demographic information.

## Key Insights for Presentation

### Distribution of rides by day of week and hour

#### On which day of week there are most traffic?
> On weekdays, the amount of rides doesn't have significant difference bewtween each other, around 27,500 trips per day.
> At weekends, the amount of rides decreases by around 50%, around 14,000 trips per day.

#### At which time of day there are most traffic?
> The peak of traffic occurs around 7-9am and 16-18pm.
> Between 10am and 15pm, the hourly traffic is around 7,500.
> Before 7 am and after 18pm, the amount of rides decreases dramatically
> During the midnight (1-5am), there are rarely people using GoBike.

### Duration by hour of day

#### What's the average duration of each hour of day?
There are two peaks in the Duration-Hour heat map, one between 8-10 am and the other between 16-18pm.
The duration of both peaks are 5-10 minutes.
Considering that most of the rides happen on weekdays. It's deduced that the most users choose to use GoBike to commute.
Most of the users choose GoBike to travel a 5-10 minute distance.

#### Duration by day of week per user type

#### What's the usage patterns of different user types?
The durations of subscribers among the week don't vary a lot on average between each other.
The duration of customers are higher at weekends compared with that on weekdays.
The average duration of customers are higher than that of subscribers everyday.
The IQR of duration are higher at weekends for both groups.

## Summary of Findings

### Univariate Exploration:
1. The dataset only contains trips starting in Feb.
2. **The riding frequency decreases significantly at weekends**
3. **Peaks occur around 8-9am and 16-18pm, which are the same as commute time.**
4. The distribution of duration has a long tail. When transforming into a log scale, the plot may fit a normal distribution, with a peak between 5-20 minutes.
5. 75% of the users are male.
6. The distribution of age has a long tail and skew left. There's a peak between 25 and 35 after applying a log transformation.
7. At weekends, trips take longer time compared with those on the weekdays.
### Bivariate Exploration:
8. **There are two peaks in the Start Hour-Duration heat map, one between 8-10 am and the other between 16-18pm. The duration of both peaks are 5-10 minutes. It indicates that the most users choose to use sharing bikes to commute, with a 5-10-minute travel distance.**
9.User Type vs. Duration: Subscaibers have shorter trips on average, but more outliers.
10. User Type vs. Sharing: bike sharing is only available to subscribers.
11. User Type vs. Day of Week: On weekdays, the user type doesn't affect the daily traffic of goBike. At weekends, the daily frequency of customers doesn't change a lot, while that of subscribers drops a lot.
12. 24-33 year-old users are the main group of the users. They mostly take 5-10 minutes trips. And this is the only peak of the heat map.
### Multivariate Exploration:
13. **The durations of subscribers among the week don't change a lot on average. The durations of subscribers at weekends are higher.**
14. The age and duration of subscribers are intensely distributed in the lower left of the plot: 20-35 year old, 3-15 minutes. The age and duration of subscribers are sparsely distributed.

