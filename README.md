# 🩺 Dr Death—Power BI Analysis

## 🖥️ Power BI Desktop

**What is Power BI?**  
Power BI is data visualization software that enables users to create dashboards, charts, and geographic maps, all powered by one or more data sources.  
It offers robust features to collect, process, analyze, and dynamically visualize data for strategic decision-making.

Released in summer 2015 and updated regularly, Power BI stands out as a **market leader** in business intelligence and data visualization software, providing advanced reporting, an extensive library of visualizations (bar charts, maps, heatmaps, treemaps, etc.), seamless integration with many data sources, and collaborative features for sharing interactive dashboards[web:16][web:17][web:18][web:21].

---

## 📂 Data Context & Analytical Question

The analysis focuses on Harold Shipman—a respected physician in Hyde, Greater Manchester, who, between 1975 and 1998, overdosed at least 215 elderly patients with opiates.

The provided data is spread across two CSV files:

**shipman-confirmed-victims.csv**  
- DateofDeath
- Name
- Age
- PlaceofDeath
- Decision
- yearOfDeath
- gender
- fractionalDeathYear
- ageBracket
- gender2

**shipman-times-comparison.csv**  
- Hour
- Shipman (count)
- Comparison (reference group)

**Key question:**  
*What kinds of people did Harold Shipman murder, and when did they die?*

---

## 📈 Key Visual & Analytical Findings via Power BI

Through dashboards and visuals built in Power BI:

- **Demographics:**
  - 45% of victims were aged 75–84
  - 83% were women
  - Most deaths occurred at home and between 1995 and 1997 (204 victims, ~30 per year)
  - Only 15 out of 215 victims were officially declared

- **Timing Patterns:**
  - Shipman’s declared times of death were far more clustered (often at 15:00–16:00) than those from other doctors.
  - These unusual patterns raise suspicions about the authenticity of reported death times.

- **Heatmap Insights:**
  - Age, date, and time of death were the main features used for analysis.
  - Visualization focused on patterns correlating age brackets and declared times.

---

## 🧠 Conclusion

Harold Shipman primarily targeted elderly women aged 75–84 (forming part of the 15 official victims).  
However, his victims also included men of all older age ranges (37 illicit victims, none officially recognized, many cremated).  
The youngest known victim was 40 years old. The murder spree stretched from 1975 to 1998, with peak years from 1995 to 1997 (30–37 murders annually).

Power BI enabled the clear identification of demographic and temporal trends in the victim profiles, and made visible the atypical reporting behaviors that set Shipman apart from other practitioners[web:16][web:17][web:18][web:21][web:22].
