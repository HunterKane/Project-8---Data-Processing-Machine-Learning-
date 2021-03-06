# Project-8---Data-Processing-Machine-Learning-

Complete this project by predicting housing prices in Califronia for more than 26 districts. 

Questions to answer:
What are the biggest factors that influence housing prices in a given area?


Machine Learning Prep:
- Transform some features
- Separate features and labels
- Convert text/categorical data into numerical data

Method for completion:

1) Data import and inspect
2) Data Cleaning 
3) Use Seaborn to represent data 
4) Use the data to create Future Engineering for Machine Learning

Dict:

* **longitude:**  geographic coordinate (district´s east-west position)
* **latitude:**  geographic coordinate (district´s north-south position)
* **housing_median_age:** median age of houses in district
* **total_rooms** Sum of all rooms in district
* **total_bedrooms** Sum of all bedrooms in district
* **population:** total population in district
* **households:** total households in district
* **median_income:** median household income in district 
* **median_house_value:** median house value in district
* **ocean_proximity:** District´s proximity to the ocean



Key points gathered from data:

Mean aggregate key points to acknowledge
- The average household is 3.07
- Average rooms are 5.43
- 0.21 bedrooms per room

Positive correlations between the following:
- Higher the income / higher the housing value
- Rooms per household/house prices (larger the house higher the price)
- Median housing age / larger districts

Weak or no correlation(no linear) between the following:
- house price and household
- population / longitude

Negative correlation
- bedrooms per room (more non-bedrooms per household)


Info gathered from Density graph:

This density graph represents the highest amount of population in relations to housing prices and area. This could mean larger cities for more housing. Higher the deman for housing the more expensive the district. 

- Highest density of housing is 100,000(MHV) / longitude of 118 & latitiude of 34
- Second highest density is 280,000(MHV) / longitude of 122 & latitiude of 37.5

Two major areas with the highest density are S.F and L.A.

- Highest density closest to the ocean / ocean proximity influences housing prices and density
- Standard of beach influences demand / demand for housing increases near ocean access



#Conclusion from Data: Top features thats influence housing price. 

- Median income has the highest importance
- Inland or not (location)
- Bedrooms her household
- Rooms per house

