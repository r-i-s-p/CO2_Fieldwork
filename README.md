# Environmental Science

This repository describes the modelling and fieldwork conducted for SP3275 Science for a Sustainable Earth. 

## Daisyworld Model
The daisyworld model is a simplified mathematical model designed to illustrate the self-regulation or feedback mechanisms between life and the environment. Daisyworld demonstrates how life can help stabilize climate conditions, supporting the broader ideas of the Gaia hypothesis. The model incorporates nonlinear dynamics, climate feedback, and biosphere-atmosphere interactions. This project also extends the model by investigating the effects of short-term perturbations on the equilibrium state of the Daisyworld model.


## CO2 Fieldwork 
Data collection and analysis was performed while investigating CO2 concentration across different elevations at Mount Faber Park, Singapore in September, 2022. 

CO2 data was systematically collected across a range of elevations using a Raspberry Pi connected to a controller board that controlled the sensors SenseAir K‐30 CO2 and Adafruit BME688. Adafruit BME688 collected additional data on humidity, temperature, air pressure and volatile gas concentration. To collect data on elevation and wind speed and direction, a Kestrel pocket weather metre was used.

### Results
A total of 353 data points spread across 13 different elevations from 30 m to 83 m were collected. A Pearson R statistical test along with a linear regression analysis of multiple independent variables with CO2 was performed, yielding a $R^2$ value of 0.744. Using the individual $R^2$ values for each variable, the Variation Inflation Factor (VIF) was computed to account for multicollinearity. After removing collinear variables, hypothesis testing was performed, yielding Elevation and Wind speed as statistically significant to mean CO concentrations. 

A second Pearson R statistical test showed that the CO2 concentration versus Elevation and Wind speed had $R^2$ = 0.72. To visualise the data, a multivariable linear regression plot was constructed in Python.
