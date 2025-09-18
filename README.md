# 🏋️‍♂️ Sport Club Analytics Dashboard (Power BI)

## 📌 Overview
This Power BI dashboard provides insights into **membership, payments, health tracking, and expenses** of a sports club.  
It helps **managers and trainers** monitor revenue, member goals, trainer allocation, and club performance.  

---

## 🚀 Features

### 👥 Membership & Demographics
- Active vs. inactive users.  
- Age & gender distribution.  
- Membership type breakdown (Basic, Premium, Family, etc.).  
- Trainer assignments and goals.  

### 💳 Payments & Revenue
- Track payments by date, mode (cash, card, transfer), and status.  
- Monthly revenue trends.  
- Average revenue per user.  

### 💰 Expenses
- Expense categories (staff, maintenance, utilities, etc.).  
- Compare revenue vs. expenses.  
- Profitability insights.  

### 📏 Health & Progress
- Track BMI, height, starting weight.  
- Compare user goals vs. current status.  
- Identify members at health risk.  

### 🎨 Consistent Visuals
- **ColorCodes** table ensures a unified design system across dashboards.  

---

## 🛠️ Technologies Used
- **Power BI**: Dashboard and visualization.  
- **Excel/CSV**: Data source preparation (`Dataset.csv`).  

---

## 📂 Data Preparation

The dataset is organized into **4 main tables**:

1. **Users**  
   - Fields: `UserID, UserName, Age, Gender, JoinDate, Goal, Trainer Name, Membership, MembershipStart, MembershipEnd, Status, Height_cm, StartingWeight, BMI`  
   - Description: Contains personal, health, and membership details of each user.  

2. **Payments**  
   - Fields: `UserID, PaymentDate, Amount, Mode, Status`  
   - Description: Tracks all member payments, payment method, and payment status.  

3. **Expenses**  
   - Fields: *(category, amount, date, description)*  
   - Description: Records sports club expenses.  

4. **ColorCodes**  
   - Fields: *(metric, hex color)*  
   - Description: Defines consistent theme colors for visuals.  

---

## 📊 Dashboards

### **Home Dashboard**
- Quick KPIs (Total Members, Active Users, Monthly Revenue, Expenses).  
- Revenue vs. Expenses comparison.  
- Membership distribution.  

### **Calculator Dashboard**
- Health calculator for BMI, progress, and fitness goals.  
- User-level details to track improvements.  

### **Overall Dashboard**
- Monthly trends of memberships, payments, and expenses.  
- Retention and churn analysis.  
- Trainer workload distribution.  

### **Members Dashboard**
- Full member list with filters (gender, age, trainer, membership type).  
- Drill-down for individual progress and payments.  

---

## 🔍 Interactive Features
- **Global filters**: Membership type, trainer, gender, status.  
- **Clickable visuals**: Filter all dashboards by clicking a category.  
- **Hover tooltips**: Extra metrics on bars, lines, and pie slices.  

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
   git clone https://github.com/your-username/Sport-Club-Analytics-Dashboard.git

2. Open the Power BI file:

. Launch Power BI Desktop.

. Open SportClubDashboard.pbix.

3. (Optional) Replace dataset:

. Place your own data file in data/Dataset.csv.

. Update data source settings in Power BI.

⚡ Challenges & Solutions

BMI Calculation: Used DAX measure to calculate BMI from height & weight.

Revenue vs. Expenses: Created measures to compare monthly income vs. club costs.

Retention Tracking: Calculated members with continuous active memberships.

Consistent Theme: Applied custom ColorCodes table for a unified dashboard look.

📜 License

This project is licensed under the MIT License - see the LICENSE
 file for details.

✅ Conclusion

The Sport Club Analytics Dashboard in Power BI provides a comprehensive and interactive view of membership, revenue, and engagement metrics.
It helps managers make data-driven decisions to improve financial health, member satisfaction, and operational efficiency.
