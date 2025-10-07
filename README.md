# Election Insights Dashboard

## 📊 Real-Time Election Visualization for News Media
Developed as part of the **Infosys Springboard Internship**

---

## 🧭 Overview
In today’s dynamic election landscape, news organizations demand **accurate, real-time insights** to report results efficiently and transparently.  
This project converts raw election datasets into **interactive Power BI dashboards**, allowing journalists, analysts, and the public to explore **vote shares, turnout trends, and constituency-level dynamics** with clarity.

Built using **Power BI**, the solution combines **historical** and **live election data (via API)** to support **data-driven reporting and storytelling** for effective news coverage.

---

## 🎯 Objective
The primary objective of this project is to develop a **scalable and interactive dashboard** that visualizes Indian election data, enabling users to:

- Analyze **voter turnout**, **party performance**, and **candidate statistics**  
- Compare **urban and rural voting behaviors**  
- Examine **historical trends** across different states and constituencies  
- Receive **real-time election updates** through API integration  

---

## 🧩 Data & Modeling

### 🔹 Data Sources
- **Historical Data:** CSV files containing Lok Sabha election results from **1962–2019**  
- **Live Data:** Integrated using the [Datameet India Election Data API](https://raw.githubusercontent.com/datameet/india-election-data/refs/heads/master/assembly-elections/assembly.csv)


### 🔹 Data Cleaning (Power Query)
- Removed duplicate entries and null records  
- Standardized **party names**, **text formats**, and **data consistency**  
- Assigned appropriate **data types** for accuracy  
- Created additional calculated columns for:
  - **Vote Share (%)**  
  - **Area**  

### 🔹 Star Schema Design
- **Fact Table:** `fact_votes` — stores measurable data such as total votes, voter turnout, and victory margins  
- **Dimension Tables:**
  - `dim_party`  
  - `dim_candidate`  
  - `dim_constituency`  
  - `dim_election_date`  


## 📈 Dashboards & Key Insights

### 🕰️ Historical Trends  
- Illustrates the evolution of voter behavior and shifts in party dominance across decades.  
- Highlights emerging and declining political parties along with changing regional voting patterns.  

### 👥 Demographic Analysis  
- Depicts gender-wise candidate participation, revealing a prominent male majority.  
- Identifies political strongholds and constituency-level dynamics across various regions.  

### 🌾 Rural Voter Dynamics  
- Analyzes the significant influence of rural regions on national election outcomes.  
- Highlights turnout trends in high-engagement states such as **Nagaland** and **Lakshadweep**.  

### 🌆 Urban Voter Landscape  
- Examines urban turnout rates, often observed to be lower than rural participation levels.  
- Emphasizes the importance of enhancing urban voter engagement and awareness initiatives.  

### 🔍 Interactive Features  
- Includes **drill-through pages** that allow users to dive deeper into state or constituency-level data.  
- Offers **dynamic filters and visuals** for smooth, intuitive, and engaging data exploration.  


## 💡 Tools & Technologies
- Power BI (Dashboarding & DAX Calculations)
- Power Query (Data Cleaning & Transformation)
- API Integration (Live Data Fetching)
- Star Schema Design (Data Modeling)


## 📸 Dashboard Preview

<img width="1311" height="734" alt="Screenshot 2025-10-06 214734" src="https://github.com/user-attachments/assets/65a187cb-d744-415c-8a28-169e5bb9212f" />

## 👥 Contributors
**Team 4 – Infosys Springboard Internship**

- Bhumi Kala  
- Santosh SK  
- Srinibas Masanta  
- Vaibhav Yadav


## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

