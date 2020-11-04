# Toronto-Retail

## Toronto Restaurant Traffic During the Covid-19 Pandemic
After coming across this OpenTable Dataset of year-over-year comparisons of restaurant reservations over the last couple of months, as well as Google's Community Mobility Reports, I wanted to see how Toronto is fairing during this pandemic and compare it to other Canadian cities.
### Summary of Insights
* The Retail activity Data for Toronto is correlated with other Canadian cities, but most closely correlated to Montreal.
* Toronto's Mobility Report Data for the Retail and Recreation category is correlated Restaurant reservations, as expected.
* Proximity data for the Retail and Recreation category is most closely correlated with proximity to transit stations in Toronto.
* Forecast from Google Community Mobility Reports shows a return to normal levels by around November of this year.
* Forecast from Toronto's OpenTable data shows a return to normal levels by December.
* The slope of the recovery trendlines for cities in the OpenTable data shows clear differences in the "eagerness to return" of different cities, perhaps dictated by economic reactivation policies.

## Google's Community Mobility Reports vs OpenTable's reservation dataset
# (Tableau Visualizations)
![](https://github.com/escobarfabio/Toronto-Retail/blob/master/fig1.png?raw=true)

![](https://github.com/escobarfabio/Toronto-Retail/blob/master/fig3.png?raw=True)


## Eagerness to Return

I calculated the slope of the trendline for each city starting from April 16 (after the downward slope) to see how fast restaurant reservations were coming back to normal after the low point in April.

The size of the bars represents the slope of the upward trendline divided by the amount of "lockdown days" defined as days were the y-o-y change was below -98%. This could be interpreted as the "impatience to return", or the effect of lockdown length on the slope. 

For instance, cities such as Hamburg and Munich were significantly more "impatient"; the length of the lockdown days seems to have had a greater effect on the slope of their upward trendlines.

Conversely, the slope of the trendline for cities like San Francisco, New York, and Seattle seems to have been less affected by the length of the lockdown. 

There could be many explanations for these differences, most probably having to do with policies dictating the speed of economic reactivation for these cities. We would have to look at these policies individually for each city to get a better idea. We would also expect cities with less covid-19 infections/deaths to have populations less scared and more eager to reactivate their economies. These are topics I will explore further in the next analysis.

![](https://github.com/escobarfabio/Toronto-Retail/blob/master/fig5.png?raw=True)


## Further Analysis

For this next section I used the OpenTable data to make a few calculations. I did them on Google Sheets ([link to the spreadsheet](https://docs.google.com/spreadsheets/d/1dduKOuzUGr5pKjHT1J4uqg_WFpfyN3TbxcNFS-rlnkQ/edit?usp=sharing)) and made a few visualizations on Tableau.

From the density graph below we can see that there's a period where all cities are at a y-o-y level of -100 around mid April, so I separated the data from April 16 to find the slope of the upward trend for each city. The slope of the trendline could arguable show the "eagerness" of that city to return to normal after quarantine.

I also counted the days when the reservations were below -98% from last year as "Lockdown Days", to see what effect  lockdown length had on different cities.

![](https://github.com/escobarfabio/Toronto-Retail/blob/master/fig4.png?raw=True)


