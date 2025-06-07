#  Uber Trip Analysis Dashboard – Power BI Project

This project presents an interactive Power BI dashboard analyzing over **103K Uber trip records**, aimed at uncovering business insights to support data-driven decision-making. The solution covers booking trends, trip characteristics, revenue generation, vehicle type preferences, time-based analytics, and location behavior.

---

##  Key Metrics Overview

- **Total Bookings:** 103.7K  
- **Total Booking Amount:** $1.6M  
- **Total Trip Distance:** 349K miles  
- **Average Trip Distance:** 3 miles  
- **Average Trip Time:** 7.4 minutes  
- **Average Booking Value:** $15  

---

##  Payment Type Breakdown

| Payment Method | Amount   | Share      |
|----------------|----------|------------|
| Uber Pay       | $1.099M  | ≈70.74%    |
| Cash           | $443K    | ≈28.54%    |
| Amazon/Google Pay | Negligible |     |

**Insight:** Majority of users prefer in-app digital payment (Uber Pay), reducing cash handling complexity.

---

##  Trip Timing Analysis (Day vs Night)

- **Night Trips:** $975K (62.75%)  
- **Day Trips:** $579K (37.25%)  

**Insight:** High night-time demand—likely linked to commuting, nightlife, or lower public transit availability.

---

## Vehicle Type Analysis

| Vehicle       | Total Bookings | Booking Value | Avg Value | Trip Distance |
|---------------|----------------|----------------|-----------|---------------|
| UberX         | 38,744         | $583,880       | $15       | 131,496 miles |
| UberXL        | 16,698         | $249,424       | $15       | 55,721 miles  |
| Uber Comfort  | 17,078         | $253,995       | $15       | 56,790 miles  |
| Uber Green    | 14,498         | $216,184       | $15       | 48,778 miles  |
| Uber Black    | 16,710         | $250,192       | $15       | 56,690 miles  |

**Insights:**
- UberX dominates in volume and revenue.
- Average booking value is stable across types.
- Uber Green is underutilized — potential for eco-marketing.

---

## Location Analysis

- **Top Pickup Point:** Penn Station / Madison Sq West  
- **Top Drop-off Point:** Upper East Side North  
- **Farthest Trip:** Lower East Side ➝ Crown Heights North (144.1 miles)  
- **Shortest Trip:** Clinton East ➝ Midtown Center (1.0 mile)  

**Insight:** Popular pickup/drop-off zones align with commuting corridors; ideal for driver allocation strategies.

---

## Bookings Trend by Day

- Peak bookings on **Sunday (19.2K)** and **Saturday (18.7K)**
- Lowest on **Friday (9.3K)**

**Insight:** End-of-week activity is high; Friday dip could indicate opportunity for ride promotions or events.

---

## Most Preferred Vehicle by Pickup Locations

- UberX is the top choice across most pickup areas.

**Insight:** Combines cost-effectiveness and availability, making it the preferred option for most riders.

---

## Time-Based Demand Insights

### Slicer: Dynamic Measure Selection
- Total Bookings
- Total Booking Amount
- Total Trip Distance

### Time of Day Insights:
- **Demand peaks between 2 PM – 5 PM**
- **Low traffic during early morning hours (12 AM – 5 AM)**

### Day of Week Patterns:
- **Weekends lead across all KPIs**
- Friday is consistently the **lowest performer**

### Heatmap Highlights:
- Midday to evening shows **dense booking patterns**
- Supports optimizing **driver shifts and pricing strategy**

---

## Details Dashboard – Drill-Through Functionality

This tab offers a detailed **trip-level table** filtered dynamically based on user interactions from other dashboards.

### Drill-Through Enabled On:
- Location (Pickup / Drop-off)
- Vehicle Type
- Slicer selections (Date, City)

### Fields Displayed:
- Trip ID, Pickup Date & Time
- Vehicle Type, Payment Type, Passenger Count
- Trip Distance, Total Amount
- Pickup Location, Drop-off Location, Total Bookings

### Use Case:
“Which UberX trips were made in Upper East Side on Saturday?”  
Drill-through lets users answer questions like this with one click.

**Insight:** Enables transparency and traceability of KPIs back to raw data — ideal for analysts, managers, and auditors.

---



## Conclusion

This Power BI solution offers a **360° view** of Uber trip operations. From high-level KPIs to transaction-level drill-through, it enables users to:

- Understand **rider behavior** by time, payment, and location
- Identify **vehicle performance** and market share
- Highlight **operational bottlenecks or demand peaks**
- Dive into **raw trip records** behind summary metrics

---

## Enhancement Recommendations

- **Expand UberX Fleet**: Based on high demand
- **Incentivize Day Trips**: Balance usage between Day/Night
- **Geo-Target Promotions**: High activity areas like Penn Station
- **Promote Uber Green**: Offer discounts to boost usage
- **Enable Raw Data Export**: Add Power Automate button for CSV/Excel export
- **Add Reset Slicer Button**: Improve UX with a 1-click reset option
- **Add Mapping Visuals**: Plot pickup/drop-off points on maps for geographic insight






