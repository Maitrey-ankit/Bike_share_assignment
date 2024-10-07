**Problem Statement**:
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. 
The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful 
business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end.

They have contracted a consulting company to understand the factors affecting the demand for these shared bikes in the American market. 
The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands


**Business Goal:**
We are required to model the demand for shared bikes with the available independent variables. 
Further, the model will be a good way for management to understand the demand dynamics of a new market. 


**Results:**

Linear regression model with an R2 of 0.788 is derived as below:
cnt = 0.574 - (0.212* windspeed) - (0.22* season_spring) + (0.246* yr_1) 
- (0.105* mnth_Dec) - (0.121* mnth_Jan) - (0.093* mnth_Nov) + (0.077* mnth_Sep)
- (0.086* holiday_1) - (0.311* weathersit_Light rain_Light snow_Thunderstorm) - (0.09* weathersit_Mist_cloudy)

**Technology Used:**
Pyhton packages: numpy, pandas, matplotlib, seaborn, sklearn, statsmodel api

**Created By:**
Anand Maitrey
