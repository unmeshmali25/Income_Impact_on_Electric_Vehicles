# Income_Impact_on_Electric_Vehicles
Trying to understand relationship between number of electric vehicle registrations and household income using linear regression


****  Data sources  ****
Income data: www.census.org (factfinder tool)
EV registrations data: California Open Data Portal (https://data.ca.gov/dataset/vehicle-fuel-type-count-zip-code)

The histograms of the data for household income in California shows that the data is normally distributed 
The data for number of electric vehicles is also normally distributed. (If you see the histogram, both the plots are
slightly skewed to the left which implies that the mean is smaller than the median. A few small values drive the mean downward
but do not affect the median. This is because of the low penetration of EVs at this point. Many zipcodes have very less numbers.

The simple linear regression results in an adjusted R squared value of 0.38
It means that 38% of the variability in the number of electric vehicles is explained by household income levels. 
That is very significant!!
