# EV and Charging Infrastructure

## Objetive

The objective is to provide information regarding the electric vehicle population in Washington State, as well as charging stations and points, using Power BI Desktop.

## About datasets

The datasets used refer to the electric vehicle population of Washington State and the alternative fuel station locator filtered for Washington state.

1.	Electric_Vehicle_Population_Data (Nov. 22 2025), 

Data.gov 
https://catalog.data.gov/dataset/electric-vehicle-population-data

2.	Alternative Fueling Station Locator.
a.	alt_fuel_stations (Dec 27 2025)
b.	alt_fuel_stations_ev_charging_units (Dec 27 2025)

AFDC (afdc.energy.gov)
https://afdc.energy.gov/stations#/analyze?country=US&region=US-WA&tab=station&fuel=ELEC&access=public&access=private

## The data

Regarding the datasets, note the following: (1) The data collection date varies by approximately 30 days, and (2) the number of cities reported in each dataset. Electric_Vehicle_Population_Data: 490; alt_fuel_stations : 231 and for alt_fuel_stations_ev_charging_units : 235.

## Used tools

Power BI Desktop
Power Query
DAX
Fuente de datos (Excel/CSV)

## Data visualization

The objective is to provide information regarding the electric vehicle population in Washington State, as well as charging stations and points, using Power BI. The following pages are presented:

1.	Overview.
2.	EV increase YoY BEV .
3.	EV increase YoY PHEV.
4.	Top 10 Make and Models .
5.	Electric Range .
6.	Clean Alternative Fuel Vehicle (CAFV) Eligibility .
7.	Geolocation BEV & PHEV: Top 10 Counties .
8.	EV Charging Stations .
9.	Charging Stations Estimated EV Dec. 2025 .
10.	Geolocation EV Charging Stations .
11.	EV Charging Ports .
12.	Distribution of EV Charging Ports .

## Insight

### Overview

•	Period analyzed, 1999 – 2026 (first orders from 2026):

    o	Total EVs: 268931 vehicles.
    o	Battery electric vehicle (BEV): 79.8% of vehicles (214577 units).
    o	Plug-in hybrid electric vehicle (PHEV): 20.2% (54354 units).

•	Peak:
    o	BEV, year 2023 with 52417 vehicles.
    o	PHEV, year 2024 with 10626 vehicles.

•	Brands:
    o	BEV: 40 brands have been marketed in 26 years, it predominates with 59.7% of the market.
    o	PHEV: 27 brands have been marketed in 26 years, 40.3% of the total.

•	To charge the vehicles, there are 8410 charging ports distributed across 2910 stations.

### EV increase YoY BEV.

•	The BEV year-on-year increase chart analyzes the years 2011-2025 (previous years are not representative values), which could indicate that there is no stable growth in the period.

•	Stages determined by the amounts of BEVs:

    1.	Start. Years: 2011, 2012, 2013, 2014, 2015, 2016 and 2017 with 16585 BEVs
    2.	Adoption. Years: 2018, 2019, 2020 and 2026 with 38234 BEVs. Consider the year 2026 as the start of orders.
    3.	Adaptation. Year: 2021 with a total of 16292 BEVs.
    4.	Growth. Years: 2022, 2024 and 2025 with a total of 90997 BEVs.
    5.	Historical peak. Year: 2023 with a total of 52417 BEVs.

### EV increase YoY PHEV.

•	The graph showing the year-on-year increase in PHEVs, analyzing the years 2011-2025, could indicate that there is no stable growth during the period either.

•	Stages determined by the number of PHEVs:

    1.	Phase. Years: 2010, 2011, 2012, 2013, 2014, 2015, 2016, 2019, 2020 and 2026 with a total of 11,255 PHEVs. Consider 2026 as the start of orders.
    2.	Adoption. Years: 2017, 2018, 2021 and 2022 with 17421 PHEVs.
    3.	Growth . Year: 2023, 2024 and 2025 with 25676 PHEVs.

### Top 10 Models & Make

•	The Top 10 BEV brands represent 90.21% (193570 units) of the total 214577.

•	The Top 10 PHEV brands represent 85.69% (46578 units) of the total 54354.

### Electric Range


•	Greater electric range of BEVs (199.6) vs PHEV (31.6).

