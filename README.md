# Tesla Open Data Analysis Project (R)

## 📌 Project Overview
This project analyzes **electric vehicle (EV) population data in Washington State** with a focus on **Tesla’s market presence**, sales trends, estimated revenue, and comparison with competitors.

The goal of this project is to demonstrate **real-world data cleaning, aggregation, and visualization skills in R** using open datasets.

---

## 📂 Datasets Used
- **Electric_Vehicle_Population_Data.csv**
  - Public EV registration data for Washington State
- **Tesla_Current_Base_Prices.csv**
  - Supplementary dataset containing current Tesla base prices (used for revenue estimation)

---

## 🧹 Data Cleaning & Preparation
Key cleaning steps performed:
- Standardized column names (replaced dots with underscores)
- Created a binary classification for Tesla vs Other manufacturers
- Filtered invalid or zero values for range and MSRP
- Ensured consistent model naming for joins
- Prepared analysis-ready datasets using tidyverse pipelines

---

## 🔍 Analysis Questions & Insights

### 1️⃣ Tesla Market Share
- Calculated the percentage of Tesla vehicles among all EVs in Washington
- Visualized Tesla vs Other EVs using a **pie chart**

### 2️⃣ Tesla Models Sold
- Identified top-selling Tesla models
- Visualized model popularity using bar charts

### 3️⃣ Estimated Revenue by Tesla Model
- Combined sales counts with current base prices
- Estimated lifetime revenue per Tesla model
- Visualized revenue using horizontal bar charts

### 4️⃣ Tesla vs Competitors (BEV Comparison)
- Compared **average electric range** and **average MSRP**
- Focused on Battery Electric Vehicles (BEV)
- Visualized differences using bar charts

### 5️⃣ PHEV vs BEV Trends
- Analyzed adoption trends over time
- Visualized trends using line charts

### 6️⃣ Top Electric Utilities for Tesla Vehicles
- Identified the top utilities supporting Tesla vehicles in Washington
- Visualized top utilities by vehicle count

### 7️⃣ Tesla Sales Over Time
- Analyzed Tesla vehicle registrations by year
- Visualized growth trends with line plots

---

## 📊 Tools & Libraries Used
- **R**
- **tidyverse**
  - dplyr
  - tidyr
  - ggplot2
- readxl
- scales

---

## 📈 Key Skills Demonstrated
- Data cleaning and transformation
- Grouping and aggregation
- Joining multiple datasets
- Exploratory data analysis (EDA)
- Data visualization with ggplot2
- Working with real-world open datasets

---

## 🚀 How to Run the Project
1. Clone the repository
2. Place the datasets in the project directory
3. Open the R script in RStudio
4. Install required libraries:
   ```r
   install.packages(c("dplyr", "tidyr", "ggplot2", "readxl", "scales"))

