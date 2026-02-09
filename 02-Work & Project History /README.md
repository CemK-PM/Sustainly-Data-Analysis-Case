# 🌍 Transition Risk & Unit Economics under Climate Policy  
### Scenario-Based Margin Stress Testing (Transition Master Case Study)

> **Executive Summary:**  
> A scenario-based analysis translating climate transition risk into company-level margins and unit economics. The project combines IPCC-aligned policy pathways with financial modeling to explore how carbon and energy price dynamics reshape industrial profitability through 2050.

---

## 🎯 The Challenge
The goal was to connect climate policy with financial performance by answering one core question:

> *How do different climate transition pathways translate into margin pressure at sector, company, and unit level?*

The work evolved across four layers:
1. Regulatory transition risk  
2. Scenario-based financial modeling  
3. Company-level exposure  
4. Unit economics and pricing stress tests  

---

## 📂 Datasets Used

This project combines **publicly available climate and economic datasets** with **scenario-based modeled extensions**.

### 🌐 Public & Institutional Sources
- **IPCC AR6 (RCP 2.6 / 4.5 / 6.0 / 8.5)** – climate transition pathways  
  https://www.ipcc.ch/report/ar6/syr/

- **World Bank – Carbon Pricing Dashboard** – ETS and carbon tax benchmarks  
  https://carbonpricingdashboard.worldbank.org/

- **IEA – World Energy Outlook 2023** – energy price trends and transition narratives  
  https://www.iea.org/reports/world-energy-outlook-2023

- **National Accounts & Industry Statistics** – baseline revenues and sector weights  
  - USA (BEA): https://www.bea.gov/data/industries  
  - Canada (Statistics Canada): https://www150.statcan.gc.ca  
  - Germany (Eurostat): https://ec.europa.eu/eurostat  

---

### 🧪 Modeled & Derived Data (Excel-Based)
- Carbon and energy intensity trajectories (2020–2050)  
- Scenario-specific carbon and energy price paths  
- Transition coefficient representing policy pace  
- Company-level cost structures inferred from sector averages  

> Some datasets are scenario-derived to support forward-looking analysis rather than historical precision.

---

## 📊 Regulatory & Scenario Modeling

**Weighted Net Margin Evolution Across Climate Scenarios (2030–2050)**  
*(Source: `Transition Risk Analysis – Executive Summary of 1&2 (2025).pdf`)*

![Scenario Margin Projection](./assets/scenario_weighted_net_margins.png)

*Margins diverge by transition timing, with early compression under aggressive mitigation and deferred risk under weak regulation.*

---

## 🧠 Driver Importance Analysis

**Relative Impact of Transition Variables on Net Margins**  
*(Source: `2) Modelling and Proposal.xlsx` – Random Forest feature importance)*

![Driver Importance](./assets/driver_importance_random_forest.png)

*Carbon and energy prices dominate margin outcomes.*

---

## 🏭 Company-Level Approach

**From Macro Scenarios to Company Exposure**  
*(Source: `3) Company Approach.xlsx`)*

![Company Approach Flow](./assets/company_approach_flow.png)

*Regulatory scenarios translated into representative company cost structures.*

---

## 🧮 Unit Economics – Core Cost Model

**Unit Cost Build-Up Under Rising Carbon and Energy Prices**  
*(Source: `Unit Economics.xlsx`)*

![Unit Economics Core](./assets/unit_economics_core_costs.png)

*Consistent linkage from €/tCO₂ to cement and concrete unit costs.*

---

## ⚠ Market-Adjusted Unit Economics (Illustrative)

**Commercial Friction Overlay on Unit Prices**  
*(Source: `Unit Economics last.xlsx` – final adjustment sheets)*

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

---

## 🧭 Why This Matters
Climate transition risk is no longer abstract.  
It is measurable, modelable, and financially material.
