# Customer Spending & Revenue Segmentation Analysis

**Tools:** Power BI, DAX  
**Domain:** Financial Analytics | Customer Segmentation  
**Portfolio:** [mg67.vercel.app](https://mg67.vercel.app/) | **GitHub:** [Mg6700](https://github.com/Mg6700)

---

## Project Overview

This project analyzes credit card transaction data to segment customers by spending behavior, identify primary revenue drivers, and surface actionable business recommendations for card product strategy. The dashboard processes 656,000+ transactions across 4 card categories, 3 income groups, and 6 job types to deliver a comprehensive view of where revenue comes from and where growth opportunities lie.

---

## Dashboard Preview

![Customer Spending & Revenue Segmentation Dashboard](<img width="1280" height="723" alt="Customer Spending   Revenue Segmentation Analysis" src="https://github.com/user-attachments/assets/90941620-233b-4d00-8712-26cf602e2ab4" />)

---

## Dataset

| Field | Description |
|---|---|
| Card Category | Blue, Silver, Gold, Platinum |
| Customer Job | Businessman, White-collar, Self-employed, Govt, Blue-collar, Retiree |
| Income Group | High, Average, Low |
| Transaction Method | Swipe, Online, Chip |
| Metrics | Revenue, Interest Earned, Transaction Volume, Avg Spend per Customer |

**Scale:** 656K transactions | $57M total revenue | $8M total interest earned

---

## Key Metrics (All-time)

| Metric | Value |
|---|---|
| Total Revenue | $57M |
| Total Interest Earned | $8.0M |
| Average Spend per Customer | $5.5K |
| Total Transaction Count | 656K |

---

## Dashboard Features

- **Quarter filter** (Q1–Q4) to track seasonal revenue trends
- **Gender filter** (M/F) for demographic spend comparison
- **Card category filter** (Blue/Silver/Gold/Platinum) for product-level analysis
- **Transaction method breakdown** (Swipe/Online/Chip) for payment channel insights
- **QTR Revenue & Transaction Count** dual-axis trend chart
- **Revenue by Income Type, Card Type, Expenditure Type, and Customer Job** bar charts
- **Card-level summary table** showing Revenue, Interest Earned, and Transaction Volume per category

---

## Key Findings

**1. Blue cards dominate revenue but signal over-reliance on entry-level customers**
Blue cards generate $47M — approximately 83% of total revenue — despite being the entry-level product. This indicates the premium segment (Gold/Platinum) is significantly underperforming its potential.

**2. High-income customers drive volume, but premium cards don't follow**
High-income customers account for $30M of revenue, yet Gold and Platinum cards combined generate only $3.7M. There is a clear mismatch between customer value and product adoption.

**3. Bills and Entertainment are the dominant spending categories**
Bills ($14M) and Entertainment ($10M) together account for ~42% of all spending — making these the core revenue-generating categories to protect and grow.

**4. Businessmen and White-collar workers are the highest-value segments**
Businessman customers contribute $18M and White-collar $10M, together representing ~49% of total revenue. Marketing and acquisition efforts should prioritize these segments.

**5. Swipe transactions dominate (~60–65%) while digital adoption lags**
Despite Chip and Online being more trackable and secure, swipe remains the primary transaction method. Low digital adoption limits data richness and fraud detection capability.

**6. Revenue is stable across quarters with no seasonal spikes**
Q1–Q4 each show approximately $14M revenue and ~163–167K transactions, suggesting steady demand with no strong seasonality to exploit.

---

## Recommendations

| Recommendation | Rationale |
|---|---|
| Launch targeted upsell campaign: Blue → Gold/Platinum | Gold/Platinum have low volume despite higher per-card value potential |
| Focus premium card marketing on Businessman & White-collar segments | These segments already drive the most revenue — higher card tier = higher ARPU |
| Promote digital transactions (Chip/Online) with incentives | Improves tracking, reduces fraud risk, increases engagement data |
| Invest in Bills & Entertainment merchant partnerships | Core spending categories — co-branding or cashback deals can drive stickiness |
| Develop retiree segment strategy | Retirees contribute $5M — an underserved segment with stable income profiles |

---

## Technical Highlights

- Built fully interactive Power BI report with cross-filtering across all visuals
- Used DAX measures for dynamic revenue calculations, average spend, and interest rate analysis
- Designed a card-category summary matrix combining 3 KPIs in a single table visual
- Applied multiple slicer types (button-style for quarters and card types, dropdown for date)

---

## How to Use

1. Clone or download the repository
2. Open the `.pbix` file in Power BI Desktop
3. Use the slicers (Quarter, Gender, Card Category, Transaction Method) to explore the data
4. Hover over charts for tooltip-level detail per segment

---

*Created by Mayur Goyal | [Portfolio](https://mg67.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/mg67)*
