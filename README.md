# Sacramento Housing Market Analysis

## Project Overview
This project analyzes rental listings in Sacramento, California to provide insights into rental prices, property types, neighborhoods, and key listing features. The goal is to help people understand market trends, compare apartments versus houses, and identify key factors that influence rent prices.

## Problem Statement
How does the rental market in Sacramento vary by property type, neighborhood, and features such number of bedrooms/bathrooms? 

## Key Insights
- Apartments generally have smaller average rents 
- Houses have higher average prices per square foot.
- Neighborhoods like Midtown and Downtown show the highest average rents.
- Number of bedrooms and property type significantly impact rent.
- Number of bathrooms does not show correlation with price besides the jump from 1 to 2.

## Dashboard Features
- **KPI Cards**: Average Price, Average Price per SqFt, Average Bathrooms, Average Bedrooms
- **Map Visual**: Geographic distribution of rental listings with bubble size representing price and price per sqft
- **Clustered Column Chart**: Average Price by key factors
- **Pie Chart**: Distribution of property types
- **Slicers**: Property Type, Neighborhood
- **Interactive filtering**: All visuals update based on slicer selections and clicking of any visual (Use on maps)

## Tech Stack
- Python (Pandas, Selenium, BeautifulSoup)
- HTML for parsing data
- Power BI Desktop (DAX, interactive visuals, KPIs, maps)
- Excel / CSV for output data

## How to Use
1. Start with Sacramento_Housing.ipynb for a short summary of how I scraped the data
2. Open Sacramento_Housing.xlsx to see the output data
3. Open Housing_Price_Analysis_Report.pbix in Power BI Desktop
4. Interact with slicers to filter by property type, neighborhood, or number of bedrooms
5. Explore the map, charts, and KPI cards for insights into Sacramento’s rental market




