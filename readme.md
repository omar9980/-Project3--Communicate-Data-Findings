# factors that affects Bike Trips ( fordgobike )
## by (Omar Mousa)


## Dataset

>fordgobike system data set
> This data set we are investigating includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. the data has about 183,412 rows ( individual rides ) and 16 columns.

## Summary of Findings

>__>(99.1 %) or riders are less than 65 years old and most of them was between 20 and 40 years old.__ 

>__>most trips' durations was  about 200 to 700 seconds (3 mins to 12 mins)__

>__>most trips are taken at 7 AM and 6 PM, with peaks at 8 AM and 5 PM__

>__>least trips were taken on sundays and saturdays ( week ends ), with peak on Thursdays and Tuesdays__

>__>the data we are investigating was collected in february month only__

>__>about ( 90 %) of the riders are subscribers__

>__>about ( 76 % ) of the riders are Males and ( 22 % ) are females and other gender was about ( 2 % )__

>__>about ( 90,7 %) of the riders are members in the Bike Share for All program.__

><br>> __yes, in the member age distribution i found that there was some people wo are older than 100 years old, actually there was some who are 143 years old which was imposible or hard to belive and they were also affecting our results and destributions.__

><br>>__i included people who were 65 years old or lower only  and they were representing about 99.1 % of the age distribution.__

><br>>__the distribution of durations showed that some people spent more than 80000 seconds on trips (22 hours and 30 mins) it is also hard to belive that number,so the data needed some cleaning.__

><br>__so i kept values with 2800 seconds or less which was representing about (98.6 % ) of the data.__

><br>>__people who are 30 years old spent more time in the trips.__

><br>>__there is a weak positive realtion ship between member age and duration of the trib__ 

><br>>__most of the subscribers and customers are 30 years old, lower percentage of members are above 40 years old.__

><br>>__most trips are taken at 7 AM and 6 PM, with peaks at 8 AM and 5 PM__

><br>>__duration doesn't depend strongly on member's gender__

><br>>__people who are not members in the bike share for all program spend slightly more tims in trips than members.__

><br>>__customers spend more time in their trips on average.__

><br>>__most subsrcribers trips are nearly of the same duration, but subscribers spend different amount of time in their tribs.__

><br>>__there was a huge difference in trips duration eachday with lower values in weekends__

><br>>__there was a huge difference in number of bike riders each day with peaks on weekends__

><br>>__number of subscriber bike riders almost the same for all days.__

><br>>__for all genders there is a weak positive relation between age and trip duration, people whose gender is "other" are more distributed with age about 30 years__

><br>>__people who aren't members in (bike_share_program_for_all) are spending much time on their trips in average cmpared to people who are members in the program.__

><br>>__average trips duration for customers is higher than average trip duration for subscribers.__

><br>>__people who are 18 years old spend much time in trips, people of different ages spend nearly the same time per user type.__

><br>>__in each day in our data set that customers spend much more time on their trips compared to subscribers.__ 

><br>>__although people whose gender is "other" represents the lowst percentage of bike riders in our data, they spend much more time in their trips if compared to "Female" or "Male" , we can also see that females spend more time in trips than males on average.__
## Key Insights for Presentation
<ol>
<li>the distribution of durations showed that some people spent more than 80000 seconds on trips (22 hours and 30 mins) it is also hard to belive that number,i tried to plot my data with logarithmic scale but the outliers was influencing the distribution,i kept values with 2800 seconds or less which was representing about (98.6 % ) of the data, the distribution was right skewed as most trips' duration was about 200 to 700 seconds with mean of about 600 seconds. </li>
<li>the distribution of the age of bike riders showed that some people were older than 100 years old, and some was 143 years old, maybe the data was recorded wrong or people gave wrong birth year number,i set scale as logarithmic scale but the outliers was still affecting my distribution, so i kept only people who are 65 years old and younger which was representing about 99% of the data. </li>    
</ol>

### feedback

>__i showed the data presentation to my sister and asked her about her opinion, she understood most of the visualstions but she was confused about scatter plots and found it difficult even after i illustrated it to her, so i decided to replace most of the scatter plots in the representation with line plots and violin plots and histograms as they are easier to see patterns in them and to understand them.__