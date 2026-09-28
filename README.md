# DataAnalytics-project
ChurnGuard is an end-to-end customer churn analytics and retention platform built with Python, SQL, Flask, Machine Learning, HTML, CSS, JavaScript, and Chart.js. It provides real-time dashboards, customer risk scoring, AI-driven insights, personalized retention offers, email campaigns, activity tracking, and data export.
# 🚀 ChurnGuard — Customer Churn Analytics & Retention Platform

> An end-to-end Data Analytics + Machine Learning platform that identifies high-risk customers, explains churn behavior, and helps businesses take personalized retention actions.

---

## 🌟 Overview

ChurnGuard transforms raw customer data into actionable business insights.

The platform combines:

* 📊 Data Analytics
* 🤖 Machine Learning
* 🗄️ SQL Database
* 🌐 Flask REST APIs
* 📈 Interactive Dashboards
* 🧠 AI-powered Customer Insights
* 📧 Personalized Retention Campaigns

Instead of only showing churn statistics, ChurnGuard connects analytics with customer-level actions such as personalized offers and retention emails.

---

## ✨ Key Features

### 📊 Executive Dashboard

* Overall Churn Rate
* Retention Rate
* ARPU
* Revenue at Risk
* Monthly Contract Churn
* ML Risk Metrics
* Interactive Chart.js visualizations

### 👥 Customer Explorer

* View customer information
* Search by name, email, or state
* Filter by risk level
* Filter by contract type
* Filter by customer status
* View detailed customer profiles

### 🤖 AI Customer Analyst

* Customer-level behavioral analysis
* Identifies potential churn reasons
* Generates natural-language insights
* Suggests retention actions
* Creates targeted promotional offers

### 🎯 Targeted Retention Offers

The system dynamically generates offers based on customer behavior, including:

* `PRICELOCK20`
* `TURBOHD30`
* `MATCHPROMO`
* `SPORT50`

### 📧 Email Campaign System

* Personalized email templates
* Email preview before sending
* Retention offers
* Competitor match offers
* Service recovery emails
* Exit survey emails
* Simulated email delivery

### 📨 Email Outbox

* Sent email history
* Delivery status
* Timestamp tracking
* Subject and body inspection
* Message ID tracking

### 📈 Customer Activity Timeline

View a chronological customer journey including:

* Subscription activity
* Support interactions
* Plan changes
* Payment events
* Churn-related activities

### 📤 Data Export

Export analyzed data for further reporting and analysis.

---

## 📊 Dashboard Insights

Example project metrics:

| Metric                |  Value |
| --------------------- | -----: |
| 👥 Customers Analyzed |    21+ |
| 📉 Churn Rate         |  28.6% |
| 🔄 Retention Rate     |  71.4% |
| 💰 ARPU               | $19.27 |
| ⚠️ Revenue at Risk    | $73.94 |
| 🤖 ML Model Accuracy  |   100% |

> These values are generated from the project's current dataset and model implementation.

---

## 🧠 Machine Learning

ChurnGuard uses customer attributes and behavioral information to calculate customer churn risk.

### Risk Categories

🟢 **LOW**
Customer shows relatively low churn risk.

🟡 **MEDIUM**
Customer may require monitoring or engagement.

🔴 **HIGH**
Customer requires potential retention intervention.

Each customer receives a numerical risk score between **0–100**.

---

## 🏗️ System Architecture

```text
Customer Data
      ↓
SQLite Database
      ↓
Python + Pandas
      ↓
Data Cleaning & Feature Engineering
      ↓
Machine Learning Model
      ↓
Flask REST APIs
      ↓
Interactive Frontend
      ↓
┌───────────────────────────┐
│ Executive Dashboard       │
│ Customer Explorer         │
│ AI Analyst                │
│ Retention Campaigns       │
│ Feedback                  │
│ Email Outbox              │
└───────────────────────────┘
```

---

## 🛠️ Tech Stack

### Backend

* Python
* Flask
* SQLite

### Data Analytics

* Pandas
* NumPy
* SQL

### Machine Learning

* Scikit-learn

### Frontend

* HTML5
* CSS3
* JavaScript
* Chart.js

### Development

* Git
* GitHub
* REST APIs

---

## 📂 Project Structure

```text
churn_analysis_project/
│
├── app.py
├── database.py
├── ml_engine.py
├── requirements.txt
│
├── index.html
├── README.md
├── walkthrough.md
│
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── data/
│   └── customer_data.*
│
└── database/
    └── churn.db
```

---

## 🚀 How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/churnguard.git
cd churnguard
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Initialize the Database

```bash
python database.py
```

### 4️⃣ Run the ML Engine

```bash
python ml_engine.py
```

### 5️⃣ Start Flask

```bash
python app.py
```

### 6️⃣ Open in Browser

```text
http://127.0.0.1:5000
```

---

## 🔌 API Endpoints

| Method | Endpoint               | Purpose              |
| ------ | ---------------------- | -------------------- |
| GET    | `/`                    | Main dashboard       |
| GET    | `/api/dashboard`       | Dashboard KPIs       |
| GET    | `/api/customers`       | Customer data        |
| GET    | `/api/customer/<id>`   | Customer profile     |
| GET    | `/api/ai/analyst/<id>` | AI customer analysis |
| POST   | `/api/email/preview`   | Email preview        |
| POST   | `/api/email/send`      | Send simulated email |
| GET    | `/api/email/outbox`    | Email history        |
| POST   | `/api/campaign/create` | Create campaign      |
| POST   | `/api/feedback/submit` | Submit feedback      |
| GET    | `/api/reports/export`  | Export reports       |

---

## 💡 Business Problem

Customer churn directly affects recurring revenue.

Traditional dashboards may show:

> "28.6% of customers churned."

ChurnGuard goes one step further:

> "Which customers are at risk, why are they at risk, and what retention action can be taken?"

This makes the project more focused on converting analytics into actionable business decisions.

---

## 🎯 Project Goals

* Identify customers with high churn probability
* Understand behavioral patterns behind churn
* Estimate potential revenue loss
* Segment customers based on risk
* Generate personalized retention strategies
* Provide an interactive business dashboard
* Connect analytics with practical business actions

---

## 📚 What I Learned

Through this project, I strengthened my knowledge of:

* SQL database management
* Data cleaning

