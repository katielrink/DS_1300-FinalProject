
# Data Analysis of Global Food Prices and CPI Score
### Overview
 Our group's founding point of interest was driven by the relationship between governments and their constituents; specifically in a manner of consumption. In this analysis we set out to find out if there was any correlation between the corruption levels of the governments and the food prices found in said countries. We wanted to know if the government corruption was a catalyst for food prices to rise higher than the natural equilibrium of the market.
Data and Model </br>
To find the correlation, if any, between the corruption levels in the government and the food prices in the country, we found a dataset of the FAO Food Price Index from the Food and Agriculture Organization of the United States. Within this dataset, we can find information about a country, the location within the country, the market name, the name of the item being sold, the price, and the date. Each data point is taken monthly from the years between 2013 to 2020. From this data, we thought it necessary to only utilize the country, name, price, and date of each item.  </br>Additionally we incorporated the Corruption Perception Index from Transparency International. From this dataset, we gain information on the country and region, the corruption perception index score, the rank, the number of sources, and the standard error for every year from 2013-2020. From this data, we will only utilize the country and the CPI score, or corruption scoring. The CPI score is calculated by combining three sources of data at minimum takes from either surveys or varying assessments to create a score from 0-100, where 0 is the most corrupt nation, whereas 100 is the most clean. This corruption can include bribery, diversion of public funds, lack of access to information on public affairs/government activities, and many other things. Unsurprisingly, the measurement of corruption has its complexities given that the scoring derives from citizens' own confidence in their government and the international perceptions as well. </br>
The price index available to us did not necessarily compile all of the complete information that may have proved useful later on in our findings, such as; the environmental origins of each food nor prices for all of the items at every year. However, we chose to continue to use the dataset because the majority of our needed information was found and there was not a more comprehensive dataset we were able to find. Given these omissions, the ideal option would have involved combining multiple datasets, so it was entirely complete. However, this combination would require some balancing to ensure that the data followed the same scales. Given the length of time we had to complete this work, we decided that it was more prudent to focus on the data we did have, as it was sufficient to be able to draw at least a crude analysis from. With the opportunity to expand on the crude analysis found at present we, or others following our conclusions, may be able to account for these missing pieces.  </br>
### Assumptions
In order to ensure that the data we analyzed was an accurate sample we needed to be able to draw a conclusion from all countries. By cross-referencing the CPI-scores with our data on prices, we chose to use Sudan, Mexico, China, Iraq, and Ethiopia. The corruption levels of these five countries are well spread and allow for multilevel understanding of corruption’s effect. To delve further into the data as a whole, we graphed the overall CPI scores of all the countries we had data on. Additionally, we graphed each of these chosen countries against each other with the CPI score as the y-axis and the data on the x-axis. This allowed us to be able to reference the CPI scores in relation to one another as we proceed with our analysis.  </br>
![](https://github.com/katielrink/DS_1300-FinalProject/blob/main/Graphs/All_CPI_Scores.png?raw=true)
 </br>As can be seen in the above line chart, we can note that Iraq and Ethiopia acted as our base cases with lower corruption index scores, but still enough to find some correlation. Additionally, Mexico and China acted as our test cases to compare against the base cases, as they held high average CPI scores. We chose Iraq and Ethiopia because they remained fairly consistent, so they can easily show comparisons against price. In contrast, Mexico and Sudan followed a more variable score, so they can demonstrate a change’s effect on price, if there are any. These values were further proved by finding the standard deviation of each CPI score from the mean value. </br>

    Sudan Mean :  3.552713678800501e-15 
    Mexico Mean :  3.552713678800501e-15 
    China Mean :  -1.4210854715202004e-14 
    Iraq Mean :  7.105427357601002e-15 
    Ethiopia Mean :  7.105427357601002e-15

Furthering with our overall understanding, we graphed prices of certain categories of food (Grains, Meat, Dairy, and Vegetables/Fruits), as well as the prices in each country over the span of 2012-2020. This way we were able to get an overall understanding of the patterns that arose within the average price itself. We graphed these as a standard line graph with the date acting as the x-axis, and the price acting as the y-axis. Despite these being discrete points at each date, we chose to still use a line graph so as to best see trends of prices increasing or decreasing. </br>
Due to our limited data, we did not have prices for several of the categories prior to 2017. And we can generally see that products with similar origins, such as vegetables and grains, both of which are crops that rely on weather conditions to grow, follow similar patterns of rise and fall in prices. This correlation is mostly likely caused by similarities in manufacturing costs, thus causing similar fluctuations in prices to maintain a profit. While Meat and Dairy initially followed similar patterns, in the later half of the graph they seem to have an inverse correlation in prices, whereas one tends to increase, the other decreases. The major change for both Meat and Dairy prices occurred around 2020, when COVID first hit. As the pandemic did cause a decline in global meat demand, the prices would generally increase as a direct result of the demand decreasing. Alternatively, as people stocked up for the upcoming pandemic, Dairy products became very highly in demand, thus the price was able to decrease. All prices, however, proceeded to increase from the initial change spike in prices due to the increased scarcity of items resulting from the pandemic. Government handling, or in some cases mishandling, is a possible element to how much meat prices rose in any given country. While this conclusion is not necessarily as strict as the guidelines for our CPI analysis, the possibility is definitely a point that can be expanded upon given our data.  </br>
![](https://github.com/katielrink/DS_1300-FinalProject/blob/main/Graphs/All_Prices.png?raw=true)
 </br>
As we can see in the graph above, the prices generally increase as the years increase, which makes sense in regards to inflation. Prices all saw a general increase around when 2020 hit due to the pandemic. However, as can be seen by the sharp increase in Iraq and Sudan prices, those were the two countries hit the hardest by COVID. Whereas, Iraq was not quite as affected by COVID, as the trends remained consistent due to it already suffering from food shortages due to the Iraq war, which had a formal ending around 2017 but definitely still holds large scale ramifications. Due to the low average prices of our data from China and Mexico, and the lack of variable data, the lines appear flat when graphed, which makes analysis on said countries incredibly difficult on a large scale. This lack of data may be attributed to our choice of dataset but, the larger context of our access to certain countries’ data also has a significant role. For instance, the data that we have gathered from China especially is not entirely unbiased seeing as the government has an unorthodox method of collecting data on entities that relate to public good. China has scored a 45 on the CPI scale and this unorthodox method of data collecting may very well play a role in this final scoring. </br>
From the above data, we then proceeded to look for any overall correlations between CPI score and the price index of our chosen countries over the years. To do this we graphed each country with its individual CPI score and average price index.  </br>
![](https://github.com/katielrink/DS_1300-FinalProject/blob/main/Graphs/Sudan_Overall.png?raw=true)
![](https://github.com/katielrink/DS_1300-FinalProject/blob/main/Graphs/Mexico_Overall.png?raw=true)
![](https://github.com/katielrink/DS_1300-FinalProject/blob/main/Graphs/China_Overall.png?raw=true)
![](https://github.com/katielrink/DS_1300-FinalProject/blob/main/Graphs/Iraq_Overall.png?raw=true)
![](https://github.com/katielrink/DS_1300-FinalProject/blob/main/Graphs/Ethiopia_Overall.png?raw=true)
</br>
As we can see from the general trends, the CPI score tends to stay fairly constant, whereas the price does not. However, due to the massive difference in the size of the values, it is hard to see any correlation on the graphs. So we calculated the pairwise correlation between each of the values using the Pearson method. The results were as follows :  </br>

    Sudan : 0.5596417936865866
    Iraq : 0.8117274052138735
    Mexico : -0.38839178996677165
    Ethiopia : 0.8760659818945472
    China : -0.9113634869979309

Given that a perfect correlation is equivalent to 1, we can see that China, Ethiopia, and Iraq all have relatively high correlations between their CPI score and their average price. Whereas Mexico has a very low correlation. Given the two that did not have high correlation levels, both had relatively high export rates, which can cause an increase in demand to allow prices to remain lower despite high corruption levels. Thus there does appear to be some form of correlation between increased corruption levels in a country’s government and increased prices of products from said country. </br>
Since it was a massive amount of data, we chose to break up the data, so that more in-depth analysis could be done. We separated the data based on whether the item fell under the category of grains, meats, fruits or vegetables, and dairy products. From there we did an individual analysis based on each to see how the results varied on a more microscopic level. </br>
### Grain Graphs and Analysis
Several of the datasets we originally chose don’t have information from grains up until 2017. Disregarding the interesting drop off seen up until that year there is a steady increase and decrease. This was an interesting pattern to consider but, we were able to determine that contextually the increase and decrease of these prices had less to do with the level of corruption from any given country and more so considered the natural seasons of plant growth. Rather than 
### Meat Graphs and Analysis </br>
In my analysis of the countries we chose, only a couple of them included meat data that was needed. The dataset only included the information for both Ethiopia and Iraq. The first analysis I had to conduct was the average price of all meats per country. This would give me a basis to then complete the correlation graph. In the correlation graph, I was able to see if the corruption perception index had any similarity with the meat prices of both countries. The other three countries which included Sudan, China, and Mexico </br>
![](https://github.com/katielrink/DS_1300-FinalProject/blob/main/Graphs/CPI-Price_Meat_Ethiopia.png?raw=true)
![](https://github.com/katielrink/DS_1300-FinalProject/blob/main/Graphs/CPI-Price_Meat_Iraq.png?raw=true)
### Fruits & Vegetables 
### Dairy Products 
To analyze the dairy items, we first looked at the overall price layout of all the items in our dataset that could be considered Dairy. By creating a large list of known dairy products, we were able to reference it and create a new dataset containing only the information on the items contained within my list of Dairy products.. By grouping each value by those having the same item name within a dataset of only dairy products, we were able to find the average value at each given month and year. From there we could graph them all in a line graph so we could see the trends in my data.  </br>
![](https://github.com/katielrink/DS_1300-FinalProject/blob/main/Graphs/Price_Dairy.png?raw=true) </br>
Now that we have a baseline understanding of the Dairy Product prices over the year for each country, we need to check its relation to the CPI scores for each country. To do this we took the data that was filtered by only the dairy information and then proceeded to filter it by country to create separate datasets for each item within each country. We then graphed the items as a line plot, once again so we could see any trends within the data, with the year acting as the x-axis and the average value (CPI score/price) as the y-axis.  </br>
![](https://github.com/katielrink/DS_1300-FinalProject/blob/main/Graphs/CPI-Price_Dairy_Ethiopia.png?raw=true)
![](https://github.com/katielrink/DS_1300-FinalProject/blob/main/Graphs/CPI-Price_Dairy_Ethiopia.png?raw=true) </br>
To confirm the above visuals, we then proceeded to calculate the correlation between the CPI Score line and the price line using the Pearson method. The results fell as follows : 

    Iraq : -0.474342978812104
    Ethiopia : 0.8974296107188423

From the above information, we can gather that Iraq seems to have a low correlation between the average CPI score and the average cost of dairy items. Alternatively, Ethiopia appears to have a very high correlation between CPI score and average price of dairy items. Given that Iraq had been in a war against terrorism for the last several years, it does make sense that the price would have fluctuations outside of the normal realm. Resultantly, we can say that a .5 correlation is enough to see some form of correlation. </br>
Unfortunately, in the specifics of Dairy there was not enough data to make a comprehensive graph, so we chose to rely on the other datasets to compensate for what data we lacked in Dairy.  </br>
### Conclusion
The premise of our original inquiry surrounded primarily on the idea that the corruptive actions of governments would have a tangible impact on citizens’ day to day lives. Rather than an abstract system of power making these seemingly unimportant decisions in an impenetrable space– we hoped to bring the hypotheticals into real world situations that would prove more impactful to the everyday citizen (despite the country). While the analysis derived from this founding question was not poorly handled by any means, the various constraints around our project left little room to account for situational discrepancies. For instance political contexts in each country may play a role in the way foods are priced, specifically the aforementioned Iraq War and effect of COVID-19. Yet, even with these other factors at play we were still able to draw a loose relationship between rising/high CPI scoring and higher prices for certain food products. Given the opportunity to expand upon our original project we may be able to refine these discrepancies and see a stronger correlation. 
