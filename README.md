# Syntecxhub_Time_series_-_category_charts

## 📌 Project Overview
This project analyzes retail sales data using time series and category-based visualizations. The goal is to understand sales trends over time, compare product categories, and analyze their contribution to total sales.

---

## 📁 Dataset
The dataset contains the following columns:
- **date** → Transaction date
- **category** → Product category
- **region** → Sales region
- **sales** → Sales amount
- **units** → Quantity sold

---

## 🧹 Data Cleaning
The dataset was cleaned using the following steps:
- Converted `date` column to datetime format
- Removed duplicate rows
- Removed missing values
- Filtered out invalid values (sales > 0 and units > 0)

---

## ⚙️ Feature Engineering
Additional features were created:
- **Month** → Extracted from date
- **Year** → Extracted from date

---

## 📈 Analysis & Visualizations

### 🔹 1. Time Series Analysis (Line Chart)
- Daily sales trend was plotted to observe changes over time
- Monthly and quarterly aggregation were used to identify patterns

### 🔹 2. Category Comparison (Bar Chart)
- Compared total sales across categories
- Added value labels for better readability

### 🔹 3. Category Share (Pie Chart)
- Displayed percentage contribution of each category

---

## 💾 Outputs
- Bar chart saved as **bar.png**
- Other charts displayed using matplotlib

---

## 📊 Key Insights
- Sales show an overall increasing trend over time
- Monthly aggregation reveals seasonal variation
- Electronics category contributes the highest sales
- Sales distribution varies across categories

---

## 📖 Chart Justification
- **Line chart** → Used to show sales trends over time  
- **Bar chart** → Used to compare sales between categories  
- **Pie chart** → Used to show percentage share  
- **Aggregation (monthly/quarterly)** → Used to reduce noise and highlight patterns  

---

## ✅ Conclusion
This project demonstrates a complete data analysis workflow including data cleaning, transformation, and visualization. The combination of time series and category-based analysis provides meaningful business insights.

---

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib
