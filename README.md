# ✈️ Flybondi Flight Delays — Data Analytics & Power BI Dashboard

Interactive BI project to analyze **flight delays and cancellations** and identify the main drivers impacting operational performance and customer experience.

Built as part of **Análisis de Datos I** using **Power BI (Power Query + Data Modeling + DAX)**.

---

## 🎯 Business Problem

Flight delays generate high operational costs and reduce customer satisfaction.  
This project focuses on answering:

- What are the **main causes** of delays?
- Which **routes/airports** concentrate the highest delay rates?
- How do **weather and seasonality** affect punctuality?
- Do **external factors** (e.g., union actions) meaningfully impact delays?

---

## 📂 Dataset

Public dataset available at:

https://drive.google.com/file/d/1pfAmrgEyqHQjOpLraFQ3wc9s9lQY-cFU/view?usp=sharing

The dataset is not stored in this repository to keep it lightweight.
Please download the file from the link above and refresh the Power BI model if needed.

---

## 🧼 Data Preparation (Power Query)

Key steps applied to improve data quality and analytical reliability:

- ✅ Data type conversion (dates, times, numeric fields)
- ✅ Fix for **Occupancy %** formatting issues
- ✅ Null handling (e.g., explicit “SinDemora” category)
- ✅ Feature engineering (e.g., **Route = Origen-Destino**, time period fields)
- ✅ Data consistency checks (negative delays handled)
- ✅ Outlier treatment using a controlled approach (winsorization threshold)

---

## 📊 Dashboard & Storytelling

The dashboard follows a question → insight → implication narrative and includes:

- KPI overview (delay/cancellation rates, avg delay)
- Delay causes breakdown (operational, technical, crew, weather, etc.)
- Geographic insights (routes & critical airports)
- Time-based trends (year/month/seasonality)
- Weather impact analysis

---

## 🔍 Key Insights (Summary)

- Delays behave as a **multifactor and structural** issue (not driven by a single variable).
- Certain **regional airports and routes** show higher severity and require operational reinforcement.
- **Seasonality and weather (storms)** increase congestion and delay rates.
- Some external factors have limited impact compared to operational drivers.

---

## ✅ Recommendations

- Strengthen operations in high-severity regional airports (staffing, turnaround buffers, ramp resources).
- Create an inter-departmental mitigation strategy (operations + crew + maintenance + boarding).
- Add preventive scheduling buffers in peak-season months.
- Implement an internal real-time BI operational board for early detection and decision-making.

---

## 🛠️ Tools

- Power BI
- Power Query (ETL)
- Data modeling + measures (DAX)
- Dashboard design & data storytelling

---

## 📁 Repository Contents

- `dashboard/` → Power BI `.pbix`
- `docs/` → Full analysis report (PDF)
- `assets/` → Dashboard screenshots used in this README

---

## ▶️ How to Open

1. Download the PBIX file from `/dashboard`
2. Open with **Power BI Desktop**
3. Refresh data (requires access to the original dataset source)

---

## 📌 License

Licensed under the MIT License.
