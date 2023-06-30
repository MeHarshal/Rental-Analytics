<h1 align="center" >Rental-Analytics</h1>
                                              
🔘 **Introduction**

Delving into the rich landscape of real estate, this study focuses on collecting and analyzing data from nobroker.in, a prominent property website, to provide insights and recommendations. By leveraging web scraping techniques, we will explore the nuances of flats categorized by their bedroom configuration (1 BHK, 2 BHK, etc.), location, rental prices, deposit amounts, and furnishing status. Our analysis aims to shed light on broader industry trends, including area-wise property dynamics, maximum, average, and minimum rents, deposit amounts, and the relationship between rent and the number of bedrooms through informative scatterplots.

🔘 **Aim of the study**

The aim of this study is to collect and analyze data from nobroker.in to provide insights and recommendations for the real estate industry, focusing on flat types, location, rent, deposit, furnishing, and bedroom count.

🔘 **Data Description**

Data Description:

The dataset obtained from web scraping using **Selenium** library and saved using **Pandas** library in a CSV file consists of information related to real estate properties. It includes the following features:

1. Type: This column represents the type of flats available, such as 1 BHK, 2 BHK, and so on.

2. Area: This column contains the location or area where the properties are situated.

3. Rent: This column provides the rental prices associated with the respective properties.

4. Deposit: This column indicates the deposit amounts required for renting the properties.

5. Furnishing: This column describes the furnishing status of the properties, categorized as fully furnished, semi-furnished, or unfurnished.

6. No_of_Bedrooms: This column specifies the number of bedrooms in each property.

These attributes provide essential details for analyzing and understanding the real estate market, enabling insights and recommendations to be derived for various stakeholders in the industry.

🔘 **Methodolgy**

Methodology:

1. Data Collection: Scrape data from nobroker.in using Selenium and save it in a structured format (e.g., pandas dataframes).

2. Data Cleaning and Preparation: Clean the collected data, handle missing values, remove duplicates, and ensure data consistency.

3. Exploratory Data Analysis: Conduct statistical analysis, create visualizations, and explore relationships between variables to gain insights into the real estate market.

4. Insights and Recommendations: Derive meaningful insights and provide informed recommendations based on the analysis results.

5. Reporting: Summarize findings, present key insights, and provide a comprehensive analysis of area-wise property dynamics, rental rates, deposit amounts, and the relationship between rent and the number of bedrooms.

🔘 **Dashboard**<br>
<img src="https://i.ibb.co/56g5TYJ/Covid-19-Analysis.png" alt="Covid-19-Analysis" border="0"><br>
This insightful real estate dashboard features interactive charts displaying property distribution by flat type, the relationship between flat type and built-up area, average and maximum rents by furnishing type, and location-wise average, maximum, and minimum built-up areas and rents. It enables users to make informed decisions based on key market insights.

🔘 **Visualizations**<br>
<img src="https://i.ibb.co/BtjVVBZ/Total-Cases-by-Continent.png" alt="Total-Cases-by-Continent" border="0">
<p></p>
<img src="https://i.ibb.co/FW3jP1c/Total-Cases-Distribution.png" alt="Total-Cases-Distribution" border="0">
<p></p>
<img src="https://i.ibb.co/2svbHBq/Total-deaths-by-Continent.png" alt="Total-deaths-by-Continent" border="0">
<p></p>
<img src="https://i.ibb.co/MGS36s6/Top-5-country-by-total-cases.png" alt="Top-5-country-by-total-cases" border="0">
<p></p>
<img src="https://i.ibb.co/YdJzVhb/Median-age-by-Continent.png" alt="Median-age-by-Continent" border="0">
<p></p>

🔘 **Findings**

1.  As the type of property increases, such as from 1 BHK to 2 BHK and beyond, the built-up area tends to increase as well. This suggests that larger property types are associated with more spacious living areas.
2. 1 BHK and 2 BHK units are in higher demand or more readily available in the market, potentially reflecting the preferences and affordability of potential buyers or tenants.
3. There is a linear relationship between number of bedrooms and rent,As the number of bedrooms increases, the rent also tends to increase. This implies that larger properties with more bedrooms command higher rental prices, likely due to the increased living space and amenities they offer.
4. The data shows that Andheri East and Andheri West have the highest number of property listings
5. The majority of properties listed on the website are fully furnished. This indicates a preference for ready-to-move-in properties with complete furnishings. It could be driven by the convenience and time-saving aspect for tenants who prefer to have all the necessary furniture and appliances already provided in their rental units.  


🔘 **Summary**

1. The analysis reveals a positive correlation between property types and their built-up areas, indicating that larger property types offer more spacious living areas.
2. 1 BHK and 2 BHK properties dominate the listings, suggesting higher demand or availability in the market.
3. There is a linear relationship between the number of bedrooms and rent, with larger properties commanding higher rental prices. Andheri East and Andheri West have the highest property listings, and fully furnished properties are preferred by tenants.

🔘 **Challenges Faced**

1. Collecting data from single platform for different location was time consuming.
2. Getting data well and consistent across different sources requires careful data cleaning and processing.
