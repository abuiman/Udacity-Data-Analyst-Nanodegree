# (Dataset Exploration Title)
## by (your name here)


## Dataset

> The dataset, 201902-fordgobike-tripdata.csv, is downloaded from Ford GoBike and licensed by Ford GoBike. This dataset includes ,23650 trips with 23 features such as locations, time, and user attributes. There are start and end stations. I noticed that most trips happen on the same stations, so I subset the dataset by choosing top 8 trips start stations with the most trips.


## Summary of Findings

> Univariate exploration: The number of trips gradually decreases when winter is coming. I assume that Thursday's trips are influenced by the launch of the program. During the day, there are more trips in the morning and afternoon than the night. It probably because of rush hours. Also, the number of trips in the afternoon is less than the morning. I assumed when riders come back home, they might not be back in the afternoon. Probably, they come back during the night so some trips fall into nighttime. It makes sense that there are more trips during the weekdays and less trips during the weekends because of working schedule.

Bivariate exploration: there is a slightly negative correlation between age and duration of trips. After separation the top 8 stations, half of stations have the most trips in the morning and another half of stations has the most trips in the afternoon. Weekdays have the most trips than weekends. In each day

Multivariate exploration: separating user types, customers and subscribers, gives more insights. Customers like to bike during the weekend and in the summer. Also, the number of trips increases in the tourist attractions like ferry building and Embarcadero. On the other hand, the trips in subscribers increase during the weekdays and after launching, the number of trips gradually increases and then decreases when the weather becomes colder. Moreover, customers ride longer than subscribers. Both of them have the longest trips at night.


## Key Insights for Presentation

> The stations with the most trips are located in San Francisco and connect to public transportations including Caltrain, Bart and Ferry. User types play a key factor on the number of trips in each location and time group. For customers, there are more trips in the weekends and in August. They also have longer trips. On the other hand, for subscribers, there are more trips during the weekends and the number of trips is influenced by the climate change. Thus, collecting more information individually from these two user types is important for the future analysis.