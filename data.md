# Data #

## Description ##
I will use the [Toronto Police Service Public Safety Data Portal site](https://data.torontopolice.on.ca/datasets/neighbourhood-crime-rates-boundary-file-) for crime data by neighbourhood. The Toronto Police Service stores data on serious crime (assault, auto theft, break and enter, robbery, theft over $5,000 and homicide) by neighbourhood for the years 2014 to 2018. 

I will also use the [Wikipedia List of Postal Codes of Canada site](https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M) for Toronto postal codes. This can provide neighbourhood geographical coordinates (latitude and longitude). 

Lastly, I will use the Foursquare API to examine the venues in Toronto neighbourhoods.

## Solving the Problem ##
With the above data, I will explore neighbourhoods in Toronto, the largest city in my home country, and look for correlations between crime rate and venue types.

I will use the Toronto Police Service serious-crime data for the most recent year, 2018. Through k-means clustering, I will group neighbourhoods by venues and examine the crime rates of the neighbourhoods in each cluster. If neighbourhoods with similar venues have similar crime rates, then I will suggest possible reasons for the correlation.

Time permitting, I will create a logistic regression model to try and predict the crime rates of neighbourhoods based on their venues. For independent variables, I will one-hot encode the venues for each neighbourhood. For the dependent variable or label, I will use the crime rate of each neighbourhood. Again, this is time permitting. 

If there is no apparent correlation between venue type and crime rate, it will refute the idea that a particular venue such as Walmart – or a combination of venues – can be used to predict the safety of a neighbourhood. 
