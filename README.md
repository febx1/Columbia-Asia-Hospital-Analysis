# 🏥 Columbia Asia Hospital: Operational & Financial Data Analysis

![GitHub License](https://img.shields.io/badge/License-MIT-green.svg)
![Data Tool](https://img.shields.io/badge/Tools-Power%20BI%20%7C%20Excel%20%7C%20Analytics-blue)
![Industry](https://img.shields.io/badge/Industry-Healthcare-red)

## 📋 Project Overview
This project provides a comprehensive data-driven evaluation of **Columbia Asia Hospital’s** departmental performance. By analyzing revenue streams, patient inflow volatility, and satisfaction metrics, this study identifies key growth opportunities and operational bottlenecks to assist hospital administration in strategic decision-making.

---

## 🚀 Key Features & Insights

### 💰 1. Financial Performance & Revenue Concentration
* **Top Drivers:** Orthopedics and General Practice lead with **$173\text{M}$ (33.96%)** and **$164\text{M}$ (32.21%)** respectively.
* **Specialty Gaps:** Significant revenue drop-off in departments like **Renal ($5\text{M}$)** and **Gastroenterology ($10\text{M}$)**, highlighting areas for targeted marketing.
* **Contribution Margin:** High-revenue departments are likely subsidizing lower-volume specialized units, suggesting a need for a "referral flywheel" between General Practice and Cardiology/Neurology.

### 📈 2. Patient Volume & Demand Volatility
* **Peak Demand:** Identified a record surge of **530 ER visits** in August, marking a critical capacity threshold.
* **Trend Patterns:** Data reveals sharp "peaks and valleys," requiring agile staffing models to handle sudden recoveries after quiet periods (e.g., February).
* **Seasonal Correlation:** The late-Q3 surge suggests a correlation with seasonal ailments or local environmental factors that increase orthopedic trauma or general illness.

### 🤝 3. Patient Experience Beyond Speed
* **Wait Time Stability:** Average wait times are maintained consistently between **35–37 minutes**.
* **Satisfaction Drivers:** Analysis shows that satisfaction variance across departments is driven more by **communication and care coordination** than by speed alone.
* **Consistency Gaps:** High-volume departments show more stable satisfaction than low-volume ones, indicating that "busy" teams may have more standardized patient-handling protocols.

---

## 🛠️ Technical Methodology
* **Data Cleaning:** Resolved high levels of missing data in specific columns and standardized categorical fields like `department_referral`.
* **Advanced Modeling:** Created dynamic measures to track month-over-month growth, revenue share per specialty, and weighted satisfaction scores.
* **Visualization:** Built interactive dashboards focusing on:
    * **Departmental Heatmaps:** Mapping revenue vs. patient volume.
    * **Temporal Analysis:** Visualizing intake recoveries and "quiet" period trends.
    * **Service Quality Matrix:** Correlating wait times with satisfaction across different medical teams.

---

## 💡 Strategic Recommendations

### 👨‍⚕️ Staffing & Operations
* **Dynamic Physician Allocation:** Increase staffing in **Orthopedics** and **General Practice** during the August surge to prevent burnout and maintain the 37-minute wait-time threshold.
* **Resource Redistribution:** Transition administrative and support staff from low-volume areas (Renal/Gastro) to high-traffic zones during peak hours to optimize "floor" efficiency.
* **Predictive Hiring:** Use the identified "intake recovery" patterns to plan seasonal hiring or locum doctor contracts ahead of Q3.

### 📉 Financial & Growth Strategy
* **Cross-Specialty Bundling:** Create care packages linking **Physiotherapy ($17\text{M}$)** with **Orthopedics ($173\text{M}$)** to ensure internal revenue retention and holistic patient recovery.
* **Tiered Discounting:** Implement a loyalty framework that offers higher accessibility discounts to elderly or low-revenue groups, improving long-term engagement.
* **Service Expansion:** Invest in the "middle tier" departments like Neurology and Cardiology ($68\text{M}$–$73\text{M}$) to turn them into secondary revenue pillars.

### 📋 Data & Quality Control
* **Source Standardization:** Implement a mandatory data-entry checklist at the registration desk to eliminate the "data gaps" discovered during this analysis.
* **Qualitative Feedback Loops:** Shift focus from "time-to-see-doctor" to "quality of interaction" in patient surveys to address the satisfaction variance between departments.

---

## 📊 Dashboard Preview
*(Tip: Add a screenshot of your Power BI/Excel dashboard here!)*
`![Dashboard Screenshot](path/to/your/image.png)`

---

## 📂 Repository Structure
```bash
├── Data/                 # Raw and Cleaned Datasets
├── Dashboards/         # Power BI (.pbix) or Excel files
├── Documentation/      # Final Report & Presentation
└── README.md           # Project Summary
