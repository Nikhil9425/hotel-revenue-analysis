# 🏨 Hotel Revenue & Performance Analysis (Power BI)

# 📌 Project Overview
This project focuses on analyzing hotel booking and revenue data for AtliQ Grands, a chain of five-star hotels operating across India. Due to increasing competition and suboptimal decision-making, AtliQ Grands has been experiencing a decline in market share and revenue in the luxury and business hotel segment.

To address this, the management decided to adopt Business Intelligence and Data Analytics. As a Data Analyst, I was tasked with building a Power BI dashboard using historical data to uncover actionable insights and support data-driven decisions.

# 🎯 Business Objective
- Analyze historical hotel booking data
- Create key hospitality performance metrics
- Build an interactive dashboard based on stakeholder mock-ups
- Identify additional insights beyond predefined metrics
- Provide recommendations to improve revenue, occupancy, and pricing strategy

# 🧩 Domain Knowledge: Hospitality
- Industry: Hospitality (Luxury & Business Hotels)
- Weekend: Friday & Saturday
- Weekday: Sunday to Thursday
- Pricing Nature: Highly elastic (demand & supply driven)

# 📊 Metrics Implemented (Level 1)
1. RevPAR (Revenue per Available Room)
   
Formula:
RevPAR = Total Revenue / Total Available Rooms
OR
RevPAR = ADR × Occupancy

Purpose: Measures how well a hotel fills its rooms at an average rate.

2. ADR (Average Daily Rate)

Formula:
ADR = Total Room Revenue / Total Rooms Sold

Explanation: Average price at which rooms are sold.

3. Occupancy %

Formula:
Occupancy = Total Rooms Occupied / Total Rooms Available

4. DSRN (Daily Sellable Room Nights)

Total rooms available for sale per day

5. URN (Utilized Room Nights)

Number of room nights where customers actually stayed

6. BRN (Booked Room Nights)
- Includes:
  - Stayed bookings
  - Cancelled bookings
  - No-show bookings

7. Realization

Formula:
Realization = URN / BRN

Purpose: Measures booking quality and cancellation impact.


# 🔄 Data Transformation & Modeling
- Data cleaning and transformation performed using Power Query
- Proper data modeling using:
- Fact tables (Bookings, Revenue)
- Dimension tables (Hotels, Dates, Rooms, Platforms)
- Relationships optimized for accurate time-based and hotel-level analysis

# 📈 Dashboard Features
- The Power BI dashboard includes:
- KPI Cards for RevPAR, ADR, Occupancy, Realization
- Trend analysis by date (weekday vs weekend)
- Hotel-level performance comparison
- Booking platform analysis (Online vs Offline)
- Occupancy vs Rating relationship

<img width="1136" height="700" alt="image" src="https://github.com/user-attachments/assets/d1232381-9e6a-46a1-ba53-b84c5dd5ce12" />

# 🔍 Key Insights & Business Learnings
## 1️⃣ Pricing Strategy Gap (Flat Pricing)
- ADR remains nearly constant over time
- RevPAR fluctuates mainly due to occupancy changes
- Indicates absence of dynamic pricing

📉 When demand increases (peak days), prices are not adjusted upward
📈 When demand drops, prices are not optimized to boost occupancy

Recommendation:
- Introduce dynamic pricing
- Separate weekday vs weekend pricing

<img width="1135" height="716" alt="image" src="https://github.com/user-attachments/assets/5196c3fa-46f1-4fac-b092-a951c85a9ff1" />

## 2️⃣ Pricing vs Occupancy Relationship
- No fixed formula for optimal pricing
- Observed pattern:
  - Price drop → Occupancy increase
  - Price hike → Occupancy decrease

This confirms elastic demand behavior in the travel & tourism industry.

## 3️⃣ Pareto Principle (80/20 Rule)
- ~80% of occupancy and revenue issues are driven by ~20% of hotels
- Low-performing hotels show:
 - Lower occupancy
 - Lower average customer ratings

<img width="1131" height="715" alt="image" src="https://github.com/user-attachments/assets/beb0543e-e78f-45e8-9a70-df83a30e8a4e" />

## 4️⃣ Impact of Ratings & Amenities
- Strong positive correlation between:
  - Average rating
  - Occupancy
Hotels with poor ratings:
- Need improvement in:
  - Service quality
  - Amenities
  - Guest experience

## 5️⃣ Booking Platform Insights
- Offline bookings have higher ADR
- Reason:
  - No third-party commission costs
  - Direct customer engagement
Strategy Suggestion:
- Encourage direct bookings with:
   - Loyalty programs
   - Website-exclusive offers

<img width="1133" height="715" alt="image" src="https://github.com/user-attachments/assets/56981d58-f529-4447-987a-6552ef1d96a6" />

## 🚀 Final Conclusion

This analysis highlights that pricing strategy, customer experience, and hotel-level performance optimization are key levers for improving revenue and occupancy. By adopting dynamic pricing, improving low-rated hotels, and boosting direct bookings, AtliQ Grands can regain market share and drive sustainable growth.

