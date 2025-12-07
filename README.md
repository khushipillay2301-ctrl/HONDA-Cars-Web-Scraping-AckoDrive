 Honda Used Car Price Analysis — Web Scraping + Data Cleaning + EDA

Scraping real-world Honda used car listings from Ackodrive & analyzing pricing patterns

📌 Project Overview

This project focuses on scraping Honda used car listings from the Ackodrive website, cleaning the extracted data, and performing a detailed Exploratory Data Analysis (EDA) to understand pricing trends, fuel types, kilometers driven, model distribution, and more.

The objective is to build a complete data pipeline:

✔ Web Scraping

✔ Data Cleaning & Preprocessing

✔ Feature Engineering

✔ Exploratory Data Analysis (EDA)

✔ Visualization of Market Trends

This project demonstrates real-world data handling skills — from raw HTML to actionable insights.

🛠️ Tech Stack

Python

Requests

BeautifulSoup (bs4)

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🌐 Website Scraped

Ackodrive – Honda Cars Collection
The project scrapes:

Car Name / Variant

Fuel Type

Transmission

Manufacturing Year

Kilometers Driven

Price (including Lakh / Cr formats)

Image URL

Listing URL

🧹 Data Cleaning Steps

The raw scraped data contains inconsistent prices, string values, and missing fields. Cleaning includes:

✔ Converting prices (₹, Lakh, Cr)

Example:

₹ 4.5 Lakh → 450000

₹ 12.2 Lakh → 1220000

₹ 1.1 Cr → 11000000

✔ Standardizing KM Driven

Handles formats like:

23,000 km

5,428 km

12k km

✔ Converting Year to Numeric

✔ Removing HTML units & text noise

✔ Handling missing values

✔ Creating new numeric columns:

price_num

km_num

year_num

📊 Exploratory Data Analysis (EDA)

The project includes detailed visualizations such as:

🔹 Histograms + KDE

Price distribution

KM driven distribution

Manufacturing year distribution

🔹 Bar Charts

Fuel type distribution

Transmission type distribution

Top Honda models

🔹 Boxplots

Price vs Fuel Type

Price vs Transmission

🔹 Scatter Plots

Price vs KM

Price vs Year

🔹 Correlation Heatmap

Shows correlation between:

Price

Year

KM Driven

Key Insights (Example)

(You can update this based on EDA results)

Diesel Honda cars have a slightly lower price trend than petrol models.

Lower KM driven → significantly higher pricing.

Automatic transmission cars are priced higher than manual.

Price strongly correlates with manufacturing year.

📈 Skills Demonstrated

Web Scraping (Requests + BeautifulSoup)

Data Cleaning & Feature Engineering

EDA & Data Visualization

Real-world data wrangling

Analytical storytelling

💡 Future Enhancements

Add machine learning model for price prediction

Scrape more brands (Toyota, Hyundai, Maruti, etc.)

Build a dashboard using Power BI or Streamlit

Automate daily scraping with cron jobs
