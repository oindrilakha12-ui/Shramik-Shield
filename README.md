# Shramik Shield 🛡️

### AI Wage Theft Detector for India’s Informal Workforce

Shramik Shield is a Databricks-powered AI system designed to identify wage theft among India’s informal workers — including construction workers, gig workers, and daily wage earners.

Millions of workers across India are underpaid due to lack of awareness of minimum wage laws, informal contracts, and exploitative practices. This project aims to bridge that gap using data, AI, and accessible insights.

---

## 🚨 Problem

* Workers often don’t know the legal minimum wage for their state and job type
* Contractors deduct arbitrary fines or underpay without accountability
* No structured system exists to detect wage theft at scale
* Welfare funds remain unused due to lack of awareness

---

## 💡 Solution

Shramik Shield analyzes worker payment data and compares it against official state-wise minimum wage data using Databricks Lakehouse architecture.

It:

* Calculates expected wages based on legal standards
* Detects underpayment instantly
* Uses AI to identify suspicious wage patterns
* Generates actionable insights for workers

---

## ⚙️ Tech Stack

* Databricks Lakehouse
* Delta Lake
* PySpark
* Spark MLlib (Anomaly Detection)
* MLflow
* React (Frontend)

---

## 🤖 AI Component

An anomaly detection model identifies patterns of systematic underpayment across regions and contractors, helping surface large-scale wage theft.

---

## 📊 Output

* Underpayment detection per worker
* Region-wise wage theft insights
* Fraud/anomaly flags
* Data visualizations via dashboards

---

## 🌍 Impact

Shramik Shield empowers workers with awareness, transparency, and data-driven proof — enabling them to take informed action against wage exploitation.

---

## 🏁 Built for

Databricks Hackathon — Open Track (Indic AI Use Case)
