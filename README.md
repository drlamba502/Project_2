# PLUGGING IN: Electric Car Charging Stations Dashboard
![](images/Electric-Car-Charger.jpg)
### Team Members:
* Yannick Kalukuta [yanowen](https://github.com/Yanrice)
* Vijay Bagavatula [vijayb023](https://github.com/Vijayb023)
* Vin Dixit                 [vinayakdixit](https://github.com/vinayakdixit)
* Dinesh Lamba          **drlamba502**
* Adil Sarwar             **asarwar1**
* Kendall Gouldthorpe  [kgouldthorpe](https://github.com/kgouldthorpe)

## Project Objective:
We will be using data that takes into account longitude and latitude of major cities in the US to find **Charging Stations** for Electric Vehicles from a set **radius**. With that `data` we will then create three visualizations to display **charging stations** around those major cities.  
#### Looking specifically at:
1. How the **charging stations** range across different cities in the US
2. The different companies of **charging stations** in each state
3. Breaking down the types of **charging stations** (**Rapid, Fast, Slow**)

## Methodology:
We will use an `API` to pull data and move it into a `SQLite` `Database`. From there we will use `JavaScript` to create various visualizations for a dashboard of different **charging stations**.
The Dashboard Components
#### Datasets to be Used:
* `API`: developer.nrel.gov
* `SQL Database`: List of states and their longitude and latitude
* `Leaflet`: Displaying the location by state of all the charging stations
* `Plotly`: Breaking down the number of each charging station company by state
* `Chart.js`: Types of Charging Stations (Rapid Charges, Fast Charges, Slow Charges)


**API Site:** [developer.nrel.gov](https://developer.nrel.gov/docs/transportation/alt-fuel-stations-v1/all/#json-output-format)
