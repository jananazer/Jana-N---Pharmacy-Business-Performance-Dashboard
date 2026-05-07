# Pharmacy Business Performance Dashboard

An interactive Power BI analytics solution that tracks sales performance, monitors expenses, and delivers actionable insights for a newly opened pharmacy.

> **Note:** All data has been replaced with mock data to protect business confidentiality. The dashboard framework and analytical methodology remain representative of the original implementation.

---

## Project Overview

**Project Date:** July 2025

This project was developed for a pharmacy launching its operations, providing a comprehensive reporting framework to monitor business health during the critical early months. The dashboard integrates sales, prescription, and expense data to develop insights on revenue trends, profitability by product and insurance plan, and operational cost management.

---

## Dashboard Pages

### 1. Overall Pharmacy Performance

A high-level summary combining OTC sales, prescription revenue, and net profit metrics.

**Key Metrics:**
- Total OTC Sales & Profit
- Total Prescriptions & Prescription Profit
- Net Profit

**Visualizations:**
- Top 5 Most Profitable OTC Categories
- Summary of Prescriptions (Refills, New RX's, Deleted, On Hold)
- Markup by Insurance Plan
- Total Monthly Expenses trend

---

### 2. Over The Counter (OTC) Sales

Detailed breakdown of OTC product performance with discount impact analysis.

**Key Metrics:**
- Total Discounts Provided
- Total Purchase Cost
- Total Profit

**Visualizations:**
- Profit by Product Category (comparing profit vs. selling price)
- Target Profit vs. Actual Profit gauge
- Category filter for drill-down analysis

**Key Insight:** Overall profit could have been approximately 1.5× higher without discounting, highlighting the substantial effect discounts have on profit margins.

---

### 3. Prescription Sales

Analysis of prescription revenue by insurance plan with patient payment breakdowns.

**Key Metrics:**
- Total Revenue
- Total Profit
- Total RX Count

**Visualizations:**
- Total New RX's and Refill RX's by Plan
- Total Patient Paid vs. Plan Paid comparison
- Target Profit vs. Actual Profit gauge
- Plan filter for detailed analysis

**Key Insight:** High prescription traffic from ODB plans indicates a strong recurring customer base, while ESI plans contribute higher margins—suggesting an opportunity to attract more privately insured patients.

---

### 4. Expenses Analysis

Comprehensive expense tracking with category and payment method breakdowns.

**Key Metrics:**
- Total Expenses
- Revenue

**Visualizations:**
- Total Monthly Expenses trend
- Total Expenses by Category
- Amount by Payment Method

**Key Insight:** Startup costs peaked in April/May prior to opening. Since launch, expenses have declined significantly with rent and utilities now representing the primary ongoing costs.

---

## Key Findings

| Finding | Impact |
|---------|--------|
| Prescription revenue is 6.6× higher than OTC sales | Prescriptions are the primary revenue driver |
| Discounts reduced OTC profit by ~33% | Opportunity to optimize discount strategy |
| ODB plans drive volume; ESI plans drive margin | Balanced growth strategy needed |
| Monthly expenses declining post-launch | Path to profitability as startup costs normalize |

---

## Technologies Used

| Tool | Purpose |
|------|---------|
| **Power BI** | Data modeling, DAX calculations, and interactive dashboard creation |
| **Excel** | Source data storage and preprocessing |

---

## Getting Started

1. Download the `.pbix` file from this repository
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Navigate through the four dashboard tabs
4. Use slicers to filter by month, product category, or insurance plan

