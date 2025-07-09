
# ☁️ Cloud Migration Tracker with JSON Risk Parsing

This project simulates a real-world **cloud migration governance dashboard** built in Power BI. It tracks project progress, parses JSON-encoded risk fields, and visualizes risk severity for leadership awareness and compliance reporting.

---

## 📌 Use Case

Designed for **PMO teams**, **cloud architects**, and **enterprise transformation leads**, this tracker:

- Monitors projects by **CAF Domain**, **Milestone**, and **Workload**
- Parses embedded **JSON risk fields** into usable columns
- Displays a **Risk Severity Breakdown** chart
- Summarizes migration progress for governance and leadership

---

## 🛠️ Tools Used

| Tool / Service | Purpose |
|----------------|---------|
| **Amazon DynamoDB** | Stores project metadata and risk fields |
| **AWS Lambda** | Prepares/transforms JSON data |
| **JSON Parsing** | Extracts `risk_type`, `risk_severity`, and `risk_owner` |
| **Power BI** | Dashboards for visualization and filtering |

---

## 🧠 Key Features

✅ Tracks cloud projects by domain and workload  
✅ Parses nested JSON fields into readable values  
✅ Visualizes risk distribution by severity  
✅ Built for cloud migration oversight and executive reporting

---

## 🧩 Architecture Diagram

<p align="center">
  <img src="architecture_diagram.png" alt="Architecture Diagram" width="500">
</p>

---

## 📊 Risk Severity Breakdown

<p align="center">
  <img src="risk_severity_chart.png" alt="Risk Breakdown" width="400">
</p>

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `README.md` | Project overview and documentation |
| `risk_severity_chart.png` | Output visual from Power BI |
| `architecture_diagram.png` | Infrastructure/process diagram |
| `cleaned_data.csv` | Sample processed project data |

---

## 🚀 Real-World Value

This dashboard can be used by:
- Cloud PMOs running migration waves
- Governance teams auditing project risks
- Architects tracking milestone progress
- Internal support teams reporting to leadership

---

## 🔗 Project Status

✔️ Complete — ready for demo  
🧠 Open for extension with live AWS integration or real-time updates via APIs
