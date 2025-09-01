
# 🍽️ Restaurant Dataset Analysis – Data Science Internship Project

## 📌 Overview
This project was developed as part of the Cognifyz Data Science Internship. It explores a dataset of 9,551 restaurants across various cities, aiming to uncover insights into customer ratings, cuisine preferences, and operational features. The analysis is structured across three levels—each building toward deeper business understanding and predictive capability.

---

## 📊 Dataset Summary
- **Source**: `Dataset.csv` (provided by Cognifyz Technologies)
- **Rows**: 9,551  
- **Columns**: 21  
- **Target Variable**: `Aggregate rating`  
- **Key Features**: Restaurant name, city, cuisines, cost, rating, votes, delivery and booking options, geolocation

---

## 🧭 Project Levels & Tasks

### 🔹 Level 1: Data Exploration & Descriptive Analysis

**Task 1: Data Exploration and Preprocessing**
- Identified dataset dimensions (rows and columns)
- Checked for missing values and handled them appropriately
- Converted data types where necessary (e.g., numeric columns)
- Analyzed distribution of `Aggregate rating` and checked for class imbalance

**Task 2: Descriptive Analysis**
- Calculated mean, median, standard deviation for numeric columns
- Explored categorical variables: `Country Code`, `City`, `Cuisines`
- Identified top cuisines and cities by restaurant count

**Task 3: Geospatial Analysis**
- Visualized restaurant locations using latitude and longitude
- Analyzed geographic distribution across cities and countries
- Investigated correlation between location and rating

---

### 🔹 Level 2: Operational Features & Feature Engineering

**Task 1: Table Booking and Online Delivery**
- Calculated percentage of restaurants offering table booking and online delivery
- Compared average ratings of restaurants with and without booking
- Analyzed delivery availability across different price ranges

**Task 2: Price Range Analysis**
- Identified most common price ranges
- Calculated average rating per price range
- Determined which rating color corresponds to highest average rating

**Task 3: Feature Engineering**
- Extracted new features (e.g., length of restaurant name/address)
- Created binary flags for booking and delivery availability
- Encoded categorical variables for modeling

---

### 🔹 Level 3: Modeling & Business Insights

**Task 1: Predictive Modeling**
- Built regression models to predict `Aggregate rating`
- Split data into training and testing sets
- Compared performance of Linear Regression, Decision Tree, and Random Forest
- Evaluated models using RMSE and R² metrics

**Task 2: Customer Preference Analysis**
- Analyzed relationship between cuisine type and rating
- Identified most popular cuisines based on vote count
- Highlighted cuisines with consistently high ratings

**Task 3: Data Visualization**
- Created histograms, bar plots, and box plots for rating distribution
- Compared average ratings across cuisines and cities
- Visualized feature-target relationships for business insights

---

## 📦 Deliverables
- ✅ Cleaned and enriched dataset  
- ✅ Annotated notebook: `Restaurant_Dataset.ipynb`  
- ✅ Modular cleaning and feature engineering logic  
- ✅ Visualizations and model comparisons  
- ✅ README.md with level-wise breakdown  

---

## 🙋‍♂️ Author
**Jaskar Jeyabalan S**  
Internship Candidate | Data Science  
📫 jaskarjeyabalan@gmail.com  
🔗 https://www.linkedin.com/in/jaskarjeyabalan
