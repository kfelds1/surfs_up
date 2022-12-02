# Surfs Up


## Purpose

The purpose of this analysis is to help W. Avy, an experience investor, determine if his surf and ice cream shop in Hawaii would bring in customers year round. To do this, it is necessary to learn more about weather trends at various times of the year, so W. Avy picked June and December: two months at opposite points in the year. By using the hawaii.sqlite database, I extracted all of the temperatures listed for these months and converted the data into a more understandable format through queries and Pandas Dataframes. This information is key to helping W. Avy run a successful surf and ice cream business, two activities that mostly require warmer temperatures.


## Results

- For the most part, the summary statistics between June and December are relatively similar. For example, the mean temperature for the month of June is about 74.9 degrees and the mean temperature for the month of December is about 71 degrees. Another instance is when comparing the maximum temperatures for the two months: the maximum temperature for June is 85 degrees and the maximum temperature for December is only 2 degrees lower at 83 degrees.
- One main difference in the summary statistics between the two months is the minimum temperature. The minimum temperature for June is 64 degrees and the minimum temperature for December is 56 degrees. Though it is not too drastic of a difference, W. Avy might have to prepare for those colder days in December when customers might not be interested in surfing or getting ice cream.
- One last point when exploring the temperatures in Oahu for these two months is that the temperature range is larger in December than it is in June. The standard deviation for temperatures in December is about 3.75 and for that of June it is about  3.26. There is more variability in temperature in DEcember, which might make the flow of customers into the surf and ice cream shop more unpredictable.
![Screen Shot 2022-12-02 at 10 27 56 AM](https://user-images.githubusercontent.com/112633146/205327741-462ee01d-de73-4fe4-9c67-1ffe77f74bf0.png)
![Screen Shot 2022-12-02 at 10 28 05 AM](https://user-images.githubusercontent.com/112633146/205327761-d0469a76-1f2c-41e6-8229-b91c67887633.png)


## Summary

Ultimately, this weather data on temperature specifically is a great start to inform W. Avy on whether or not he should have his shop open year round. The temperature evidently affects someone's choice to go surfing or consume ice cream that day. However, as mentioned in the 'Results' section, there is not too drastic of a difference in temperatures between the two months. December's temperatures are slightly lower, which might raise some concern in surfing and ice cream popularity, but it likely is not enough information to allow W. Avy to make a decision. We must explore other weather variables that may impact the likelihood of surfing and ice cream consumption.

Since Oahu is a tropical island, rain can often be sudden and unpredictable. Is there a time of year when it is rainier than others? Using the hawaii.sqlite database to explore rain trends in June and December could inform W. Avy's choice to stay open year round. 

After creating two additional queries outlining the amount of rainfall on the island in June and December, we can see that December has a higher average rainfall at 0.22 inches compared to June's average rainfall of 0.14 inches. In addition, the standard deviation of rainfall in December is higher than that of June, indicating a larger variability in rainfall in December. Similar to the temperatures, this might mean that the rain trends are more unpredictable in December. Seeing as December is a rainier season than June, in combination with the slightly cooler temperatures, W. Avy might have to strongly consider whether or not keeping the shop open in the colder season is the best idea for him financially.

![Screen Shot 2022-12-02 at 10 44 46 AM](https://user-images.githubusercontent.com/112633146/205331343-1c56ad4a-43c3-4ef4-9385-f63006a7fee0.png)
![Screen Shot 2022-12-02 at 10 44 53 AM](https://user-images.githubusercontent.com/112633146/205331380-b714b115-801c-4b01-bb98-df7092e10f36.png)

