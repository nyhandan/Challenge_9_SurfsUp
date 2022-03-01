# Challenge 9 SurfsUp
Attempt 1 Dan Nyhan


## Purpose
W. Avy wants more information about temperature trends before opening the surf shop in Oahu, Hawaii. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December. Then I converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

Deliverable 1 is the June dataframe, and Deliverable 2 is the December dataframe. 


## Results
### June summary statistics:

![June_statistics](https://github.com/nyhandan/Challenge_9_SurfsUp/blob/main/Challenge_9_SurfsUp/June_statistics.png)

### December summary statistics:

![December_statistics](https://github.com/nyhandan/Challenge_9_SurfsUp/blob/main/Challenge_9_SurfsUp/December_statistics.png)

### Three Differences between June and December 
- The minimum temperature recorded in December is 56 degrees, which is 8 degrees less than the minimum temperature of 64 degrees in June

- The standard deviation of December temperatures is ~3.74, whereas the standard deviation of June temperature is ~3.25

- The 1st quartile of December temperatures is 69 degrees, whereas in June it is 73 degrees.


## Summary

### Three Key Points
The 3 key points I derived from the summary statistics are the minimum temperatures, standard deviation, and 1st quartile of temperatures for both June and December. 

The minimum temperature is significant because it can help determine if June and/or December will be subject to days that are too cold to go surfing. That would have a major impact on the customer traffic of the surf shop. 

Standard deviation is also important because it can help predict temperature fluctation from the average in each month. One standard deviation represents 68% of the data from the average, 34% over and 34% under. June has a standard deviation of 3.25 degrees and an average temp of 74.9 degrees. This means there is a 68% chance that the temperature on a day in June will be between 71.65 an 78.15 degrees. December's standard deviation of 3.74 degrees and has an average temp of 71.04 degrees. There is also a 68% chance that the temperature on a day in December will be between 67.3 an 74.78 degrees. 

The 1st quartile metric describes 25th percentile of data, meaning 75% of the data is greater than this set. In terms of the temperatures in this data set, it shows the temperature of coldest quartile of temperatures in relation to the median. This can describe the range of the coldest days to expect for each month, as it is from the minimum (0 percentile) to the 25th percentile. The 1st quartile of December temperatures is 69 degrees, whereas in June it is 73 degrees. 

### Two Suggested Queries
