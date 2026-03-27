# 🏨 Hotel Booking Cancellation Analysis

## 📌 Project Overview
This project analyzes hotel booking data to uncover patterns behind customer cancellations and provide actionable strategies to reduce revenue loss.

Despite high booking volume, a significant portion does not convert into actual stays. This project explores why this happens and how hotels can respond strategically.

---

## 🎯 Objectives
- Identify key drivers of booking cancellations  
- Analyze customer behavior across segments  
- Evaluate the impact of booking channels and lead time  
- Provide business recommendations to improve conversion  

---

## 📊 Dataset Overview
The dataset contains hotel booking information, including:
- Customer type (Transient, Group, Contract)
- Distribution channel (OTA, Direct, Corporate)
- Lead time
- Deposit type
- Cancellation status
- Arrival date
- Room type

---

## 🧹 Data Preparation
- Handling missing values (categorical → "Unknown", numerical → median)
- Removing duplicates
- Feature engineering:
  - Lead time grouping
  - Seasonality (monthly trends)
  - Customer segmentation

---

## 📈 Dashboard Preview

📌 **Interactive Dashboard (Tableau Public):**  
👉 (https://public.tableau.com/views/Hotel_Booking_17744604831810/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📊 Key Insights

### 🔴 High Cancellation Rate
36.99% of bookings are canceled, meaning more than 1 in 3 bookings do not generate revenue.

### 🌐 OTA Dominates but Risky
Online Travel Agents generate the highest bookings but also the highest cancellations due to low commitment.

### 👥 Transient Customers = High Risk
Individual travelers are the biggest contributors to cancellations due to flexible planning.

### 💳 No Deposit = Red Flag
Bookings without upfront payment are significantly more likely to be canceled.

### ⏳ Lead Time Effect
The longer the booking is made in advance, the higher the chance of cancellation.

### 📅 Seasonality Pattern
Cancellations peak during July–September and decrease toward year-end.

---

## 🛠 Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Tableau (Data Visualization)  
- Excel (Data Processing)  

---

## 🚀 Key Takeaway
High booking volume does not always translate into revenue. By improving customer commitment, optimizing booking channels, and enhancing trust through better service, hotels can significantly reduce cancellations and improve business performance.

---
## 📚 What I Learned
- Understanding customer behavior in the hospitality industry and how it impacts business performance  
- Identifying key factors that drive booking cancellations such as lead time, booking channel, and deposit type  
- Transforming raw data into meaningful business insights and actionable recommendations  
- Building interactive dashboards in Tableau to communicate insights effectively  
- Applying data-driven thinking to solve real-world business problems  
