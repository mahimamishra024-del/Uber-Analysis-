# 🚖 Uber Ride Analytics Dashboard

## 📌 Overview

This project presents a **comprehensive data analysis of Uber ride bookings**, focusing on demand patterns, revenue generation, cancellations, and customer behavior.

The objective is to uncover **actionable business insights** and identify opportunities to improve operational efficiency and user experience.

---

## 🎯 Objectives

* Analyze overall ride demand and revenue trends
* Identify key factors behind ride cancellations
* Evaluate vehicle-wise performance
* Understand ride distance and payment behavior
* Provide data-driven business recommendations

---

## 📊 Dataset

The dataset contains ride-level information, including:

* Booking ID & Customer ID
* Date & Time of ride
* Vehicle type
* Ride distance
* Booking value (revenue)
* Payment method
* Booking status (Completed / Cancelled)
* Ratings (Customer & Driver)

---

## 🛠 Tools & Technologies

* **Python** (Pandas, Matplotlib)
* **Google Colab**
* **Data Visualization**
* **Dashboard Design (Matplotlib)**

---

## 🧹 Data Cleaning & Preparation

* Removed unwanted characters from IDs
* Converted date and time into proper formats
* Handled missing values in revenue and cancellation columns
* Standardized booking status categories
* Removed duplicate records
* Created new features like:

  * **Is Cancelled Flag**
  * **Revenue Column**

---

## 📈 Key Insights

### 🚀 Overall Performance

* Total Bookings: **150K**
* Total Revenue: **₹51.85M**
* Average Daily Rides: **~410**
* Cancellation Rate: **~25%**

➡️ Strong demand observed, but cancellations impact efficiency.

---

### 🚗 Vehicle Performance

* **Auto** is the top-performing category
* **Go Mini & Go Sedan** show consistent demand
* **Uber XL** has the lowest utilization

➡️ Mid-tier and economy segments drive the business.

---

### 💰 Revenue & Ride Distribution

* Majority rides fall within **5–20 km range**
* **UPI (~45%)** is the dominant payment method
* Cash usage (~25%) is declining

➡️ Clear shift toward digital payments.

---

### ❌ Cancellation Analysis

* High cancellation rate (~38%) is a key concern
* Customer cancellations: plan changes, incorrect details
* Driver cancellations: long pickup distance, vehicle issues

➡️ Need for better driver allocation and routing optimization.

---

### ⭐ Ratings Analysis

* Customer Rating: **~4.40**
* Driver Rating: **~4.23**

➡️ Service quality remains stable despite operational issues.

---

## 📊 Dashboard

The project includes multiple dashboards:

* Overall Performance Dashboard
* Vehicle Performance Analysis
* Revenue & Ride Distribution
* Cancellation Analysis
* Ratings & Revenue Insights

---

## 📂 Project Structure

```
uber-ride-analysis/
│
├── data/
│   └── dataset.csv
│
├── notebook/
│   └── uber_analysis.ipynb
│
├── README.md
```

---

## 💡 Business Recommendations

* Reduce cancellations through improved driver matching
* Optimize pickup distance and routing
* Focus on high-performing vehicle categories
* Improve performance of premium segments
* Strengthen digital payment ecosystem

---

## 🚀 Conclusion

The analysis highlights **strong demand and revenue potential**, but also reveals **high cancellation rates as a major operational gap**.

By addressing these inefficiencies, Uber can significantly enhance both **customer experience and revenue performance**.

---

## 👩‍💻 Author

**Mahima Mishra**
