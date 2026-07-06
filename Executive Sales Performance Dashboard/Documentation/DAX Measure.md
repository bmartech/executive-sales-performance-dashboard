
# DAX Measures Documentation

## Project Overview

This document describes the key DAX measures used in the Executive Sales Performance Dashboard. These measures were created to calculate KPIs, compare performance over time, and generate dynamic business insights.

---

## Total Revenue

```DAX
Total Revenue = SUM(Orders[Revenue])
```

**Purpose:** Calculates the total revenue generated from all sales.

---

## Total Profit

```DAX
Total Profit = SUM(Orders[Profit])
```

**Purpose:** Calculates the total profit generated from all sales.

---

## Total Orders

```DAX
Total Orders = DISTINCTCOUNT(Orders[OrderID])
```

**Purpose:** Counts the total number of unique orders.

---

## Total Customers

```DAX
Total Customers = DISTINCTCOUNT(Orders[CustomerName])
```

**Purpose:** Counts the total number of unique customers.

---

## Total Units Sold

```DAX
Total Units Sold = SUM(Orders[Quantity])
```

**Purpose:** Calculates the total quantity of products sold.

---

## Average Order Value

```DAX
Average Order Value =
DIVIDE([Total Revenue], [Total Orders])
```

**Purpose:** Calculates the average amount spent per order.

---

## Repeat Purchase Rate

**Purpose:** Measures the percentage of customers who made more than one purchase.

---

## Customer Churn

**Purpose:** Measures the percentage of customers who did not return during the selected period.

---

## Revenue Change (%)

**Purpose:** Compares current revenue with the previous month to determine growth or decline.

---

## Dynamic Business Insight

**Purpose:** Generates automatic business insights based on dashboard KPIs, helping users quickly understand sales performance without manually interpreting charts.

---

## Dashboard KPIs

- Total Revenue
- Total Profit
- Total Orders
- Total Customers
- Total Units Sold
- Average Order Value
- Repeat Purchase Rate
- Customer Churn
- Revenue Change (%)

---

## Author

**Martins F. Balogun**  
Data Analyst | Power BI Developer