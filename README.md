# Telecom Customer Churn Insights & Interactive Analytics Dashboard

An end-to-end data analytics project focused on identifying customer churn patterns, analyzing subscriber lifespans, and evaluating the impact of customer service interactions for a telecommunications provider. This project seamlessly combines **Python** for exploratory data analysis (EDA) and data cleansing with **Power BI** for executive-level business intelligence reporting.

---

## 📊 Project Executive Summary
Understanding why customers leave is critical for telecom sustainability. This project aims to diagnose key pain points in customer accounts, explore correlation metrics between operational variables (like service calls or plan structures), and present them in a highly optimized interface.

### 🎯 Key Performance Indicators (KPIs) Captured
* **Total Churn Volume:** 3.33K customers transitioned out.
* **Average Customer Service Calls:** 1.56 calls per account (a critical threshold metric discovered for loyalty prediction).
* **Overall Churn Split:** 14.49% True Churn vs. 85.51% Retained.

---

## 🎨 UI/UX Design & Color Palette Strategy
To maximize professional readability and modern visual appeal, the dashboard avoids generic bright styles and deploys a custom **Dark-Teal Modern Theme**:
* **Primary Dashboard Background:** `#022B3A` (Deep Slate Teal)
* **Card & Visual Containers:** `#044353` (Muted Petrol Navy)
* **Active Metric Highlights:** `#20B2AA` (Light Sea Green)
* **Secondary Analytical Splits:** `#87CEEB` (Sky Blue)
* **Text Hierarchy:** Pure White (`#FFFFFF`) for prominent core metrics, Muted Steel Blue (`#B0C4DE`) for axis categories and labels.
* **Depth & Illusion (3D Effect):** Built using soft visual borders (`8px` container border radius) combined with native dark shadows (`60%` transparency) to construct structured high-depth interface elements.

---

## 🛠️ Repository Architecture
```bash
├── data/
│   └── telecom_churn_data.csv       # Raw analytical dataset
├── python/
│   └── churn_prep_analysis.py       # Python preprocessing & metric profiling script
├── dashboard/
│   └── Telecom_Churn_Dashboard.pbix # Interactive Power BI Dashboard source file
└── README.md                        # Project documentation (You are here)
