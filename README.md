# surfs_up

**Purpose**

The purpose of the surfs up analysis was to determine the temperature trends for a surf shop in Oahu. This analysis was specifically carried for the months of June and December from the years of 2010-2017 in Oahu. Graphs were added to easily view the statistics from each month and for visual representation of the data. Important to note, graphs are more user-friendly to read and understand the data on hand versus a table. 

**Results**

June Data
<img width="1423" alt="Screen Shot 2022-01-04 at 7 21 06 PM" src="https://user-images.githubusercontent.com/90429568/148141455-8b51d8d9-0224-4235-bbb4-add41e3dcb36.png">
Upon initial glance of the table, the following could be noted:
- Mean temperature for the month of June falls at approxmately 75 degrees
- Min temperature is at 64
- Max temperature is at 85
- From the graph, it can be inferred that temperatures range from 65-85 degrees and approximately 1,750 readings were collected. Indicative that the dataset is siginificant in sample size and not small.
- The list of the datapoints further add validity to the data as the statistics for the month of June are gathered from the year 2010 till the year of 2017. It's seven years worth of data and as such accurately represents the weather patterns for the months of June and December in Oahu.

In contrast, the following is December Data:

<img width="1423" alt="Screen Shot 2022-01-04 at 7 27 48 PM" src="https://user-images.githubusercontent.com/90429568/148141906-ce2e7c3d-c555-46f8-aaea-8603ab0dee9b.png">

As already mentioned, upon intial glance for the month of December table, the following could be noted:
- Mean temperature for the month of December falls at approximately 71 degrees
- Min tempearature is 56
- Max temperature is 83
- The graph shows that december temperatures are a little bit colder than June since the minimum temperature in June is around 64 but for the month of December its at 56. While, the minimum temperature is one of the indicators of the temperature differences between the June and December, it is also an outlier. This is because the mean temperature for Dec is similar to mean temperature for June, around 70 degrees. Furthermore the max temperatures for both months are at 80 degrees. 
- It is aslo important to note while the time range for both June and December is same i.e. 2010-2017, number of data points collected varies. There were only 1,400 readings recorded for the month of December in comparison to 1,750 readings for the month of June. While the dataset only differs by about 300 data points, it does not play a huge role in skewing the dataset. Overall, both June and December temperature graphs show a similar trend. 

**Summary**

While the average temperatures are similar it would be ideal to know which temperatures occur the most in the month of June and December. To gather this information, a histogram plot was created.
<img width="1423" alt="Screen Shot 2022-01-04 at 8 00 12 PM" src="https://user-images.githubusercontent.com/90429568/148144304-04128c71-2df5-4bb9-84b6-25a00d1eb02f.png">
From this histogram it could be inferred that 75 and 80 degree temperatures occur the most at a frequency of about 300-350 times.

-<img width="1423" alt="Screen Shot 2022-01-04 at 8 02 59 PM" src="https://user-images.githubusercontent.com/90429568/148144406-cee1de71-d9a0-41bd-b40e-d5b377a4baee.png">
In contrast, December histogram shows similar frequencies for the temperatures ranging between 75-80.
In terms of the variability of the data, June's data seems to be more variable in comparison to December. However the median is in line with the mean in both graphs, indicating a normal distribution and as such statistically significant results. 
From this analysis, it seems like both June and December are suitable months for opening up a surf shop in Oahu. However, knowing a specific station would be helpful. To achieve this, stations dataset was merged with temperature dataset to determine which station would prove to be the ideal location for the surf shop.
Since, there were a lot of data points, following steps were taken to clean up the dataset in a meaningful manner:
- Two dataframes were created: 1- June and 2- Dec
- These two dataframes were merged and then duplicates and NA values were dropped
- There were still too many datapoints to go through and as such an analytical decision was made to see which stations hit the mean of the mean i.e. 73 (71+75/2) in both months of June and December and 9 different stations populated in the list as follows:

<img width="1423" alt="Screen Shot 2022-01-04 at 10 35 26 PM" src="https://user-images.githubusercontent.com/90429568/148157296-a3586c33-365e-44c9-b9e3-0e704a96609b.png">

In real world, more analysis would have to be done i.e. other weather conditions around these stations such as wind speed and the probablity of storms around each station. However, at the moment these 9 stations would be ideal for the surf shop that will be sustainable all year round.



