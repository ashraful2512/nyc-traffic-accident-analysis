# 🚧 NYC Traffic Accident Analysis

This project analyzes **New York City motor vehicle collision data** to uncover patterns and insights related to traffic accidents. Using data cleaning, exploratory data analysis (EDA), and interactive visualizations, the project identifies trends associated with road conditions, time of day, contributing factors, and accident hotspots.

---

## 📌 Project Overview

Traffic accidents are a significant public safety concern in urban environments. This project explores NYC collision data to better understand when and where accidents occur and what factors contribute to them. The insights derived from this analysis can support data-driven decision-making for improving road safety.

---

## 📁 Dataset

- **Source**: NYC Open Data – *Motor Vehicle Collisions – Crashes*
- **Sample Dataset Included**: `sample_motor_vehicle_collisions.csv` (2,000 records)
- **Full Dataset**: The original dataset contains over **1 million crash records**, including information on location, time, injuries, and contributing factors.

> ⚠️ *Note*: Due to GitHub file size limitations, only a sample of the dataset is included in this repository. The full dataset can be accessed directly from NYC Open Data.

---

## 📊 Key Visualizations

The project includes several visualizations to highlight spatial and temporal accident patterns:

- 🚦 **Heatmap of Crashes by Weekday and Hour**
- 🗺️ **Geographical Accident Hotspots (Mapbox)**
- 📈 **Top Contributing Factors to Accidents**
- 🎯 **Injury Severity Distribution**
- 📊 **Temporal Trends in Collisions**

These visualizations provide insights into high-risk periods and locations, as well as the most common causes of accidents.

---

## 🧹 Data Processing

Key preprocessing steps include:

- Handling missing or inconsistent values.
- Converting date and time fields into appropriate datetime formats.
- Extracting temporal features such as **hour**, **day**, and **weekday**.
- Filtering and aggregating data to support meaningful visualizations.
- Preparing geographic coordinates for spatial analysis.

---

## 🛠️ Tools & Technologies

| Tool/Library | Purpose |
|-------------|---------|
| **Python** | Programming language |
| **pandas** | Data manipulation and cleaning |
| **NumPy** | Numerical computations |
| **Seaborn** | Statistical visualizations |
| **Matplotlib** | Static plotting |
| **Plotly Express** | Interactive and geographic visualizations |
| **Jupyter Notebook / Google Colab** | Development environment |

---

## 🚀 How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ashraful2512/nyc-traffic-accident-analysis.git
