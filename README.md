# SurfsUp_Challenge

## Overview:
An analysis was performed on temperature data from the state of Hawaii for the months of June and December to look for any difference in temperatures between
those two months. The results of this analysis are being used to determine the feasability of opening a new store that sells ice-cream. In order to understand possible
seasonality and the effect that different seasons may play on ice cream sales it is important to understand the differences, if they exist, of temperature
between summer and winter (when temperatures are most likely to be different).

## Results
Three key differences in the temperature data between the months of June and December are:

1. December has the coldest minimum temperature (56), which is to be expected as December typically has lower temperatures in the northern hemisphere
2. December has a total of nearly 2,000 less readings for the month, despite have 1 more day in the month than June

-		December has a total of 1517 readings
-		June has a total of 1700 readings


3. The temperatures in December are overall lower than in June as evidenced by the percentiles

-  		December percentiles: 25% 69, 50% 71, 75% 74
-		June percentiles: 25% 73, 50% 75, 75% 77
June Data

![Page1](.\Images\june_temp_data.png)

Dec Data

![Page2](.\Images\dec_temp_data.png)

## Summary
The average temperature between the months of June and December in Hawaii is very similar (nearly 75 for June and 71 for December). The maximum temperature is also
similar (85 for June and 83 for December). While December in general is a colder month the temperature for half of the readings (as indiciated using the
percentiles) remains above 70 degrees, and 75% of the readings are 69 degrees or above. Two additional queries that would be beneficial to learn additional information
regarding the similarities and/or differences between June and December are:

1. A query that looks at the difference in the number of readings at different stations and whether tempearture differs among the different stations. This would be beneficial to know if certain areas of the island are warmer/colder than others.
2. A query that looks at precipitation compared to temperatures (ie is there more precipitation with higher or lower temperatures).
