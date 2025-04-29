# 📊 Adventure Works Sales Dashboard

This Power BI project analyzes sales and profitability using the **AdventureWorksDW2022** dataset.  
It demonstrates key business intelligence techniques such as data modeling, DAX measures, and effective visual storytelling.

---

## 🗂️ Repository Contents

```
/AdventureWorks/
 ├── AdventureWorksDW2022.7z        # Compressed raw data files
 ├── SalesDashAdventureWorks.pbix   # Power BI report file
 ├── Images/                        # Dashboard screenshots
 └── README.md
```

---

## 📥 How to Get Started

1. **Download or clone this repository.**
2. Extract the data:
   - Unzip `AdventureWorksDW2022.7z` into a folder named `Data/` (in the same directory as the PBIX file).
3. Open `SalesDashAdventureWorks.pbix` in **Power BI Desktop**.
4. If prompted, re-map the data source location to the extracted folder.

> ⚠️ The `.pbix` file expects the data in a local `Data/` folder. You may need to update the source path under **Transform Data > Advanced Editor**.

---

## 📊 Dashboard Features

- **Sales Overview**: Total sales, profit margins, and sales volume across time.
- **Category & Product Insights**: Drill-down visuals for product categories and subcategories.
- **Customer Segments**: Analysis by region, demographics, and customer types.
- **Profitability Trends**: Gross margin and YoY growth patterns.

📸 **Preview**  
![Dashboard Preview](./Images/dashboard-overview.png)

---

## 📚 About the Dataset

The **AdventureWorksDW2022** dataset simulates a global manufacturing company’s sales and customer data.  
It includes:
- Fact tables for Internet and Reseller Sales
- Dimension tables for Products, Customers, Territories, and more
- Time dimension for calendar-based analysis

More info: [Microsoft Docs](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure)

---

## 🛠 Tools Used

- **Microsoft Power BI Desktop**
- **Power Query** for ETL
- **DAX** for calculated measures and time intelligence
- **7-Zip** to compress raw data

---

## 🚀 Improvements Planned

- Deploy to Power BI Service with row-level security
- Add navigation buttons and bookmarks
- Enhance KPI cards with dynamic trend indicators

---

## 🙋‍♂️ Contact

Created by Yash Patel  
📧 [LinkedIn](#) | 🌐 [Portfolio](#)
