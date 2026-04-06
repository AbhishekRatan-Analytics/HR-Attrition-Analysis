# HR Employee Attrition Analysis Dashboard

<img width="1917" height="778" alt="image" src="https://github.com/user-attachments/assets/9deb6778-64da-4544-ab48-7358e31ad1bf" />



> **A business analyst portfolio project** — identifying the root causes of employee attrition and quantifying the cost to the organisation using the IBM HR Analytics dataset.

---

## The Business Problem

A company is losing **26.8% of its workforce every year** — nearly double the industry benchmark of 13%.

That translates to **394 employees** and an estimated **$7.69M in annual replacement costs** (based on the industry-standard 3× monthly salary model). Leadership needs to know: *who is leaving, why, and what can be done about it?*

This project answers those questions with data.

---

## Key Findings

| # | Finding | Data |
|---|---------|------|
| 1 | **Sales Representatives are the highest-risk role** | 49.4% attrition — nearly 2× the company average |
| 2 | **Overtime nearly doubles the likelihood of leaving** | 39.9% attrition (OT) vs 21.6% (no OT) |
| 3 | **New hires are walking out in the first 2 years** | 40.3% attrition for 0–2 year tenure employees |
| 4 | **Gen Z employees (18–25) are the most likely to leave** | 43.1% attrition — highest of any age group |
| 5 | **Low job satisfaction is an early warning signal** | Level 1 satisfaction → 33.6% attrition vs 24.4% at Level 4 |

---

## Business Recommendations

**1. Audit overtime policy in the Sales department**
Employees working overtime leave at nearly twice the rate of those who don't. A targeted review of workload distribution in Sales — the department with both the highest attrition (33.4%) and the highest overtime burden — could recover a meaningful number of employees annually.

**2. Redesign the 90-day onboarding programme**
The 0–2 year tenure cohort has a 40.3% attrition rate. This points to a role-fit or cultural integration failure at the entry point. Structured check-ins, mentoring, and early engagement surveys in the first 90 days can reduce early-exit risk.

**3. Review compensation bands for Sales Representatives**
Sales Representatives have the highest attrition (49.4%) and sit in the lower-middle income range. Reducing Sales attrition from 33% to 20% through targeted compensation review would save approximately **$1.4M annually** in replacement costs alone.

---

## Dashboard Features

- **5 KPI tiles** — Total Headcount, Active Employees, Overall Attrition %, Est. Cost of Attrition, Benchmark comparison
- **6 charts** — Attrition by Job Role, Department, Overtime, Age Group, Tenure Band, Job Satisfaction
- **2 interactive slicers** — filter the entire dashboard by Department and Gender
- **Key Findings panel** — written interpretation of the top 3 insights

---

## Project Structure

```
hr-attrition-analysis/
│
├── HR-Employee-Attrition-Dashboard.xlsx   # Main Excel workbook
│   ├── Raw Data                           # Cleaned source data (1,470 rows, 34 columns)
│   ├── Pivot                              # 8 pivot tables — one per business question
│   ├── KPI                               # KPI calculations with methodology notes
│   ├── Data Points                        # Supporting analysis
│   └── Dashboard                          # Interactive Excel dashboard
│
├── dashboard-preview.png                  # Dashboard screenshot
└── README.md                              # This file
```

---

## Tools & Methodology

| Area | Detail |
|------|--------|
| **Tool** | Microsoft Excel |
| **Techniques** | Pivot tables, IF/IFS formulas, VLOOKUP, conditional formatting, chart design, slicer interactivity |
| **KPI modelling** | Attrition % = Attrition Count ÷ Total Headcount; Cost = Attrition Count × (Avg Monthly Income × 3) |
| **Benchmark source** | Industry standard healthy attrition: 10–15% (midpoint 13%) |
| **Dataset** | IBM HR Analytics — synthetic/public dataset, 1,470 employee records |

---

## Dataset Acknowledgement

This project uses the **IBM HR Analytics Employee Attrition & Performance** dataset, a publicly available synthetic dataset widely used for HR analytics practice. It does not represent any real organisation or real individuals.

In a real-world engagement, additional data would strengthen the analysis:
- Exit interview themes and verbatim feedback
- Team-level manager effectiveness scores
- Offer acceptance / rejection data from recruiting
- Internal mobility and promotion history

---

## About This Project

This project was built as part of my Business Analyst portfolio to demonstrate:
- Translating raw HR data into actionable business insights
- Building a decision-maker-facing dashboard (not just charts)
- Quantifying the financial impact of a people problem
- Communicating findings in plain business language

**Author:** Abhishek Ratan
**Connect:** [LinkedIn](https://www.linkedin.com/in/abhishek-ratan/)

---

*If you found this project useful or have feedback, feel free to open an issue or connect on LinkedIn.*
