# Cocacola 

# **COCACOLA**

## **Table of Contents**

- [Project Overview](project_overview)
- [Data Source](data_source)
- [Tools Used](tools_used)
- [Data Cleaninig](data_cleaning)
- [Exploratory Data Analysis (EDA)](exploratory_data_analysis_(EDA))
- [Data Analysis](data_analysis)
- [Data Insights](data_insights)
- [DAX Used in Power Query](dax_used_in_power_query)
- [Results of DAX](results_of_dax)
- [Recommendations](recommendations)
- [Conclusion](conclusion)
- [Future enhancements](future_enhancements)
---

### **Project Overview**

This project provides an analytical overview of Coca-Cola's sales performance in 2024. It visualizes key revenue trends across countries, sales channels, product categories, and distributors to help identify growth opportunities and optimize business strategies.

### **Data Source**
The data is soucre from Coca-Cola's sales records, including international sales, various distribution channels, and product inventory.

### **Tools Used**
The dashboard likely used Power BI or Tableau for visualization, Excel or SQL for data manipulation, and DAX for calculations.

### **Data Cleaning**
- Handled Missing Data: Any null values in revenue, sales channels, or product names were removed or replaced.
- Standardized Data Formats: Ensured uniform currency, date formats, and categorical data consistency.
- Filtered Outliers: Unusual revenue spikes or missing distributor names were addressed.

### **Exploratory Data Analysis (EDA)**
1. **Revenue by Countries**
   **- Highest Revenue:** Malawi (₦3.0K), followed by Canada (₦2.9K) and Burkina Faso (₦2.8K).
   **- Lowest Revenue:** Tanzania (~₦1.8K).
**Observation:** African and North American regions contribute significantly to revenue.

**2. Revenue by Sales Channel**
     - Retail (45.8%) is the dominant sales channel.
     - Direct Sales (41.6%) is slightly behind retail.
     - Online Sales (12.5%) has the lowest share.
**Observation:** Coca-Cola’s online presence is underutilized, representing an opportunity for digital sales expansion.

**3. Product by Quantity**
    - Schweppes leads sales with 1,444 units, followed by Monster (1,008 units).
    - Limca (407 units) has the lowest quantity sold.
**Observation:** Schweppes is the most preferred product, while Limca requires a marketing push.

**4. Revenue by Distributor Name**
     - **Top distributors:** Devin Abbott (₦3.0K) and Aphrodite Brennan (₦2.9K).
     - **Lowest revenue distributors:** Levi Douglas & Jelani Warner (₦1.8K).
**Observation:** Stronger partnerships with high-performing distributors could improve overall sales.

### **Data Analysis**
    **- Revenue Trends:** African and North American markets are strong performers.

    **- Sales Channel Efficiency:** Retail is the most effective channel, while online sales lag behind, suggesting potential for digital strategy improvement.

    **- Product Popularity:** Schweppes is a top seller, indicating a need to boost marketing for less popular products like Limca.

### **Data Insights**
    - Focusing on high-revenue countries could drive growth.
    - Enhancing online sales channels may increase market share.
    - Exploring partnerships with top distributors could amplify sales efforts.

### **DAX Used in Power Query**
    - Total Revenue: SUM(Sales[Revenue])
    - Top Country Revenue: TOPN(1, Sales, Sales[Revenue], DESC)
    - Sales by Channel: CALCULATE(SUM(Sales[Revenue]), Sales[Channel] = "Retail")

### **Results of DAX**
    - Successfully aggregated revenue across different dimensions.
    - Identified top-performing products and distributors.
    - Provided insights into sales channel efficiency.

### **Recommendations**
    - Expand Online Sales Channels – Increase marketing and partnerships for e-commerce sales.
    - Boost Low-Performing Products – Consider promotions or rebranding for Limca and other underperforming drinks.
    - Focus on High-Performing Regions – Strengthen distribution in Malawi, Canada, and Burkina Faso.
    - Leverage Top Distributors – Offer incentives for high-performing distributors to increase their sales.



### **Conclusion**
The dashboard highlights Coca-Cola’s strong presence in Africa and North America, the dominance of retail sales, and the opportunity to expand digital channels. By leveraging top-performing distributors and optimizing product strategy, Coca-Cola can drive further revenue growth.

### **Future Enhancements**
   - Incorporate real-time sales tracking.
   - Implement predictive analytics for demand forecasting.
   - Conduct sentiment analysis on customer preferences.
