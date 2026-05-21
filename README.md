# 🌿 Green Destinations — HR Attrition Analysis

> An interactive HR analytics dashboard analyzing employee attrition patterns across age, income, tenure, and overtime at Green Destinations travel agency.

🔗 **Live Dashboard:** [View Here](https://akhtarayan57.github.io/Green-Destinations-Attrition-Analysis/green_destinations_dashboard.html)

---

## 📋 Project Overview

Green Destinations is a well-known travel agency. The HR Director noticed a rise in employee attrition and commissioned a data-driven investigation to identify trends and patterns across the workforce.

This project analyzes survey data from **1,470 employees** to answer:
- What is the overall attrition rate?
- Do factors like **age**, **years at the company**, and **income** influence whether employees leave?

---

## 📊 Key Findings

| Metric | Value |
|--------|-------|
| Total Employees Surveyed | 1,470 |
| Employees Who Left | 237 |
| **Attrition Rate** | **16.1%** |
| Avg Monthly Income (Left) | $4,787 |
| Avg Monthly Income (Stayed) | $6,833 |
| Avg Age (Left) | 33.6 years |
| Avg Age (Stayed) | 37.6 years |
| Avg Tenure (Left) | 5.1 years |
| Avg Tenure (Stayed) | 7.4 years |

### 🔴 Attrition by Age Group
| Age Group | Attrition Rate |
|-----------|---------------|
| 18–24 | 39.2% ⚠️ Highest |
| 25–34 | 20.2% |
| 35–44 | 10.1% ✅ Lowest |
| 45–54 | 10.2% |
| 55+ | 15.9% |

### 💰 Attrition by Monthly Income
| Income Band | Attrition Rate |
|-------------|---------------|
| < $3,000 | 28.6% ⚠️ Critical |
| $3,000–$6,000 | 12.7% |
| $6,000–$10,000 | 12.0% |
| $10,000–$15,000 | 13.5% |
| $15,000+ | 3.8% ✅ Lowest |

### 📅 Attrition by Tenure
| Years at Company | Attrition Rate |
|-----------------|---------------|
| 0–1 years | 34.9% ⚠️ Highest |
| 2–3 years | 18.4% |
| 4–5 years | 13.1% |
| 6–10 years | 12.3% |
| 10+ years | 8.1% ✅ Most Loyal |

### ⏰ Overtime Impact
| Overtime Status | Attrition Rate |
|----------------|---------------|
| Works Overtime | 30.5% ⚠️ |
| No Overtime | 10.4% ✅ |

> Overtime employees leave at **3× the rate** of non-overtime employees.

---

## 💡 HR Recommendations

1. **Focus on Early-Career Retention** — Employees aged 18–34 are the highest-risk group. Mentorship programs and clear career paths can help retain young talent.

2. **Review Compensation for Low Earners** — Employees earning under $3,000/month have a 28.6% attrition rate. Targeted pay raises are the highest-ROI retention lever.

3. **Strengthen Onboarding** — 34.9% of employees leave in their first year. A structured 90-day onboarding and regular check-ins can dramatically reduce early exits.

4. **Audit Overtime Culture** — With 30.5% attrition among overtime workers vs 10.4% for others, workload redistribution or additional hiring is urgently needed.

---

## 🗂️ Repository Contents

```
Green-Destinations-Attrition-Analysis/
│
├── green_destinations_dashboard.html   # Interactive HR dashboard (open in browser)
├── greendestination.csv                # Raw employee survey dataset
└── README.md                           # Project documentation
```

---

## 🛠️ Built With

- **HTML / CSS / JavaScript** — Interactive dashboard
- **Python** — Data analysis and aggregation
- **PptxGenJS** — PowerPoint report generation
- **Data Source** — Green Destinations Employee Survey (n = 1,470)

---

## 👤 Author

**Ayan Akhtar** · [@akhtarayan57](https://github.com/akhtarayan57)

---

*This project was created for internal HR analysis at Green Destinations. Data is anonymized and used for reporting purposes only.*
