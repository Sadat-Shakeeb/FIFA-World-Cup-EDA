# ⚽ FIFA World Cup EDA

This project performs **Exploratory Data Analysis (EDA)** on a dataset containing information about **FIFA World Cup matches, world rankings, and tournaments (1930–2022)** to uncover historical trends, team performance insights, and player behavior patterns.

---

## 📂 Data Sources

The following datasets were used in this analysis:

- **fifa_ranking_2022-10-06.csv:** Contains FIFA world rankings as of October 6, 2022.  
- **world_cup.csv:** Provides information about World Cup tournaments — host, teams, champions, and attendance.  
- **matches_1930_2022.csv:** Includes detailed match data from all FIFA World Cups between 1930 and 2022.

---

## 🧰 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Regular Expressions (re)

---

## 📊 Analysis Performed

The project includes the following analytical steps:

- **Data Loading & Inspection:**  
  - Imported and examined datasets, reviewed structure and key attributes.  

- **Data Cleaning:**  
  - Handled missing values and standardized inconsistent team names (e.g., "Germany DR" → "West Germany").  

- **Basic Statistics:**  
  - Calculated total matches, goals, average goals per match, total and average attendance.  

- **Tournament Performance:**  
  - Identified countries with most wins, runner-ups, and 3rd-place finishes.  
  - Visualized title distributions with pie and bar charts.  

- **Team Participation Over Time:**  
  - Analyzed team participation across editions and visualized with heatmaps.  

- **FIFA Ranking Movements:**  
  - Tracked teams whose rankings increased, decreased, or remained unchanged.  

- **Knockout Match Analysis:**  
  - Estimated probabilities of teams winning Quarter-finals, Semi-finals, and Finals.  

- **Playing Strategy Analysis:**  
  - Studied goal-scoring behavior across match halves (1st Half, 2nd Half, Extra Time).  

- **Substitution Impact:**  
  - Measured effect of substitutions on match outcomes.  

- **Expected vs Actual Goals:**  
  - Compared actual vs. expected goals (xG) for 2018 and 2022 to find overperforming/underperforming teams.  

---

## 🧠 Key Findings and Conclusions

- **Top Performers:**  
  - Brazil holds the most World Cup titles, followed by Italy and Argentina.  

- **Consistent Participant:**  
  - Brazil is the only nation to appear in every tournament.  

- **Emerging Teams:**  
  - Qatar, Canada, and Wales joined as new participants in recent years.  

- **Ranking Trends:**  
  - Clear breakdown of teams with improved or declined FIFA rankings.  

- **Knockout Stage Dynamics:**  
  - Teams play more aggressively in the 2nd half during knockout games.  
  - Mexico, Romania, Peru, Spain, and Canada displayed distinct strategies in knockouts.  

- **Substitution Effectiveness:**  
  - While substitutes rarely scored, substitutions improved team performance in multiple matches — showing effective coaching decisions.  

- **Performance Insights (2018 & 2022):**  
  - Argentina underperformed at home but excelled abroad (2018).  
  - Russia was a 2018 underdog, scoring far more than expected (home advantage).  
  - Netherlands overperformed in 2022 (+52% xG).  
  - Portugal scored 40% above expected goals in 2022.  
  - Brazil was the most overrated in both 2018 & 2022, underperforming relative to xG.  

---

## 🚀 Future Scope

- Incorporate **player-level statistics** (goals, assists, expected goals) for deeper insights.  
- Build **predictive models** to forecast match outcomes using machine learning.  
- Develop an **interactive Streamlit or Power BI dashboard** for real-time visualization.  
- Include **sentiment analysis** on fan reactions and social media during tournaments.  
- Extend dataset with **Euro Cup and Copa America** results for cross-tournament comparison.

---

## 💻 How to Reproduce the Analysis

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/fifa-world-cup-eda.git
   cd fifa-world-cup-eda
