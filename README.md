# An Analysis of Kickstarter Campaigns

### Overview of Project

I am analyzing data from various kickstarters from around the world in order to get a better idea 
of when and how someone should start their own kickstarter campaign. I analyze these data by creating different
visualizations, setting up different parameters to isolate certain data types, and by performing
various measurements on the dataset.

## Analysis and Challenges

### Analysis

I analyzed the data sets by creating pivot charts and different graphs.

Here is a line chart visualizing different outcomes based on when a kickstarter was launched:
![Theater_Outcomes_vs_Launch](https://github.com/Kyle2Miles93/Kickstarter_Analysis/blob/main/Theater_Outcomes_vs_Launch.png)

Here are the various outcomes displayed in a line chart based on the monetary goals of each kickstarter:
![Outcomes_vs_Goals](https://github.com/Kyle2Miles93/Kickstarter_Analysis/blob/main/Outcomes_vs_Goals.png)

I also used various formulas and functions to calculate percentages and averages, as well as performing filtering.
These included:

> =AVERAGE()

> =COUNTIFS()

> =ROUND()

> =VLOOKUP()

### Challenges 

Some challenges I encountered performing the analysis involved interacting with my software, which
loosely tied into challenges with actually analyzing the data. I experienced the following:

1) Creating the different pivot charts, I had some trouble creating the right display using
the various attributes for columns or rows, and creating the right filters was also tricky.

2) In order to find out how to convert a number to a percentage, I investigated Youtube. The video explained that I would
have to format the numbers by customizing the number using the following code: 
> **0\\\%**

This made everything a percentage without increasing the number by a lot.
3) Using **VLOOKUP** presented some challenges in figuring out which arguments to use with
regards to syntax and column names.

## Results

### Based on Launch Date

- One could conclude that one should start a kickstarter campaign in the months of March, April and May. The line charts
based on Launch date show these months as the most successful in proportion to the amount of failures and cancelations
in those months.

- A second conclusion: December tends not to be very good at all to start a kickstarter campaign.

### Based on Goals

Based on the analysis of outcomes based on the goals of each campaign, one could conclude:

- Kickstarters' goal amounts shouldn't be ***too*** high because the data showed
that if the goal amount is too lofty then the pledged amount tends to be quite short of the goal.
Under the column goal amount **45000 to 50000** and **greater than 50000** we see that the success rate drops sharply
while the failure rate increases.

### Limitations of the dataset

1) The data set is from a century before the current time, which means the data might be outdated.
If we are to determine how relevant the data is, it would be best to only conclude our findings based on a shorter time frame. Actually year 1900
would be a major outlier and would heavily skew the data. The same goes for the fact that it includes kickstarters from around the globe. The data set is so broad 
regionally that it would be tough to focus without applying a bunch of filters all the time.

2) another limitation is that the data set only includes timestamps for dates, so I had to perform some conversions to change them to
actual dates. Also, I had to change some attributes to different types, because they were showing as general text when they should
have been percentages or numbers, etc.

### Other possible tables or graphs I could include

I could have represented theater outcomes based on the pledge amount in another line graph
or else a stacked column and line graph hybrid. This would show success in an equally informative 
but completely different way than showing the outcomes based on goal amount. It would tell us the results of the
outcomes based on *terminal* instead of *initial* timeframes. A more **retrospective** analysis, if you will.

We could also represent the data by showing how much success each country had based on, say,
goal amount or even category of kickstarter. This would show which cultures tend to start what kinds of campaigns.
This would be a completely different analysis for a different objective, but arguably just as useful.



