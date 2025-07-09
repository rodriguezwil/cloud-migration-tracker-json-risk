
# 📊 Cloud Migration Tracker + Risk Governance Dashboard

This project simulates a real-world **cloud governance dashboard** for tracking cloud migration initiatives and visualizing risk exposure. Built in Power BI and backed by structured JSON risk data, it helps project managers and cloud leads maintain visibility across workloads, CAF domains, and migration phases.

---

## 🚀 Project Highlights

✅ Tracks projects by CAF Domain, Milestone, and Workload  
✅ Parses JSON risk fields into severity, type, and owner  
✅ Includes pie chart for Risk Severity Breakdown  
✅ Architecture diagram visualizes the full data flow  
✅ Includes sample data and README documentation  
✅ Designed for PMOs, governance leads, and entry-level cloud analysts

---

## 📁 Folder Structure

```
cloud-migration-tracker-json-risk/
├── cleaned_data.csv          → Sample migration project data
├── risk_severity_chart.png   → Pie chart visualizing risk severity
├── architecture_diagram.png  → End-to-end architecture for project flow
├── README.md                 → Full documentation and project overview
```


## 🧰 Technologies Used

- Power BI
- JSON parsing (embedded string field breakdown)
- AWS DynamoDB (source data simulation)
- AWS Lambda (for transformation logic simulation)
- GitHub (project documentation + versioning)

---

## 🛠️ How to Reproduce This Project

1. Open `cleaned_data.csv` in Power BI  
2. Import the data into Power BI  
3. Build the following visuals:
   - Donut chart by `caf_domain`
   - Column chart by `milestone`
   - Pie chart using `risk_severity`
   - Table summary of all fields
4. Save as `.pbix` or publish to Power BI service

---

## 🎯 Project Status

✅ Fully functional, tested visuals  
✅ JSON parsing fields prepared  
✅ Visuals + diagram included  
✅ GitHub-ready and recruiter-friendly

---

## 👨‍💻 About the Author

**Wil Rodriguez**  
Cloud & API Enthusiast | Technical PM | AWS Support Builder

[📁 GitHub Profile](https://github.com/rodriguezwil)  
[🔗 LinkedIn](https://www.linkedin.com/in/wil-rodriguez/)
