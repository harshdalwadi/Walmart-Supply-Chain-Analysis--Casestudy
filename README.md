# 📊 Walmart Supply Chain Analysis & Optimization

## 🏬 Project Overview
This project aims to analyze Walmart's supply chain using **data-driven insights and machine learning models**. By leveraging historical sales data, we identify inefficiencies and provide optimization strategies to improve inventory management, pricing, and logistics.

## 🎯 Objectives
- **Understand** Walmart’s supply chain structure and key challenges.
- **Perform exploratory data analysis (EDA)** to uncover trends and patterns.
- **Apply machine learning models** for sales forecasting.
- **Identify key drivers** affecting Walmart’s sales performance.
- **Recommend strategic improvements** for enhanced efficiency and profitability.

## 📊 Dataset Description
The dataset contains Walmart’s sales records, including:
- **Store Information**: Store type, size, and department details.
- **Sales Data**: Weekly sales performance across different stores.
- **Economic Indicators**: CPI, fuel price, unemployment rate.
- **Promotions & Holidays**: Impact of markdowns and special events on sales.

### 📂 Data Files
- `walmart_original.csv` - Raw dataset with all available data.
- `walmart_preprocessed.csv` - Cleaned and transformed dataset.

## 🔍 Data Analysis & Insights
### 1️⃣ Data Cleaning & Preparation
- Handled missing values in markdowns and promotions.
- Converted date features to structured time series components.
- Standardized numerical columns for consistent analysis.

### 2️⃣ Exploratory Data Analysis (EDA)
- **Sales Trends**: Weekly sales patterns across different stores.
- **Holiday Impact**: Major spikes in sales during festive seasons.
- **Correlation Analysis**: Store size and fuel price have strong relationships with sales.
- **Geographical Trends**: Identified sales variations across store locations.

### 3️⃣ Predictive Modeling
We implemented and compared different models to forecast Walmart’s sales:
- **Linear Regression**: Established baseline trends.
- **Random Forest Regressor**: Achieved high accuracy with non-linear relationships.
- **Hyperparameter Tuning**: Optimized Random Forest for better predictions.
- **Feature Importance Analysis**: Store size and holiday seasons are major predictors.

![Sales Trends](https://github.com/harshdalwadi/Walmart-Supply-Chain-Analysis--Casestudy/blob/main/download.png)

## 📈 Key Findings & Business Impact
✔ **Larger stores tend to have higher sales, but not always the highest efficiency.**  
✔ **Holidays and promotions lead to drastic sales fluctuations.**  
✔ **Fuel price changes slightly impact Walmart’s sales trends.**  
✔ **The optimized Random Forest Model provides a more reliable sales forecast.**  
✔ **Markdowns on specific products drive sales increases but need strategic planning.**  

## 🚀 Recommendations
🔹 **Optimize Inventory Management**: Reduce overstocking and stockouts using predictive analytics.
🔹 **Refine Pricing Strategy**: Dynamic pricing based on economic trends and demand forecasts.
🔹 **Enhance Marketing Strategies**: Align promotions with seasonal demand peaks.
🔹 **Logistics Improvement**: Use real-time analytics for warehouse and transportation efficiency.
🔹 **Leverage External Data**: Integrate weather conditions, competitor pricing, and regional events for better insights.

## 🛠️ Technology Stack
- **Programming Language**: Python 3.x
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn, Random Forest, Linear Regression

## 🚀 How to Run the Project
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/harshdalwadi/Walmart-Supply-Chain-Analysis--Casestudy.git
   cd Walmart-Supply-Chain-Analysis--Casestudy
   ```
2. **Install Dependencies:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. **Run the Jupyter Notebook:**
   - Open `Data_Visualisation_Term_Project.ipynb`
   - Run each cell sequentially for data analysis and model training.

## 👥 Contributors
- **Harsh Dalwadi** – Data Analysis & Machine Learning
- **Nilka Patel** – Research & Documentation
- **Krutarth Majmundar** – Visualization & Reporting

## 📜 License
This project is licensed under the **MIT License**. Contributions are welcome! 🚀
