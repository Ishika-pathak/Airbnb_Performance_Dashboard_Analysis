# Airbnb Performance & Portfolio Dashboard | Power BI

# Project Overview

This project focuses on analyzing Airbnb listing data across major global cities using Microsoft Power BI. The dashboard explores listing trends, host performance, property distribution, pricing, and customer satisfaction.

The objective is to understand how Airbnb listings perform across different markets and identify patterns that can help hosts and property managers make better business decisions.

# Project Objectives

- Analyze Airbnb listing growth over time.
- Compare Superhost and regular host performance.
- Explore listing distribution across cities and room types.
- Understand customer satisfaction through review ratings.
- Analyze host responsiveness and guest experience.
- Explore property types, pricing, and availability patterns.

# Dataset

Source: Maven Analytics – Airbnb Listings and Reviews Dataset
DOWNLOAD DATASET FROM HERE - https://mavenanalytics.io/data-playground/airbnb-listings-reviews

The dataset is included in this repository and consists of two main CSV files:

1. Listings.csv

Contains listing-level information, including:
- Listing ID and Host ID
- Host Since
- City and Neighbourhood
- Latitude and Longitude
- Property Type and Room Type
- Price
- Superhost Status
- Host Response Time and Response Rate
- Acceptance Rate

2. Reviews.csv

Contains customer review information, including:
- Listing ID and Review ID
- Review Date
- Reviewer ID
- Overall Review Score
- Cleanliness
- Check-in
- Communication
- Location
- Value

# Tools & Technologies

- Microsoft Power BI Desktop – Dashboard development and data visualization
- Power Query – Data cleaning and transformation
- DAX – Calculated measures and KPI development
- CSV – Dataset storage and input

# Data Cleaning & Preparation

Data cleaning and transformation were performed using Power Query.

Key steps included:

- Checking missing and null values.
- Removing unnecessary columns.
- Standardizing date and numeric data types.
- Validating Listing IDs.
- Assigning appropriate geographic data categories.
- Preparing datasets for analysis.

# Data Modeling

A relational data model was created in Power BI using Listing ID as the common field between the Listings and Reviews tables.

- Listings table connected to Reviews table.
- Many-to-one relationship established.
- Bidirectional cross-filtering configured for interactive analysis.
- Unnecessary dictionary tables excluded from the final model.

# Dashboard Features

The report consists of three interactive pages.

1. Executive Overview

- Total Listings
- Total Cities
- Total Hosts
- Total Superhosts
- Total Reviews
- Listing growth trends over time
- Room-type-wise listing trends

2. Ratings & Market Analysis

- Superhost vs. Regular Host distribution
- City-wise listing comparison
- Average review ratings across cities
- Property type and room type analysis
- Price and availability comparison

3. Host & Customer Experience

- Overall guest satisfaction analysis
- Cleanliness, Check-in, Communication, Location, and Value ratings
- Host response time analysis
- Superhost performance comparison

# Key Insights

The dashboard helps explore several patterns in Airbnb's global listing data:

- Entire homes and private rooms account for a significant share of listings.
- Listing growth varies across different years and markets.
- Superhost distribution differs across cities.
- Guest satisfaction can be evaluated across multiple service attributes.
- Host responsiveness can be compared with customer review scores.

# Project Structure

```text
Airbnb-Performance-Dashboard/
│
├── Dataset/
│   ├── Listings.csv
│   └── Reviews.csv
│
├── Airbnb_Performance_Dashboard.pbix
│
└── README.md
```

# How to Run the Project

1. Clone or download this repository.
2. Open `Airbnb_Performance_Dashboard.pbix` using Power BI Desktop.
3. If Power BI cannot locate the CSV files, navigate to Transform Data → Data Source Settings.
4. Update the file paths to point to the CSV files included in the repository.
5. Refresh the data to explore the interactive dashboard.

Note: The dataset is already included in this repository. No separate dataset download is required.

# Credits & Acknowledgements

- Dataset: Maven Analytics
- Project Inspiration: Mansi G. – Power BI Tutorial
- Tools: Microsoft Power BI
