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
#### Code snippet

- This Python script scrapes information about wine products from a specific webpage using BeautifulSoup.
- It extracts data like wine names, bottle sizes, and MRP, storing it in lists and then creating a Pandas DataFrame to organize the collected information.
![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/6efca6ce-eec0-4cb9-bf50-54e48d7a31f1)

![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/f2f414f4-2640-45be-8816-e7ead685a34f)

- This code snippet uses BeautifulSoup to find and print the text content of HTML elements with the class "fw-500 m-0 text-dark ll-product-title."
- It extracts and displays the names of products from the webpage.
![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/b9e8287a-5006-469e-9308-69a2ff6c497b)

![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/a2de5cec-f1c5-4a61-b0a6-36754de173c1)

- This code snippet utilizes BeautifulSoup to find and print the text content of HTML elements with the class "wbr-amount fs-16."
- It extracts and displays the Maximum Retail Prices (MRP) of products from the webpage.
![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/bcc3c034-4616-4369-82af-4fd5a406c01f)
![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/7fea26cd-4d39-442e-9dfa-634a38d0149d)

- This code snippet employs BeautifulSoup to locate and print the text content of HTML elements with the class "btn color-black p-0 fw-500 wbr-cmp-variation-view-toggle."
- It extracts and displays the bottle sizes of products from the webpage.
![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/c76f60ca-b28c-46af-84a8-16bebde91fa8)

- This code creates a Pandas DataFrame named 'domesticwine' by combining the extracted data from three lists: 'names' for product names, 'mrp' for prices, and 'bottle_size' for bottle sizes.
- The DataFrame organizes this information into columns with the respective names: 'Name,' 'Price,' and 'Bottle size.'
![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/95db6afb-119e-4e22-8d83-09ceb6e6fb51)
![image](https://github.com/sarthak0613/Living-Liquidz-Wine---beer-data-analysis/assets/135547703/02d17268-0ec3-4de6-b1a0-abc342cb6a90)

### Similarly I have created dataframes for different category of liquors from the website. The python(ipynb) file has all the code for rest of the categories.

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


