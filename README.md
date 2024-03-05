# nosql-challenge\
This project focuses on analyzing the hygiene and ratings of food establishments within the UK, specifically targeting those within London and near the newly added restaurant, "Penang Flavours." Utilizing MongoDB for data management and Pandas for data analysis, the project aims to uncover insights into establishment ratings, hygiene scores, and geographic proximity to "Penang Flavours." The dataset, contained in a MongoDB database called uk_food, includes details such as business names, types, local authority information, rating values, and geocode data.

Using data queries in order to find certian information important to the analysis of the json file labeled "establishments.json", data was displayed and dataframe were created. In summary, establishments with a specific hygiene score were identified. Establishments in London with a RatingValue greater than or equal to 4, using regex for flexible matching on the LocalAuthorityName, were identified. A search for top-rated establishments near "Penang Flavours," considering geographic proximity and hygiene scores was carried out.Pandas was employed for converting query results into DataFrames, facilitating detailed examination and manipulating data.

Key Findings:

Hygiene Score Analysis: Identified establishments with hygiene scores equal to 20, providing insights into the distribution of hygiene standards across the dataset.

Rating Analysis in London: Found establishments in London with high RatingValues, indicating a concentration of highly rated establishments within specific areas.

Proximity to "Penang Flavours": The top 5 establishments with a RatingValue of 5 and sorted by the lowest hygiene score nearest to "Penang Flavours" were identified, highlighting competitive standards in the vicinity.

Aggregation on Hygiene Scores: Grouped establishments by Local Authority based on hygiene scores, revealing trends and outliers in hygiene standards across different authorities.
Analysis

The exploratory analysis provided valuable insights into the hygiene and rating standards of food establishments in the UK, with a particular focus on London. High-rated establishments near "Penang Flavours" suggest a competitive environment with generally high hygiene standards. The aggregation by Local Authority further emphasizes the variance in hygiene standards, which could inform potential areas for improvement or highlight regions with exemplary standards.

The use of MongoDB's querying capabilities, combined with Pandas' data manipulation strengths, proved effective in extracting, analyzing, and presenting relevant data points for this analysis. Future directions could include a deeper geographic analysis using more sophisticated geospatial querying and aggregation techniques in MongoDB.
