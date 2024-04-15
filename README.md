# Project Title: Electricity Production

## Team Members: Rachel, Luke, Victor, and Ben

## Project Description/Outline:
- Using the electric production data set found on Kaggle, the latitudes/longitudes of each country involved from Geoapify, and the population data of each country found on the API Ninjas, our group would like to explore the electricity production of countries around the world to see what kind of trends and relationships we can identify. We are also particularly interested in how the United States compares to the rest of the world regarding our electricity production. 
## Research Questions:
- How does the United States compare to other countries in terms of electricity production?
- How does population impact electricity production?
- How do the ratios of non-renewables vs renewables for electricity compare in countries?
- What do we predict the future non-renewables to renewable ratio will look like for the U.S.?
## Datasets and APIs Used:
- Electricity Production Dataset from Kaggle.com: https://www.kaggle.com/datasets/sazidthe1/global-electricity-production
- Geoapify API: https://apidocs.geoapify.com/
- Country Information API: https://api-ninjas.com/api/country

## Analysis:
### Summary
- In our first graph, we could see that the United States is a second largest producer of electricity overall. We can also see that the population bar chart is Skewed to the right, which will tell us that the median values we aggregate will be a better measure of center than the means.
- In our initial look of the summary statistics and measure of center statistics data frames, we can see that the United States produces 12.85 MWh of electricity per person compared to the median value of 5.12 MWh. In addition, Only 22.53% of our electricity produced using renewable energy sources compared to the median value of 47.47%.
- As we work our way down and start to look at our first scatterplot, we could see that there appears to be a strong linear relationship (r-value of .81) between population size and overall electric production.
- In the comparison between population and Electricity produced using non-renewables, we see a week to moderate linear relationship in our scatterplot. We see a similar comparison when we look at population and electricity produced with renewables. 
- As we breakdown our statistical summary further, we examined which countries used the lowest percentage of renewables to produce their electricity. We found that the United States landed squarely within those bottom 10 countries.
- As we take further into the breakdown between different types of renewable energy sources used to produce electricity, we found that hydroelectric was the most widely used amongst countries involved in the study.
- Finally, we begin to examine the current trends with US production of electricity. In our scatterplot and bar graph, we can see that there is a positive upward trend with the use of renewables and a downward trend with using nonrenewables to produce our electricity. Based on the available data, our linear regression model suggest that by 2033 the United States should be able to achieve a ratio of approximately one unit of non-renewablily produced electricity for every six units of renewablily produced electricity. 
- For comparison, when we examined a similar relationship for China, we found it by 2033. China would be shifted completely over to renewables if they stayed on the same trajectory.
### Conclusions
- As of 2023, the US produces a large amount of its electricity using nonrenewable energy sources comparatively to other countries involved in the dataset. 
- The United States does appear to be shifting towards utilizing renewable energy sources to produce its electricity, but potentially at a slower pace than other countries within the data set.
### Limitations
- Some of the countries in the dataset do not have data extending back as far as others. This could make it harder to make predictions based off them.
