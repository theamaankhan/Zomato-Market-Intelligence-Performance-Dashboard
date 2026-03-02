# 🍽️ Zomato Market Intelligence & Performance Dashboard
## 📌 Project Overview
- This project is an extension of my earlier Python-based EDA project (Zomato-Restaurant-Market-Analysis) and transforms exploratory insights into a strategic, executive-level Business Intelligence dashboard using Power BI.
- The dashboard analyzes 9545 restaurants across 15 countries and 141 cities, focusing on service penetration, pricing distribution, cuisine segmentation, and geographic concentration to uncover expansion opportunities and operational gaps.

## 📂 Dataset
The dataset used for this analysis is included within this repository.

- 📊 Total Records: 9545 restaurants
- 🌍 Coverage: 15 countries | 141 cities
- 📌 Source: Public Zomato Restaurants Dataset

🔗 Direct Access:
[Dataset 1](Dataset/zomato.csv)
[Dataset2 ](Dataset/Country-Code.csv)


## 📊 Dashboard Overview
The dashboard is divided into two strategic layers:

1️⃣ Executive Overview-
Provides a macro-level understanding of scale, service enablement, and customer experience.

🖼️ Screenshot
<p align="center">
  <img src="Images/Zomato Dashboard image 1.png" width="800"/>
</p>

### 🔑 Key KPIs Displayed
- Total Restaurants: 9.5K+
- Total Cities: 141
- Total Countries: 15
- Average Rating: 3.4★
- Delivery Penetration: 25.7%
- Booking Penetration: 12.1%

### 📈 Key Executive Insights
- Despite strong geographic scale, only 25.7% of restaurants are delivery-enabled, and just 12.1% support reservations — indicating substantial service expansion headroom.
- Customer ratings cluster around “Average” and “Good,” highlighting stable but non-premium customer experience.
- Ultra-Premium segments drive bookings, while Mid-Range and Budget segments dominate delivery behavior.

2️⃣ Pricing & City-Level Insights
Provides micro-level segmentation of pricing power, supply concentration, and cuisine dominance.

🖼️ Screenshot
<p align="center">
  <img src="Images/Zomato Dashboard image 2.png" width="800"/>
</p>

### 🔑 Key KPIs Displayed
- Median Cost for Two (City-wise)
- Reservation Enablement % by City
- Delivery Enablement % by City
- Restaurant Count by City
- Cuisine × Price Category Matrix (9545 total restaurants segmented)

### 📊 Key Strategic Insights
- Restaurant supply is heavily concentrated in the New Delhi NCR region, creating geographic dependency risk.
- Emerging tier-2 cities like Mohali show ~100% delivery enablement despite lower restaurant volumes — indicating operational scalability outside metros.
- Budget & Mid-Range North Indian, Chinese, and Fast Food cuisines drive platform volume.
- Premium & Ultra-Premium tiers are anchored by North Indian, Chinese and Italian cuisines — revealing a clear mass-volume vs premium-value segmentation dynamic.
- High-spend but low-supply cities emerge as potential expansion targets.

🎯 Business Questions Answered
- Where is restaurant supply geographically concentrated?
- What is the true penetration of delivery and booking services?
- Which cuisines dominate volume vs premium pricing tiers?
- Are there cities with pricing power but limited supply?
- Where should expansion efforts be prioritized?

## 🛠️ Tools & Technologies
- Power BI Desktop
- DAX (custom measures for penetration & benchmarking)
- Data Modeling & Relationship Management
- Interactive Filtering & Cross-Page Drill

## 💡 Skills Showcased
This project was a deep dive into advanced Business Intelligence and strategic dashboard development. Here’s what was mastered:
- ⚙️ Data Modeling & Structuring: Built a relational data model connecting countries, cities, cuisines, and price tiers to enable dynamic cross-filtering and segmentation.
- 🧮 DAX Measures & Benchmarking: Created custom measures for Delivery Penetration, Booking Penetration, Median Cost, and benchmarking calculations (Median vs Average) to identify pricing skew and service gaps.
- 📊 Advanced Visual Analytics: Designed Column, Bar, Donut, Scatter, and Matrix visuals to analyze pricing distribution, cuisine dominance, and city-level concentration.
- 🗺️ Geographic Intelligence: Used map-based visualization to assess country and city-level restaurant distribution and identify geographic dependency risks.
- 📈 Penetration & Segmentation Analysis: Measured service enablement (Delivery & Booking %) across price tiers and cities to uncover monetization headroom.
- 🔢 KPI Framing & Executive Metrics: Structured key performance indicators (Total Restaurants, Rating, Service Penetration) for executive-level readability.
- 🎨 Dashboard UX & Visual Hierarchy: Designed a clean, professional layout with consistent color themes, visual prioritization, and strategic insight placement.
- 🖱️ Interactive Reporting Features:
  -  Slicers: Enabled dynamic filtering by country, city, cuisine, and price category.
  - Cross-Filtering: Allowed real-time interaction across visuals for deeper analysis.
  - Drill-Down: Enabled city-level and price-tier level exploration for granular insights.
- 📊 Business Insight Translation: Transformed raw restaurant data into strategic recommendations around expansion, service enablement, and pricing segmentation.


## 📈 Analytical Enhancements Beyond EDA
This project goes beyond descriptive analysis by:
- Converting static EDA findings into interactive BI insights
- Benchmarking delivery vs booking penetration
- Identifying supply-demand mismatches
- Segmenting cuisine performance across price tiers
- Highlighting expansion-ready markets

## 🎓 Learning Outcomes
- Learned to structure dashboards for executive decision-making.
- Strengthened DAX skills for penetration and benchmarking calculations.
- Improved ability to synthesize multi-dimensional data into strategic narratives.
- Enhanced visual hierarchy and data storytelling for business stakeholders.

## 🚀 Business Implications
- Service Expansion Opportunity: With only 25.7% delivery and 12.1% booking penetration, enablement strategy can drive incremental growth.
- Geographic Diversification: Heavy NCR concentration suggests need for balanced expansion.
- Premium Strategy: Italian and premium North Indian segments present margin-focused opportunities.
- Operational Scalability: Tier-2 cities demonstrate readiness for platform growth.

## 🏁 Conclusion
- This dashboard transforms raw restaurant data into a strategic market intelligence tool. By quantifying service gaps, pricing distribution, and geographic concentration, It highlights both saturation risks and expansion opportunities.
- The project demonstrates the ability to move from exploratory analysis to executive-level business insight — a key capability for data analyst and BI roles.

## 👤 Author
Amaan Khan Aspiring Data Analyst | Power BI | Data Visualization | Analytics

📧 Email: amaankhanamaan8@gmail.com 🔗 LinkedIn: www.linkedin.com/in/theamaan-khan
