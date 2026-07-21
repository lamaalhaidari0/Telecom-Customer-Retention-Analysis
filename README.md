# Telecom Churn Analysis & Revenue Protection

A data-driven analysis project identifying customer retention strategies and revenue protection mechanisms for telecom companies facing high churn rates.

## Project Overview

This project analyzes customer churn patterns in the telecom industry to understand why customers leave and how to prevent revenue loss. Through SQL analysis, data visualization, and strategic recommendations, we've identified actionable insights to improve customer retention.

**Business Impact:**
- **Identified Revenue Loss:** $1.64M annualized revenue exposure
- **Churn Focus:** Month-to-Month contracts and Fiber Optic services
- **Timeline Risk:** Highest churn in first 12 months of customer lifecycle

## Project Structure

```
├── analysis.ipynb                           # Python analysis with SQL queries
├── Data_Driven_Customer_Retention_Strategy.pptx  # Executive presentation
├── Telecom_Churn_Executive_Dashboard.pbix   # Power BI interactive dashboard
└── README.md                                # This file
```

## Key Files Explained

### 1. **analysis.ipynb**
Jupyter notebook containing SQL-based analysis of customer churn data. Includes:
- Database setup and data loading from CSV
- SQL queries analyzing churn patterns
- Top reasons for customer churn
- Internet type impact on churn rates
- Revenue impact calculations by service type
- Uses SQLite for data storage and pandas for data manipulation

**To run:**
```bash
jupyter notebook analysis.ipynb
```
*Requires: pandas, sqlite3, jupyter*

### 2. **Data_Driven_Customer_Retention_Strategy.pptx**
Executive-level presentation covering:
- Business problem and revenue exposure
- Interactive dashboard overview
- Root cause analysis (Fiber Optic, Month-to-Month contracts, tenure risk)
- Strategic recommendations with data backing
- Implementation actions

### 3. **Telecom_Churn_Executive_Dashboard.pbix**
Interactive Power BI dashboard titled "Telecom Customer Retention & Revenue Analytics" featuring:

**Key Performance Indicators:**
- **Annualized Revenue Loss** - $1.64M (primary KPI in large card format)
- **Total Lost Customers** - 1,756 churned customers

**Data Visualizations:**
- **Customer Churn Danger Zone by Tenure (Area Chart)** - Shows churn distribution across customer lifecycle (0-80+ months). Reveals two critical risk periods: immediate onboarding (0 months) and late tenure (80+ months), with stable middle phase
- **Annual Revenue Share by Churn Status (Donut Chart)** - Churned customers represent $1.64M (32.27%), while active customers generate $3.45M (67.73%), demonstrating the impact of retention
- **Total Revenue by Internet Type (Bar Chart)** - Fiber Optic dominates with ~$1.3M revenue exposure, followed by DSL (~$0.2M) and Cable (~$0.2M)
- **Total Revenue by Contract Duration (Bar Chart)** - Month-to-Month contracts account for ~$1.4M (highest risk), One-Year (~$0.2M), Two-Year (~$0.1M)




### Top Churn Drivers

1. **Contractual Vulnerability**
   - Month-to-Month contracts show highest churn risk
   - Primary driver of revenue leakage
   - Recommendation: Incentivize 1-year or 2-year agreements

2. **Product Performance Issue**
   - Fiber Optic services have disproportionately high churn
   - Despite being premium, revenue-generating service
   - Recommendation: Enhance value proposition and upgrade equipment

3. **Early Lifecycle Risk**
   - Majority of churn happens in first 12 months
   - Critical onboarding and early retention period
   - Recommendation: Strengthen early customer engagement

4. **Top Reasons for Churn**
   - Competitor offered better devices (313 customers)
   - Competitor made better offer (311 customers)
   - Poor support staff attitude (220 customers)
   - Competitor offered more data (117 customers)

## Strategic Recommendations

### 1. Upgrade Customer Support Quality
- Implement empathy and technical training for support agents
- Tie performance incentives to Customer Satisfaction (CSAT) scores
- Expected Impact: Reduce support-related churn by ~10%

### 2. Revamp Fiber Optic Value Proposition
- Offer free high-performance router upgrades to existing customers
- Review and optimize pricing models
- Expected Impact: Stabilize Fiber Optic churn rates

### 3. Stabilize Month-to-Month Contracts
- Deploy automated loyalty incentives (10% discount or 1 free month)
- Encourage migration to 1-year or 2-year plans
- Expected Impact: Reduce contract-related churn by ~15%



## Technologies Used

- **Python 3.x** - Data analysis and scripting
- **SQL** - Query and analyze data
- **SQLite** - Lightweight database
- **Pandas** - Data manipulation and analysis
- **Jupyter Notebook** - Interactive analysis environment
- **Power BI** - Business intelligence dashboard
- **PowerPoint** - Executive presentations

## How to Use

### Quick Start
1. Review the **Data_Driven_Customer_Retention_Strategy.pptx** for executive summary
2. Explore the **Telecom_Churn_Executive_Dashboard.pbix** for visual insights
3. Run **analysis.ipynb** to see detailed SQL analysis and calculations

### For Data Analysis
```bash
# Install required packages
pip install pandas jupyter

# Launch notebook
jupyter notebook analysis.ipynb
```

### For Dashboard
1. Open Power BI Desktop
2. Open `Telecom_Churn_Executive_Dashboard.pbix`
3. Refresh data connection to your datasource
4. Export insights to stakeholders

## Key Metrics

| Metric | Value |
|--------|-------|
| Annual Revenue Loss | $1.64M |
| Customers Churned | 1,756 |
| Highest Churn Service | Fiber Optic  |
| Most Risky Contract | Month-to-Month |
| Peak Churn Period | 0-12 months tenure |


## Files to Download for Analysis

- **telco.csv** - Source data file (required for notebook)
- **telecom_churn.db** - SQLite database (auto-generated)

## Questions?

This analysis addresses:
- Why are customers leaving?
- Which customer segments are at risk?
- What's the revenue impact?
- Which retention strategies are most effective?
- How can we stabilize contracts?


---
## Author:
Prepared by: Lama Alhaidari

*Last Updated: JUL 2026 *

