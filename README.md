# Uber Ride Hailing Analytics | Power BI

**Advanced Uber Trip Analysis Dashboard for Ride-Hailing Operations**

<img width="886" height="491" alt="image" src="https://github.com/user-attachments/assets/56a10343-bd8d-43a6-8320-e648db1fd138" />


A comprehensive **Power BI** dashboard analyzing **104,000+ Uber trips** worth **$1.6 Million** in total booking value. This project showcases deep ride-hailing analytics, demand pattern recognition, and actionable business insights — directly transferable to companies 

---

## 🎯 Project Objective

To extract meaningful operational and strategic insights from Uber trip data to optimize fleet management, pricing strategy, driver allocation, and revenue growth in urban ride-hailing markets.

---

## 📊 Key Business Insights

- **Night trips** represent **65.28%** of total bookings with strong peak between **6 PM – 11 PM**
- **UberX** is the top performing vehicle type (**38,744 trips**, **$583K** revenue)
- Average trip distance is only **3 miles** — typical high-frequency urban mobility pattern
- Significant **weekend demand surge** (Saturday & Sunday)
- Major hotspots identified: **Upper East Side North** & **Penn Station / Madison Square West**
- **Uber Pay** dominates payment methods with **67%** market share

---

# 🚀 Key Business Insights (The Strategy)
I focused my analysis on three core pillars: Demand Heat, Fleet Efficiency, and Fintech Adoption.

## 1. Temporal Demand & Peak Management
The Weekend Surge: Data shows a significant spike in bookings on Saturdays and Sundays. Unlike the double-peak (morning/evening) of weekdays, weekend demand remains consistently high throughout the afternoon.

- The 6 PM Bottleneck: Bookings begin to climb at 3 PM and reach a daily zenith between 6:00 PM and 8:00 PM.

- Strategic Recommendation: Implement "Demand-Based Incentives" for drivers during this window to prevent high cancellation rates.

## 2. Fleet & Product Mix
 - UberX is the Volume King: With 38,744 bookings, UberX handles the bulk of the traffic. However, Uber Comfort and Uber Black maintain       higher average booking amounts (~$15.0), suggesting they are more profitable per mile.

- Distance vs. Value: The average trip distance is 3 miles with a $15.0 average fare. This suggests a high-density urban environment         where short-distance, high-frequency trips are the primary revenue driver.

## 3. Geospatial High-Traffic Zones
- Top Pickup: Penn Station/Madison Sq West (4.5K bookings). This indicates transit hubs are the lifeblood of the platform.

- Top Drop-off: Upper East Side North.

- Strategic Recommendation: Pre-positioning drivers near transit hubs 20 minutes before peak commute times can reduce Estimated Time of Arrival (ETA) by an estimated 15-20%.

## 4. Payment Ecosystem (Fintech Integration)
- Digital Dominance: 67% of users pay via Uber Pay, while 32% still use Cash.

- Insight: In a market like Bangladesh, converting that 32% cash segment to digital (e.g., Pathao Pay) reduces friction for drivers and improves the platform's liquidity.

## 🛠️ Technical Implementation
- Data Modeling: Built a Star Schema to handle 100k+ rows efficiently.

- DAX Engineering: Created custom measures for:

- GMV (Total Booking Value)

- Avg Trip Time (15-16 mins across vehicle types)

- Dynamic Time Slicing (Day vs. Night shifts)

- Visualizations: * Heat Map: A 24-hour/7-day matrix to identify supply-demand gaps.

- Vehicle Performance Table: Ranking fleet types by revenue density.

## 📊 Dashboard Previews
I. Overview (Executive Level)
A bird's-eye view of revenue, total miles (349K), and booking volume. Perfect for monitoring monthly KPIs.

II. Time Analysis (Operational Level)
A deep dive into hourly trends and "Day Name" distributions to help ops teams manage driver shifts.

III. Trip Details (Tactical Level)
The granular "Ground Truth"—allowing for audit-level analysis of individual Trip IDs, payment types, and passenger counts.


## ✨ Key Features

- Executive KPI Dashboard
- Deep Time & Demand Analysis (Hourly + Heatmap)
- Vehicle Performance Breakdown
- Geospatial Hotspot Analysis
- Payment Behavior Insights
- Full Transactional Details Page

---

## 🛠 Tech Stack

- **Power BI Desktop**
- **DAX** (Advanced Measures & Calculations)
- **Power Query** (Data Modeling & ETL)
- Star Schema Design

---

## 📁 Repository Structure

```bash
Uber-Ride-Hailing-Analytics-PowerBI/
├── Uber_Trip_Analysis.pbix
├── data/
│   └── uber_trips.csv
├── screenshots/
│   ├── overview.png
│   ├── time-analysis.png
│   └── details.png
├── README.md
└── insights.md
```
## 📷 Screenshots
<img width="375" height="187" alt="image" src="https://github.com/user-attachments/assets/22e22bdd-70d5-446a-be1d-e65b75b27e28" />
<img width="812" height="491" alt="image" src="https://github.com/user-attachments/assets/299e0d11-fb7e-4185-82ff-8ccf9ea33707" />

<img width="410" height="323" alt="image" src="https://github.com/user-attachments/assets/d8f4da76-bc30-46d1-8466-5cb49847d3fd" />

## 🎯Potential Use Cases

- Uber fleet operators optimizing vehicle deployment
- City transportation planners
- Data analysts practicing Power BI + DAX skills
- Ride sharing company

🔮 Future Enhancements

- Driver performance analytics
- Customer segmentation
- Predictive demand forecasting
- Integration with real-time Uber API data
- Mobile-responsive view

---

## 🙏 Acknowledgments

I would like to extend my heartfelt thanks to [Data Tutorial](https://www.youtube.com/watch?v=b3oIdJ3ZiTU&t=4427s ) for their incredible Power BI tutorials.  

Your step-by-step guidance on dashboard design, DAX measures, time intelligence, and business-oriented analytics played a major role in the successful completion of this **Uber Ride Hailing Analytics** project. 

Thank you for consistently delivering high-value content that helps aspiring data analysts build real-world projects like this one.

---

**Made with ❤️ and powered by great learning resources**

***Made with ❤️ using Power BI***   

Feel free to fork this project, improve it, or use it as a template for your own ride-sharing analytics dashboard!
Star ⭐ this repo if you found it helpful!




