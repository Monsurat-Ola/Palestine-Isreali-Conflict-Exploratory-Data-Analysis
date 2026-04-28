# 📊 Israeli–Palestinian Conflict Fatalities (2000–2023)



---

## 🎯 Research Objective
Is the intensity of the conflict increasing linearly, or does it follow a cyclical pattern? This project evaluates fatality rates across time, regions, and causes to identify structural trends in conflict intensity.

## 📁 Dataset Overview
* **Source:** B'Tselem Fatality Database
* **Scope:** 11,124 records (2000 – 2023)
* **Tech Stack:** `Python` (`pandas`, `matplotlib`, `seaborn`, `plotly`)

## 🛠️ Methodology
1. **Data Cleaning:** Implemented median imputation for missing ages and categorical fills for unknown records.
2. **Feature Engineering:** Developed new metrics: `life_stage`, `is_minor`, and `ammo_category`.
3. **Analysis:** Executed a multi-dimensional EDA (Univariate to Temporal) to identify spikes vs. baseline trends.

## 📈 Key Insights
* **Intensity:** The conflict is **cyclical, not linear**. Fatalities are increasingly concentrated in extreme "bursts" (e.g., 2002, 2009, 2014).
* **Demographics:** Palestinians account for 90.7% of fatalities; 20.1% of all victims were minors (<18).
* **Geography:** Gaza remains the epicenter, representing 69.5% of total fatalities.
* **The "July Trap":** 77% of all July fatalities across 23 years occurred in a single month: July 2014.

