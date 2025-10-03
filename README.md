# ECommerce-Olist-Sales-Analysis

## 🛢 About CSV To SQL Connection
CSV files are a simple and widely used format for raw data, but they become limiting as datasets grow and queries get more complex. Moving CSV data into SQL databases provides structure, scalability, and efficiency, allowing faster lookups, relational joins, and more advanced analytics.

The process typically starts by creating a database and defining tables that mirror the structure of the CSV file. Using Python libraries like pandas for reading the CSV and database connectors for establishing the connection (with credentials such as user, password, host, and database name), the data is then inserted into the SQL tables. Once set up, the database becomes the backbone for queries, automation, and integration with dashboards or applications, replacing flat-file limitations with a more reliable and dynamic system.

---

## 🔍 Project Overview
The **E-Commerce Olist dataset** provides a comprehensive look at Brazilian online retail, capturing orders, customers, sellers, products, payments, and reviews across a large marketplace. This project analyzes key dimensions of the dataset to better understand customer behavior, order patterns, delivery performance, and overall sales dynamics.

The objective is not only to describe the data but also to uncover insights into how the marketplace operates, where inefficiencies occur, and what opportunities exist for improvement. By linking visual patterns to customer experience and seller performance, this analysis aims to provide actionable recommendations for improving logistics, product offerings, customer satisfaction, and financial stability.

---

## 📊 Analysis Highlights

---

## 📂 File Structure

```

ECommerce-Olist-Sales/
│
├── Olist_Customers_Dataset.csv            # Dataset
├── Olist_Geolocation_Dataset.csv          # Dataset
├── Olist_Order_Items_Dataset.csv          # Dataset
├── Olist_Order_Payments_Dataset.csv       # Dataset
├── Olist_Orders_Dataset.csv               # Dataset
├── Olist_Products_Dataset.csv             # Dataset
├── Olist_Sellers_Dataset.csv              # Dataset
├── csv_to_sql.ipynb                       # For setting up connectivity
├── ECommerce-Olist-Sales.ipynb            # Jupyter Notebook with analysis & charts
└── README.md                              # Project documentation

```

---

## ⚙️ Technologies Used

* Python
* Libraries: pandas, numpy, matplotlib, seaborn
* Jupyter Notebook for analysis and visualization

---

## 📊 Data Source

* **Dataset Name:** Brazilian E-Commerce Public Dataset by Olist
* **Source:** Kaggle
* **Link:** [https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 🚀 How to Use This Project

1. Clone or download the repository:

   ```bash
   git clone https://github.com/teesta57/ECommerce-Olist-Sales.git
   ```
2. Open the `ECommerce Olist Sales.ipynb` file.
3. Explore the dashboard and analyse the data.

---

## 🤝 Contributing

You're welcome to fork the project, explore the dataset, enhance visualizations, or suggest improvements.

---




