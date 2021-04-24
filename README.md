# Final-Project
Team Name: The Pythons

Names: Gray Cleric, Ethan Rubenstein, Teresa Davison

Emails: GRC43@pitt.edu, edr38@pitt.edu, tid30@pitt.edu



Descripition/Links to datasets:

Arrest Data:

Description: The data is the Pittsburgh polices records of local Pittsburgh arrests.  The data has basics details of the crime including 
the location, age of criminal, crime commited, time of day, etc.  

Link: https://data.wprdc.org/dataset/arrest-data

Property Data:

The second metric was the average property sale value for each Pittsburgh zip code since 2013. The data includes all property transaction values, including transactions well below the fair market value of the property. For example, some recorded transactions involved the sale of property for $1, which would bring down the mean property value for that zip code because property is relatively expensive. After filtering transactions below $1,000, the sold prices were grouped by zip code and then averaged. To combine with the other two datasets, a points system was implemented that assigns 5 points to the top 20th percentile, 4 points to the top 40th percentile, and so on. Both other datasets use a similar points system to give equal weight to each factor.

Link: https://data.wprdc.org/dataset/real-estate-sales


Restaurant Data:

This data set is a set of all of the restaurants in Allegheny County with geographic locations including zip code, size, description of use, and a "status" of either 1 or 7 to indicate if the restaurant is currently open. Restaurants are a fairly good metric to judge a neighborhood by since they can create a sense of community, as well as providing easy access to good food. This is not only good for overall quality of living and diversion but is very useful for those who do not have the time to cook, such as people with demanding jobs or college students. The matter is slightly complicated by the factors like walkability, price of UberEats, or parking/car accessability if there is not good walkability and people must drive. However, in terms of general enjoyment, having many restaurants around must be a good thing for the happiness of residents and social life in the area. This dataset provides the data needed to see the number of restaurants in a given area that would be available to residents.

Link: https://data.wprdc.org/dataset/allegheny-county-restaurant-food-facility-inspection-violations/resource/112a3821-334d-4f3f-ab40-4de1220b1a0a



Abstract: (summary of findings- What is the best neighborhood? How did you determine it? Brief summary of metrics)
-decide what neighborhood is best - We decided that Squirrel Hill is the best overrall.  It has a bunch of enjoyable restaurants, good properties, and low crime rates.  It is a great place 

-explain metrics - We used a 20% scale in which the top 20% for a given dataset is a 5. The top implies that it is the most optimal for a given dataset. Total points possible for a given neighborhood
with this system is 15 points across the 3 datasets.  We decided that this would be a good metric because we felt like looking at the percentiles 
in 20% intervals gives us the general trend of the datasets as they apply to varying neighborhoods.  In retrospect, we could have even broken it into smaller
intervals and assigned more points so that we would not have had to narrow down the best neighborhood as much in the end, but the system definitely worked
well for us in this project.  
