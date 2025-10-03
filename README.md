## 📊 Daikibo Industrials Analysis

This repository contains two analytical tasks conducted for **Daikibo Industrials**, aimed at uncovering operational inefficiencies and workplace equity concerns across their global factory network.

---

### 🧭 Overview

Daikibo operates multiple factories across Japan, Germany, and China. This project includes:

1. **Telemetry Analysis** — identifying which factory experienced the most machine breakdowns and which device types were most failure-prone.
2. **Equality Audit** — classifying job roles based on gender pay equality scores to highlight potential discrimination.

---

### 📁 Contents

| File Name                          | Description |
|-----------------------------------|-------------|
| `Daikibo-Telemetry-Dashboard.png`   | Screenshot of Tableau dashboard showing machine downtime per factory and device type. |
| `Updated_Task5_Equality_Table.xlsx`       | Edited Excel file with a new column classifying job roles by fairness of pay. |

---

### 📌 Task 1: Telemetry Analysis

**Objective:**  
Analyze machine telemetry data collected from four Daikibo factories during May 2021 to determine:
- Which factory had the highest total downtime.
- Which machine types contributed most to that downtime.

**Methodology:**
- Data imported into Tableau from a unified JSON file.
- Created a calculated field (`Unhealthy`) assigning 10 minutes of downtime per unhealthy status.
- Built two bar charts:
  - **Down Time per Factory**
  - **Down Time per Device Type**
- Combined charts into a dashboard with interactive filtering.

**Outcome:**  
The dashboard reveals the most problematic factory and its most failure-prone machines. This insight supports targeted maintenance and operational improvements.

---

### 📌 Task 2: Gender Pay Equality Audit

**Objective:**  
Classify job roles based on their **Equality Score** (ranging from -100 to +100) to assess fairness in compensation between genders.

**Methodology:**
- Used the provided `Equality Table.xlsx` file.
- Added a new column: `Equality class`, using the following logic:
  - `Fair` → Score between -10 and +10
  - `Unfair` → Score between -20 and -11 or +11 and +20
  - `Highly Discriminative` → Score below -20 or above +20

**Outcome:**  
The updated table highlights roles and locations with significant pay disparities, enabling Daikibo to prioritize corrective actions.

---

### 📬 Contact

For questions or collaboration, feel free to reach out via GitHub or email.

