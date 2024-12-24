# Context
In recent years, there has been a growing interest in leveraging data-driven approaches to predict hotel prices, considering various influencing factors. While previous studies have explored pricing models, they often lacked a comprehensive integration of location-specific attributes, customer preferences, and hotel features. Furthermore, many models were developed using static datasets that did not account for dynamic filtering criteria or real-world applicability.

This study aims to bridge these gaps by constructing a machine learning model to predict hotel prices based on a detailed dataset collected from www.obilet.com on 17.12.2024. The dataset, refined through automated scraping using Selenium and manual verification, includes data from hotels filtered by city and price range (highest and lowest). Key features such as distance to city center, customer ratings, number of reviews, and accommodation types have been meticulously incorporated.

In summary, this research focuses on analyzing and predicting hotel prices by considering factors such as hotel location, ratings, reviews, pricing policies, and included amenities. By integrating advanced machine learning techniques, the study aims to provide actionable insights for both consumers and businesses, enabling more informed decisions in the hospitality industry.

# Content

This project emphasizes the importance of accurate data collection and preprocessing. Hotel data was sourced from www.obilet.com on 17.12.2024, with filters applied to include only relevant details such as city, pricing range, and key hotel attributes. The dataset comprises 176 rows and 9 columns, featuring variables like hotel name, address, distance to the city center, customer ratings, and accommodation types.

Initial inspection of the dataset revealed some missing values in attributes such as customer reviews and star ratings. These gaps were addressed using appropriate imputation methods in Python. Hotels with insufficient or inconsistent data were excluded from the final dataset to ensure model reliability.

The cleaned dataset, with 176 rows and 9 columns, forms the basis for the analysis. Variables are categorized into key factors such as location, pricing, customer feedback, and amenities. The refined dataset is ready for machine learning applications to predict hotel prices and provide insights for the hospitality industry.

# Columns

Hotel_Name: Contains the names of the hotels.

Hotel_Address: Indicates the location of the hotel.

Distance_to_Center: Represents the hotel's distance to the city center.

Number_of_Reviews: Total number of customer reviews for the specific hotel.

Customer_Rating: The average rating given to the hotel by customers.

Number_of_Stars: The number of stars assigned to the hotel by the website.

Price: The accommodation fee for a couple (two adults only) between 01.09.2025 and 07.09.2025.

Free_Cancellation: Indicates whether the hotel charges an additional fee for reservation cancellations.

Accommodation_Type: Specifies what is included in the price for the respective hotel.
