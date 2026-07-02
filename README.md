# 📊 Sales Data Analysis

A data analysis project exploring sales performance using the **Superstore Sales Dataset**. The project covers data cleaning, exploratory analysis, and visualization to uncover key business insights around revenue, top products, seasonal trends, regions, and customer segments.

---

## 📁 Dataset

- **Source:** [Superstore Sales Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Records:** 9,800 order line items (9,789 after cleaning)
- **Columns:** 18 — including Order Date, Ship Date, Customer info, Region, Category, Sub-Category, Product Name, and Sales

---

## 🧹 Data Cleaning

- Checked and removed duplicate rows
- Dropped 11 rows with missing `Postal Code` values
- Converted `Order Date` to proper datetime format
- Extracted `Year` and `Month` for time-based analysis

---

## 🔍 Analysis Performed

- **Total Sales** across the full date range
- **Top 5 Selling Products** by revenue
- **Monthly Sales Trend** (Jan 2015 – Dec 2018)
- **Category-wise Sales Share** (Technology, Furniture, Office Supplies)
- **Yearly Sales & Year-over-Year Growth %**
- **Region-wise Sales** (West, East, Central, South)
- **Segment-wise Sales** (Consumer, Corporate, Home Office)

---

## 📈 Key Insights

- Total sales: **$2,252,607.41**
- **Technology** is the leading category, contributing 36.7% of revenue
- Sales dipped 5.3% in 2016 but rebounded with 31.5% growth in 2017 and 20.8% growth in 2018
- **West** and **East** regions together account for over 60% of total sales
- **Consumer** segment drives over half (50.9%) of all revenue
- Top product: **Canon imageCLASS 2200 Advanced Copier** ($61,599.82 in sales)

---

## 🛠️ Tools & Libraries

- Python 3
- Pandas — data cleaning & aggregation
- Matplotlib — data visualization
- Jupyter Notebook

---

## 📂 Project Structure

```
├── sales_analysis.ipynb      # Main Jupyter Notebook (cleaning + analysis + charts)
├── train.csv                 # Dataset (Superstore Sales)
├── top5_products.png         # Chart: Top 5 selling products
├── monthly_trend.png         # Chart: Monthly sales trend
├── category_share.png        # Chart: Sales share by category
├── yearly_growth.png         # Chart: Yearly sales with YoY growth
├── region_segment.png        # Chart: Sales by region and segment
└── README.md
```

---

## ▶️ How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/your-username/sales-data-analysis.git
   cd sales-data-analysis
   ```
2. Install dependencies
   ```bash
   pip install pandas matplotlib
   ```
3. Open the notebook
   ```bash
   jupyter notebook sales_analysis.ipynb
   ```
4. Run all cells to reproduce the cleaning, analysis, and charts

---

## 📄 Report

A 1-page PDF summary report (`sales_report.pdf`) is included, covering key metrics, top products, and charts — suitable for quick review or sharing.

---

## 👤 Author

shahzadi
