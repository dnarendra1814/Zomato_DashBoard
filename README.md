# Zomato Restaurant Analysis Dashboard

A single-page Power BI dashboard that analyzes restaurant performance, customer engagement, and service availability (online delivery and table booking) across 250 Zomato restaurants in 15 Indian cities.

## Screenshot

![Overview](screenshots/overview.png)

## Problem / Objective

The dashboard is built to answer questions such as:

- How many restaurants are there, and how well are they rated overall?
- Which cuisines and cities have the highest average ratings?
- How many restaurants offer online delivery and table booking?
- Does a higher rating mean more customer engagement (votes)?
- How do results change by city, cuisine, price range, delivery option, and table booking?

## Dataset

- **Source:** [Add the source, e.g. Kaggle dataset name / link]
- **File:** `Zomato.xlsx`
- **Size:** 250 restaurants, 10 columns, 15 cities (all in India), no missing values
- **Columns:**

| Column | Description |
|---|---|
| Restaurant Name | Name of the restaurant |
| City | City where the restaurant is located |
| Country | Country (India) |
| Cuisine | Primary cuisine type |
| Rating | Customer rating (2.5 to 4.9) |
| Votes | Number of customer votes |
| Average Cost for Two | Average cost for two people |
| Price Range | Price category from 1 (low) to 4 (high) |
| Online Delivery | Whether online delivery is available (Yes/No) |
| Table Booking | Whether table booking is available (Yes/No) |

## Tools Used

- Power BI Desktop
- DAX (measures and calculations)
- SQL (data preparation)

## Dashboard Features

- **KPI cards:** Total Restaurants, Average Rating, Total Votes, Average Cost
- **Slicers:** City, Cuisine, Online Delivery, Table Booking, Price Range
- **Visuals:**
  - Top 10 Cities by Restaurant Count
  - Total Restaurants by Table Booking (donut chart)
  - Online Delivery Availability (pie chart)
  - Average Rating by Cuisine (bar chart)
  - Rating vs. Votes by Restaurant (scatter plot)

## Key Insights

- **Overall:** 250 restaurants with an average rating of **3.78**, about **643K total votes**, and an average cost for two of about **741**.
- **Services:** **70%** of restaurants (175) offer online delivery, but only **34.8%** (87) offer table booking.
- **Cuisines:** **Seafood** has the highest average rating (4.13), followed by **Continental** and **South Indian** (4.01 each). **North Indian** is the lowest (3.49). Each cuisine has only 12 to 26 restaurants, so these gaps are indicative rather than conclusive.
- **Cities:** **Surat** has the most restaurants (23), followed by Hyderabad (22) and Ahmedabad (21). **Mumbai** (3.99) and **Jaipur** (3.98) have the highest average ratings, while **Chandigarh** (3.44) has the lowest.
- **Ratings vs. votes:** There is almost no relationship between a restaurant's rating and its number of votes (correlation of about -0.05), so a high rating does not mean more engagement.

## How to Open

1. Download `Zomato_Restaurant_Analysis.pbix` from this repository.
2. Open it in **Power BI Desktop**.
3. Use the slicers to explore the data.

## Author

**Narendra Deshmukh**
GitHub: [Narendra1418](https://github.com/Narendra1418)
