# 📌 Project Title

🏈 **NFL Sports & Player Performance Dataset**

## 📌 Introduction

The **NFL Sports & Player Performance Dataset** is a comprehensive data analytics study designed to explore how **college performance** and **pre-draft athletic metrics** translate into **NFL career success**.  

By integrating multiple datasets — including **NFL Combine results**, **Draft history**, **College statistics**, and **Professional player performance** — this project uncovers the data-driven patterns behind what makes an athlete successful in the league.  

The goal is to understand which factors best predict success at the professional level:  
- Do combine metrics like the **40-yard dash**, **bench press**, or **vertical jump** correlate with long-term performance?  
- Which colleges and conferences consistently produce top NFL talent?  
- How do **age, height, weight, and position** influence productivity and fantasy points?  
- Do certain **teams, states, or regions** have higher talent output or better draft efficiency?  

The project combines **statistical analysis**, **visual analytics**, and **predictive insights** to help scouts, analysts, and fans better interpret how early-stage indicators shape a player’s professional journey.  

The resulting **interactive dashboard** provides a multi-page exploration of the NFL talent pipeline:  
- **Player Performance Overview** – Evaluates player productivity, fantasy points, and physical influences.  
- **Combine & Draft Analysis** – Examines how combine metrics and draft positions predict career outcomes.  
- **College & Conference Insights** – Highlights dominant colleges and conferences shaping the NFL landscape.  
- **Geographic Analysis** – Maps where successful players come from and how region impacts player success.  
- **Team & League Performance** – Analyzes team efficiency, win rates, and rookie vs. veteran balance.  

Ultimately, this project connects data from **college** and **combine stages** to **career performance outcomes**, offering a data-driven perspective on how **raw athleticism, education, and geography** contribute to success in the NFL.  

## 📂 Data Collection & Additional Fields

The dataset was provided as part of an academic assignment and was not collected directly by me.
It compiles player, team, draft, and combine data from 1999 onward, covering variables like fantasy points, physical measurements, and college performance indicators.

In addition to the raw fields, numerous derived and calculated fields were created to enrich the analytical depth of the project — allowing exploration of year-over-year (YoY) trends, positional comparisons, and team-level insights.

## ⚙️ Calculated Fields & Columns Created

To support advanced exploration of performance, draft, and college data, the following calculated columns and measures were developed using Power BI.

---

### 🧩 Calculated Columns

| Column Name | Description |
|--------------|-------------|
| Player Category | Categorizes players (Rookie, Veteran, Elite, etc.). |
| Is Rookie | Boolean flag (1 = Rookie, 0 = Veteran). |
| DraftTier | Groups players by draft round tiers (Early, Mid, Late). |
| Short Player Name | Abbreviated name for visualization clarity. |
| HeightBin | Groups players into height categories (Short, Medium, Tall). |
| Age Group | Categorizes players by age (Rookie ≤24, Prime 25–30, Veteran 31+). |
| Career Bin | Categorizes players by career length (Short, Medium, Long). |

---

### 📊 Performance & Career Metrics

| Measure | Description |
|----------|-------------|
| Average Fantasy Point | Mean fantasy score per player or team. |
| Total Fantasy Point | Cumulative fantasy points across all seasons. |
| Rookie Fantasy Point | Fantasy points in the first season. |
| First3YearsFantasyPoint | Total fantasy points in the first three career years. |
| AvgCareerbyTier | Average career length by player tier. |
| Career Length | Seasons active (Last Year – Draft Year). |
| Peak Age | Age corresponding to highest player performance. |
| YoY % Peak Age | Year-over-year change in peak age. |

---

### 🧠 Draft & Combine Metrics

| Measure | Description |
|----------|-------------|
| Average Draft Round | Mean draft round per player or team. |
| Average DraftPick | Average overall draft pick. |
| DraftCount | Total number of drafted players. |
| DraftPickCount | Count of draft picks per year. |
| Avg Wonderlic | Mean Wonderlic score. |
| Total Wonderlic | Sum of all Wonderlic scores. |
| Total 40YD | Sum of recorded 40-yard dash times. |
| YoY % 40YD | Year-over-year change in 40-yard dash performance. |
| YoY % Vertical | YoY change in average vertical jump. |
| YoY % AvgDraftRound | YoY change in draft round averages. |
| YoY % Total Wonderlic | YoY change in total Wonderlic scores. |
| Average BenchPress | Mean bench press repetitions. |
| Average Vertical | Mean vertical jump height. |
| Average 40YD | Mean 40-yard dash time. |

