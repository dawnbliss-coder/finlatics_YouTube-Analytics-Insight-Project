# YouTube Data Analysis Project

This project explores a dataset of the **top YouTube channels across the world**, offering insights into what drives success on the platform. With detailed information on subscriber counts, views, earnings, upload frequency, country demographics, and channel metadata, this project provides a comprehensive look at YouTube’s biggest creators.

A perfect dataset for aspiring content creators, data analysts, and anyone curious about the evolving digital content landscape.

---

## Technologies Used

- **Python** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive development environment

## Install dependencies
- **pip install pandas numpy matplotlib seaborn jupyter

## Dataset Overview

This dataset contains 1000+ YouTube channels with attributes such as:

- **rank** – Global ranking based on subscribers  
- **Youtuber** – Channel name  
- **subscribers** – Total subscribers  
- **video views** – Total lifetime video views  
- **category** – Content genre  
- **uploads** – Total number of videos uploaded  
- **Country** – Country of the channel  
- **channel_type** – Type/classification of the channel  
- **monthly & yearly earnings** – Estimated revenue  
- **subscribers/video views (last 30 days)** – Recent growth  
- **created_year/month/date** – Channel creation timeline  
- **Population, Urban Population, Unemployment Rate** – Country-level indicators  
- **Latitude, Longitude** – Geolocation data  
- **Gross tertiary education enrollment (%)** – Education indicator  

---

## Data Preprocessing

To ensure accurate analysis, the dataset was cleaned through:

- Removing redundant columns  
- Filling missing values using median, mean, or mode  
- Dropping rows missing essential channel-type fields  
- Standardizing categorical data  
- Preparing a country-level subset for geographic/economic analysis  
- Checking for outliers and null values  

---

## Key Analytical Questions

This project answers several important questions, including:

### **Channel-Level Analysis**
- Who are the top 10 YouTube channels by subscribers?  
- Which content category has the highest average subscribers?  
- How many videos are uploaded on average per category?  
- What is the distribution of channel types?  
- Is there a correlation between subscribers and total video views?  
- Are there any outliers in yearly earnings?  
- What are the trends in subscriber growth over the last 30 days?  
- What does the distribution of channel creation dates look like?  
- Are there seasonal trends in upload frequency?  
- What is the average number of subscribers gained per month since creation?

### **Country-Level Analysis**
- Which are the top 5 countries with the most YouTube channels?  
- Is there a relationship between education enrollment and number of channels?  
- How does unemployment vary in countries with many channels?  
- What is the average urban population percentage?  
- Are there patterns based on latitude and longitude?  
- Is there a correlation between channel subscribers and country population?  
- How do the top 10 YouTube-active countries compare by population?  
- Is subscriber growth related to a country’s unemployment rate?

### **Channel Type & Earnings**
- How do monthly earnings vary across categories?  
- How do last-30-days video views vary across channel types?  

---

## Project Goal

To uncover meaningful insights about YouTube success by examining creator metrics, category behavior, geographic influences, and economic context. The project provides a holistic view of digital content creation and global YouTube trends.

---
