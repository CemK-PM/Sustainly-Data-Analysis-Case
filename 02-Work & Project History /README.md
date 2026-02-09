
# 🌍 Transition Risk & Unit Economics under Climate Policy  
### Scenario-Based Margin Stress Testing (Transition Master Case Study)

> **Executive Summary:**  
> A scenario-driven analysis translating climate transition risk from regulatory frameworks into company-level margins and unit economics. The project combines IPCC-aligned policy scenarios, financial modeling, and illustrative market adjustments to explore how carbon and energy price dynamics reshape industrial profitability through 2050.

---

## 🎯 The Challenge
The objective was to bridge climate policy with financial performance, answering one core question:

> *How do different climate transition pathways translate into margin pressure at sector, company, and unit level?*

The work evolved across four analytical layers:
1. Regulatory transition risk  
2. Scenario-based financial modeling  
3. Company-level exposure  
4. Unit economics and pricing stress tests  

---

## 📂 Datasets Used

This project relies on a mix of **public datasets**, **sector benchmarks**, and **scenario-based synthetic extensions**.

### 🌐 Public & Institutional Sources
- **IPCC AR6 (RCP Scenarios 2.6 / 4.5 / 6.0 / 8.5)**  
  Climate transition pathways used to define policy ambition and mitigation speed.  
  Source: https://www.ipcc.ch/report/ar6/syr/

- **World Bank – Carbon Pricing Dashboard**  
  Historical and current ETS and carbon tax levels used to extrapolate future carbon price trajectories.  
  Source: https://carbonpricingdashboard.worldbank.org/

- **IEA – World Energy Outlook 2023**  
  Energy price trends and transition narratives used for scenario-specific energy cost assumptions.  
  Source: https://www.iea.org/reports/world-energy-outlook-2023

- **National Accounts & Industry Statistics**  
  Used for baseline revenues and sector weighting:
  - USA: Bureau of Economic Analysis (BEA)  
  - Canada: Statistics Canada  
  - Germany: Eurostat  

---

### 🧪 Modeled & Derived Datasets (from Excel Models)

These datasets are constructed inside the provided Excel files using transparent assumptions:

- **Carbon Intensity Trajectories (2020–2050)**  
  Annual exponential decay of emissions intensity by scenario.

- **Energy Intensity Trajectories**  
  Gradual efficiency improvements applied consistently across scenarios.

- **Carbon Price Scenarios**  
  Exponential growth rates (8–12% annually) depending on RCP pathway.

- **Energy Price Scenarios**  
  Linear price increases (€/GJ) differentiated by scenario.

- **Transition Coefficient (k)**  
  Scenario-specific factor representing the pace of regulatory tightening.  
  *Used as a structural parameter, not a forecast variable.*

---

### 🏭 Company & Unit-Level Data

Derived using sector averages and illustrative firm profiles:

- **Company-Level Cost Structures**  
  Energy cost share, carbon exposure, and operating margins inferred from sector benchmarks.

- **Unit Economics (Cement / Concrete)**  
  - €/tCO₂ → €/ton cement → €/m³ concrete cost linkage  
  - ETS pass-through modeled explicitly  
  - Energy and material costs layered consistently  

- **Market Adjustment Factors (Illustrative)**  
  - Competitive pressure  
  - Policy intensity  
  - Sustainability premiums (e.g. EPD effects)  

> ⚠ These factors are **directional stress overlays**, not empirically calibrated datasets.

---

## 📊 Regulatory & Scenario Modeling

**Weighted Net Margin Evolution Across Climate Scenarios (2030–2050)**

![Scenario Margin Projection](./assets/scenario_weighted_net_margins.png)

*Margins diverge sharply depending on transition timing, with early compression under aggressive mitigation and deferred risk under weak regulation.*

---

## 🧠 Driver Importance Analysis

**Relative Impact of Transition Variables on Net Margins**

![Driver Importance](./assets/driver_importance_random_forest.png)

*A Random Forest model was used to assess variable importance. Carbon and energy prices dominate margin outcomes.*

---

## 🏭 Company-Level Approach

**From Macro Scenarios to Company Exposure**

![Company Approach Flow](./assets/company_approach_flow.png)

*Sector-level transition risk translated into representative company cost structures.*

---

## 🧮 Unit Economics – Core Cost Model

**Unit Cost Build-Up Under Rising Carbon and Energy Prices**

![Unit Economics Core](./assets/unit_economics_core_costs.png)

*Cost-consistent linkage across emissions, energy, and unit pricing.*

---

## ⚠ Market-Adjusted Unit Economics (Illustrative)

**Commercial Friction Overlay on Unit Prices**

![Unit Economics Market Adjustment](./assets/unit_economics_market_adjusted.png)

> ⚠ *Illustrative layer.*  
> Demonstrates how competition, regulation, and sustainability signaling may amplify cost pressure beyond pure accounting logic.

---

## 💻 Technical Implementation
- **Python:** Scenario logic, projections, charts  
- **Excel:** Regulatory modeling, company approach, unit economics  
- **Visualization:** Programmatic charts refined for reporting  

---

## 🚀 Key Insights

| Area | Insight |
|---|---|
| Financial Risk | Carbon & energy prices dominate margin outcomes |
| Timing Effect | Early mitigation = short-term pain, long-term stability |
| Company Exposure | Structural sensitivity outweighs scale |
| Unit Economics | Cost realism strong; pricing realism weakens under soft factors |
| Strategy | Climate strategy increasingly *is* margin strategy |

---

## 🛠 Tech Stack & Skills
- **Tools:** Python (Pandas, NumPy, Matplotlib), Excel  
- **Methods:** Scenario Analysis, ESG Risk Modeling, Unit Economics  
- **Skills:** Climate Transition Risk, Financial Interpretation, Strategic Modeling  

---

## ⚠ Disclaimer
This project is analytical and illustrative, not a valuation or investment recommendation.  
Some datasets are scenario-derived to support forward-looking analysis rather than historical accuracy.

---

## 🧭 Why This Matters
Climate transition risk is no longer abstract.  
It is measurable, modelable, and financially material.
