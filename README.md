# Target - SQL Analytics & E-commerce Analysis

## 📚 Overview

This project analyzes Target Inc.'s e-commerce order data using advanced SQL techniques. The analysis focuses on understanding customer purchasing patterns, delivery logistics, and generating insights through data mining and statistical modeling approaches.

---

### **Business Problem**

- Analyze Target's e-commerce transaction patterns
- Understand customer behavior through order history analysis
- Identify key metrics for improving customer retention and satisfaction

---

### **Analysis Approach**

**Key Insights:**
- 📊 **Dataset Size**: 99,441 records across multiple tables
- 🔍 **Tables Analyzed**: 
  - `orders`: Order transactions (99,441 records)
  - `order_items`: Item details within orders
  - `customers`: Customer profiles
  - `products`: Product information
  - `payments`: Payment processing records
  - `geolocation`: Delivery location data
- 🎯 **Objective**: Extract insights for business decision-making using SQL analytics

---

### **Methodology Highlights**

| Aspect | Analysis | Result |
|--------|----------|--------|
| Total Records | 99,441 orders | Multi-table analysis |
| Tables | 6 tables (customers, orders, etc.) | Comprehensive dataset |
| Coverage | Nov 2016 - Sep 2018 | 2+ year historical data |

---

### **Data Structure**

```sql
-- Orders Table
SELECT * FROM orders;
-- Key columns: order_id, customer_id, order_status, order_purchase_timestamp

-- Order Items
SELECT * FROM order_items;
-- Links orders to specific products and quantities

-- Customers
SELECT * FROM customers;
-- Customer profile information for analysis

-- Products & Payments
-- Additional tables for comprehensive transaction analysis
```

---

### **Strategic Recommendations**

✅ **Order Analysis**: Implement SQL-based analytics for large-scale order processing  
✅ **Customer Segmentation**: Use order patterns to identify high-value customers  
✅ **Delivery Optimization**: Analyze geolocation data to improve last-mile delivery  

---

### **Business Impact**

SQL analytics enable Target to:
- Process millions of orders efficiently with SQL queries
- Understand customer purchasing behavior through pattern analysis
- Optimize delivery logistics using geolocation insights

---

*By Rahul Sharma | Business Analyst specializing in SQL analytics and e-commerce data mining*
