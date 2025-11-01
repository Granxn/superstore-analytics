Superstore Sales & Operations Analytics
End-to-end data analytics project using Python (Pandas), SQL, and Power BI.
Focus: Cleaning a raw sales dataset (~9,800 rows), auditing shipping data, and building an interactive dashboard that transparently communicates data limitations and actionable business insights.

Technologies:
Python (Pandas, Matplotlib), SQL, Power BI (DAX, Power Query), Git

🚀 Dashboard Preview & Data Audit Findings
Page 1: Executive Sales Overview
High-level KPIs and professional annotation highlighting lead time artifact (inflated by missing Ship_Dates imputed as 122 days).

Page 2: Product Deep Dive
Analyze top-selling hero products, sales by category, and average per-product sales (actual data only).

Page 3: Shipping & Operations Analysis
Clear root cause analysis of data spike in lead time, with imputed_flag slicer for KPI comparison and transparency.

🛠️ Project Structure
/data/ – Raw & cleaned datasets (ignored by git)

/notebooks/Superstore_Analysis_Project.ipynb – All Python cleaning, audit, validation, feature engineering steps

/powerbi/ – Power BI dashboard files (ignored by git)

/reports/figures/ – Dashboard screenshots (used in README)

.gitignore – Excludes data/system files for clean repo

README.md – Story + instructions

Full dashboard (PBIX) or data available upon request.

💡 Key KPIs & Insights
Total Sales (Winsorized): 796.38K

Total Unique Orders: 1,975

Average Lead Time (All Data): 111.87 Days (distorted; see audit insight above)

Average Lead Time (Actual Only): 99.14 Days (true business value using DAX measure)

Top Product: Canon imageCLASS 2200 Advanced Copier

Top Region: West

Main Data Risk: 1,283 orders (13%) had missing shipping dates, inflating lead time — clearly flagged on dashboard

📚 What You'll Learn
True end-to-end delivery: cleaning → audit → dashboard

Communication of data risks & findings for business/stakeholder trust

How clear visual analytics + transparency helps drive reliable business decisions

Want the interactive dashboard or demo?
See my full portfolio at https://github.com/Granxn or connect on LinkedIn
