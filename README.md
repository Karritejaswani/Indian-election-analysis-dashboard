# 🗳️ Indian Election Analysis Dashboard

### 📊 Project Overview
This project presents an **interactive Power BI dashboard** that visualizes Indian election data across multiple states, years, and political parties.  
It allows users to explore **voting trends, party performance, and voter demographics** interactively, providing actionable insights into India’s electoral landscape.

---

## 🎯 Objectives
- Analyze historical election data from **1962 to 2019**.
- Compare **party-wise performance** across different states and constituencies.
- Study **voter turnout patterns** in **urban vs. rural** regions.
- Understand **gender and age group participation** in elections.
- Build a professional, easy-to-use **Power BI dashboard** for quick insights.

---

## 🧩 Dataset Information
**Dataset Name:** `indian-state-level-election.csv`  
**Source:** Collected from publicly available Indian election statistics.

### Key Columns:
| Column Name | Description |
|--------------|-------------|
| State | Name of the Indian state |
| Party | Political party name |
| Candidate Name | Name of the contesting candidate |
| Year | Election year |
| Votes | Number of votes received |
| Gender | Gender of voters/candidates |
| Age Group | Age category of voters |
| Urban Turnout % | Urban voter turnout percentage |
| Rural Turnout % | Rural voter turnout percentage |
| District Name | Name of the district |
| Margin Bucket | Vote margin category |

---

## 📈 Dashboard Highlights

### 🧭 Filters and Slicers
- **State Selector** – View results for specific Indian states.
- **Party and Candidate Name** – Compare performance of parties and candidates.
- **Year Range Slider (1962–2019)** – Analyze election trends over time.

### 🗺️ Key Visuals
1. **Map View:** Displays state-wise winning party distribution.  
2. **Seats Won Card:** Shows total number of seats won (e.g., 2825 seats).  
3. **Urban & Rural Turnout Gauges:** Indicates voter engagement by region.  
4. **Age-wise Vote Analysis:** Visualizes participation across different age groups.  
5. **Gender-wise Vote Split:** Pie chart comparing male vs. female voter turnout.  
6. **Party Performance Charts:**  
   - Votes by Candidate and Party  
   - Constituency counts by Winning Margin

---

## 🧠 Insights Derived
- The **Indian National Congress** showed widespread dominance across several election years.  
- **Urban vs. Rural turnout** remained relatively balanced, with minor variations depending on region.  
- **Younger voters (18–25)** show strong participation in recent years.  
- **Male and female voting participation** rates are closely matched, showing gender balance in elections.  
- Certain states consistently favor specific parties, revealing **regional strongholds**.

---

## 🛠️ Tools & Technologies Used
| Tool | Purpose |
|------|----------|
| **Power BI** | Data visualization and dashboard creation |
| **Microsoft Excel / CSV** | Data preprocessing and cleaning |
| **DAX** | Custom measures and calculated fields |
| **GitHub** | Version control and project sharing |

---

## 🚀 How to Use
1. **Download the Power BI file:**  
   `Election final dashboard.pbix`

2. **Download the dataset:**  
   `indian-state-level-election.csv`

3. **Open in Power BI Desktop.**  
4. Load the dataset and refresh data connections if prompted.  
5. Explore the dashboard using slicers and filters.

---

## 📂 Repository Structure

```
indian-election-analysis-dashboard/
│
├── indian-state-level-election.csv      # Dataset
├── Election final dashboard.pbix        # Power BI project file
├── README.md                            # Project documentation
└── /images                              # Screenshots of dashboard
```
---

## 💡 Future Enhancements
- Add real-time election updates using APIs.  
- Include **predictive analytics** to forecast election outcomes.  
- Integrate **Power BI Service** for web-based access.  
- Expand dataset to include **voter education, turnout campaigns**, and **regional issues**.

---

## 🧑‍💻 Author
**Project By:** Karri Tejaswani  
**Team Members:** Lalit, jayanth, and Mudit  
**Tools Used:** Power BI, Excel, GitHub  

---



## ⭐ Acknowledgments
Special thanks to my teammates Lalit,jayanth and Mudit for their collaboration, contributions, and support throughout the project.

This dashboard was created as part of the Infosys Springboard Data Analytics Virtual Internship, serving as the Final Milestone Project.
It demonstrates our team’s ability to analyze large datasets, apply Power BI visualization techniques, and derive meaningful insights from real-world election data.
