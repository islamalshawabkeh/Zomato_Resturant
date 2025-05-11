# Zomato_Resturant
# 🍽️ Zomato Power BI Dashboard

## 📘 Project Overview

This Power BI dashboard project analyzes Zomato's restaurant data to deliver actionable insights on restaurant performance, customer feedback, pricing trends, and cuisine diversity. The interactive visualizations support data-driven decisions for restaurant operators, marketers, and analysts.

---

## 🏢 About Zomato

Zomato is a global restaurant discovery and food delivery platform that offers detailed listings, reviews, and services for millions of users. Established in 2008, Zomato provides rich data on dining preferences and trends across countries.

---

## 🎯 Objectives

- Build an interactive dashboard visualizing key Zomato metrics.
- Deliver insights into restaurant locations, ratings, cuisines, pricing, and order patterns.
- Enable better decision-making using clean, connected data and engaging visuals.

---

## 📁 Datasets Used

| Dataset Name          | Description |
|-----------------------|-------------|
| `restaurant.xlsx`     | Restaurant details: name, location, services, and ratings. |
| `menu.xlsx`           | Menu items, dish names, availability, and pricing. |
| `orders.xlsx`         | Order types (dine-in, delivery, takeaway), and order frequency. |
| `reviews.xlsx`        | Customer reviews, feedback, and average ratings. |
| `cuisines.xlsx`       | Cuisine types offered by restaurants. |

---

## 🔧 Data Preparation

### Cleaning
- Removed duplicates and formatting errors.
- Standardized inconsistent entries (e.g., fixed `"Sí£o Paulo"` to `"São Paulo"`).

### Transformation
- Normalized data by separating cuisines and services into dimension tables.
- Created calculated columns for full addresses and cleaned service types.

### Relationship Mapping
- Linked tables by `restaurant_id`, `cuisine_id`, etc. for efficient data modeling.

---

## 📊 Key Metrics & Visualizations

| Metric | Description |
|--------|-------------|
| **Total Restaurants** | Count by country, city, and locality. |
| **Average Ratings** | Identify best- and worst-rated restaurants. |
| **Cuisine Variety** | Restaurants with the widest cuisine offerings. |
| **Order Trends** | Frequency and type of customer orders. |
| **Average Cost** | Price comparison across cities and restaurant types. |

---

## 🖥️ Dashboard Pages

1. **Overview** – Global stats, top cities, and restaurant count.
2. **Customer Insights** – Reviews, sentiment, and rating analysis.
3. **Cuisine & Orders** – Top cuisines and ordering behavior.
4. **Affordability** – Pricing trends and value-for-money metrics.

---

## 🔍 Filters & Interactivity

- Filter by **country**, **city**, **rating**, **cuisine type**, and **services**.
- **Drill-through** into restaurant-specific trends and customer feedback.
- **Map visualizations** for geographic restaurant spread.

---

## ⚙️ Technical Implementation

- **Tool**: Power BI Desktop  
- **Modeling**: Star schema with dimension and fact tables  
- **DAX**: Used for measures like Avg Rating, Cost per Cuisine, Order Count  
- **Custom Design**: Visual theme aligned with Zomato’s color palette and fonts

---

## 📦 Deliverables

- ✅ `ZomatoDashboard.pbix` file  
- ✅ Documentation of data cleaning and model relationships  
- ✅ User guide for dashboard navigation  

---

## 🗓️ Project Timeline

| Week | Milestone |
|------|-----------|
| 1    | Data collection and cleaning |
| 2    | Transformation & model setup |
| 3    | Dashboard layout & visualizations |
| 4    | Testing, user feedback, and deployment |

---

## 📌 Conclusion

This Power BI dashboard empowers Zomato stakeholders to monitor restaurant performance, uncover customer preferences, and respond quickly to market trends. It is designed to be scalable and intuitive for both daily operational use and executive reporting.

---

## 👤 Author

**[ISLAM ALSHAWABKEH]**  
Email: [islamshawabkeh12@gmail.com]  
LinkedIn: [www.linkedin.com/in/islamalshawabkeh] 
##
**[ FOR QUICK VIEW OPEN PFD FILE]** 