---

### 🏫 College & Conference Insights

| Measure | Description |
|----------|-------------|
| College Win Ratio | College Wins ÷ (College Wins + Losses). |
| Players per College | Average players drafted per college. |
| Total Players per College | Total players drafted from each college. |
| Top College | College with the highest cumulative fantasy points. |
| Top College by Draft | College with the most draft selections per year. |
| Total College | Total number of unique colleges. |
| Average Passing Yds by Conference | Mean passing yards by conference. |
| Average Rushing Yds by Conference | Mean rushing yards by conference. |
| Average Receiving Yds by Conference | Mean receiving yards by conference. |
| Average Performance by Conference | Overall performance metric per conference. |

---

### 🏈 Team & League Performance

| Measure | Description |
|----------|-------------|
| Total Team Win | Total wins per team. |
| Average Win % | Average team win percentage. |
| Average Win % Per Draft | Team win percentage grouped by draft year. |
| Top Team | Team with highest fantasy output or win rate. |
| YoY % Total Team Wins | Year-over-year change in team win totals. |
| IsTop5FantasyTeam | Indicates teams in the top 5 for fantasy points. |
| Talent Distribution Index | Measures equality of performance across positions. |
| YoY % Talent Distribution Index | Year-over-year variation in team balance. |
| Unique Position per Team | Number of distinct positions per team. |
| Veteran to Rookie Ratio | Ratio of veterans to rookies. |
| VeteranContributionPct | Veteran share of total team fantasy points. |
| RookieContributionPct | Rookie share of total team fantasy points. |
| YoY % Veteran-Rookie Ratio | Year-over-year change in experience mix. |

---

### 📈 Player Output Metrics

| Measure | Description |
|----------|-------------|
| Total Passing Yds | Total passing yards accumulated. |
| Total Rushing Yds | Total rushing yards accumulated. |
| Total Receiving Yds | Total receiving yards accumulated. |
| Top Player | Player with the highest cumulative fantasy points. |
| Top Player Points | Total fantasy points of top player. |
| Player Rank | Rank assigned based on fantasy point performance. |
| YoY % Fantasy Point | Year-over-year change in total fantasy points. |
| YoY % Receiving Yds | YoY change in total receiving yards. |
| YoY % Rushing Yds | YoY change in total rushing yards. |
| YoY % Passing Yds | YoY change in total passing yards. |
| YoY % First 3 Years Fantasy Point | YoY change in early career performance. |
| YoY % Total Player % | Year-over-year change in total player share. |

---

### 💡 Purpose of These Calculations

These calculations were designed to:
- Evaluate player development and career growth.  
- Identify college and conference success patterns.  
- Analyze rookie vs. veteran contribution to team performance.  
- Reveal year-over-year (YoY) trends across athletic, draft, and fantasy metrics.  
- Support interactive storytelling through Power BI dashboards.

## 🧹 Data Cleaning & Preparation

Before analysis, extensive data cleaning and transformation were performed to ensure consistency, accuracy, and usability across datasets covering the years **1999–present**.  

The raw dataset included multiple tables (Player Stats, Combine Results, Draft Data, College Records, and Team Performance). Each table contained missing values, inconsistent naming conventions, and duplicate entries that required preprocessing.

---

### 🧭 Steps Performed

