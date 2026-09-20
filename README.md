# UrbanGlow — Sales & Profit Analytics Dashboard

## Project Overview

This project presents an end-to-end **Sales & Profit Analytics solution for UrbanGlow**, an e-commerce beauty and personal-care business selling through Zepto.

The project demonstrates the complete analytics workflow:

**Client Requirements → Raw Data → Data Cleaning → Analysis → Interactive Dashboard → Business Insights**

---

## 1. Client Requirements & Business Problem

UrbanGlow operates an e-commerce business selling beauty and personal-care products across India.

The client provided approximately six months of messy and unorganized transactional data and required a complete analytics solution covering:

- Data cleaning and formatting
- Data organization
- Missing-value and duplicate checks
- Net Sales calculation
- Gross Profit calculation
- Gross Profit Margin calculation
- Cancellation Rate analysis
- Interactive dashboard
- Key business insights
- Business recommendations

### Client Requirements

![UrbanGlow Client Requirements](images/client-requirements.png)

---

## 2. Raw Data

The original Excel workbook contains approximately **1,010 transaction records** covering April–September 2026.

The raw dataset includes information such as:

- Order ID
- Order Date
- Quantity
- Customer
- Product
- Brand
- Unit Price
- Payment Mode
- Order Status
- Cost per Unit
- Net Sales
- Gross Profit
- Gross Profit Margin
- Region

The raw dataset contains several data-quality issues, including inconsistent text formatting, different representations of payment modes and order statuses, and inconsistent brand labels.

### Raw Dataset

![UrbanGlow Raw Dataset](images/raw-data.png)

---

## 3. Data Cleaning & Transformation

The raw dataset was cleaned and transformed into an analysis-ready dataset.

Key cleaning activities included:

- Standardizing date fields
- Standardizing numeric fields
- Formatting monetary values in INR
- Normalizing Brand and Product names
- Standardizing Payment Mode
- Standardizing Order Status
- Validating Net Sales calculations
- Validating Gross Profit calculations
- Validating Gross Profit Margin
- Checking duplicate records
- Removing non-transactional/junk columns
- Preparing the dataset for dashboard analysis

Multiple raw brand labels caused by inconsistent spacing were normalized so that the same brand was not incorrectly treated as separate brands.

### Cleaned Dataset

![UrbanGlow Cleaned Dataset](images/cleaned-data.png)

---

## 4. Interactive HTML Dashboard

The cleaned dataset was transformed into an interactive **Sales & Profit Executive Dashboard**.

The dashboard provides management with a consolidated view of:

- Total Net Sales
- Gross Profit
- Gross Profit Margin
- Orders
- Units Sold
- Average Order Value
- Cancellation Rate
- Unique Customers
- Sales & Profit Trends
- Top Products
- Brand Performance
- Regional Performance
- Payment Mode Performance
- Cancellation Analysis
- Product Profitability

### Dashboard Overview

![UrbanGlow Sales & Profit Dashboard](images/dashboard-overview.png)

### Interactive Filters

Users can analyze the business using filters for:

- Date
- Region
- Brand
- Product
- Payment Mode
- Order Status

The dashboard visuals and KPI cards update according to the selected filters.

---

## 5. Key Business Insights

The dashboard automatically generates data-driven insights based on the selected analytical scope.

### Revenue & Profitability

The dataset contains approximately **₹10.03 lakh in total Net Sales** and approximately **₹7.36 lakh in Gross Profit** across 1,010 records.

Revenue and profit are analyzed separately to identify products and segments that contribute differently to sales and profitability.

### Product Performance

The dashboard identifies the **Top 10 Products** based on:

- Net Sales
- Units Sold

This helps distinguish high-revenue products from high-volume products.

### Brand Performance

After normalization, approximately **30 distinct brands** are represented compared with 57 raw brand labels.

This prevents inconsistent brand naming from fragmenting brand-level analysis.

### Cancellation Analysis

The overall cancellation rate is approximately **16.7%**.

Cancellation performance can be analyzed by:

- Payment Mode
- Region
- Time Period
- Product

### Regional Performance

Sales, profit, order volume and margin can be compared across:

- East
- West
- North
- South

### Time Trend

The dashboard provides a monthly view of sales and profit performance.

The reporting period contains a partial September period, so the September result should be interpreted accordingly.

### Dashboard Insights & Recommendations

![UrbanGlow Dashboard Insights](images/dashboard-insights.png)

---

## 6. Business Recommendations

Based on the analysis, management can consider:

1. Reviewing high-revenue but comparatively lower-margin products for pricing or cost optimization.
2. Investigating payment modes and regions with elevated cancellation rates.
3. Monitoring high-volume products whose profitability is comparatively weak.
4. Maintaining standardized Brand and Product master data for future reporting.
5. Investigating changes in monthly order volume while accounting for the partial September period.
6. Focusing regional improvement efforts on areas with weaker margins rather than evaluating regions only by sales volume.

---

## 7. Project Deliverables

| Deliverable | Description |
|---|---|
| Raw Excel Data | Original source transaction data |
| Cleaned Excel Data | Validated and analysis-ready dataset |
| HTML Dashboard | Interactive Sales & Profit Executive Dashboard |
| README | Project documentation and business explanation |

---

## 8. Project Workflow

```text
Client Requirements
        ↓
Raw Data
        ↓
Data Cleaning & Validation
        ↓
Data Transformation
        ↓
Business Analysis
        ↓
Interactive HTML Dashboard
        ↓
Key Insights
        ↓
Business Recommendations   
9. Technologies Used
- Microsoft Excel
- HTML
- CSS
- JavaScript
- Chart.js
- Data Cleaning & Transformation
- Business Intelligence
- Sales & Profit An
