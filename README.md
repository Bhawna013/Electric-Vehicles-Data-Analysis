# Electric Vehicle Data Analysis Dashboard using Tableau
---

## Business Context
The global automotive industry is experiencing a rapid transition from internal combustion engine (ICE) vehicles to electric vehicles (EVs). Governments are promoting EV adoption through subsidies, tax benefits, and environmental regulations, while manufacturers continue investing in battery technology and charging infrastructure.

For manufacturers, policymakers, and investors, understanding EV adoption patterns is essential for making strategic decisions regarding production planning, infrastructure investment, incentive programs, and market expansion.

This dashboard analyzes electric vehicle registration data to identify market trends, customer adoption patterns, manufacturer performance, and regional demand using Tableau.

---

## Business Problem   
Despite the rapid growth of electric vehicles, stakeholders often struggle to answer critical business questions such as:

- Which EV technology dominates the market?
- Which states have the highest EV adoption?
- How has EV demand changed over time?
- Which manufacturers are leading the industry?
- Are government incentive programs influencing adoption?
- Which vehicle models are driving market growth?

Without a centralized analytical dashboard, these insights remain fragmented, making strategic decision-making difficult.

The objective of this project was to convert raw registration data into an interactive business intelligence dashboard that supports data-driven decision making.

---
## Business Objective
The dashboard was designed to answer the following analytical questions:

- Measure the current size of the EV market.
- Compare Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).
- Analyze long-term EV adoption trends.
- Identify regions with the highest market penetration.
- Evaluate manufacturer market share.
- Understand the relationship between CAFV eligibility and vehicle adoption.
- Identify the most successful vehicle models.

These objectives help different stakeholders make informed business decisions.

---
## Dataset Understanding
The dataset contains electric vehicle registration records with attributes including:

- Vehicle Make
- Vehicle Model
- Model Year
- Electric Vehicle Type
- Electric Range
- State
- CAFV Eligibility
- Registration Information

Each record represents one registered electric vehicle.

Before building the dashboard, the dataset was reviewed for missing values, inconsistent categories, and duplicate records to ensure reliable reporting.

---

## KPI Selection
Rather than displaying every available field, only business-relevant KPIs were selected.

1. **Total Registered Vehicles**
This KPI measures the overall size of the EV market and serves as the primary indicator of adoption.

**Business Value**
    - Estimates market demand.
    - Helps manufacturers evaluate market opportunity.
    - Supports investment decisions.

2. **Average Electric Range**
Electric range is one of the most important purchase considerations for EV buyers.

Tracking average range helps evaluate technological improvements across manufacturers.

**Business Value***
    - Measures battery technology advancement.
    - Indicates consumer value proposition.
    - Supports product benchmarking.

3. **BEV vs PHEV Distribution**
Battery Electric Vehicles represent fully electric transportation, while Plug-in Hybrid Vehicles still rely partly on fuel.
Comparing these categories reveals where the industry is heading.

**Business Value**
    - Identifies technology transition.
    - Assesses customer preference.
    - Helps manufacturers prioritize R&D investments

---

## Dashboard Design Rationale
Every visualization was chosen to answer a specific business question.

A. **EV Adoption by Model Year (Area Chart)**
**Why this visualization?**
- Management needs to understand whether EV adoption is accelerating or slowing over time.
- The area chart effectively highlights long-term growth patterns.

**Business Question**
How has EV adoption evolved over the years?

**Insight**
The dashboard shows steady growth beginning in 2011, with significant acceleration after 2018 and peak registrations in 2023. This trend reflects increasing consumer confidence, improved charging infrastructure, and supportive government policies.



B. **EV Distribution by State (Map)**
**Why this visualization?**
- Geographical analysis helps identify markets with strong EV penetration.
- Maps reveal regional patterns much more effectively than tables.

**Business Question**
Where are electric vehicles most widely adopted?

**Insight**
California leads EV registrations by a substantial margin, followed by Washington, Oregon, and New York. These states benefit from stronger charging infrastructure, environmental policies, and consumer incentives.

**Business Impact**
Companies can prioritize these regions for dealership expansion, charging stations, and marketing campaigns.



C. **Top 10 Manufacturers (Bar Chart)**
**Why this visualization?**
- Understanding manufacturer dominance helps evaluate competitive positioning.
- A ranked bar chart enables quick comparison of market share.

**Business Question**
Which manufacturers dominate the EV market?

**Insight**
Tesla accounts for approximately 69% of total registered EVs, demonstrating significant market leadership. Other manufacturers, including Nissan, Chevrolet, Ford, and Rivian, maintain considerably smaller market shares.

**Business Impact**
Emerging manufacturers must differentiate through pricing, battery performance, technology, or customer experience to compete effectively.


D. **CAFV Eligibility Analysis (Donut Chart)**
**Why this visualization?**
- Government incentives are an important factor influencing EV adoption.
- This chart evaluates how many vehicles qualify for Clean Alternative Fuel Vehicle incentives.

**Business Question**
How significant is CAFV eligibility across the market?

**Insight**
Approximately 41.8% of vehicles qualify for CAFV incentives, while a large proportion remains classified as unknown. This suggests opportunities for improved policy reporting and highlights the influence of incentive programs on adoption.

**Business Impact**
Policy makers can use this information to evaluate incentive effectiveness and identify areas requiring better program awareness.


E. **Top Vehicle Models (Treemap)**
**Why this visualization?**
- Individual vehicle models often determine a manufacturer's market success.
- Treemaps effectively display proportional market share.

**Business Question**
Which vehicle models drive the EV market?

**Insight**
Tesla Model Y and Tesla Model 3 dominate registrations, with Nissan Leaf remaining a strong performer. The concentration among a few models indicates strong product-market fit and brand loyalty.

**Business Impact**
Manufacturers can benchmark successful products to understand customer preferences regarding range, pricing, and design.

---

## Key Business Insights  
The analysis produced several important findings:

- The EV market has grown consistently, indicating increasing consumer acceptance.
- Battery Electric Vehicles account for approximately 78% of registrations, demonstrating a        market shift toward fully electric transportation.
- California continues to dominate EV adoption due to infrastructure maturity and policy support.
- Tesla maintains overwhelming market leadership, reflecting strong brand recognition and          technological advantage.
- Higher electric range continues to be an important competitive differentiator.
- CAFV incentives appear to contribute positively to EV adoption in eligible regions.

---

## Business Recommendations
Based on the analysis, the following recommendations can be made:

**Manufacturers**
- Increase investment in BEV development rather than hybrid technology.
- Focus on extending battery range while reducing vehicle cost.
- Expand operations into high-growth states.

**Policymakers**
- Continue financial incentives that encourage EV adoption.
- Expand charging infrastructure in emerging markets.
- Improve CAFV data quality for better policy evaluation.

**Investors**
- Prioritize companies focused on BEV technology.
- Monitor states showing accelerating EV adoption for infrastructure investments.  

---
## Limitations
This analysis is based on registration data and therefore has several limitations:

- It does not include vehicle sales revenue.
- Customer demographics are unavailable.
- Charging station availability is not included.
- Vehicle pricing and battery specifications are absent.
- The dataset represents registrations rather than total market demand.

---

## Dashboard Preview  
<img width="1566" height="680" alt="image" src="https://github.com/user-attachments/assets/62cde6fe-292e-4733-9026-5e9b50ac12d3" />


