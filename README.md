# CO2_Fieldwork

This repository describes the data collection and analysis performed while investigating CO2 concentration across different elevations at Mount Faber Park, Singapore in September, 2022. 

### Methodology
CO2 data was systematically collected across a range of elevations using a Raspberry Pi connected to a controller board that controlled the sensors SenseAir K‐30 CO2 and Adafruit BME688. Adafruit BME688 collected additional data on humidity, temperature, air pressure and volatile gas concentration. To collect data on elevation and wind speed and direction, a Kestrel pocket weather metre was used.

### Results
A total of 353 data points spread across 13 different elevations from 30 m to 83 m were collected. A Pearson R statistical test along with a linear regression analysis of multiple independent variables with CO2 was performed, yielding a $R^2$ value of 0.744. Using the $R^2$ values, the Variation Inflation Factor (VIF) was computed to account for multicollinearity. After removing collinear variables, hypothesis testing was performed, yielding Elevation and Wind speed as statistically significant to mean CO concentrations. 

A second Pearson R statistical test showed that the CO2 concentration versus Elevation and Wind speed had $R^2$ = 0.72. To visualise the data, a multivariable linear regression plot was constructed in Python.
