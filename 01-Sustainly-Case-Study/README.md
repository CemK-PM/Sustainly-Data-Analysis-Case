# 🌍 Climate Risk & Carbon Footprint Analysis (Sustainly Case Study)

> **Executive Summary:** This project evaluates the carbon footprint and climate-related financial vulnerabilities of energy giants RWE and EnBW by integrating multi-source environmental and regulatory data.

---

### 🎯 The Challenge
The objective was to quantify how climate change impacts a major energy provider's operations. The analysis focused on three pillars: **Emission Trends**, **Geographic Physical Risks**, and **Financial Exposure** to evolving carbon taxation.

---

### 🔍 Data Sources & Methodology
The study cross-references verified emission data with global climate indices:
* **[EU ETS Emissions Database](https://sdi.eea.europa.eu/data/76f260d6-2d41-4dfc-b0de-ee1fd3ee74f2):** Primary source for verified 2005–2024 GHG data.
* **[European Drought Observatory (EDO)](https://data.jrc.ec.europa.eu/dataset/12a852fe-8a43-4d04-9c75-1d3ef2ac673c):** Used for mapping facility-level drought and water stress (SPEI index).
* **[World Bank Carbon Pricing Dashboard](https://carbonpricingdashboard.worldbank.org/):** Source for carbon tax trends and global compliance costs.

---

### 📝 Strategic Narrative
To transform raw metrics into actionable risk insights, the workflow followed a structured approach:
1. **Data Synthesis:** Addressed missing historical data using a custom **Forward/Backward Fill** methodology to ensure a reliable 20-year trend projection.
2. **Spatial Risk Mapping:** Overlaid facility coordinates with EDO drought maps, identifying specific operational "hotspots" in North Rhine-Westphalia vulnerable to water scarcity.
3. **Financial Modeling:** Projected potential compliance costs under 2030 carbon price scenarios, highlighting RWE’s higher sensitivity to regulatory shifts compared to EnBW.

---

### 🚀 Key Insights
| Metric | Analysis Result |
| :--- | :--- |
| **Financial Impact** | Potential carbon compliance costs exceeding **€16 Billion/year** by 2030. |
| **Physical Risk** | Critical drought exposure identified for key facilities in the Netherlands and Germany. |
| **Comparative Risk** | RWE maintains a higher emission intensity, necessitating faster decarbonization to mitigate financial risk. |

---

### 📊 Full Report & Visuals
The comprehensive analysis, including detailed risk maps, synthetic data logic, and strategic recommendations, is available in the final report:

👉 [**Download/View Full Case Study Report (PDF)**](./Cem_Kahvecioglu_Sustainly_Case_Study.pdf)

---

### 🛠 Tech Stack
* **Analysis:** Python (Pandas, Folium), Excel (Financial Modeling).
* **Concepts:** ESG Risk Assessment, Carbon Pricing, GIS Mapping.
