# employment_analysis
In this project, I have tried to extract employment and unemployment data of USA using Python's web API from FRED.

Aim - Pull down Employment data from FRED using their Python API

Result: We used an incredibly rich data source and then performed the following actions <br>
a. Observe and extract the data using relevant API calls
b. Transform the data into relevant tables for further use
c. Loading the dataset in respective dataframes which was then used for Feature Engineering

Data was cleaned of noise and we performed some feature enginnering on the data sets to get the results <br>

1. We pulled out unemployement data of all the states in the US from 1950 to present <br>
This plot shows the rate of unemployment data of New York vs Washington DC

As expected, unemployment rates shot up significantly when Covid hit, that is in 2020

![newplot](https://user-images.githubusercontent.com/77953290/233462389-a7fffbbb-58f2-4469-bc7e-685a8a113c45.png)

<br>
2. Since the unemployment rate was at its peak when Covid hit, we decided to plot the unemployment rates for May 2020, for each state 
<br>

![unemployment rate](https://user-images.githubusercontent.com/77953290/233463524-a4612c77-c8e3-4258-97b0-eb957391ff8f.png) <br>

3. We joined another table to this one and decided to plot the unemployment rate vs participation rate:
(Participation rate is: No. of people actively participating for job interviews)
<br> This data was plotted from December 2020 - Present 


![participation vs unemployement](https://user-images.githubusercontent.com/77953290/233464015-96ea5115-d857-4ddc-9bf3-4ac71a11ea70.png)