•	BEVs. The largest number of units (28748 vehicles) are in the 201-300 electric range. The smallest number (2634 vehicles) are in the electric range greater than 301.

•	PHEVs. The largest number of units (50099 vehicles) are between 1 – 50. The smallest number in the electric range greater than 150 (14 vehicles).


### CAFV Eligibility 


•	Of the total number of electric vehicles (EVs = BEV + PHEV), only 28.5% fall into the Eligibility for Clean Alternative Fuel Vehicles (CAFV).

•	In absolute values, BEVs dominate Clean Alternative Fuel Vehicle (CAFV) Eligibility with 46289 units.

•	In percentage value, PHEVs dominate with 55.6% (vs 21.6% BEVs).

•	BEVs with the longest electric range (R3: 201–300) are predominantly eligible for CAFV incentives (62.1%).

•	PHEVs with the shortest electric range (R1: 1–50) are predominantly eligible for CAFV incentives (85.9%).



### Geolocation BEV & PHEV: Top 10 Counties


•	There is a concentration of EVs in the state.

•	The Top 10 counties have 91.4% (245724) of the state's EVs.

•	The Top 10 counties have 202 cities (41.2%) out of the total of 490 cities in the database.



### EV Charging Stations


•	The database includes 231 cities with a total of 2920 stations.

•	The Charging Station Saturation Level (CSSL), that is, the ratio of charging stations to the number of electric vehicles in the city over all years, is divided into six groups, CSSL1 – CSSL6, with CSSL1 being the highest saturation level.

•	Lowest % Station City/EVs City ratio (0.1%). Newcastle: 1335 EVs vs 1 charging station.

•	Highest Station City/EVs City % ratio (150%). Marblemount : 2 EVs vs 3 charging stations.

•	State ratio % Station City/EVs City is low 1.1% (2920 Stations /268931 EVs).


### Charging Stations Estimated EV Dec. 2025


•	The database includes 231 cities with a total of 2920 stations.

•	The number of EVs that could remain in December 2025 has been estimated. A battery life of 12 years is assumed, after which the vehicle is discarded.

•	The saturation level of charging stations for estimated electric vehicles (CSSL- EBEVs ) is in six large groups: CSSL-EBEVs1 - CSSL-EBEVs6, with CSSL-EBEVs1 being the highest saturation level.

•	Lowest ratio of charging stations to city EVs (2.4%). Newcastle: 1053 EVs vs 1 charging station.

•	Highest Station City/EVs City % ratio (300%). Marblemount : 1 EV vs 3 charging stations.

•	The ratio of Station City to EVs in the state is low at 1.6% (2920 Stations / 188091 EVs).


### Geolocation EV Charging Stations


•	There is a concentration of charging stations in a few cities in the state


### EV Charging Ports


•	The database includes 235 cities with a total of 8,410 charging ports. The Charging Port Saturation Level (CPSL), that is, the ratio of charging ports to the number of existing EVs over all years in the city, is divided into ten broad groups, CPSL1 – CPSL10, with CPSL1 being the highest saturation level.

•	Lowest Ports City/EVs City ratio (0.1%). Lake Forest Park: 959 EVs vs 1 charging port.

•	Highest Ports City/EVs City % ratio (400%). Washtucna : 1 EV vs 4 charging ports.

•	State Ratio % Ports City/EVs City of state is low 3.1% (8410 Ports /268931 EVs).

•	The type of connector can influence the impact on car charging demand at each station:
 
    o	The top 5 connector types (J1772, TESLA, J1772COMBO, CHADEMO J1772COMBO, CHADEMO J1772 J1772COMBO = 7454) represent 88.6% of the total number of connectors (8410).
    
    o	The J1772 connector (5359) represents 63.7% of the total number of connectors (8410).

### Geolocation of EV Charging Ports

•	There is a concentration of cargo ports in a few cities in the State.

### Limitations or elements not included

1.	Cities where EVs exist but no charging stations and/or ports, or where charging stations and ports exist but no EVs are registered. This could be due to the difference in the number of cities included in each database.
2.	The estimate is made taking into account a linear degradation of the batteries in BEVs. It is considered that, by the age of 12, the battery has already completely degraded.
3.	Other factors in battery life are not taken into consideration: temperature and climate, charging habits, brand and chemistry, battery replacement, sale or export of BEVs.
4.	The charging speed of each BEV vehicle is not taken into consideration.


