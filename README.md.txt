# Superstore Sales Analytics

End-to-end sales analytics project analyzing the Superstore dataset. Includes data cleaning (Python, Pandas), SQL queries, and an executive dashboard built in Power BI.

---

## 🚀 Dashboard Preview

### Page 1: Executive Sales Overview
![Executive Overview](reports/figures/01_executive_sales_overview.png)

### Page 2: Product Deep Dive
![Product Deep Dive](reports/figures/02_product_deep_dive.png)

### Page 3: Shipping & Operations Analysis
![Shipping Analysis](reports/figures/03_shipping_analysis.png)

---

## 🛠️ Project Structure

* **/data/raw/**: Raw dataset (Not uploaded to Git)
* **/data/processed/**: Cleaned dataset (Not uploaded to Git)
* **/notebooks/Superstore_Analysis_Project.ipynb**: Colab notebook with all Python cleaning code and analysis.
* **/powerbi/superstore_report.pbix**: Power BI report file (Not uploaded to Git)
* **/reports/figures/**: Dashboard screenshots.

---

## 💻 How to Run

1.  Download the raw data (e.g., from Kaggle or another source) and place it in `/data/raw/`.
2.  Run the `/notebooks/Superstore_Analysis_Project.ipynb` in Google Colab to perform cleaning. This will generate the cleaned file in `/data/processed/`.
3.  Open the `/powerbi/superstore_report.pbix` file in Power BI Desktop.
4.  If needed, refresh the data source to point to the `superstore_cleaned_final.csv` file on your local machine.

---

## 🔑 Key KPIs & Insights

* **Total Sales (Winsorized):** $796.38K
* **Total Unique Orders:** 1,975
* **Average Lead Time:** 111.87 Days
* **Top Month:** February 2018 ($35.8K)
* **Top Region:** West ($259K)
* **Top Product (Hero):** Canon imageCLASS 2200 Advanced Copier