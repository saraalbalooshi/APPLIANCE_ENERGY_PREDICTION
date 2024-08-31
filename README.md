<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 20px; height: 55px">

#  <font style='color:skyblue'> PROJECT TITLE: APPLIANCE ENERGY PREDICTIONS 

---

## <font style='color:skyblue'>  Abstract <a id='section-1'></a> 


Energy consumption is rapidly increasing globally, leading to energy scarcity and environmental damage. This project aims to analyze the factors influencing the rising energy consumption of home appliances, explore methods to reduce this consumption, and predict energy usage using regression models. The challenge involves supervised machine learning to predict appliance energy usage based on factors like temperature, humidity, and pressure. Various algorithms, including linear regression, have been employed for energy consumption prediction.
## <font style='color:skyblue'>  Problem Statement <a id='section-2'></a>
The dataset consists of 10-minute intervals spanning around 4.5 months. It encompasses temperature and humidity readings from a ZigBee wireless sensor network within the house, along with energy consumption data recorded every 10 minutes through m-bus energy meters. Additionally, weather information sourced from Chievres Airport, Belgium, via Reliable Prognosis, has been integrated into the dataset.
##  <font style='color:skyblue'> Data Set <a id='section-3'></a>


<div style="display: flex;">

<div style="flex: 50%; padding-right: 10px;">

| Feature       | Description                           |
|:--------------|:--------------------------------------|
| lights        | Energy use of light fixtures          |
| T1            | Temperature in kitchen area            |
| RH_1          | Humidity in kitchen area               |
| T2            | Temperature in living room area        |
| RH_2          | Humidity in living room area           |
| T3            | Temperature in laundry room area       |
| RH_3          | Humidity in laundry room area          |
| T4            | Temperature in office room             |
| RH_4          | Humidity in office room                |
| T5            | Temperature in bathroom                |
| RH_5          | Humidity in bathroom                   |
| T6            | Temperature outside the building       |
| RH_6          | Humidity outside the building          |
| T7            | Temperature in ironing room            |
| RH_7          | Humidity in ironing room               |

</div>

<div style="flex: 50%; padding-left: 10px;">

| Feature       | Description                           |
|:--------------|:--------------------------------------|
| T8            | Temperature in teenager room 2         |
| RH_8          | Humidity in teenager room 2            |
| T9            | Temperature in parents’ room           |
| RH_9          | Humidity in parents room               |
| T_out         | Temperature outside (from Chievres weather station) |
| Press_mm_hg   | Pressure (from Chievres weather station) |
| RH_out        | Humidity outside (from Chievres weather station) |
| Windspeed     | Wind speed (from Chievres weather station) |
| Visibility    | Visibility (from Chievres weather station)    |
| Tdewpoint     | Tdewpoint (from Chievres weather station)      |
| rv1           | Random variable 1                     |
| rv2           | Random variable 2                     |
| Date          | Date and time format                   |
| Appliances    | Energy used by appliances (Target Feature)      |

</div>

</div>
