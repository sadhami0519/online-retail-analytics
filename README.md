# Online Retail Data Analytics Project (On-going)

## 📌 Overview
This project analyzes an online retail dataset to extract meaningful insights using data cleaning, feature engineering, exploratory data analysis (EDA), customer churn analysis, and code optimization with the Fireducks library.

## 📂 Dataset
The dataset consists of transactional data from an online retail store, including:

- **InvoiceNo**: Unique transaction ID  
- **StockCode**: Product identifier  
- **Description**: Product name  
- **Quantity**: Number of units purchased  
- **InvoiceDate**: Transaction date and time  
- **UnitPrice**: Price per unit  
- **CustomerID**: Unique customer identifier  
- **Country**: Customer's country  

## 🛠️ Key Steps

### 1️⃣ Data Cleaning
- Removed missing values, especially in CustomerID  
- Removed missing and inconsistent values in Description  
- Removed outliers  

### 2️⃣ Feature Engineering
- Created a **TotalPrice** column (*Quantity × UnitPrice*)  
- Extracted **Year, Month** from InvoiceDate  
- Generated **Recency, Frequency, and Monetary (RFM)** features for customer analysis  
- Identified high-value customers using spending patterns  

### 3️⃣ Exploratory Data Analysis (EDA) & Visualization
- Sales trends over time (**monthly, yearly**)  
- **Country-wise revenue distribution**  
- **Product popularity** based on sales volume  
- **Customer purchasing behavior analysis**  
- Used **Matplotlib** for visualizations  

### 4️⃣ Customer Churn Analysis
- Defined churned customers based on inactivity thresholds  
- Applied **RFM Analysis** to assess at-risk customers
- Implemented a 90-day churn threshold and generated a histogram on the churn analysis

### 5️⃣ Code Speed-Up with Fireducks 🚀
- Used the **Fireducks** library to accelerate data operations  

## 🔧 Tech Stack
- **Python (pandas)**  
- **Data Visualization**: Matplotlib  
- **Performance Optimization**: Fireducks  

## 📈 Key Insights
- The majority of sales come from a few key countries.  
- Certain products exhibit **seasonal trends**.  
- **Customer churn analysis** helps in identifying at-risk customers.  
- Using **Fireducks** significantly enhances code execution speed.  

## 🌟 Future Enhancements
- Implement **predictive modeling** to forecast future sales.  
- Deploy an **interactive dashboard** using **Streamlit** or **Dash**.  
- Automate data processing using **Apache Spark**.  

## 📜 Conclusion
This project showcases the power of **data analytics and optimization** in e-commerce. By leveraging **data cleaning, EDA, feature engineering, customer churn analysis, and performance tuning**, businesses can drive better decision-making and enhance customer retention.

