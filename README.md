# Seattle Weather
The purpose of this project is to investigate whether it rains more in Seattle, WA than in New York City, NY. We want to use data to determine whether it rains more in Seattle, WA than in New York City, NY.

# Data
We will use daily precipitation measured in Seattle and New York from January 1, 2020 to January 1, 2024. The data sets were downloaded from the National Centers for Environmental Information Online search tool. https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND 

# Data Preparation
In order to prepare the data to be analyzed we first had to overcome the obstacle that there were more datapoints for New York than Seattle. To do this, we decided to take the average of the daily precipitation rate. Next, we converted the DATE column to be a datetime data type, which will allow Python to recongize that, that column is a date. Next, unnecessary columns that did not pertain to our purpose was removed. Then to create one cohesive dataset we joined the two datasets using a left join based on Date. Then we went through the process of tidying the data by creating a city column and using that to differentaite between the two cities instead of have one column for each city. 

# Data Analysis
To be able to fully analyze the data we broke down the problem into multiple questions that can be analyzed. We chose the questions: On average does Seattle or New York City rain more? In what months does Seattle rain more, and vice versa. Then we did a test plot of just plotting the data in a line chart and used color to differentiate between cities. We found this made the graph look too cluttered and busy, thus making it hard to analyze anything. Therefore, we then decided to plot a line chart of the average precipitation levels each month. Next, we plotted the average precipitation levels each year. 
