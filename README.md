# 🚲 Analysis of London Bike Sharing System

## 🎯 Objective
This project analyzes and visualizes the **London bike-sharing system** usage patterns. The dataset includes factors like **weather conditions**, **holidays**, **seasons**, and more. Using **Python** for data preprocessing and **Tableau** for visualizations, the project uncovers the key factors affecting bike rentals in London.

## 🛠️ Tools and Technologies

- **Python**: For data cleaning, analysis, and manipulation using:
  - 🐼 Pandas
  - 📊 NumPy
  - 🎨 Matplotlib
  - 🔍 Seaborn
- **Tableau**: For creating interactive visualizations and exploring rental patterns under various conditions.

## 📑 Key Steps and Process

### 1. 📥 Data Download
We programmatically downloaded the **London bike-sharing dataset** using the Kaggle API.

### 2. 🧹 Data Preprocessing and Cleaning
- **Pandas** was used to explore, assess, and manipulate the dataset.
- Data formats for **weather**, **date**, and **time** were normalized.
- We then exported the cleaned dataset to an Excel file: `london_bikes_final.xlsx`.

### 3. 📊 Descriptive Analysis
- Analyzed **bike rental patterns** across different time periods (hours, days, months, and seasons).
- Investigated the effects of **weather**, **holidays**, and **working days** on bike-sharing demand.

### 4. 🌧️ Extreme Condition Analysis
- Identified days with **extreme weather** conditions (e.g., high wind speeds, heavy rainfall).
- Explored how these weather events impacted the number of rentals.

### 5. 📈 Data Visualization in Tableau
Once we had our final dataset, we created the following **five visualizations** in **Tableau**:
1. **Total Number of Bike Rides**: Displayed in the top left.
2. **Moving Average Chart**: Our main visual, showing trends over time.
3. **Temperature vs. Wind Speed Heat Map**: To analyze how these two factors interact.
4. **Weather and Hour Breakdown**: Displayed in tooltips when hovering over charts.
   - Displays the number of bike rides split by **weather conditions** and **hour** of the day.
   
### 🖼️ Example Visuals:
- **Heat Map**: Showed the relationship between temperature and wind speed.
- **Moving Average Chart**: Showed how bike rentals evolved over time.

### 🔧 Enhancements
- Made adjustments to the chart formatting (e.g., fixing title font sizes) for a cleaner look.

## 🔗 How to Recreate This Project
You can **clone the repository** and follow these steps to recreate the analysis:

1. **Clone the repository**:
   ```bash
   https://github.com/Gkkumar2/London-bike-sharing-Analysis-project.git
