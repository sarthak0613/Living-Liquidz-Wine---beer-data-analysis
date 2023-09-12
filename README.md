# Living-Liquidz-Wine-and-beer-data-analysis

![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/d5800f43-f123-44e5-825f-d82e025756ee)


### --Overview--

Welcome to the Living Liquidz Wine & Beer Data Analysis GitHub repository! This project focuses on extracting and analyzing data related to wines and beers from the Living Liquidz website (https://livingliquidz.com/). Through web scraping, I have collected valuable information about alcoholic beverages(wine & beer) available on the website, and this repository contains the code and documentation for this data extraction and analysis process.

### --Introduction--
Living Liquidz is a well-known platform for wine and beer enthusiasts, offering a wide range of alcoholic beverages. This project aims to leverage web scraping techniques to extract product data, analyze trends, and gain insights into the available wine and beer products on the Living Liquidz website.

### --Approach--

![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/db2efe4b-920a-49e5-ab06-7514e24c2c82)


### --Data Extraction--

- I used web scraping tools, such as Beautiful Soup and Requests in Python, to extract product details. This includes product names, prices, descriptions, ratings, and more.
- The website has multiple pages of products, so i implemented pagination handling to collect data from all available pages.
- Extracted data was stored in structured formats like CSV for further analysis.
- Code snippet
  ![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/56a79503-1a2d-433e-b905-26639201e1d5)

  
  ![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/11aae8cf-2989-48e5-ab14-65a4976b772e)

### --Data Cleaning--

- Addressed missing or incomplete information by either filling in missing values or removing rows with insufficient data.
- Converted data types of specific columns, such as prices and ratings, to facilitate analysis.
- Eliminated duplicate product entries to ensure data integrity.
- Cleaned and standardized text data, such as product names and descriptions, for better analysis.
- Data after cleaning
- ![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/66b51d0b-bddb-4d9e-8aa2-4ed05719ee05)

### --Insights--

- Average price of bottle sizes
![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/4abc60aa-287d-45e6-858f-d09a21f39e5c)

- Count of liquor by bottle size & type
![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/14d061e4-30fd-4eed-b91a-d1438618e4b8)

- Average price by liquor category
![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/69b73104-5d6f-4c3c-bdd3-2347513e245b)

- Proportion of liquor type
![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/fc2aad3e-1aff-4a46-9641-8482cecfe7b1)

### --Some key insights--

- Total Wines- 1019 
- Domestic- 162
- Imported- 857
- Max price of wine- 475000
- Min price of wine- 750


- Total Beers- 117
- Domestic- 102
- Imported- 15
- Max price of beer- 695
- Min price of beer- 100

### --Dashboard--

![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/2f5b0ba4-a66d-4f47-a8c6-6f7e77171a1a)


### --Challenges faced--

- Data on the website may not always be consistent, leading to variations in product listings
- Data cleaning of the raw data in csv using power query.
- Combining dataframe as one dataframe.


