 🏛️ Executive Summary: Heritage Skills SA Training Operations & Asset Risk Analytics

**Project Overview:**

*Heritage Skills SA* is a South African non-profit organization (NPO) delivering specialized field-training modules—including **Ground Penetrating Radar (GPR) Spatial Mapping, Archaeological Site Cataloguing, Community Surveys, and 3D Digital Preservation**—across Gauteng, Western Cape, KwaZulu-Natal, and neighboring provinces.

This project evaluates operational efficiency, educational outcomes, and asset management across **100 participant training records** funded by major donors including SAHRA, DSAC, the National Lotteries Commission, and private donors.

---

### 🔑 Key Findings & Operational Analytics

**1. Measurable Skill Acquisition & Educational Impact**

* **Significant Skill Gains:** Across all four modules, participants demonstrated an average pre-to-post test score increase of **+32.4 points**.
* **Top-Performing Curriculum:** The `3D_Digital_Preservation` and `GPR_Spatial_Mapping` tracks achieved the highest learning outcomes, with post-training mastery scores averaging **85%–88%**.
* **Curriculum Adjustment Needed:** The `Community_Arch_Survey` module recorded lower overall post-test averages (~70%) and lower baseline entry scores, indicating a need for introductory pre-course material.

**2. Asset Exposure & Financial Risk**

* **20% Equipment Loss/Unreturned Rate:** Approximately 1 in 5 assigned field hardware units (e.g., GPS units, field tablets, dumpy levels, laser scanners) were recorded as `Unreturned` or `Missing` post-training.
* **Grant Renewal Vulnerability:** Equipment loss was heavily concentrated in cohorts funded by **DSAC** and **SAHRA**. Without automated asset controls, hardware replacement costs directly threaten NPO operational budgets and multi-year grant renewals.

**3. Regional Attendance & Completion Bottlenecks**

* **Attendance vs. Performance:** Attendance strongly correlated with module completion; participants with `<70%` attendance consistently failed to meet minimum certification benchmarks ($\ge 60\%$).
* **Geographic Disparities:** Field modules in **KwaZulu-Natal (KZN)** experienced higher rates of absenteeism and incomplete records compared to urban centers in **Gauteng (GP)** and **Western Cape (WC)**, pointing to field travel and logistics constraints.

---

### 🛠️ Analytics & Data Engineering Approach

* **Data Quality Remediation:** Processed a dirty dataset containing mixed date formats (`YYYY/MM/DD`, `DD/MM/YYYY`), unstandardized text casing, duplicate participant IDs, and out-of-range numerical anomalies (e.g., negative test scores and attendance $>100\%$).
* **Distribution-Agnostic Imputation:** Implemented **Grouped Median Imputation** by training module for missing continuous attributes, preserving real data distribution shapes without introducing parametric bias.
* **Interactive Visualization:** Constructed an executive **Tableau Dashboard** featuring global regional filters, KPI scorecards, module performance bullet charts, and an asset risk tracking matrix for quick donor and operational auditing.

---

### 💡 Strategic Recommendations

| Domain | Actionable Strategy | Target Outcome |
| --- | --- | --- |
| **Asset Management** | Enforce a digital sign-out/sign-in protocol tied to facilitator verification prior to issuing completion certificates. | Reduce hardware loss from **20% to <2%**. |
| **Field Operations** | Allocate localized transport stipends for rural field modules, particularly in KwaZulu-Natal. | Elevate rural module attendance to **>85%**. |
| **Sponsor Relations** | Embed automated pre/post skill-gain analytics into quarterly reporting for DSAC and SAHRA. | Demonstrate clear ROI and secure long-term grant funding. |

---

### 💻 Technologies Used

* **Data Processing & Cleaning:** Python (`pandas`, `numpy`, `scikit-learn`)
* **Visualization & Business Intelligence:** Tableau Desktop / Public
* **Documentation & Version Control:** Git, GitHub, Markdown
