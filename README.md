# Python_Main-Project
# 🌦️ Weather Data Analytics — Multi-City Climate Analysis

## 📌 Project Overview

This project analyzes **5 years of weather data from multiple cities** to identify temperature, rainfall, humidity, wind speed, pressure, and seasonal patterns.

The project demonstrates the complete **Data Analytics workflow**, including data cleaning, preprocessing, exploratory data analysis (EDA), statistical analysis, feature engineering, and data visualization using **Python, Matplotlib, Seaborn, and Plotly**.

---

## 🎯 Objectives

The main objectives of this project are to:

* Analyze weather patterns across different cities.
* Study temperature variations over time.
* Identify rainfall and precipitation patterns.
* Analyze humidity and wind-speed trends.
* Compare weather conditions between cities.
* Identify seasonal and monthly patterns.
* Study relationships between different weather variables.
* Detect outliers and unusual weather observations.
* Present insights using static and interactive visualizations.

---

## 📂 Dataset

The dataset contains daily weather observations collected for multiple cities over a five-year period.

### Key Variables

| Variable            | Description             |
| ------------------- | ----------------------- |
| `Date`              | Observation date        |
| `City`              | City name               |
| `State`             | State/region            |
| `T2M`               | Average temperature     |
| `T2M_MAX`           | Maximum temperature     |
| `T2M_MIN`           | Minimum temperature     |
| `RH2M`              | Relative humidity       |
| `WS2M`              | Wind speed              |
| `PS`                | Surface pressure        |
| `ALLSKY_SFC_SW_DWN` | Surface solar radiation |
| `PRECTOTCORR`       | Corrected precipitation |

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical calculations
* **Matplotlib** — Static data visualization
* **Seaborn** — Statistical visualization
* **Plotly** — Interactive visualization
* **Scikit-learn** — Data preprocessing and analytical support

### Development Environment

* Jupyter Notebook
* GitHub

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Data Validation
   ↓
Feature Engineering
   ↓
Descriptive Statistics
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Correlation Analysis
   ↓
Key Findings
   ↓
Conclusion & Recommendations
```

---

## 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Checked dataset dimensions.
* Inspected data types.
* Checked for missing values.
* Checked and handled duplicate records.
* Standardized city and state information.
* Converted date values into proper datetime format.
* Created additional time-based features.
* Checked numerical variables for unusual values.
* Identified potential outliers.
* Validated the cleaned dataset before analysis.

---

## ⚙️ Feature Engineering

Additional variables were created to improve the analysis:

* **Year**
* **Month**
* **Month Name**
* **Season**
* **Temperature Range**
* **Rainy Day Indicator**
* **Heavy Rain Indicator**
* **Temperature Category**
* **Weather Category**

These features helped identify seasonal and temporal weather patterns.

---

# 📊 Data Visualization

A variety of visualization techniques were used to make the analysis comprehensive and visually informative.

## Matplotlib

The following charts were created using Matplotlib:

* 📉 Histogram
* 📈 Line Plot
* 📊 Column Chart
* 🧩 Subplots

## Seaborn

The following statistical visualizations were created using Seaborn:

* 📊 Bar Plot
* 🔵 Scatter Plot
* 📦 Box Plot
* 🔗 Pair Plot
* 🔥 Correlation Heatmap
* 🎻 Violin Plot

## Plotly

Interactive visualizations were created using Plotly:

* 🥧 Interactive Pie Chart
* 📈 Interactive Line Chart
* 🔵 Interactive Scatter Plot

---

## 📈 Key Analysis Areas

### 🌡️ Temperature Analysis

* Compared average temperatures between cities.
* Analyzed monthly temperature trends.
* Compared minimum, maximum, and average temperatures.
* Examined temperature distributions using box plots and violin plots.

### 🌧️ Rainfall Analysis

* Compared total precipitation between cities.
* Studied monthly rainfall patterns.
* Identified rainy and heavy-rain days.
* Examined precipitation distributions and outliers.

### 💧 Humidity Analysis

* Compared average humidity across cities.
* Studied the relationship between humidity and temperature.
* Examined humidity patterns across seasons.

### 💨 Wind Analysis

* Compared average wind speeds between cities.
* Investigated relationships between wind speed and other weather variables.

### 🔗 Correlation Analysis

Correlation analysis was performed to understand relationships among:

* Temperature
* Maximum temperature
* Minimum temperature
* Humidity
* Wind speed
* Pressure
* Solar radiation
* Precipitation
  
## 🎓 Project Outcome
* The dataset contains 18,260 daily observations covering 10 cities from 2021–2025.
* Chennai recorded the highest average temperature at approximately 27.9°C, followed closely by Kochi at 27.6°C.
* Srinagar recorded the lowest average temperature at approximately 9.4°C, showing a clear climatic difference from the other cities.
* Mumbai recorded the highest total precipitation, followed by Kochi and Guwahati.
* May was the hottest month overall, with an average temperature of approximately 28.6°C.
* July recorded the highest total precipitation, followed by August and September, showing a strong seasonal rainfall pattern.
* The most common weather category was Normal (46.5%), followed by Rainy (20.1%) and Heavy Rain (13.3%).
* Temperature had a very strong positive correlation with minimum temperature (0.96) and maximum temperature (0.95).
* Temperature also showed a moderate positive relationship with surface pressure (0.66) and solar radiation (0.38).
* The analysis showed clear city-wise and seasonal variations in temperature, rainfall, humidity, and other weather variables.
* The combination of Matplotlib, Seaborn, and Plotly provided both detailed statistical visualizations and interactive exploration.

🎓 Conclusion

The analysis demonstrates significant differences in weather conditions across cities and seasons. Tropical and coastal cities generally experienced higher temperatures and precipitation, while Srinagar showed substantially lower temperatures. Rainfall was strongly concentrated during the mid-year months, particularly July. Overall, the project demonstrates how data cleaning, exploratory data analysis, statistical analysis, and visualization can be used to transform raw weather data into meaningful insights.
