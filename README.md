Exploratory Data Analysis (EDA) on Airbnb Listings

📌 Introduction

This project explores Airbnb listings using Exploratory Data Analysis (EDA) to uncover insights about price trends, availability, neighborhood differences, and correlations among key features.

📊 Dataset Overview

The dataset contains 48,895 listings, with attributes such as:

Location: Latitude, Longitude, Neighborhood

Pricing: Price per night

Availability: Number of days available per year

Room Type: Entire home/apartment, Private room, Shared room

Host Details: Number of listings per host

Reviews: Number of reviews per listing

🔍 Key Findings

1️⃣ Price vs. Room Type

Observation: Higher prices do not necessarily indicate a private room.

Insight: Entire homes/apartments are generally more expensive, but some private rooms have high prices too.

Visualization Used: Boxplot comparing room type vs. price

2️⃣ Price vs. Availability

Observation: No clear linear relationship between price and availability.

Insight: Expensive listings are not always less available; demand, seasonality, and host strategies may play a role.

Visualization Used: Scatter plot comparing price vs. availability

3️⃣ Correlation Analysis

Findings:

No strong positive correlations between key features.

Higher availability is weakly correlated with hosts managing multiple listings.

Manhattan listings tend to have higher latitude values.

Queens listings tend to have higher longitude values.

Visualization Used: Correlation heatmap

📌 Next Steps

Investigate seasonal trends (if date-based data is available).

Perform outlier analysis to see how extreme values affect patterns.

Use machine learning models to predict prices based on available features.

📁 Repository Structure

📂 Airbnb-EDA
 ├── 📊 datasets/         # Raw and cleaned datasets
 ├── 📜 notebooks/        # Jupyter notebooks for analysis
 ├── 📄 images/           # Plots and visualizations
 ├── 📄 README.md         # Project overview (this file)
 ├── 📄 EDA_report.md     # Detailed findings (this document)

🎯 Conclusion

This analysis provides initial insights into Airbnb listings. Further exploration of time-based trends and machine learning could improve pricing predictions.

💡 Want to contribute? Feel free to fork this repo and add new analyses!
