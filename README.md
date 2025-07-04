# Zomato-Restaurant-Analysis
ntry, and city
Services like online delivery or table booking
Average rating categories
Identify restaurants with the highest number of cuisines served.
Create a multi-page Power BI report with easy navigation.
Ensure the report is accessible via web browsers and mobile devices.
🛠 High-Level Steps

Data Import: Load restaurant data from multiple Excel files.
Data Transformation: Clean and preprocess the data (fix city names, remove unused columns, create new tables, etc.).
Data Modeling: Define relationships between tables, ensuring correct cardinality and filter directions.
Data Manipulation: Categorize geographic columns, create user-defined hierarchies, and group countries into continents.
Using DAX (Data Analysis Expressions):
Define a "Rating Color" column based on the rating scale.
Create measures like Restaurant Count, Average Cost, Average Rating, and Cuisine Count.
Map countries to continents.
Data Visualization: Develop interactive Power BI reports with:
Cards displaying key metrics (Average Cost, Average Rating, Restaurant Count)
Maps showing restaurant distribution
Slicers for filtering data
Infographic designer visuals for top restaurants
Gauges to visualize restaurant ratings and costs
Navigation buttons for an intuitive user experience
Publishing & Accessibility:
Publish the report On netlify
🏗 Dataset Details The dataset consists of multiple Excel files containing restaurant information across different continents. Key tables include:

Restaurant Data: Restaurant name, address, city, country, cuisines, average cost, rating, etc.
Geographic Data: Country codes and continent mappings.
Fact Table: Aggregated restaurant-related metrics.
