# 🔍 EDA Findings: Forest Fires in Portugal

This document summarizes key insights derived from the exploratory data analysis (EDA) of the Forest Fires dataset collected from the Montesinho natural park in Portugal.

---

## 🗓️ Temporal Patterns

- **August and September** recorded the **highest number of fire incidents**, suggesting seasonal susceptibility.
- **July and May**, while having fewer fire counts, showed a **higher average burned area**, indicating more severe fires during those months.

---

## 🧭 Spatial Distribution

- Fires are **not evenly spread** across the park.
- Specific **grid zones show clustering of fires**, implying localized geographic or land-use vulnerabilities.

---

## 🌡️ Environmental Influences

- **Temperature (`temp`)**: Slight positive correlation with fire size — warmer days tend to result in larger fires.
- **Relative Humidity (`RH`)**: Moderate **negative correlation** with fire size — fires are more intense during drier conditions.
- **Wind Speed (`wind`)**: Weak positive correlation — higher wind may aid in the spread, but not strongly predictive alone.
- **Rain (`rain`)**: Almost always zero on fire days — not a significant factor once fire has started.

---

## 🔥 Fire Behavior Indices

- **ISI (Initial Spread Index)**: Positively correlated with burned area — indicates fire intensity and spread potential.
- **FFMC, DMC, DC**: Show general variation across the dataset; useful for modeling risk levels.

---

## 📈 Pairwise Relationships

- **Pairplot analysis** of `temp`, `RH`, `wind`, `rain`, `ISI`, and `log_area` revealed:
  - **RH inversely related** to fire size.
  - No strong linear patterns overall — suggests the need for **non-linear modeling** or **feature engineering** in ML tasks.

---

## 🧪 Distribution Observations

- **Burned area** is **highly right-skewed** — most fires are small, but a few extreme cases burn large areas.
- A **log transformation** of the `area` feature helps in stabilizing variance and improving modeling performance.

---

## 📌 Additional Observations

- Boxplots showed **outliers** in rain and wind.
- Fire spread tends to occur under **moderate temperature, low humidity, and minimal rain** conditions.

---

## ✅ Conclusion

This EDA has identified key temporal, spatial, and environmental factors influencing forest fires in Portugal. These findings can help:
- Inform **predictive models**.
- Support **fire risk assessment** tools.
- Aid **policy and land management decisions** for high-risk months and zones.

---

📊 *Further steps could include supervised ML modeling, clustering high-risk zones, or integrating remote sensing data for deeper analysis.*