| Step | Description |
|------|-------------|
| **1. Data Import & Inspection** | Imported all datasets into Power BI (64-bit) and Excel from provided CSV files. Reviewed column headers, data types, and duplicates. |
| **2. Handling Missing Values** | Replaced or removed null values in key metrics (Height, Weight, 40YD, Bench, Vertical, Fantasy Points). Missing numeric data were replaced with O and metrics (Hometown, HomeState) with Unknown. |
| **3. Data Type Correction** | Converted incorrect data types (e.g., Year as text → integer, Fantasy Points as float). |
| **4. Removing Duplicates** | Used player name + year as a composite key to remove repeated records. |
| **5. Standardizing Names** | Cleaned inconsistent player, college, and team names using proper case and text normalization. |
| **6. Derived Fields Creation** | Added new columns like `Age Group`, `HeightBin`, `Career Bin`, and `Player Category` to support analysis. |
| **7. Outlier Detection** | Identified and reviewed extreme values in 40YD, Bench, and Fantasy Points to confirm data validity. |
| **8. Data Merging** | Combined multiple tables (Combine, Draft, and Team Performance) using Player ID and Year as primary keys. |
| **9. Calculated Columns & Measures** | Created DAX measures for YoY changes, averages, and performance ratios to enhance analytical depth. |
| **10. Validation** | Cross-checked totals, averages, and YoY metrics with sample data to ensure calculation accuracy. |
| **11. 64-bit Power BI Memory Fix** | Encountered a model size error in Power BI Desktop (32-bit). Migrated the project to **Power BI 64-bit version**, increasing memory handling capacity for large datasets. This allowed for smooth model refresh and measure calculations without crashing. |

---

### 🧩 Data Transformation Tools

| Tool | Purpose |
|------|----------|
| **Power BI (64-bit, version 2024.3)** | Main platform for data modeling, measure creation, and visualization. |
| **Excel** | Used for initial cleaning, validation, and lookup checks. |
| **Power Query (M Language)** | Applied for data transformation, joins, and normalization. |
| **DAX** | Created custom measures and calculated columns (e.g., YoY%, Ratios, Indexes). |

---

### 🧠 Outcome

After cleaning and transformation:
- All records were standardized from **1999–present**.  
- Missing and inconsistent values were fixed.  
- 64-bit Power BI resolved prior model crashes caused by data size.  
- New analytical fields (e.g., YoY%, Rookie Contribution, Talent Index) were generated.  
- A unified model connecting **Player → College → Draft → Team → Performance** was established for advanced analysis.

---

💡 *This process ensured that every visualization and metric in the dashboard is accurate, efficient, and optimized for high-performance analytics.*

## 📊 Exploratory Data Analysis (EDA)

After cleaning and preparing the dataset, an Exploratory Data Analysis (EDA) was conducted to understand player performance patterns, positional trends, and relationships between combine, draft, and career outcomes.  
The EDA helped uncover early insights that shaped subsequent modeling, visualization, and hypothesis testing.

---

### 🧠 Key Objectives
The goal of this phase was to:
- Identify **distributions**, **outliers**, and **missing patterns** across variables.  
- Explore how **physical metrics (Height, Weight, 40YD, Bench, Vertical)** relate to player performance.  
- Analyze **fantasy point trends** across positions and years.  
- Understand how **college performance** and **draft rounds** impact long-term success.  
- Establish relationships between **rookie/veteran contributions** and **team win percentages**.

---

## 🔍 Exploratory Data Analysis (EDA)

The dataset was analyzed to uncover trends, relationships, and patterns in player and team performance from **1999–2023**.  
EDA focused on:
- Player demographics (age, height, weight)
- Combine metrics (40YD, Bench Press, Vertical)
- Draft details (Round, Pick, Team)
- Career outcomes (Games Played, Fantasy Points)
- College and conference contributions

### 🧩 Key Findings
- Average player age is **26**, with performance peaking at **ages 23–25**.  
- **Quarterbacks and Wide Receivers** generate the highest fantasy points overall.  
- A positive correlation exists between **40YD speed** and **career length**.  
- Players from **SEC and Big 12** conferences consistently outperform others.  
- Fantasy points and wins have shown a **steady YoY increase of 7–8%**.  

### 📊 Visualization Methods
- **Bar and Column Charts:** Used to compare player positions, team performance, and college representation.  
- **Maps:** Visualized player distribution by state and position.  
- **YoY Line Charts:** Showed changes in average fantasy points, draft rounds, and win percentages over time.




