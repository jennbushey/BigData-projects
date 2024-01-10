# Housing Permits

[![Language](https://img.shields.io/badge/language-PySpark-blue.svg)](https://www.python.org/)

### The Assignment

Projects should propose solutions that are scalable, i.e., "big data" solutions. You can use "small data" to develop, test, and demo your solutions, but your solutions should scale to larger datasets. This implies that you need to use a big data framework, e.g., Hadoop or Spark or Flink, to implement your solution.

Apart from evaluating your project quality and progress, the goal of this presentation and the following presentations will be to facilitate collective learning through a variety of big data problems and approaches.

### Our Solution

Working in a team of 5 we were able to use a google colab notebook to preprocess each data source using resilient distributed datasets (RDD), perform basic exploratory data analysis big data using pyspark, and perform regression analysis using the PySpark Machine Learning Library (MLlib).

#### Feature Category Explanation

**Economic Indicators** - Large-scale economic indicators that may affect the housing prices in an economy. Ie employment rate, a city’s wealth, its population and growth, etc

-   Average Home Price
-   Unemployment Rate
-   Housing Starts
-   Calgary Population
-   Interprovincial Immigration
-   Inflation Rate
-   Assessed Year

**Group Price Indicators** - Factors that may influence a house price broadly based on other, location based factors. Ie neighborhood, density, crime rate, distance to downtown, desirability, etc

-   Density by Community
-   Community Name/Code
-   Crime Count
-   Resident Count
-   New Development by Community

**Individual Price Indicators** - Individual factors that may influence a house price, ie land size, type of dwelling

-   Property Type
-   Land Use Designation
-   Dwelling Type
-   Land Size

### Presentations

#### [Presentation 1]()

The presentation introduces our team and briefly describe the following information:

-   The chosen big data problem and why it is important to study.
-   The source(s) for data collection.
-   The target variable we are modeling and potentially interesting features of the dataset we will be focusing on during the project.
-   Any anticipated EDA and/or modeling techniques we might use.

#### [Presentation 2]()

The presentation includes how we've prepared the data for modeling (i.e., any cleaning, transformations, feature engineering, or Exploratory Data Analysis).

#### [Presentation 3]()

The final presentation shows our progress after the second set of presentations. In this presentation, the data has been fully preprocessed and the results of EDA are beginning to be defined. Moreover, by now, we have completed the preliminary modeling phase, where we have tried multiple models and/or model-tuning techniques and have insight into what is working for the data. We outline the remaining steps to take and any steps we need to redo based on the current results.

### [Final Report]()

The report comprehensively, yet concisely, describes how we acquired, processed, and modeled the data.

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
