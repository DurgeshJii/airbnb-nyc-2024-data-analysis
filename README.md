# 🏠 Airbnb NYC 2024 Data Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on Airbnb listings
in New York City using Python.

The objective is to transform raw Airbnb listing data into meaningful
insights about pricing, room types, neighbourhoods, availability,
reviews, and geographical distribution.

---

## 🎯 Objectives

The main objectives of this project are:

- Understand the structure of the Airbnb dataset
- Clean and prepare the data for analysis
- Identify missing and duplicate records
- Analyze Airbnb price distribution
- Compare prices across NYC neighbourhood groups
- Analyze room-type pricing
- Study listing availability
- Explore the relationship between reviews and price
- Analyze geographical distribution of listings
- Create a price-per-bed feature
- Study correlations between numerical variables

---

## 📊 Dataset

The dataset contains 20,770 Airbnb listings and 22 initial columns.

Important columns include:

- `id`
- `name`
- `host_id`
- `host_name`
- `neighbourhood_group`
- `neighbourhood`
- `latitude`
- `longitude`
- `room_type`
- `price`
- `minimum_nights`
- `number_of_reviews`
- `reviews_per_month`
- `availability_365`
- `number_of_reviews_ltm`
- `license`
- `rating`
- `bedrooms`
- `beds`
- `baths`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Loading

The Airbnb CSV dataset was loaded using Pandas.

### 2. Initial Exploration

The dataset was examined using:

- `head()`
- `tail()`
- `shape`
- `info()`
- `describe()`

### 3. Data Cleaning

The following cleaning operations were performed:

- Removed missing-value rows
- Removed duplicate records
- Converted `id` and `host_id` into object data types
- Verified remaining null values

### 4. Exploratory Data Analysis

The following analyses were performed:

- Price distribution
- Availability distribution
- Neighbourhood-level pricing
- Room-type pricing
- Review vs price relationship
- Geographical distribution
- Correlation analysis

### 5. Feature Engineering

A new feature was created:

`price_per_bed = price / beds`

This helps compare the effective cost of accommodation relative to
the number of beds.

---

## 📈 Key Findings

### Average Price by Neighbourhood Group

| Neighbourhood | Average Price |
|---|---:|
| Manhattan | $204.15 |
| Brooklyn | $155.14 |
| Queens | $121.68 |
| Staten Island | $118.78 |
| Bronx | $107.99 |

### Average Price per Bed

| Neighbourhood | Price per Bed |
|---|---:|
| Manhattan | $138.71 |
| Brooklyn | $99.79 |
| Queens | $76.34 |
| Bronx | $74.71 |
| Staten Island | $67.73 |

Manhattan had the highest average price as well as the highest
average price per bed in this analysis.

---

## 📊 Visualizations

The project includes:

- Price distribution histogram
- Price boxplot
- Availability distribution
- Neighbourhood price comparison
- Room-type price comparison
- Reviews vs price scatter plot
- Pair plot
- Geographical listing distribution
- Correlation heatmap

---

## 💡 Business Insights

The analysis can help Airbnb hosts and analysts understand:

- How location affects listing prices
- Relative pricing across neighbourhood groups
- The cost associated with accommodation capacity
- Distribution of listing availability
- Differences between room types
- Geographic concentration of Airbnb listings

---

## 🚀 Future Improvements

Possible extensions of this project include:

- Interactive Power BI dashboard
- Interactive geographical map
- Price prediction model
- Revenue estimation
- Host performance analysis
- Seasonal pricing analysis
- Advanced outlier treatment
- Statistical hypothesis testing
- Machine Learning based price prediction

---

## 👨‍💻 Author

**Durgesh Yadav**

Data Analyst | Python | SQL | Power BI | Excel

---

⭐ If you find this project useful, consider giving the repository a star!
