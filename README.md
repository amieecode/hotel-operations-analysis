# Hotel Harmony: Data Insights for Optimised Operations
## Project Overview

This project analyses hotel booking data for Elite Hotels International to uncover insights that improve operational efficiency, customer satisfaction, and revenue management.
Utilising Python-based data analysis, the project examines booking patterns, cancellation behaviour, guest preferences, and pricing trends to inform data-driven decision-making in the hospitality industry.

## Business Problem

Elite Hotels International faces challenges with:
- High booking cancellations
- Seasonal demand fluctuations
- Pricing optimisation
- Understanding guest behaviour across booking channels
The goal of this analysis is to identify patterns and actionable insights that enable management to optimise operations and enhance the guest experience.

## Dataset Description
The dataset contains 119,390 hotel bookings with information on:

Booking details (lead time, arrival dates, stay duration)
- Guest demographics (adults, children, country)
- Booking channels (market segment, distribution channel, agent)
- Financial data (Average Daily Rate – ADR)
- Booking outcomes (cancellations, special requests, reservation status)

## Tools & Technologies
Python
- Pandas & NumPy – data cleaning and manipulation
- Matplotlib & Seaborn – data visualisation
- Scikit-learn – regression and logistic regression analysis
Power BI
Excel

## Data Cleaning & Preparation
Key preprocessing steps included:
- Handling missing values in country, children, agent, and company
- Converting date fields to datetime format
- Removing duplicate records
- Creating engineered features such as total stay nights

## Key Metrics
- Average Booking Lead Time
- Cancellation Rate
- Average Stay Duration (Occupancy Proxy)
- Special Requests Frequency
- Revenue Metrics (ADR trends)

## Key Insights
Booking Trends
- Peak bookings occur in August, July, and May
- City Hotels receive more bookings but also higher cancellations

Cancellations
- Longer lead times increase cancellation likelihood
- Non-refundable deposits significantly reduce cancellations
- Guests with special requests cancel less frequently

Revenue & Pricing
- City Hotels have higher ADR than Resort Hotels
- ADR increased steadily from 2015 to 2017
- Online and Direct channels generate higher ADR

Guest Behavior
- Guests with more special requests tend to pay higher ADR
- Repeated guests stay shorter on average than new guests

## Business Recommendations
- Introduce stricter deposit policies for long lead-time bookings
- Use dynamic pricing during peak seasons
- Incentivise special requests and personalisation to reduce cancellations
- Focus marketing on high-value channels like Online TA and Direct bookings
- Strengthen loyalty programs based on repeat guest behaviour

## Future Work
- Build a cancellation prediction model
- Develop an interactive Power BI / Tableau dashboard
- Perform customer segmentation for targeted marketing
- Forecast demand using time-series models

## Dashboard View
![Dashboard](https://github.com/amieecode/hotel-operations-analysis/blob/main/Images/Elite%20Hotel%201.png)
![Dashboard](https://github.com/amieecode/hotel-operations-analysis/blob/main/Images/Elite%20Hotel%202.png)
![Dashboard](https://github.com/amieecode/hotel-operations-analysis/blob/main/Images/Elite%20Hotel%203.png)
![Dashboard](https://github.com/amieecode/hotel-operations-analysis/blob/main/Images/Elite%20Hotel%204.png)

# Author
BuiltbyAmiee
