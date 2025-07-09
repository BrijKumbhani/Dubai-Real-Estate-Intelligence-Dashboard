# 🏙️ Dubai Real Estate Intelligence Dashboard

Welcome to the **Dubai Real Estate Intelligence Dashboard** – an interactive Power BI project that uncovers deep insights into the Dubai housing market using real-world housing data. Built as part of my Business Analyst internship, this project focuses on data-driven decision-making for investors, agents, and policymakers.

---

## 📊 Project Objective

To design a professional and dynamic Power BI dashboard that delivers actionable insights into Dubai’s residential real estate landscape — including pricing trends, property size distribution, age profiling, and category-based segmentation.

---

## 📁 Dataset Overview

The dataset includes the following fields:

- `SquareFeet`: Size of the property (in sqft)
- `Bedrooms`: Number of bedrooms
- `Bathrooms`: Number of bathrooms
- `Neighborhood`: Urban/Suburb/Rural classification
- `YearBuilt`: Year the property was constructed
- `Price`: Selling price of the property

### 🔧 Enriched Columns (Calculated using DAX):
- `PricePerSqft = Price / SquareFeet`
- `PropertyAge = 2025 - YearBuilt`
- `ListingCategory = Budget / Mid-Range / High-End (based on price quantiles)`

---

## 📌 Features of the Dashboard

### 🔹 Key Metrics (KPI Cards)
- Total Listings  
- Average Price  
- Average Price per Sqft  
- Average Property Size  
- Highest Property Price  

### 🔹 Interactive Visuals
- 📍 **Bar Chart**: Sum of SquareFeet by Neighborhood  
- 📈 **Line Chart**: Average Price by Property Age  
- 🧮 **Scatter Plot**: SquareFeet vs PricePerSqft by Listing Category  
- 🧱 **Stacked Column Chart**: Price by Bedrooms and Listing Category  
- 🌍 **Tree Map**: SquareFoot distribution by Neighborhood & Category  
- 🕑 **Histogram**: PropertyAge distribution (binned)

### 🔹 Slicers (User-Controlled Filters)
- Neighborhood  
- Bedrooms  
- Bathrooms  
- Listing Category  
- Price Range  

---

## 🧠 Insights Uncovered

- **Urban areas dominate high-end listings**, while suburbs mostly house mid-range and budget properties.
- **Most properties are under 10 years old**, indicating a modern housing inventory.
- **Strong correlation** between property size and price, with high-end outliers skewing higher.
- **Apartments and villas** are the most common property types across categories.
- **Price per sqft varies by area**, confirming the impact of location on property valuation.

---

## ✅ Technologies Used

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query for data transformation**
- **Microsoft Excel (pre-processing)**

---

## 📥 Deliverables

- `Dubai Real Estate Intelligence Dashboard.pbix`: Fully interactive Power BI file
- Summary Slide (PowerPoint): Business Questions, Key Takeaways, and Strategic Recommendations
- Explanatory Video (optional for viewers): Full walkthrough of the dashboard and insights

---

## 🧠 What I Learned

- Advanced data modeling using DAX  
- Effective dashboard storytelling and user experience  
- Data cleaning and enrichment via Power Query  
- Real-world business problem-solving through visual analytics

---

## 🚀 Author

**Brij Kumbhani**  
Business Analyst Intern | Power BI Developer  
🔗 LinkedIn: https://www.linkedin.com/in/brij-kumbhani/  
📫 Email: brijkumbhani162@gmail.com  

---

## 🌟 Live Preview / Demo

> 📽️ Coming soon: Link to explanatory video walkthrough  
> 📁 Download `.pbix` file from this repository to explore the dashboard on your machine

---

