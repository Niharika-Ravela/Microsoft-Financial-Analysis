# Microsoft FY24 Q3 Financial Statements Analysis  
Power BI Visualization Project  

This project analyzes **Microsoft’s FY24 Q3 financial statements**, comparing them with **FY23 Q3**.  
The goal is to understand revenue trends, operational performance, and the impact of cloud + AI growth (including Copilot momentum) on Microsoft’s financial trajectory.

---

## 📊 Objectives

- Compare **FY24 Q3 vs FY23 Q3** performance  
- Visualize revenue and income indicators (KPIs)  
- Identify which segments drive growth  
- Explore how cloud services & AI adoption influence revenue patterns  
- Communicate trends through clean Power BI visuals  

---

## 🧰 Tools Used

- **Power BI Desktop**  
- **Excel** (data source & cleaning)  
- **Power Query Editor**  
- Microsoft’s official FY24 Q3 financial statement data  

---

## 📥 Data Source

Microsoft Investor Relations — FY24-Q3 Earnings:

https://www.microsoft.com/en-us/Investor/earnings/FY-2024-Q3/press-release-webcast

Dataset: Yearly/Quarterly Income Statements

---

## 🔄 Data Preparation Workflow (Your Original Steps — Cleaned & Structured)

### **1. Load Data**
- Loaded the financial statements into Power BI using Excel workbooks as source.

### **2. Transform Data in Power Query Editor**
- Selected required columns and dropped unused columns  
- Removed null and empty rows  
- Removed the first two rows  
- Promoted first row to headers  
- Cleaned and standardized values  
- Ensured consistency between FY23 and FY24 values  

### **3. Model the Data**
- Created a comparison table for FY23 vs FY24  
- Built KPI measures for:
  - Total Revenue  
  - Operating Income  
  - Net Income  

### **4. Visualizations**
- Tabular view comparing FY23 and FY24 metrics  
- KPI cards showing YoY change  
- Clustered bar chart to visualize year-over-year shifts  

---

## 📈 Key Insights  

(*Your analysis, preserved*)  

- **Net Income decreased by ~0.52%** compared to last year  
- **Total Revenue and Operating Income grew**, showing strong business fundamentals  
- Cloud and AI-driven segments continue to strengthen revenue mix  
- FY24 reflects early financial impact of **Copilot** and AI-integrated products  

---

## 🖼 Sample Visual

![image](https://github.com/user-attachments/assets/157fb773-0697-4df4-9d3e-8c83a408c263)

---

## 📁 Repository Structure

```plaintext
Microsoft-Financial-Analysis/
├── data/                # Raw or cleaned Excel/CSV files (optional)
├── reports/             # Power BI .pbix file or exported PDF
├── screenshots/         # Visuals from the dashboard
└── README.md
