# 🛍️ Vrinda Store — Annual Sales Data Analysis 2022

<div align="center">

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Type-Data%20Analysis-0077B5?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Year](https://img.shields.io/badge/Period-2022-gold?style=for-the-badge)

**End-to-end sales analysis of an Indian fashion e-commerce store across 7 platforms and 31,000+ orders**

[📊 View Dashboard](#dashboard-preview <img width="1202" height="597" alt="dashborad" src="https://github.com/user-attachments/assets/0eec99cd-7c6a-4a6b-98ef-855b8ebbe283" />
) · [📋 Key Insights](#key-insights) · [🚀 Recommendations](#strategic-recommendations) · [📁 File Structure](#file-structure)

</div>

---

## 📌 Project Overview

This project presents a **complete annual sales analysis** for Vrinda Store — an Indian fashion retailer selling across multiple e-commerce channels including Amazon, Myntra, Flipkart, Ajio, Meesho, and Nalli.

The goal was to transform raw transactional data (31,047 orders across 12 months) into an **interactive Excel dashboard** with 7 charts and a full set of **actionable business recommendations** for the client.

> **Business Question:** *Where did ₹2.12 Crore come from — and where is the next ₹50 Lakhs hiding?*

---

## 🗂️ File Structure

```
vrinda-store-analysis/
│
├── 📊 Vrinda_Store_Data_Analysis.xlsx     ← Main Excel file (raw data + dashboard)
├── 📄 README.md                            ← This file
│
├── 📁 docs/
│   ├── Documentation_Package.html         ← Full stakeholder documentation
│   ├── Presentation_Guide.md              ← How to present this project
│   └── Stakeholder_Comms_Guide.md         ← Manager & client communication
│
├── 📁 data/
│   └── data_dictionary.md                 ← Column definitions & data notes
│
└── 📁 assets/
    └── dashboard_preview.png              ← Dashboard screenshot
```

---

## 📊 Dataset Details

| Property | Value |
|---|---|
| **Source** | Vrinda Store internal order management system |
| **Period** | January 2022 – December 2022 |
| **Total Records** | 31,047 orders |
| **Columns** | 21 fields per order |
| **Channels** | Amazon, Myntra, Flipkart, Ajio, Meesho, Nalli, Others |
| **Currency** | INR (₹) |
| **Geography** | Pan-India (all states) |

### Key Fields

| Column | Description |
|---|---|
| `Order ID` | Unique order identifier |
| `Gender` | Customer gender (Men / Women) |
| `Age` / `Age_Group` | Customer age and derived group (Teenager / Adult / Senior) |
| `Date` / `Month` | Order date and extracted month |
| `Status` | Delivered / Cancelled / Returned / Refunded |
| `Channel` | E-commerce platform |
| `Category` | Product type (Kurta, Set, Saree, etc.) |
| `Amount` | Order value in INR |
| `ship-city` / `ship-state` | Delivery location |

---

## 📈 Dashboard Preview

The Excel dashboard includes **7 interactive charts** connected to slicers for Month, Channel, and Category filtering:

| # | Chart | Type | Purpose |
|---|---|---|---|
| 1 | Monthly Sales & Orders | Combo (Bar + Line) | Track seasonal trends |
| 2 | Sales by Gender | Pie / Donut | Identify dominant customer base |
| 3 | Order Status Breakdown | Pie | Measure operational health |
| 4 | Top 5 Cities by Revenue | Bar | Geographic concentration |
| 5 | Age Group × Gender | Grouped Bar | Customer segmentation |
| 6 | Revenue by Sales Channel | Column | Channel ROI comparison |
| 7 | Revenue by Product Category | Bar | Product portfolio analysis |

---

## 💡 Key Insights

### 🏆 Performance Highlights

- **Total Revenue:** ₹2,11,76,377 (~₹2.12 Crore)
- **Total Orders:** 31,047
- **Peak Month:** March 2022 (₹19.3 Lakhs)
- **Delivery Success Rate:** 92.3%

### 👥 Customer Profile
- **Women** account for **64%** of revenue (₹1.36 Cr vs ₹0.76 Cr for Men)
- **Adult Women aged 30–49** are the #1 customer segment with 10,740 orders
- Teenager women (under 30) are a strong secondary segment at 6,560 orders

### 📍 Geographic Concentration
Top 5 cities drive disproportionate revenue:
1. 🥇 **Bengaluru** — ₹17.7 Lakhs
2. 🥈 **Hyderabad** — ₹13.7 Lakhs
3. 🥉 **New Delhi** — ₹11.6 Lakhs
4. **Chennai** — ₹9.2 Lakhs
5. **Mumbai** — ₹9.2 Lakhs

### 🛒 Channel Performance
| Channel | Orders | Revenue |
|---|---|---|
| **Amazon** | 11,016 | ₹75.2 Lakhs (35%) |
| **Myntra** | 7,254 | ₹49.4 Lakhs (23%) |
| **Flipkart** | 6,703 | ₹45.7 Lakhs (22%) |
| Ajio | 1,931 | ₹13.3 Lakhs |
| Nalli | 1,484 | ₹10.2 Lakhs |
| Meesho | 1,398 | ₹9.3 Lakhs |

### 🧵 Category Performance
| Category | Revenue |
|---|---|
| **Set** | ₹1.05 Crore (49%) |
| **Kurta** | ₹49.6 Lakhs |
| **Western Dress** | ₹31.5 Lakhs |
| Saree | ₹10.1 Lakhs |
| Top | ₹11.9 Lakhs |

---

## 🚀 Strategic Recommendations

| Priority | Recommendation | Based On | Est. Impact |
|---|---|---|---|
| 🔴 High | Expand Sets collection with new seasonal variants | Sets = 50% of revenue | +₹15–25L |
| 🔴 High | Increase Amazon Sponsored Products investment | Amazon = 35% channel share | +₹10–20L |
| 🔴 High | Target Adult Women 30–49 as primary marketing persona | Largest order segment (10,740) | +₹8–15L |
| 🟡 Medium | Launch Q4 festive campaign (Diwali, Navratri) | 4-month decline from Sep–Dec | +₹5–10L |
| 🟡 Medium | Reduce returns (3.4%) via improved size guides | 1,045 returned orders | +₹4–7L |

---

## 🛠️ Tools & Skills Used

- **Microsoft Excel** — Data cleaning, pivot tables, interactive dashboard
- **Data Analysis** — Trend analysis, segmentation, cohort grouping
- **Business Intelligence** — KPI identification, chart storytelling
- **Stakeholder Communication** — Documentation, presentation, email templates

---

## 📋 How to Use This Project

1. **Download** `Vrinda_Store_Data_Analysis.xlsx`
2. Open in **Microsoft Excel** (2016 or later recommended)
3. Navigate to the **Dashboard** sheet
4. Use the **slicers** (Month / Channel / Category) to filter dynamically
5. Refer to `docs/Documentation_Package.html` for full chart explanations

---

## 📚 Learning Outcomes

This project demonstrates the following analytical skills:

- ✅ Raw data cleaning and preparation in Excel
- ✅ Building pivot tables from scratch
- ✅ Creating a multi-chart interactive dashboard with slicers
- ✅ Deriving business insights from sales data
- ✅ Formulating and presenting actionable recommendations
- ✅ Professional stakeholder documentation

---

## 👤 Author

**[Kiran Sindam]**
Data Analyst | Excel · Python · Power BI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/kiransindam/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github)](https://github.com/kiransindam)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-orange?style=flat-square)](https://aistudio.google.com/apps/80abc1d3-fe16-48f2-a577-f20e4c746d99?fullscreenApplet=true&showPreview=true&showAssistant=true)

---

## Download and Open that HTML Files

### link- 1 :

[GitHub_LinkedIn_Guide.html](https://github.com/user-attachments/files/26490150/GitHub_LinkedIn_Guide.html)

### link- 2 :

[Vrinda_Store_Documentation_Package.html](https://github.com/user-attachments/files/26490209/Vrinda_Store_Documentation_Package.html)

## 📄 License

This project is available for educational and portfolio purposes.
Raw data belongs to Vrinda Store and is used for analysis demonstration only.

---

<div align="center">
  <sub>If this project helped you, please ⭐ star the repository!</sub>
</div>

