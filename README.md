# Uber Ride Bookings Analytics Dashboard

Interactive Power BI dashboard analyzing Uber/NCR ride bookings — covering booking trends, revenue, cancellations, vehicle-type performance, and ratings.

## 📊 Dashboard Preview
Uber_Dashboard_Screenshots.docx

## 📁 Pages in This Dashboard

- **Home Page** — Landing page with navigation to all report sections
- **Overall** — Booking status breakdown, ride volume trend over time, and key summary metrics
- **Vehicle Type** — Total/success booking value, average and total distance travelled by vehicle category
- **Revenue** — Ride volume trend, revenue by payment method, and Top 5 Customers by booking value
- **Cancellation** — Cancellation breakdown by customer vs. by driver, with cancellation reasons
- **Ratings** — Customer and driver rating comparison across vehicle types

## 🛠️ Tools Used

- **Power BI** — Data modeling, DAX measures, and dashboard visualization
- **Power Query** — Data cleaning and transformation
- **Excel/CSV** — Source data preparation

## 📂 Data Source

NCR (Delhi-NCR) ride booking dataset for 2024 — 150,000 records including booking status, customer ID, vehicle type, pickup/drop location, booking value, ride distance, ratings, and payment method.

## 🔑 Key Insights

- Out of 150,000 total bookings, **93,000 (62%)** were successfully completed, while **18%** were cancelled by drivers and **7%** by customers
- Total booking value across completed rides was **₹5.18 crore (~₹51.8M)**, with an average booking value of **₹508**
- **Auto** had the highest total booking value (₹13M) and total distance travelled (625.62K) among all vehicle types
- **UPI** was the dominant payment method, generating ₹23M in bookings, more than double the next highest (Cash, ₹13M)
- Average driver rating stood at **4.23**, while average customer rating was slightly higher at **4.4**, consistent across vehicle types
- Cancellation split was fairly even between reasons on both sides — customer cancellations were led by "Wrong Address" (22.5%), while driver cancellations were spread almost equally across all four reasons (~25% each)
- The top 5 customers by total booking value contributed **₹22,434** combined, led by Customer CID2674107 (₹4,987)
