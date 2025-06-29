# 📌 Executive Summary

Overview

This repository delivers an in-depth Exploratory Data Analysis (EDA) of the Spanish business landscape, based on official data sources. The project includes three key deliverables:

- Original Excel datasets (raw data)
- Python Jupyter Notebook (`EDA companies in Spain.ipynb`)
- Interactive Power BI Dashboard (`EDA Empresas España.pbix`)

The goal is to help stakeholders, policymakers, analysts, and business developers gain strategic insights into how companies are distributed geographically and sectorally, and how they are structured by size and legal entity.

---

## Key Insights

- **Geographic Concentration:** What the data shows:
Madrid, Catalonia, and Andalusia together represent a significant percentage of the total number of registered companies in Spain. These regions consistently attract the highest volume of business activity due to favourable infrastructure, access to skilled labour, and proximity to national and international markets.

Business implications:

These regions are likely to remain the main drivers of Spain’s GDP and employment.

Investors and business developers should prioritise these hubs for market entry or expansion strategies.

Regional policy differences may influence how incentives, taxation or labour regulations affect company growth — this requires constant monitoring.
- **Sector Breakdown:**:
The service sector dominates, accounting for the majority of registered businesses. Industrial sectors show strong regional concentrations, especially in autonomous communities with historic manufacturing clusters (e.g., Basque Country, Catalonia).

Business implications:

The dominance of services indicates opportunities for B2B and B2C providers in areas like tech, professional services, tourism, and hospitality.

The relative strength of industry in certain regions highlights local supply chains and potential for nearshoring strategies.

Emerging sectors (e.g., renewable energy, digital services) could benefit from additional market analysis to quantify growth potentia
- **Company Size:** The vast majority of Spanish companies are micro-enterprises (<10 employees) or small enterprises (10–49 employees). Medium-sized and large companies make up only a small share of the overall distribution.

Business implications:

Policies must be designed to address structural barriers faced by SMEs, such as limited access to financing, lower productivity, and challenges scaling internationally.

Investors should evaluate resilience: micro-enterprises are more exposed to market volatility, while medium-sized firms often have greater capacity for innovation and exports.

For B2B providers, the predominance of micro and small businesses means shorter sales cycles but higher customer churn.
- **Legal Structure:** Private limited companies (Sociedades Limitadas) are the most common legal entity, offering flexibility for entrepreneurs and small businesses. Self-employed workers (autónomos) and cooperatives represent a significant segment, especially in specific industries like agriculture and social economy.

Business implications:

The large share of autónomos suggests a strong entrepreneurial spirit but also a need for policies that protect sole traders during economic downturns.

Legal structures can impact taxation, liability, and access to funding — this must be factored into any market entry or M&A strategy.

For public sector initiatives, promoting conversions from sole proprietors to more formal structures could foster job creation and economic stability.
- **Trends Over Time:** Preliminary comparisons, when possible, show modest growth in the overall number of businesses, with some regional disparities. Sectors such as digital services, green energy, and logistics are showing more robust post-pandemic recovery, while traditional sectors like retail and hospitality have uneven performance.

Business implications:

Areas with slow recovery may require additional policy support or private intervention to modernise their economic base.

Stakeholders should monitor trend shifts for early signs of structural change, e.g., decline in certain traditional industries and acceleration in knowledge-based sectors.

Time-series data can help model scenarios for resilience planning and resource allocation.

---

## Deliverables Detail

### 1) Original Data
- Provided in `/data/` as Excel files.
- Covers Autonomous Communities, economic activities, employee size bands, and legal status.
- Data cleansing steps documented in the Python Notebook.

### 2) Python Jupyter Notebook (`/notebooks/EDA companies in Spain.ipynb`)
- Contains all data cleaning and transformation logic.
- Uses `pandas`, `numpy`, and `matplotlib` for descriptive statistics and visualisation.
- Easily adaptable for updated data or additional dimensions.

### 3) Power BI Dashboard (`/dashboards/EDA Empresas España.pbix`)
- Interactive visualisations with filters for region, sector, size, and legal structure.
- Drill-down capabilities to analyse specific Autonomous Communities or industry branches.
- Built for both technical and non-technical stakeholders.

---

## Analytical Focus Areas

| Area                 | Description                                                                                      |
|----------------------|--------------------------------------------------------------------------------------------------|
| **Geographic Focus** | Identify economic clusters and regional disparities.                                             |
| **Sectoral Analysis**| Quantify the dominance of key sectors and niche activities.                                      |
| **Size Profiling**   | Assess the weight of SMEs vs. large companies to guide support programmes and funding strategies.|
| **Legal Structure**  | Understand implications for compliance, tax and growth barriers.                                 |
| **Trend Monitoring** | Track changes over time to assess resilience and future opportunities.                           |

---

## ✅ Recommendations

- **Policy:** Regions with a high percentage of micro-enterprises may benefit from tailored digitalisation programmes and SME financing.
- **Investment:** Industrial and technology clusters present high potential for private or institutional investment.
- **Risk Management:** Sectors dominated by sole proprietors may require extra attention in risk mitigation planning.

---



## Deliverables Recap

- ✔️ Clean source data
- ✔️ Fully documented Python Notebook
- ✔️ Power BI Dashboard ready for stakeholder presentations

---

**Author:**  
Antonio Romero

