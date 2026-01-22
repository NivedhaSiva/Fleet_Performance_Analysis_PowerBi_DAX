# 🚚 Fleet Performance & Delivery Efficiency Dashboard (Power BI)

A full‑scale analytics project designed to evaluate fleet productivity, fuel efficiency, and operational costs using logistics trip data.  
This dashboard integrates **Trip_Data** and **Vehicle_Master** tables to uncover insights into delivery reliability, driver performance, and vehicle cost efficiency.

---

## 📌 Project Objective
- Measure **vehicle efficiency** across trips.
- Identify **cost‑heavy assets** (high maintenance or poor fuel efficiency).
- Analyze **driver performance** and delivery reliability.
- Provide actionable insights for **fleet optimization and cost reduction**.

---

## 🛠️ Tools & Techniques
- **Power BI** → Interactive dashboard development, KPI cards, Key Influencers visual, decomposition trees.
- **Power Query** → Data cleaning, transformation, and relationship modeling.
- **DAX** → Custom calculations including:
  - `Cost per km = (Fuel_Consumed × Fuel Price + Maintenance Cost) ÷ Distance`
  - `Total Distance by Vehicle Type`
  - `On‑Time Delivery % by Destination`
- **Data Modeling** → One‑to‑many relationship between Vehicle_Master and Trip_Data for aggregation.

---

## 📊 Dashboard Components
- **Fleet Overview** → Trip counts, destinations, delivery status distribution.
- **Key Influencers** → Explains factors influencing On‑Time vs Late deliveries (Driver_ID, Distance_km, Vehicle_Type).
- **Cost Analysis**  
  - Maintenance cost distribution by vehicle type (Trucks highest, Vans moderate, Mini‑Trucks lowest).  
  - Average cost per km comparison across vehicle types.
- **Driver Insights**  
  - Driver D03 shows 1.83× higher likelihood of On‑Time deliveries.  
  - Productivity varies significantly across drivers.
- **Delivery Reliability**  
  - On‑Time delivery rate ~60%.  
  - Delhi & Pune destinations had the highest number of on‑time trips.
- **Fuel Efficiency Trends**  
  - Efficiency tracked by delivery date, highlighting fluctuations across January–February.

---

## ⭐ Key Insights
- **Maintenance Costs**: Trucks account for the largest share of maintenance expenses (up to 18K), impacting profitability.
- **Fuel Efficiency**: Vans show better cost/km ratios (~27.25) compared to Trucks (~30.23), making them more efficient for medium‑distance trips.
- **Driver Performance**: Driver D03 consistently delivers on time, while others show late patterns linked to longer routes.
- **Delivery Reliability**: Longer distances and certain vehicle types increase the likelihood of late deliveries.
- **Destination Analysis**: Delhi and Pune had the highest on‑time delivery counts, while Hyderabad and Chennai lagged.

---

## 📂 Dataset Schema
**Trip_Data**
- Trip_ID  
- Vehicle_ID  
- Driver_ID  
- Origin  
- Destination  
- Distance_km  
- Fuel_Consumed_L  
- Delivery_Status  
- Delivery_Date  

**Vehicle_Master**
- Vehicle_ID  
- Vehicle_Type  
- Capacity_kg  
- Maintenance_Cost  

---

## 📸 Dashboard Preview
![Fleet Performance Dashboard](images/Fleet_Performance.png)

---

## 👩‍💻 Author
**Nivedha Sivakumar**  
Data Analyst | Power BI & AI Practitioner  
- GitHub: [nivedha-sivakumar-git](https://github.com/nivedha-sivakumar-git)  
- LinkedIn: [Nivedha Sivakumar](https://linkedin.com/in/nivedha-sivakumar)  

---

## 🚀 How to Use
1. Clone the repository.  
2. Open the `.pbix` file in Power BI Desktop.  
3. Explore visuals, DAX measures, and relationships.  
4. Modify dataset or visuals for your own fleet analysis.

---

