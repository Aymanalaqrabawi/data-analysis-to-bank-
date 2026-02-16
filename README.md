# Bank Card Analytics Dashboard – Power BI

## Project Overview
End-to-end banking analytics solution built using Power BI to analyze card distribution, credit limits, customer behavior, and transaction-related indicators.

The dashboard provides strategic insights for risk monitoring, card portfolio analysis, and client activity tracking.

---

## Business Objectives
- Analyze card portfolio distribution (type & brand)
- Monitor chip adoption rate
- Track credit limit patterns
- Study PIN change behavior over time
- Identify trends in account opening activity

---

## Dataset Description
The dataset includes:

- 6,146 total cards
- Card type (Debit / Credit / Prepaid)
- Card brand (Mastercard, Visa, Amex, Discover)
- Chip availability
- Credit limit values
- PIN last change year
- Account open date
- Client-level aggregation

---

## Data Preparation (Power Query)
- Data cleaning and type correction
- Date formatting and transformation
- Handling missing values
- Creation of derived columns
- Standardization of categorical fields

---

## Data Modeling
A relational data model was implemented using:

- One-to-Many relationships between:
  - Clients → Cards
  - Cards → Transactions (if applicable)
- Optimized model to avoid ambiguity
- Reduced cardinality for performance improvement

Model design follows star-schema principles for analytical efficiency.

---

## DAX Measures Implemented
- Total Cards
- Average Credit Limit
- Average Cards per Client
- Card Distribution by Brand
- Card Type Distribution
- Chip Penetration Rate
- Account Growth Trend
- PIN Change Frequency by Year

Time intelligence logic applied for yearly trend analysis.

---

## Key Insights

- 89% of issued cards include chip technology.
- Average credit limit ≈ 14,350.
- Mastercard dominates total card portfolio.
- Debit cards represent the largest share of issued cards.
- Significant increase in account openings observed after 2018.
- PIN change activity peaked between 2008–2011.

---



## Tools & Technologies
- Power BI Desktop
- Power Query (ETL)
- DAX
- Data Modeling
- Time Intelligence

---

## Business Value
This dashboard supports:
- Portfolio performance monitoring
- Risk exposure visibility
- Client behavior analysis
- Strategic decision-making in retail banking
