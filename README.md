# (Toronto Bus Delay EDA)
## by (Eniang, Eniang Nsa)


## Dataset


    The Toronto Bus Delay Dataset was gotten from Kaggle. It is the Bus Delay from The TTC that was recorded for the first 6 month of the year 2022. It consist of 27351 records and 10 Fields.
    The steps taken was first to download the data and load it on the Machine. Then explore it to get familiar and see its structure. I spotted some inconsistency in it, like some missing values and data in the wrong format. This was adequately taken care of.
    Then i moved on to the do further exploration and analysis in this fields i was interested in. One Drawback i experience in this choice of data was that it had not much Numeric Fields i could do calculations with. I had more Categorical variables to do my analysis with.

## Summary of Findings

1. Kipling and Kennedy Stations appeared most in our data. 

2. For the Incident which i called the reason for the delay, the Operations and Mechanical occurred most. 

3. For the total hours spent by each Incident that led to delay, we had Diversion with the highest or should i say longest hour spent. This is a suprising Phenomenon. Although the Diversion had a relatively low frequency, it had the longest hour spent during delay. Which means, once the incident that leads to delay is Diversion, we should expect it to last for a while according to our data.

4. For days with the longest delay time, Wednesdays and Thursday were the Highest. The rest had a fairly close amount in hours except Sunday that had the least Delay time.

5. Faceting for each Incident, Diversion that had the highest amount of delay time had a relatively low frequency of Daily occurrence. Whereas, Operations and Mechanical Incident had high frequencies daily through out the week. This tells us something about the city and transport system of toronto. 

6. Also when we did a Faceting with the number of hours daily for each Incident, we saw that Diversion had higher Min Delay times for all the days of the week. Also Incident recorded as "General" also had a high Min Delay time. The Operation and Mechanical had a low Min Delay time. What this means is that, although the Operations and Mechanical had high occurrence, they did not last so long compared to the Diversions and General incident. Once the Incident that is causing the delay is Diversion, we can expect to wait longer compared to other reasons.

7. When The column of focus was Day, a Faceting plot of Min Delay time showed a pattern that Diversion had it's highest on three days of the week, Monday, Wednesday and friday. Other days were low. Operations and Mechanical were low on these days too. However, other Incident were high on days when Diversion was low. We see a Fluctuating Pattern.

## Key Insights for Presentation

1. Wednesdays have a the highest delay times. 
2. Diversion have a low frequency in terms of occurrence but has a much higher impact in the lenght of time it spends when it occurs. This is clearly seen from the visuals.
