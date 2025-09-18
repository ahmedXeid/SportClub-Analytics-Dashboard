# 🏋️‍♂️ Sport Club Analytics Dashboard (Power BI)

## 📌 Overview
This Power BI dashboard provides insights into **membership, revenue, activities, and resource utilization** within a sports club.  
It is designed for **club managers** to monitor key performance indicators, improve decision-making, and optimize member engagement.  

---

## 🚀 Features

### 👥 Membership Insights
- Total members overview (active vs. inactive).  
- Age and gender distribution.  
- New vs. returning members trend.  

### 💰 Financial Analysis
- Revenue from memberships, activities, and additional services.  
- Monthly income trend line.  
- Profit breakdown by category.  

### 🏀 Activities & Engagement
- Participation by activity (football, swimming, tennis, gym, etc.).  
- Peak hours and facility utilization.  
- Retention analysis for long-term engagement.  

### 📊 Performance Metrics
- Membership growth over time.  
- Average revenue per member.  
- Attrition/retention indicators.  

### 🌍 Geographic Distribution
- Member locations visualized on a map (if available).  

---

## 🛠️ Technologies Used
- **Power BI**: Data visualization and dashboard creation.  
- **Excel / CSV**: Data preparation and cleaning.  

---

## 📂 Data Preparation
- **Dataset**: `Dataset.csv` (located in the `data` folder).  
- **Fields Included**:  
  - Member details (Name, Gender, Age, Join Date).  
  - Membership type (Basic, Premium, Family, etc.).  
  - Activity participation.  
  - Payment and revenue information.  
  - Location (optional).  

- **Data Cleaning Steps**:  
  - Calculated age from birthdate.  
  - Standardized membership categories.  
  - Added status classification: Active / Inactive.  
  - Created calculated columns for revenue analysis.  

---

## 📊 Visualizations

### **Overview Dashboard**
- Membership growth trend.  
- Revenue over time.  
- Gender and age breakdown.  

### **Financial Dashboard**
- Revenue by category (memberships, activities, extras).  
- Monthly income distribution.  
- Average revenue per member.  

### **Engagement Dashboard**
- Activity participation distribution.  
- Retention rate tracking.  
- Peak activity hours.  

### **Members Dashboard**
- Detailed list of members with filters for demographics, membership type, and activity participation.  
- Drill-down capability by department, age, or location.  

---

## 🔍 Interactive Features
- **Global Filters**: Membership type, status, location, gender.  
- **Clickable Visuals**: Select activity types or demographics to filter all visuals.  
- **Hover Tooltips**: Extra insights on each chart.  

---

## 🖼️ Screenshots

### Home Dashboard
![Home Dashboard](./screenshots/Home.PNG)

### Calculator Dashboard
![Calculator Dashboard](./screenshots/Calculator.PNG)

### Overall Dashboard
![Overall Dashboard](./screenshots/Overall.PNG)

### Members Dashboard
![Members Dashboard](./screenshots/Members.PNG)

---

## ▶️ Getting Started

1. Clone the repository:  
   ```bash
   git clone https://github.com/ahmedXeid/Sport-Club-Analytics-Dashboard.git
2. Open the Power BI file:

. Launch Power BI Desktop.

. Open SportClubDashboard.pbix.

3. (Optional) Replace dataset:

. Place your own data file in data/Dataset.csv.

. Update data source settings in Power BI.

⚡ Challenges & Solutions

Revenue Classification: Used conditional columns to separate revenue sources.

Retention Calculation: Created DAX measures to track returning vs. new members.

Standardization: Cleaned inconsistent activity/membership names.

📜 License

This project is licensed under the MIT License - see the LICENSE
 file for details.

✅ Conclusion

The Sport Club Analytics Dashboard in Power BI provides a comprehensive and interactive view of membership, revenue, and engagement metrics.
It helps managers make data-driven decisions to improve financial health, member satisfaction, and operational efficiency.
