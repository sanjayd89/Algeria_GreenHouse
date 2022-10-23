# Exploratory Data Analysis of AICU data

We have overall 6 months of data for various datasets

## 1.0 Insights from Greenhouse Climate:
### 1.1 Climate conditions
-	Water requirement has increased over the months
-	Sensor for Crop pipe Temperature (Growth circuit) is not working as temperature readings are not being recorded by the same
-	As the climate is moving from colder (Jan) to hotter temperatures (June) evident by increase in temperature of air (Tair), the humidity deficit within the Greenhouse is increasing and correspondingly to Relative Humidity of air is reducing.
-	Except for end of June month, the CO2 dosage is maintained constant within the Greenhouse to facilitate plant growth.
### 1.2 Setpoints comparison between Realized and established Setpoints
-	Humidity deficit setpoint is not triggered which means proper levels of moisture is maintained in the air inside Greenhouse.
-	Sensor measuring realized Rail pipe minimum temperature is not working as not data is captured.
## 2.0 Insights from Resources consumption
-	Resources like Heat consumption, Electricity (peak and off-peak hours), CO2 Consumption is reducing over the given period but the Water requirements for Irrigation as well as Drainage increasing.
## 3.0 Insights from Lab Analysis of Concentration of Elements present in Irrigation and Drainage water
-	Over the 6 month period, the concentration of various salts are increasing in the drainage water.
-	Irrigation has numerous advantages, but significant concerns exist as well. The main threat to soil health in dry regions is the accumulation of salts, and in some cases also sodium. As salt accumulation increases in the soil, crops have more difficulty getting the water that’s there. When sodium accumulates, aggregates break down and soils become dense and impossible to work. Over the centuries, many irrigated areas have been abandoned due to salt accumulation.
-	Hence, high concentration of salts in the drainage water indicates effective removal of the salts from the soil leading to healthy soil composition.
-	The ph value of irrigation water is more towards alkaline whereas the drainage getting more acidic by the end of 6 months.
-	Water pH is important for crop management because it affects the solubility of fertilizers and the efficacy of insecticides and fungicides before its applied to the crop. Generally, the higher the water pH, the lower the solubility of these materials. 
-	The Electrical conductivity of drainage water is increasing as the months go by.
-	Iron concentration is continuously increasing in the drainage water from the month of February. 
## 4.0 Insights of Slabs at Root Zone using Grodan Sensors
-	Temperature & Electrical Conductivity variation across 2 slabs is same
-	Water content is high in slab 1 compared to slab 2
-	The water content is reducing over the 6 month period leading to higher temperature at the root zone.
## 5.0 Insights from Crop Parameters:

- Stem thickness plays important factor in overall crop growth
- Stem thickness is directly proportional to Stem elongation and inversely proportional to number of trussess formed


## 6.0 Tomato Quality 
-	Flavor is directly related to %Juice which is Percentage juice pressed from the fruit wall of the tomato
-	Higher the weight of the tomato lower is the acid content in Tomato


## 7.0 Insights from Final Produce
-	Truss development time is inversely proportional to Avg no. of harvested trusses as well as Weight of fruits of Class A. Class A means top quality trusses that can be commercially traded whereas Class B refers to trusses that cannot be commercially traded.
-	This means if we can maintain the conditions inside the Greenhouse to facilitate truss development, we can get good quality of Tomatoes.
