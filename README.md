# surfs_up

## Overview of the Analysis
Our client, W. Avy, is interested in opening a new start-up surf and ice-cream shop on the Hawaiian island of Oahu.  W. Avy wants to be sure that this would be a wise business investment that could be profitable throughout the entire year.  Climate temperature was his biggest concern; so to help get a better understanding, we needed to extract weather data during what might be considered the hottest and coldest months of the year, on avearge.  Therefore, two seperate queries were completed for the months of June and December using data acquired through the SQLAlchemy database.  After extracting all the necessary temperature information, we are able to create data frames that will help W. Avy evaluate and compare the temperature extremes for Oahu, and be able to make an informed business decision.

## Results*

#### June Temperature Summary
![image](https://user-images.githubusercontent.com/93561592/154825604-8fae3532-8640-42c2-bc16-4bbc59ddbd5d.png)

The maximum recorded temperate out of 1700 days of information was only 85.0 degrees, with a minimum temperature of 64.0 degrees.  The overall daily average for June came in at 74.94 degrees.

#### December Temperature Summary
![image](https://user-images.githubusercontent.com/93561592/154825854-50f449cc-6320-4456-9bad-0e3b4482dad4.png)

The maximum recorded temperate out of 1517 days of information got as high as 83.0 degrees, with a minimum temperature of only 56.0 degrees.  The overall daily average for December came in at 71.04 degrees.

### Key differences from the results
* There were 183 more days of data for the month of June; though with over 1500 days of data for both months, this would probably only have minimal to no measurable variances in the results
* The overall daily average temperature was only about four degrees higher for the month of June compared to December, indicating that the seasonal temperature variances remain relatively consistent throughtout the year.
* The daily temperature appears to be more variable for the month of Decemeber than June given its larger range of recorded minimum and maximum temperatures.

## Summary
When comparing the yearly temperatures for Oahu using our findings, it would be reasonable to conclude that a surf and ice-cream shop would certainly be able to maintain sound  operations throughout the year, without having to make significant seasonal adjustments.  However, it should be noted that comfortable temperatures are only one factor in determining the overall climate in any given area.  Precipitation, severe weather threats, and daylight hours are just a few examples of some other areas that should first be evaluated to help W. Avy make the best decision possible.  We can gather more data and process additional queries to help us give W. Avy our best reccommendations, but that will be for another challenge.

**All temperatures are recorded in Fahrenheit*
