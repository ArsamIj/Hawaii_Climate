# Hawaii_Climate

## Overview / Summary

The project uses Python and SQL Alchemy to do a basic climate analysis and data exploration of the climate dataset. The analysis takes into consideration 12 month’s worth of precipitation data and outputs it in bar graph to identify ideal time. Least amount of precipitation was recorded in October 2016 to January 2017, where no outliers are identified as are during the remaining. 

![Prcp_in_Hawaii](https://user-images.githubusercontent.com/119286287/224222724-64a18919-9245-49c9-808a-54b77f23c14d.PNG)

The second analysis is performed on precipitation and temperature observed by the most active station. 

![Tobs_at_Station_A](https://user-images.githubusercontent.com/119286287/224222768-35ad9199-74a1-4d2c-bf88-af87f72d5c90.PNG)

The same observations are then verified using Flask App.
The following routes are available to use; 
@app.route('/')
Welcome to the Climate Analysis API!<br/>
Available Routes:<br/>
/api/v1.0/precipitation<br/>
/api/v1.0/stations<br/>
/api/v1.0/tobs <br/>
/api/v1.0/temp/start/end <br/>

