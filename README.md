# Superstore Sales Dashboard

A Power BI Sales Performance Dashboard analyzing Superstore sales data to track Sales, Profit, Orders & Profit Margin across Category, Region & Time.

## 📊 Dashboard Overview

![Dashboard Screenshot](screenshot.png)

## ✨ Key Features

**KPI Cards:**
- Total Sales - 2.30M
- Total Profit
- Total Orders - 9,994 Orders
- Profit Margin %

**Visuals:**
- Sales by Category - Technology, Furniture, Office Supplies
- Profit by Region - West, East, Central, South
- Sales Trend by Year / Month - Line Chart
- Sales by State - Map View
- Slicers - Year, Region, Category

## 🛠️ Tech Stack

- Power BI Desktop
- Power Query - Data Cleaning
- DAX - Measures & Calculations
- Superstore Dataset (Kaggle) - 9,994 Rows

## 📈 DAX Measures Used

```DAX
Total Sales = SUM(Superstore[Sales])
Total Profit = SUM(Superstore[Profit])
Total Orders = COUNTROWS(Superstore)
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
 Key Insights
Technology category has highest SalesWest Region has highest Sales, South Region growth is lowQ4 Sales Peak - Holiday Season EffectFurniture category Profit Margin is low compared to others📂 Project StructurejavascriptSuperstore-Sales-Dashboard/
├── Superstore Sales Dashboard.pbix   # Main Power BI File
├── Superstore.csv                    # Dataset
└── README.md                         # Project Details🚀 How To Use
Download this RepoOpen .pbix file in Power BI DesktopUse Slicers to filter by Region / Category / Yearjavascript
### GitHub lo Ela Pettali?

**1.** `Superstore-Sales-Dashboard` repo open chey
**2.** **Add file > Create new file** click chey
**3.** File name lo `README.md` ani raayi
**4.** Paina code motham paste chesi **Commit changes** kotti

Ayipoyindhi!

**Oka chinna pani:** Nee dashboard screenshot unte, dani peru `screenshot.png` ani petti repo lo upload chey - appudu README lo photo kuda kanipisthundhi!

**Pettesava? Ayipoyaka screenshot pampu!**
