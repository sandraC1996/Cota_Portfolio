# Assigment two - **Goverment Debt**

## Understanding Goverment Debt with Data visualization

To understand how goverment debt has affected each country, we should start by learning the current GDP. On the next graph we can see the difference between each of the countries:

<iframe src="https://data.oecd.org/chart/6gMq" width="660" height="495" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6gMq" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</a></iframe>


Although this information is important, it has a main problem. It doesn't let's us understand how the change of debt has ocurred through time.

To solve this problem we change the graph to a grid of line charts. Where we can clearly see how each GDP has transform trough time for each country. 

### Evolution of GDP from 1995 to 2019 separated by country - Flouris 1

<div class="flourish-embed flourish-chart" data-src="visualisation/5290759"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

Using this method, it's easier to understand how much debt was each country in a specific year. However, now it's not clear how it compares from one country to another, because you are seeing each of them in a separated graph. 

My first tought was to get all of this information display in a single graph. Having time as the x-axis and the GDP on the y-axis. To differentiate each country, I asigned a different colour for each one. 

### Evolution of GDP from 1995 to 2019 - Flouris 2

<div class="flourish-embed flourish-scatter" data-src="visualisation/5291037"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

After doing this visualization method, I realized you can see which countries have the biggest change between the years and how it compares to each other. However it was not going to help the viewer process the information. Which made me understand, it was not the right method to use. By getting all the countries in the same line graph, the information is hard to follow and you get lost when you try to follow the evoultion of debt from a single one. 

This made me create one last graph. It shows the GDP on a specific year for each of the countries, but having a range of the different values it takes through all the years. This way you can see all the countries, how their debt compares to each other in every specific year, and understand how it move through time with the slider.

### Evolution of each country GDP value by year - Flouris 3

<div class="flourish-embed flourish-scatter" data-src="visualisation/5291172"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

##### Data source
[OECD](https://data.oecd.org/gga/general-government-debt.html)
