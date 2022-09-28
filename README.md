# Ford-GoBike-System-Dataset-Analysis
# Ford GoBike System Dataset
## by Zhiyu Wang


## Dataset

> The dataset describes information about 183,000 rides in the Ford GoBike System covering the greater San Francisco Bay area, with user behavior as well as user demographic information.


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

## Key Insights for Presentation

1. The riding frequency is higher on weekdays, and has it peak at 8-9am and 16-18pm.
2. There are two peaks in the Start Hour-Duration heat map, one between 8-10 am and the other between 16-18pm. The duration of both peaks are 5-10 minutes. It indicates that the most users choose to use sharing bikes to commute, with a 5-10-minute travel distance.
3. The durations of subscribers among the week don't change a lot on average. The durations of subscribers at weekends are higher.
