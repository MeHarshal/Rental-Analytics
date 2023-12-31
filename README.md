<h1 align="center" >Rental-Analytics</h1>
                                              
🔘 **Introduction**

Delving into the rich landscape of real estate, this study focuses on collecting and analyzing data from nobroker.in, a prominent property website, to provide insights and recommendations. By leveraging web scraping techniques, we will explore the nuances of flats categorized by their bedroom configuration (1 BHK, 2 BHK, etc.), location, rental prices, deposit amounts, and furnishing status. Our analysis aims to shed light on broader industry trends, including area-wise property dynamics, maximum, average, and minimum rents, deposit amounts, and the relationship between rent and the number of bedrooms through informative scatterplots.

🔘 **Aim of the study**

The aim of this study is to collect and analyze data from nobroker.in to provide insights and recommendations for the real estate industry, focusing on flat types, location, rent, deposit, furnishing, and bedroom count.

🔘 **Data Source**

The data source for this analysis is nobroker.in, a real estate property website. The data was obtained by utilizing Selenium, a web scraping tool, within a Jupyter Notebook environment. The website was accessed programmatically to extract relevant information such as property types, built-up areas, rental prices, location details, and furnishing status. The collected data serves as the foundation for conducting the analysis and generating insights in this study.

🔘 **Data Description**

Before Conducting the analysis, the data was scrapped from nobroker.in using selenium library and the scrapped data was processed and saved into csv file using pandas library.<br>

<img src="https://i.ibb.co/pK91SvS/Rental-Scrapping-1.png" alt="Rental-Scrapping-1" border="0">
<p></p>
<img src="https://i.ibb.co/w6Xz0r5/Rental-Scrapping-2.png" alt="Rental-Scrapping-2" border="0">
<p></p>
<img src="https://i.ibb.co/K2rbtQh/Rental-Scrapping-3.png" alt="Rental-Scrapping-3" border="0">
<p></p>
<img src="https://i.ibb.co/tcxsc0T/Rental-Scrapping-4.png" alt="Rental-Scrapping-4" border="0">
<p></p>
<br>
The dataset obtained from web scraping using <b>Selenium</b> library and saved using <b>Pandas</b> library in a CSV file consists of information related to real estate properties. It includes the following features:

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

<img src="https://i.ibb.co/zSfBP2V/Dashboard.png" alt="Dashboard" border="0"><br>
This insightful real estate dashboard features interactive charts displaying property distribution by flat type, the relationship between flat type and built-up area, average and maximum rents by furnishing type, and location-wise average, maximum, and minimum built-up areas and rents. It enables users to make informed decisions based on key market insights.

🔘 **Visualizations**<br>

<img src="https://i.ibb.co/xzKMTKB/EDA-1.png" alt="EDA-1" border="0">
<p></p>
<img src="https://i.ibb.co/7YbRPY2/EDA-2.png" alt="EDA-2" border="0">
<p></p>
<img src="https://i.ibb.co/WyHhqPV/EDA-3.png" alt="EDA-3" border="0">
<p></p>
<img src="https://i.ibb.co/3vPx31X/EDA-4.png" alt="EDA-4" border="0">
<p> There are more number of 1 BHK, 2 BHK property listed in website compared to other type of property.</p>
<img src="https://i.ibb.co/YDNR4MP/EDA-5.png" alt="EDA-5" border="0">
<p>As the type of property is increasing, the built up area is also increasing.</p>
<img src="https://i.ibb.co/cr3DV1z/EDA-6.png" alt="EDA-6" border="0">
<p>There is a linear relationship between number of bedrooms and rent, as number of bedrooms is increasing, rent is also increasing.</p>
<img src="https://i.ibb.co/h2NqKLG/EDA-7.png" alt="EDA-7" border="0">
<p></p>

🔘 **Findings**

1.  As the type of property increases, such as from 1 BHK to 2 BHK and beyond, the built-up area tends to increase as well. This suggests that larger property types are associated with more spacious living areas.
2. 1 BHK and 2 BHK units are in higher demand or more readily available in the market, potentially reflecting the preferences and affordability of potential buyers or tenants.
3. There is a linear relationship between number of bedrooms and rent,As the number of bedrooms increases, the rent also tends to increase. This implies that larger properties with more bedrooms command higher rental prices, likely due to the increased living space and amenities they offer.
4. The data shows that Andheri East and Andheri West have the highest number of property listings
5. The majority of properties listed on the website are fully furnished. This indicates a preference for ready-to-move-in properties with complete furnishings. It could be driven by the convenience and time-saving aspect for tenants who prefer to have all the necessary furniture and appliances already provided in their rental units.  


🔘 **Summary**

1. The analysis indicates that as property types increase, there is a corresponding increase in their built-up areas, highlighting the availability of more spacious living spaces.
2. The market is dominated by 1 BHK and 2 BHK properties, suggesting a strong demand or higher supply of these types of units.
3. A positive linear relationship exists between the number of bedrooms and rent, with larger properties commanding higher rental prices. Andheri East and Andheri West emerge as popular locations with the highest property listings, while fully furnished properties are preferred by tenants.

🔘 **Challenges Faced**

1. Website Structure and Updates: Adapting to changes in the website's structure and layout during scraping, requiring frequent adjustments to the code.
2. Data Consistency and Quality: Ensuring accurate and reliable data by addressing variations, missing information, and inconsistencies in property listings.
3. Captcha and Access Restrictions: Overcoming security measures like Captcha and access restrictions to maintain uninterrupted scraping.
4. Dynamic Content and Rate Limiting: Handling dynamically loaded content and pagination while managing rate limits and potential IP blocking to collect comprehensive data.
