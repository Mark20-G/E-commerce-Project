# 📦 Brazilian E-Commerce – Sales & Operations Analysis Project

## 🔍 About the Project  
This project presents a full end-to-end business analysis based on a Brazilian E-Commerce dataset. The objective was to explore trends in sales, delivery performance, customer satisfaction, and geography — and to deliver actionable insights for operational and strategic decision-making.

The project covers every major step of the data analysis lifecycle: data engineering using SQL (ETL), data modeling, analytical reporting with Power BI, and a final executive presentation with findings and recommendations.

---

## 🧩 Project Workflow

### ✅ Project Scoping  
Defined business goals and analytical questions (e.g., seasonality, order cancellations, delivery delays) based on customer journey and operational metrics.  
📄[Scope.docx](https://github.com/user-attachments/files/21101792/Scope.docx)


### ✅ Data Engineering: ETL (Bronze–Silver–Gold)  
Built an ETL pipeline in SQL:
- **Bronze Layer**: Raw ingested data.
- **Silver Layer**: Cleaned and validated tables using procedures like `load_silver`, with deduplication, normalization, surrogate keys, and type enforcement.  
- **Gold Layer**: Analytical tables used for DAX measures and dashboards.  
📄 [Cleaning_Documentation.docx](https://github.com/user-attachments/files/21101819/Cleaning_Documentation.docx)


### ✅ Data Modeling  
Created a star-schema model aligning facts and dimensions using surrogate keys for clean joins.  
📷 ![Data flow](https://github.com/user-attachments/assets/4e873278-3a49-4bf7-8cd5-bc29e5cca3cd)


### ✅ Dashboard Design (Power BI)  
Created 3 dashboards connected directly to SQL views:
- **Performance Overview Dashboard**: Sales trends, seasonality, KPIs.
- **Customer & Delivery Dashboard**: Review scores, delays by state, delivery vs estimated.
- **Product & Payment Insights Dashboard**: Revenue per order, category scores, payment method analysis.  
📄 [Dashboards view.pdf](https://github.com/user-attachments/files/21101826/Dashboards.view.pdf)


### ✅ Analytical Insights  
Used DAX and SQL to calculate:
- Revenue trends, monthly averages, cancellation rate, review distribution, revenue per order, delivery time by region.
- Identified clear seasonal patterns, regional performance gaps, and product category insights.

### ✅ Summary Presentation  
Built an executive summary with:
- **Key strengths** (e.g., operational efficiency, customer satisfaction)
- **Weaknesses** (e.g., rising cancellations, post-2017 revenue decline)
- **Recommendations** (short/mid-term actions for growth and optimization)  
📄 [Analysis presentation – E-Commerce.pptx](https://github.com/user-attachments/files/21101830/Analysis.presentation.E-Commerce.pptx)


---

## 📁 Included Files

- [Scope.docx](https://github.com/user-attachments/files/21101792/Scope.docx) – Business goals and analytical questions  
- [Cleaning_Documentation.docx](https://github.com/user-attachments/files/21101819/Cleaning_Documentation.docx) – ETL and data cleaning process  
- [Dashboards view.pdf](https://github.com/user-attachments/files/21101826/Dashboards.view.pdf) – Dashboard screenshots  
- [Analysis presentation – E-Commerce.pptx](https://github.com/user-attachments/files/21101830/Analysis.presentation.E-Commerce.pptx) – Executive summary and insights  

---

## 🛠 Tools Used

- **SQL (T-SQL)** – ETL pipeline and data transformation  
- **Power BI** – Dashboard building and interactive visualizations  
- **Word, PowerPoint** – Project documentation and executive presentation  
- **Draw.io** – Data modeling and schema design  

---

## 👨‍💻 About Me

Hi! I'm Mark,  
A data analyst passionate about turning messy datasets into clear, decision-driving insights.  
In this project, I applied structured data engineering (ETL), SQL analytics, DAX, and dashboarding to deliver business-ready analysis.

This project is part of my growing portfolio — feel free to check out my 📊 Tableau Dashboards Project or 🏗 Data Warehouse Build using SQL Server.

More projects coming soon – stay tuned! 🚀
