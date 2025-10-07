# Election Insights Dashboard

## 📊 Real-Time Election Analytics

Part of the **Infosys Springboard Internship**, this project delivers an interactive Power BI dashboard that transforms raw Indian election data into clear insights for journalists, analysts, and the public.

---

## 🎯 Key Goals

- Track voter turnout, party performance, and candidate stats  
- Compare urban vs. rural voting patterns  
- Analyze historical trends across states and constituencies  
- Access real-time updates via API integration  

---

## 🧩 Data & Modeling

- **Historical Data:** Lok Sabha results (1962–2019)  
- **Live Data:** [Datameet India Election Data API](https://raw.githubusercontent.com/datameet/india-election-data/refs/heads/master/assembly-elections/assembly.csv)  
- **Processing:** Removed duplicates, standardized party names, added calculated fields like Vote Share (%)  
- **Schema:** Star schema with `fact_votes` (measures) and dimension tables (`dim_party`, `dim_candidate`, `dim_constituency`, `dim_election_date`)  

---

## 📈 Dashboard Highlights

- **Historical Trends:** Evolution of voter behavior and party dominance  
- **Demographics:** Gender distribution and regional strongholds  
- **Rural & Urban Analysis:** Insights on turnout and engagement patterns  
- **Interactive Features:** Drill-through pages, dynamic filters, and visual exploration  

---

## 💡 Tools

- Power BI (Dashboard & DAX)  
- Power Query (Data cleaning)  
- API Integration (Live data)  
- Star Schema Design (Data modeling)  

---

## 📸 Preview

<img width="1311" height="734" alt="Dashboard Preview" src="https://github.com/user-attachments/assets/65a187cb-d744-415c-8a28-169e5bb9212f" />

---

## 👥 Contributors

**Team 4 – Infosys Springboard Internship**  
- Bhumi Kala  
- Santosh SK  
- Srinibas Masanta  
- Vaibhav Yadav  

---

## 📜 License

MIT License – see [LICENSE](LICENSE) for details.
