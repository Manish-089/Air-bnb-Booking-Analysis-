

# Airbnb Booking Analysis

This repository contains a Jupyter Notebook that analyzes Airbnb booking data. The analysis covers data cleaning, exploration, statistical summaries, and potential visualizations related to Airbnb listings.

## Project Overview

The goal of this project is to analyze an Airbnb dataset by exploring key factors such as price, room type, availability, and the number of reviews. The dataset provides insights into host listings and patterns in different neighborhoods.

## Table of Contents

- [Dataset Overview](#dataset-overview)
- [Analysis Steps](#analysis-steps)
- [Libraries Used](#libraries-used)
- [How to Run](#how-to-run)
- [Conclusions](#conclusions)

## Dataset Overview

The dataset contains the following key columns:

- `listing_id`: Unique identifier for each listing.
- `listing_name`: Name of the Airbnb listing.
- `host_id`: Identifier for the host.
- `neighbourhood_group`: Region or neighborhood group where the listing is located.
- `latitude` & `longitude`: Geographical coordinates of the listing.
- `room_type`: Type of room (e.g., Private Room, Entire Home/Apartment).
- `price`: Price per night for the listing.
- `total_reviews`: Total number of reviews received.
- `last_review`: Date of the most recent review.
- `reviews_per_month`: Number of reviews per month.
- `host_listings_count`: Number of listings managed by the host.
- `availability_365`: Number of days per year the listing is available.

## Analysis Steps

The notebook includes the following steps:

1. **Data Loading**:
    - Import the dataset into a Pandas DataFrame for further analysis.
    - Display initial rows to understand the structure of the data.

2. **Data Exploration**:
    - Check the variables available in the dataset.
    - Investigate key columns like `price`, `room_type`, and `availability_365` to understand distribution patterns.

3. **Data Cleaning**:
    - Renaming columns for readability (e.g., `id` to `listing_id`, `calculated_host_listings_count` to `host_listings_count`).
    - Handling missing values and incorrect data types.

4. **Statistical Summary**:
    - Compute key statistics such as mean, standard deviation, and range for important numerical fields like `price`, `total_reviews`, and `availability_365`.
    
5. **Data Visualization** *(optional)*:
    - Create visualizations to better understand the relationships between variables.
    - Potential visualizations: Price distribution, Room type vs. Price, Listings by neighborhood.

## Libraries Used

The analysis uses the following Python libraries:

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical computations.
- `matplotlib`: For creating visualizations (if included).
- `seaborn`: For enhanced visualizations (if included).



## Conclusions

- **Price Variations**: Analyzed how the price of Airbnb listings varies across different room types and neighborhoods.
- **Host Activity**: Investigated the number of listings managed by hosts and the impact on availability and reviews.
- **Geographical Insights**: Mapped the distribution of listings across neighborhoods to identify popular areas.

---

This file outlines the workflow of your project and gives future users a clear idea of what to expect and how to run the notebook. Let me know if you'd like any modifications!
