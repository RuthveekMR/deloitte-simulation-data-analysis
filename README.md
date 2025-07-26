# 📊 Deloitte Australia Data Analytics Simulation - Daikibo Industrials

This project is a simulation task provided by Deloitte Australia, aimed at solving real-world business problems using **Data Analytics** and **Visualization** tools like **Tableau** and **Excel**. The client, **Daikibo Industrials**, required insights into factory operations and gender pay equality.

## 🧠 Project Overview

The project was divided into two major tasks:

### ✅ Task 1: Factory Downtime Analysis Using Tableau

#### 🔍 Objective
- Identify which **factory** experienced the most machine breakdowns.
- Pinpoint **device types** responsible for most breakdowns in that factory.

#### 🏭 Data Description
- Telemetry data collected from 4 global Daikibo factories:
  - Daikibo Factory Meiyo (Tokyo, Japan)
  - Daikibo Factory Seiko (Osaka, Japan)
  - Daikibo Berlin (Berlin, Germany)
  - Daikibo Shenzhen (Shenzhen, China)
- 9 types of devices per factory, reporting health status every 10 minutes.
- Data format: JSON  
- ✅ Data Source: [daikibo-telemetry-data.json (Google Drive)](https://drive.google.com/file/d/1ecHg2qtMnw5Pbujl_GazxU6NqEU3h7kU/view?usp=drive_link)

#### 🛠 Tools Used
- **Tableau** for data visualization and dashboarding
- **Calculated Field**: Created `Unhealthy = 10` for every "unhealthy" status (indicating 10 mins downtime)

#### 📊 Visuals Created
- Bar chart of **Downtime per Factory**
- Bar chart of **Downtime per Device Type**
- Interactive **Dashboard**: Selecting a factory filters device data accordingly

#### 🏆 Key Insights
- **Factory with Highest Downtime**: `Daikibo Factory Seiko (Osaka)`
- **Devices with Most Breakdowns**: `Laser Cutter` and `Laser Welder`

#### 📸 Dashboard Snapshot

![Dashboard Screenshot](Dashboard%201.png)

---

### ✅ Task 2: Gender Pay Equality Classification

#### 🎯 Objective
- Investigate gender pay equality across factories and job roles.
- Classify roles based on an **Equality Score** ranging from -100 to +100.

#### 📄 Dataset
- Columns: `Factory`, `Job Role`, `Equality Score`

#### ✅ Classification Logic
| Equality Score Range | Class                |
|----------------------|----------------------|
| -10 to +10           | Fair                 |
| <-10 or >10          | Unfair               |
| <-20 or >20          | Highly Discriminative |

#### 🛠 Tools Used
- **Microsoft Excel** for formula-based classification and data wrangling

---

## 📁 Repository Structure
📦 deloitte-daikibo-data-analytics
┣ 📄 Macora Industries Tableau Dashboard.twbx
┣ 📄 Equality Table.xlsx
┣ 🖼️ Dashboard 1.png
┣ 📄 README.md

---

## 🧠 Skills Demonstrated

- Data Analysis & Visualization
- Dashboard Design using Tableau
- Excel-based Classification Logic
- Business Problem Solving
- Interpretation of IoT/Telemetry Data

---

## 🚀 Outcome

Successfully derived actionable insights for the client:
- Pinpointed operational inefficiencies at factory level
- Identified key devices contributing to downtime
- Supported equality investigation using data classification

---

## 📬 Contact

**Ruthveek M R**  
Email: [ruthmys123@gmail.com](mailto:ruthmys123@gmail.com)  
GitHub: [github.com/RuthveekMR](https://github.com/RuthveekMR)  
LinkedIn: [linkedin.com/in/ruthveek](https://linkedin.com/in/ruthveek) *(Add if applicable)*

---



