# Production-Quantity-Prediction

The given data is monthly production quantity for a specific agricultural product  in 10 different states of a country between  2015 to  2020. 

 **This work aims to predict the production quantity for the product from Jan 2021 to Dec 2021.
**

The Data looks like below :
1.production_Quantity.csv with 4 columns: 
startdate, enddate: start day and end day of each month between January 2015 to Dec 2020.
production: production quantity, regionID : ID of states

2.Precipitation_Daily.csv has 4 columns 
startdate, enddate: start day and end day at a daily frequency between January , 2014 to Mar, 2022.
precipation: daily precipation
regionID: ID of states

3. SoilMoisture_Daily.csv with 4 columns:
startdate, enddate: start day and end day at daily frequency between January , 2014 to Mar , 2022.
smos: Soil Moisture at 5cm depth (measured by the ratio Vol/Vol) at daily frequency
region_id: ID of states

4. Temperature_Daily.csv with 4 columns:
startdate, enddate: start day and end day at daily frequency between January , 2014 to Mar , 2022.
temp: Average daily temperature(C) on land at daily frequency
region_id: ID of states

5. NDVI_8.csv with 4 columns:
startdate, enddate: start day and end day at 8-day frequency between Dec, 2013 to Mar, 2022.
ndvi: Normalized Difference Vegetation Index  at 8 day frequency 
region_id: A unique identifier for the 10 provinces

6. production_Prediction.csv with 4 columns :
startdate, enddate: start day and end day of each month between Jan 2021 to Dec 2021.
production: This column needs to be predicted with their predictions of specific agricultural product.
region_id: ID of states
