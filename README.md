# EDA Using Power BI  
## Project Title: Marketing Campaign Effectiveness

---

## Problem Statement

The marketing team runs campaigns across multiple channels:
- Email
- Social Media
- TV
- Search Ads

Although marketing spend is increasing, management is unsure whether these campaigns are delivering a good **Return on Investment (ROI)**.

### Leadership Wants to Know:
- Which channels generate the highest revenue  
- Which campaigns are underperforming  
- How efficiently marketing money is spent  

You are responsible for building a **campaign performance analytics solution** to support smarter marketing investments.

---

## Analysis Questions

1. Identify missing or inconsistent marketing data  
2. Which marketing channels generate the highest revenue?  
3. Calculate ROI for each campaign using DAX  
4. Analyse conversion rates across channels  
5. Perform univariate analysis on campaign spend  
6. Identify underperforming campaigns  
7. Design a campaign performance dashboard  
8. Which channels should receive increased investment?  
9. How can insights improve future marketing strategy?

---

## 1. Identify Missing or Inconsistent Marketing Data

The dataset was examined in **Power Query Editor** for missing values and logical inconsistencies.

- No null values were found in key columns such as:
  - Spend
  - Revenue
  - Clicks
  - Conversions
- Logical conditions were satisfied:
  - Clicks ≤ Impressions  
  - Conversions ≤ Clicks  

**Conclusion:**  
The dataset is clean and suitable for analysis.  
There are no missing or inconsistent marketing data issues.

---

## 2. Which Marketing Channels Generate the Highest Revenue?

Revenue analysis by marketing channel shows:

- **Search Ads** generate the highest revenue  
- Followed by **TV** and **Email**

This indicates that **digital channels** are more effective in driving revenue compared to traditional channels.

**Key Insight:**  
✔️ Search Ads generate the highest revenue

---

## 3. Calculate ROI (Return on Investment) Using DAX

ROI was calculated using a **DAX measure** by comparing total revenue against total marketing spend.

This helps:
- Evaluate campaign profitability  
- Identify campaigns with positive or negative returns  

---

## 4. Analyse Conversion Rates Across Channels

Conversion rate analysis reveals:

- **Search Ads** and **Email Marketing** have higher conversion rates  
- **TV campaigns** have the lowest conversion rate  

**Reason:**  
TV campaigns focus more on brand awareness rather than direct conversions.

---

## 5. Univariate Analysis on Campaign Spend

Findings from univariate analysis:

- **TV campaigns** require the highest investment  
- **Email campaigns** operate at the lowest cost  

This analysis highlights:
- Cost-heavy campaigns  
- Spending patterns across marketing channels  

---

## 6. Identify Underperforming Campaigns

Underperforming campaigns were identified based on:
- Low ROI  
- High spend  

**Observations:**
- TV-based campaigns show low efficiency  
- Some Social Media campaigns underperform  

These campaigns require optimization or budget reallocation.

---

## 7. Campaign Performance Dashboard Design

An interactive **Power BI dashboard** was designed using:

- KPI Cards
- Bar Charts
- Tables

### Dashboard Metrics:
- Campaign Spend
- Revenue
- ROI
- Conversion Rate

### Filters:
- Channel
- Region
- Campaign

This enables **data-driven marketing decisions**.

---

## 8. Channels Recommended for Increased Investment

Based on ROI, conversion rates, and revenue efficiency:

### Increase Investment In:
- **Search Ads**
- **Email Marketing**

### Optimize or Reduce Investment In:
- Social Media (needs optimization)
- TV Advertising (low ROI)

**Conclusion:**  
Reallocating budget toward high-performing digital channels will improve overall marketing effectiveness.

---

## 9. How Insights Improve Future Marketing Strategy

Campaign performance insights enable:

- Better budget allocation  
- Identification and optimization of underperforming campaigns  
- Improved targeting and personalization  

Continuous monitoring of:
- ROI
- Conversion rates  

helps marketers:
- Adjust strategies in real time  
- Reduce inefficient spending  
- Maximize marketing effectiveness  

**Result:**  
Higher ROI and more successful future marketing campaigns.

---
