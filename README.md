# 📊 Sales Data Analysis and Interactive Visualization Dashboard(Jupyter Notebook)

This project analyzes and visualizes a sales dataset using **Pandas**, **Matplotlib**, **Seaborn**, and **Plotly Dash**. The dataset contains detailed information about customer orders, such as order quantity, price, country, product line, and more.

## 🚀 Features

- Cleans and preprocesses the dataset
- Handles missing values and outliers
- Derives profit metrics
- Generates visual insights using:
  - Boxplots for outlier detection
  - Bar charts for product line performance
  - Line plots for monthly sales trends
  - Pie charts for country-wise sales share
- An **interactive dashboard** using Dash with dropdown filters

## 📂 Dataset Overview

The dataset includes 2823 customer order records across 25 columns such as:

- `ORDERNUMBER`, `QUANTITYORDERED`, `PRICEEACH`, `SALES`
- `ORDERDATE`, `PRODUCTLINE`, `CUSTOMERNAME`, `COUNTRY`, etc.

## 🧰 Tech Stack

- Python 🐍
  - `pandas`
  - `seaborn`
  - `matplotlib`
  - `plotly`
  - `dash`

## 📌 Key Insights

- **Total Orders:** `252`
- **Top-Selling Product Line:** `Classic Cars`
- **Top Country by Sales:** `USA`
- **Total Sales:** `9,289,680.57`
- **Total Profit:** `-78,995.43` *(due to MSRP being higher than sale price in some cases)*
- **Total Products Sold:** `95,113`

## 📊 Visualizations

- Horizontal Bar Chart: Product Line Sales
- Line Plot: Monthly Sales Trends
- Pie Chart: Country-wise Sales Distribution

## 🧼 Data Cleaning

- Dropped high-missing-value columns: `ADDRESSLINE2`, `STATE`, `TERRITORY`
- Filled missing postal codes with `'No Data'`
- Removed outliers from `SALES` using IQR method
- Derived `Profit` column as: `SALES - (MSRP × QUANTITYORDERED)`

## 📈 Interactive Dashboard

Built using **Dash**, this app includes:

- Two dropdowns: Product Line & Country
- Dynamic bar chart updating on selection


## 📌 How to Run

1. Clone this repo
2. Open `Sales_analysis.ipynb` in Jupyter Notebook or JupyterLab
3. Run all the cells to view:
   - Data preprocessing
   - Insight extraction
   - Visualizations
   - Interactive Dashboard

## ✍️ Author

**Anshika Dubey**  
B.Tech CSE (Data Science), SRMCEM  
[LinkedIn](https://www.linkedin.com/in/anshika-dubey-3a89b5287/) | [GitHub](https://github.com/Anshika-Dubey)

## 🪪 License

📄 *This project is licensed under the MIT License.*
