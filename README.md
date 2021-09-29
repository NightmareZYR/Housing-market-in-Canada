# Housing-market-in-Canada
This is an exploration of Housing market in Canada.

All the code and tables are in the document folder.

# Data collection - Point2homes.ca

![Image of point2homes](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Point2homes.png)

Data is collected from Point2homes.ca (Data Collection folder) and store in the CSV file (Data folder).

Data is classified as Houses which are in NS, PE, NB, NL, QC, ON, MB, SK, AB, and BC.

![Image of point2homes](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Provinces.png)

Codes are:

Data Collection 0 : Atlantic region   - NS, PE, NB, NL

Data Collection 1 : Central Canada    - QC, ON

Data Collection 2 : Prairie Provinces - MB, SK, AB

Data Collection 3 : West Coast        - BC

Tables are the CSV files begin with **"Point2_data_"** 

Data Collection 4 (New): Collect all the housing data which has price drop in the last six months 

# Data cleaning  

## Data cleaning 0:
### 1. Combining all collected data
### 2. Adding Columns "Province" and "Region"

Point2_data_Canada_house_ExcludingNorth (Combined all collected data and adding columns "Province" and "Region")

![Image of point2homes](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Canada%20Housing%20Data%20excluding%20North.png)

## Data cleaning 1:
### 1. Formating and irrelevant columns
* Drop irrelevant columns
* Clean the format
### 2. Missing values
* Store missing values (for future improvements)
* Drop the missing values or replace them(future updates)
### 3. Duplicated values
* Store duplicated values (for future improvements)
* Drop duplicated values 
### 4. Outliers
* Store outliers (for future improvements)
* Drop outliers

## Data cleaning 2:
### 1. Adding 'Latitude' Column, 'Longitude' Column, and 'Location' Column
* Collect 'Latitude', 'Longitude', 'Location' using Geopy.
### 2. Remove the NaN values of rows in new columns.
### 3. Use Folium to verify the coordinates of data from NS, PE, NB, and NL on the map.

## Data cleaning 3:
### 1. Use Folium to verify the coordinates of data from QC and ON on the map.

## Data cleaning 4:
### 1. Use Folium to verify the coordinates of data from MB, SK, AB and BC on the map.
### 2. Combine all the provinces together.

![Image of data cleaning](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Data%20with%20coordinates.png)

## Data cleaning 5 (New):
### 1. Combine all the collected data which has price drop in the six months.
### 2. Store them in the file.

# Data Visualization
## Data visualization 0:
* Use Folium to visualize all the data on the map

![Image of data visualization map](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Map.png)
Blue: Altlantic Region; Red: Central Canada; Green: Prairie Provinces; Purple.

## Data visualization 1:
### 1. Number of houses with different Bedrooms on the housing market.

![Image of data visualization map](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Bedrooms_counts.png)

### 2. Number of houses with different Bathrooms on the housing market.

![Image of data visualization map](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Bathrooms_counts.png)

### 3. Number of houses with different bedroom-bathroom combo on the housing market.

![Image of data visualization map](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Combo_counts.png)

### 4. Average housing price with different bedroom-bathroom combo on the housing market.

![Image of data visualization map](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Combo_Price.png)

### 5. Average housing squarefeets with different bedroom-bathroom combo on the housing market.

![Image of data visualization map](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Combo_avgSqft.png)

### 6. Average housing price per squarefeet on the housing market.

![Image of data visualization map](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Price_per_Sqft.png)

### 7. Average housing price per bedroom on the housing market.

![Image of data visualization map](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Price_per_Bedroom.png)

### 8. Average housing price per bathroom on the housing market.

![Image of data visualization map](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Price_per_Bathroom.png)

### 9. Distributed housing price (coordinates) on the housing market.

![Image of data visualization map](https://raw.githubusercontent.com/NightmareZYR/Housing-market-in-Canada/main/Documents/Sceenshoots/Price_coordinates.png)







