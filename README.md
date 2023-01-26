# Statistics

## Introduction


Welcome! This repository contains projects coded in Python aimed towards utilising statistics to unfold findings.
There are 3 parts to this repository; statistics_1, statistics_2 and statistics_3. In the subsequent paragraphs, each project will be explained and elaborated. 
Any form of feedback will be appreciated. Thank you for coming by. :) 
  
  
## [Statistics_1](statistics_1.ipynb)

Through analysing the datasheet on the weather, the aim of this project is to unearth if there is a possibility of a relationship between temperature and various factors.

Plotting a bar graph(Figure 1.1), the 'Summary' of the weather is on the x-axis and the 'Temperature' being the y-axis. It is clear that the 'Summary' of weather is related to the 'Temperature'. From Figure 1.1, when the weather is 'Dry', the 'Temperature' tends to be higher at above 25 degrees. In 'Cloudy' weathers, the 'Temperature' tends to fall between 10 to 25 degrees, while 'Breezy' and 'Foggy' weathers have lower 'Temperatures' below negative 0 degrees. 

However, it is vauge to conclude that the 'Summary' of weather determines that the 'Temperature' will be of a certain range, albeit the clear association between the two factors. 

For example, from Figure 1.1, in 'Windy' weathers the 'Temperature' falls below 8 degress while a 'Windy and Dry' weather falls above 25 degrees which is a significant differenece from just 'Windy' weathers. 

Figure 1.2 shows that there is a negative correlation between 'Humidity' and 'Temperature'. the higher the 'Temperature', the lower the 'Humidity'. The coefficient of correlation ranges from -1 to 1 which shows that there is a strong negative correlation.

In Conclusion. The 'Temperature' of the weather is affected by various factors such as the 'Humidity' and the 'Summary' of the weather. 


## [Statistics_2](statistics_2.ipynb)

A slight EDA(Exploratory Data Analysis) is done the the dataset to analyse, explore and sum up its main features.

After creating and new column, 'Month' , from the 'Order Date', we can use the new data to conclude which month generates the best sale.
By generating a 'Sales' column by multiplying the 'Price Each' and 'Quantity Ordered'. Grouping the dataset by month and plotting a bar graph of 'Month' against 'Sales' shows that the 12th 'Month' gains the highest 'Sales' in Figure 2.1. 

To find out which city makes the highest 'Sales', we extract the city from the 'Purchase Address'. This can be done by defining a function to get city from the adress and identifying that the 'Purchase Address' has a format of street name, city, postal code. 

Grouping the data by 'City' and plotting a bar chart(Figure 2.2) of 'City' against 'Sales', we can see that 'San Francisco' has the highest returns in 'Sales'.

Subsequently, to find the 'City' that makes the best 'Sales' across 12 months, we group multiple columns together and query the 'Sales' of each 'City' in the first 3 'Months'.  Plotting the data of the 'Sales' that each 'City' mkaes across 12 'Months' by looping through all the cities and grouping the current city's 12 'Month' 'Sales' and plotting a line plot for each 'City' as seen in Figure 2.3. 

From Figure 2.3, it can be seen that 'San Francisco' generates the most 'Sales' across all 12 'Months' and has the highest 'Sales' in the 12th 'Month'.

In investigating which 'Products' have the highest 'Sales', we compare by gross sales and plot the 'Products' against 'Sales' as shown in Figure 2.4. It can be seen that the 'Macbook Pro Laptop' has the highest 'Sales'. 

However, though Figure 2.4 shows that the 'Macbook Pro Laptop' has the highest 'Sales', it does not necessarily mean that it has the highest 'Quantity Ordered'. In Figure 2.5, it shows that the 'Quantity Ordered' for 'Macbook Pro Laptop' is one of the lowest ranking in 'Prodcuts' while its 'Unit Price' is the highest which is the likely factor to its success in 'Sales'.

To find the timing where buyers are the most active, an 'Hour' column is created from the 'Order Date' column. Figure 2.6 is formed by the aggregation of 'Hours' and count by the amount of 'Order ID'. It can be seen that the two peak periods where buyers are most active are at the  '12' and '19' 'Hour'.  
