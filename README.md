# AirBnB-Project

This project provides an Exploratory Data Analysis (EDA) of Airbnb listings in New York City. The goal is to uncover trends regarding pricing, neighborhood popularity, and room types to provide actionable insights for hosts and travelers.

🛠 Project Overview
The dataset contains information about Airbnb listings in New York City, including pricing, location data, review metrics, and host details.

Key Steps Taken:
Data Cleaning:

Removed duplicates and irrelevant columns (license, house_rules, id, host id).

Converted price and service fee from currency strings to numerical (float) types.

Handled missing values in last review, reviews per month, and review rate number.

Exploratory Data Analysis (EDA):

Visualized price distributions across the city.

Analyzed the frequency of room types (Entire home, Private room, etc.).

Identified neighborhood trends (Manhattan vs. Staten Island).

Examine relationships between prices, neighborhoods, and room types using box plots.

Analyzed review trends over time.

📊 Key Insights
Neighborhood Popularity: There is a significantly higher volume of listings in Manhattan and Brooklyn compared to other boroughs.

Pricing: Listings maintain relatively consistent price ranges across different neighborhood groups.

Review Trends: Activity peaked significantly in 2019, with over 40,000 reviews recorded.

💻 Technologies Used
Python

Pandas & NumPy (Data Manipulation)

Matplotlib & Seaborn (Data Visualization)

Jupyter Notebook

🚀 How to Run

Open the Jupyter Notebook: jupyter notebook AirBnB_project.ipynb
