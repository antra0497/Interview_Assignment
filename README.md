# Indoor Facilities Management Analysis : F&P

**Original Data:  Json Format**
```
* Indoor air quality data [iaq.json] : (102629, 5)
* Outdoor air quality [oaq.json] : (2892, 4)
* Sensor locations [floors.json] : (2, 3)
```

**Processed Data:** 
Pandas Dataframe and .CSV output.
Loaded dated into pandas dataframe and normalized it where required


**Data wrangling steps:**
```
1. Datetime conversion
2. Creating separate date and time feature
3. Checking/ treating missing values 
4. Checking for inconsistency in the data 
5. Stats check: with respect to required operational values
6. Data rollup: hourly and daily basis
7. Calculation Humidity Ratio
8. Data Merge

```

# Analysis Report: 

**1. Indoor Air Quality (IAQ) Analysis:** As the given indoor data includes indoor temperature, humidity, and CO2 levels, we can analyze the IAQ of the building. We  can analyze mean and standard deviation of each sensor on both the floor. We can also identify any area that have high CO2 levels, which may indicate poor ventilation. We can suggest improving the ventilation system in those rooms to enhance the IAQ. The temperature readings from different sensors can be compared to identify areas with a high or low temperature, and hence help to optimize heating and cooling systems

<img src="https://user-images.githubusercontent.com/25953832/224866796-66f526f2-9691-48a6-bb43-aea86c7440be.png" width=50% height=50%>


**2. Outdoor Air Quality (OAQ) Analysis:** We can also analyze the OAQ data and see how it affects the IAQ of the building. We can compare outdoor data with the indoor data to identify any correlations. We can also analyze the wind speed data and see how it affects the IAQ of the building, as wind speed affects the ventilation of the building.

<img src="https://user-images.githubusercontent.com/25953832/224866772-8cd3d752-5b10-419e-ae74-de8d10aa8ded.png" width=50% height=50%>



**3.) Occupancy analysis:** The indoor temperature and CO2 measurements can be used to estimate occupancy levels in different areas of the building. By analyzing the patterns of temperature and CO2 fluctuations, we can identify which areas are frequently occupied and which ones are not. This information can be used to optimize HVAC systems and ventilation rates.

<img src="https://user-images.githubusercontent.com/25953832/224866740-eba9d133-91e5-4f26-ab6f-e28f243b7f28.png" width=50% height=50%>



**4. HVAC Analysis :** The indoor temperature and humidity measurements can be used to optimize the HVAC system of the building. By analyzing the data from temperature and humidity sensors in the building, we can gain insights into how the HVAC system is performing and identify areas for improvement. For this we will look for correlations between temperature and humidity data for each sensor

Humidity ratio is the ratio of the mass of water vapor to the mass of dry air in a given air-vapor mixture. It is an important parameter in indoor environmental quality (IEQ) analysis as it affects thermal comfort, indoor air quality, and building energy performance.

<img src="https://user-images.githubusercontent.com/25953832/224866677-1806b362-5d6e-425a-b2e3-b26bc45c40d8.png" width=50% height=50%>



**Read Full Report Here:** [Link](https://github.com/antra0497/Interview_Assignment_FandP/blob/main/presentation/Presentation-Analysis.pdf)

# PowerBI Dashboard

**PDF Version** [Link](https://github.com/antra0497/Interview_Assignment_FandP/blob/main/powerbi_dashboard/dashboard.pdf)

