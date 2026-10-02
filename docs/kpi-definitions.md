# KPI Definitions

This document defines the key performance indicators used in the E-Commerce Operations & Business Intelligence Dashboard.

## 1. Total Sales

**Definition:** Total net sales generated from all orders.

**Calculation:**

Total Sales = SUM(Net Sales)

**Dashboard Value:** Approximately ₹42.52M

---

## 2. Total Orders

**Definition:** Number of unique orders in the dataset.

**Calculation:**

Total Orders = DISTINCTCOUNT(Order ID)

**Dashboard Value:** 5,000 orders

---

## 3. Total Profit

**Definition:** Total profit generated from all orders.

**Calculation:**

Total Profit = SUM(Profit)

**Dashboard Value:** Approximately ₹7.71M

---

## 4. Average Order Value

**Definition:** Average net sales value generated per order.

**Calculation:**

Average Order Value = Total Sales / Total Orders

**Dashboard Value:** Approximately ₹8.50K

---

## 5. Return Rate

**Definition:** Percentage of orders that were returned.

**Calculation:**

Return Rate = Returned Orders / Total Orders

---

## 6. Cancellation Rate

**Definition:** Percentage of orders that were cancelled.

**Calculation:**

Cancellation Rate = Cancelled Orders / Total Orders

---

## 7. On-Time Delivery Rate

**Definition:** Percentage of completed orders delivered on time, excluding cancelled orders.

**Calculation:**

On-Time Delivery Rate =
On-Time Orders / (On-Time Orders + Delayed Orders)

**Dashboard Value:** Approximately 90.4%

---

## 8. Fulfillment Rate

**Definition:** Percentage of total orders that reached either an on-time or delayed delivery status.

**Calculation:**

Fulfillment Rate =
(On-Time Orders + Delayed Orders) / Total Orders

---

## 9. Profit Margin

**Definition:** Percentage of sales retained as profit.

**Calculation:**

Profit Margin = Total Profit / Total Sales

---

## 10. Processing Time

**Definition:** Number of days required to process an order before shipment.

The dashboard analyzes the average processing time across warehouses.

---

## 11. Delivery Time

**Definition:** Number of days taken to deliver an order.

The dashboard analyzes average delivery time across different shipping methods.

---

## 12. Customer Complaints

**Definition:** Number of orders associated with a recorded customer complaint.

Complaints are analyzed by product category to identify areas requiring customer-experience improvement.