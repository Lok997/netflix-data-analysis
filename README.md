# 🎬 Netflix Data Analysis Project (End-to-End)

## 📌 Overview
This project presents a complete end-to-end data analysis pipeline on a Netflix movies dataset. It focuses on transforming raw data into meaningful insights using data cleaning, feature engineering, and visualization techniques.

The goal is to simulate a real-world business scenario where data-driven decisions are made based on content trends and audience preferences.

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📂 Dataset Summary
- **Total Records:** 9,827  
- **Columns:** 9  
- **Data Quality:** No missing values or duplicates  

### Key Features:
- Release Date  
- Title  
- Popularity  
- Vote Count  
- Vote Average  
- Genre  

---

## 🔄 Data Processing Pipeline

### ✔️ Data Cleaning & Transformation
- Converted `Release Date` to DateTime and extracted year  
- Removed irrelevant columns (`Overview`, `Original Language`, `Poster URL`)  
- Categorized `Vote Average` into:
  - Popular  
  - Average  
  - Below Average  
  - Not Popular  

### ✔️ Feature Engineering
- Split multi-genre values using `.str.split()`  
- Applied `explode()` to create individual rows per genre  
- Converted Genre into categorical type  

📈 Dataset expanded from **9,827 → 25,552 rows**

---

## 📊 Exploratory Data Analysis

Visual analysis was performed using Matplotlib and Seaborn to identify patterns in:
- Genre distribution  
- Popularity trends  
- Release patterns  
- Vote categories  

---

## 🔍 Key Insights

- 🎭 **Most Frequent Genre:** Drama (3,715 entries)  
- 🎯 **Least Frequent Genre:** Western  

- ⭐ **Most Popular Movie:** Spider-Man  
  - Genres: Action, Adventure, Sci-Fi  

- 📉 **Least Popular Movies:**  
  - The United States vs. Billie Holiday  
  - Threads  

- 📅 **Peak Release Year:** 2020  

- 📊 **Audience Preference Insight:**  
  Majority of movies fall under "Average" and "Popular" categories  

---

## 📈 Business Impact

- Helps identify high-performing genres for content strategy  
- Enables data-driven decision-making for production planning  
- Provides insights into audience preferences and trends  


