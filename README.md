# NewYork Airbnb_data_inspection.project

Project Overview

This project performs Exploratory Data Analysis (EDA) on New York Airbnb data to uncover trends and patterns in rental listings. We use libraries like Pandas, Matplotlib, Seaborn for cleaning, visualization, and analysis.

Objective:

Analyze room types, prices, and availability across different neighborhoods.
Understand host behavior and listing patterns.
Detect potential outliers in prices.
Provide recommendations for guests and hosts based on insights.

The dataset contains 20,765 entries and 22 features, including:

id: Unique identifier for each listing,
name: Title of the Airbnb listing,
host_name: Name of the host,
neighborhood_group: Group (borough) where the listing is located,
latitude/longitude: Geolocation of listings,
price: Nightly rental price,
room_type: Type of accommodation (e.g., entire home, private room),
reviews_per_month: Average monthly reviews for the listing and 
availability_365: Number of available days in the year

Steps and Workflow:
1) import libraries
2) upload dataset
3) initial exploration with pandas
4) data cleaning with pandas 
5) data analysis with mathplotlib and seaborn

Key Findings and Insights

Price Trends:
Manhattan has the most expensive listings, followed by Brooklyn.
Entire homes/apartments cost significantly more than private or shared rooms.

Outliers in Price:
Few listings priced at $10,000+ were detected, indicating the need to filter such extreme values.

Availability Patterns:
Listings with high availability tend to have lower prices and more reviews, likely due to better guest experience.

License
This project is open-source and licensed under the MIT License. 
