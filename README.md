
# 🏥 Healthcare Analytics Dashboard | Power BI

## 📌 Project Description
End-to-end healthcare analytics dashboard built in Power BI using star schema modeling, DAX-driven KPIs, and interactive visualizations to analyze patient demographics, provider performance, and financial outcomes.

---

## 🎯 Project Overview
This project demonstrates real-world Business Intelligence skills by building an interactive healthcare dashboard that delivers insights into:
- Patient demographics and medical conditions
- Hospital and doctor performance
- Revenue trends, insurance impact, and high-cost admissions

The dashboard is designed using best practices in data modeling, Power Query transformations, and business-aligned KPIs.

---

## 🧱 Data Model
The solution follows a **Star Schema** for optimal performance.

### Tables Used
- **Fact_Admission** – Transactional data (admissions, billing amount, room number, medication, test results)
- **Dim_Patients** – Patient demographic information
- **Dim_Provider** – Hospital and doctor details

### Relationships
- One-to-Many relationships from dimension tables to the fact table
- Foreign keys validated using Power Query column profiling

---

## 🔧 Data Preparation (Power Query)
- Enabled Column Quality, Column Distribution, and Column Profiling
- Verified primary and foreign keys
- Ensured clean and consistent data before modeling

---

## 📐 KPIs Implemented
- **Total Admissions**
- **Average Length of Stay**
- **Net Revenue**
- **Average Revenue per Admission**
- **High-Cost Admission Percentage**
- **Revenue Contribution (%)**

All KPIs were created using DAX and aligned with real healthcare business logic.

---

## 📊 Dashboard Pages

### 1️⃣ Overview
- High-level KPIs
- Admission trends
- Revenue trends

### 2️⃣ Patient Analysis
- Age group distribution
- Gender split
- Medical condition insights
- Length of stay patterns

### 3️⃣ Provider Performance
- Top hospitals by admissions
- Top doctors by admissions
- Average length of stay for top hospitals
- Admission type distribution

### 4️⃣ Financial Performance
- Revenue trend over time
- Revenue by medical condition
- Revenue by insurance provider
- High-cost admission analysis

---

## 🎛️ Interactive Features
- Date slicer (Month-Year)
- Insurance provider filter
- Medical condition filter
- Admission type filter
- Page navigation using buttons

---

## 🧠 Key Learnings
- Fact tables naturally contain repeating values
- Top-N analysis must be based on measures, not text columns
- Average-based rankings can cause ties
- Healthcare financial data must account for refunds and adjustments
- Proper slicer selection improves usability and storytelling

---

## 🛠️ Tools & Technologies
- Power BI Desktop
- DAX
- Power Query


---

## 🚀 How to Use
1. Download the `.pbix` file
2. Open it in Power BI Desktop
3. Refresh the data if required
4. Interact with slicers and visuals to explore insights


---

## 📌 Author
**Srishti Singh**  
Business Analyst | Power BI | Data Analytics

---

⭐ If you find this project useful, feel free to star the repository!

