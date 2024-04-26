# Predicting Calgary Housing Prices

[![Language](https://img.shields.io/badge/language-PySpark-blue.svg)](https://www.python.org/)

This project utilizes PySpark for scalable big data solutions to predict housing prices in Calgary. The team processed data using resilient distributed datasets (RDD) and conducted exploratory data analysis (EDA) and regression analysis with PySpark's MLlib.

#### Feature Category Explanation

**Economic Indicators** - Large-scale economic indicators that may affect the housing prices in an economy. Ie employment rate, a city’s wealth, its population and growth, etc.

-   Average Home Price
-   Unemployment Rate
-   Housing Starts
-   Calgary Population
-   Interprovincial Immigration
-   Inflation Rate
-   Assessed Year

**Group Price Indicators** - Factors that may influence a house price broadly based on other, location based factors. i.e. neighborhood, density, crime rate, distance to downtown, desirability, etc.

-   Density by Community
-   Community Name/Code
-   Crime Count
-   Resident Count
-   New Development by Community

**Individual Price Indicators** - Individual factors that may influence a house price, i.e. land size, type of dwelling

-   Property Type
-   Land Use Designation
-   Dwelling Type
-   Land Size

### Presentations

-   [Presentation 1:](./Presentation%201.pdf) Introduction and problem importance.
-   [Presentation 2:](./Presentation%202.pdf) Data preparation, cleaning, and transformation.
-   [Presentation 3:](./Presentation%203.pdf) EDA, modelling, and results.

### Final Report

-   [Final Report:](./Final%20Report.pdf) Comprehensive overview of data acquisition, processing, and modeling.

### Data sources:

Accessed data by API request and directly downloaded where necessary.

-   The City of Calgary [Assessed Property Values](https://data.calgary.ca/Government/Historical-Property-Assessments-Parcel-/4ur7-wsgc)
-   The City of Calgary [Civic Census by Community and Dwelling Structure](https://data.calgary.ca/Demographics/Civic-Census-by-Community-and-Dwelling-Structure/set9-futw)
-   The City of Calgary [Prosperous City Indicators](https://data.calgary.ca/Government/Prosperous-City-Indicators/nbta-7ws9/about_data)
-   The City of Calgary [Community Crime and Disorder Statistics](https://data.calgary.ca/Health-and-Safety/Community-Crime-and-Disorder-Statistics-2012-2019-/848s-4m4z)
-   The City of Calgary [Open Calgary Development Permits](https://data.calgary.ca/Business-and-Economic-Activity/Development-Permits/6933-unw5/about_data)
-   The City of Calgary [Open Calgary Building Permits](https://data.calgary.ca/Business-and-Economic-Activity/Building-Permits/c2es-76ed/about_data)
-   The City of Calgary [Historical Community Populations](https://data.calgary.ca/Demographics/Historical-Community-Populations/jtpc-xgsh)
-   Statistics Canada [Interprovincial Migration](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1710002201)
-   Statistics Canada [Historical CPI](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810025901)
