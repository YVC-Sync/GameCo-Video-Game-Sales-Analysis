# GameCo: Video Game Sales Analysis
**Know the Data. Master the Market.**

<img src="GameCo case study logo.png" alt="Instacart Logo" width="130">

Analyzed global video game sales to support GameCo’s strategy across marketing, operations, and finance. This included regional genre preferences, platform trends, publisher performance, and deeper modeling using Python and machine learning. The goal was to guide GameCo on how to better target its markets and refine its planning using real data.

---

## 🚀 Fast Facts for Busy Reviewers

- **Tool Stack:** Python (Pandas, Seaborn, Matplotlib, Scikit-learn), Tableau, Excel  
- **Data Source:** Cleaned and structured dataset of 16,000+ game titles  
- **Key Wins:**
  - Created custom features like `sales_per_title` and `na_focus_ratio`  
  - Used KMeans clustering to group publishers by behavior and performance  
  - Visualized genre trends, peak years, and platform performance with Tableau  
  - Tied insights to publisher strategy and market positioning

---

## 🎯 The Challenge
GameCo wanted to understand how different publishers and genres perform globally and regionally to strengthen its strategy. 

Questions I explored:
- Which publishers are dominant globally or regionally?
- How do sales vary by year and platform?
- What genres perform best in each region?
- Can clustering uncover strategic behavior patterns?
- How efficient are publishers based on average sales per title?

---

### 🛠️ Tools Used  

- **Python** (Pandas, Seaborn, Matplotlib, Scikit-Learn)  
- **Excel** (cleaning, pivot tables, regional summaries)  
- **Tableau** (dashboards, executive visuals)  
- **Machine Learning** (KMeans clustering for publisher strategy)

---

## 🧠 Key Questions Explored

- Which genres sell best by region?
- How do sales shift over time, especially after 2010?
- Which publishers are most consistent, efficient, or dominant in specific regions?
- What patterns emerge when clustering publishers by sales behavior?
- How do sales vary by platform and release year?
- What regional preferences should GameCo focus its marketing around?


---

## 🧼 Workflow Summary

This project followed a two-phase workflow: initial exploration in Excel and Tableau, then a deeper dive in Python for advanced analysis and modeling.

- Cleaned and standardized the dataset (column names, data types, missing values)
- Explored sales trends by region, genre, and platform using pivot tables and Tableau dashboards
- Created new features like `sales_per_title` and `na_focus_ratio` to measure publisher efficiency and regional focus
- Scaled relevant data for clustering and modeling
- Used Python for advanced EDA, feature engineering, and KMeans clustering to group publishers by behavior

📁 Final cleaned dataset: `vgsales_final_cleaned_dataset.xlsx`

---

### 📈 What I Found  

- **Action games** dominate North America, **Sports** lead in Europe, and **RPGs** are key in Japan.  
- **Nintendo** consistently ranks at the top with strong first-party titles.  
- Sales peaked between **2005–2009**, with a clear decline after 2010.  
- ML helped group publishers with similar behavior, revealing efficient vs. high-volume strategies.  
- Regional focus matters marketing should never be one-size-fits-all.

---

### 🧹 Machine Learning Insight  

Clustering publishers uncovered four key behavior groups. This adds context to platform strategies and can guide GameCo when planning partnerships or studying competitors.

---

### 💡 Business Impact for GameCo  

- Tailor marketing by region: Action (NA), Sports (EU), RPG (JP)  
- Fill publisher gaps: EA and Ubisoft underperform on newer platforms  
- Anticipate trends: Invest more in digital distribution and platform transitions  
- Use clustering to guide competitive strategy and resource planning

---

## 💼 From Data to Decisions

This project helps GameCo:
1. Partner with publishers showing global consistency and high efficiency  
2. Focus marketing efforts on region-genre fit  
3. Spot underutilized publishers with strong performance per title  
4. Track platform cycles to align future releases  

---

## 📁 Repository Structure

```bash
GameCo-Video-Game-Sales-Analysis/
│
├── 01 Data/           # Original, cleaned, and regional Excel datasets
├── 02 Notebooks/      # Jupyter Notebook with ML + clustering analysis
├── 03 Tableau/        # Tableau workbook for genre, region, and publisher trends
├── 04 Reports/        # Case study, slides, and reflection documents
│
├── GameCo Neon Logo.png   # Custom logo used in README header
├── LICENSE                # Project license
└── README.md              # Project overview and insights
```
---

### 🔗 View the Full Case Study  
[🌐 www.yariselvelacanto.com/data](http://www.yariselvelacanto.com/data)

