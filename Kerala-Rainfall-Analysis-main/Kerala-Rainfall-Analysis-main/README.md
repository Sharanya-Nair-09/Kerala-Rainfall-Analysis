# Kerala Rainfall Analysis 

Exploratory analysis of **Kerala’s rainfall patterns (1901–2018)** with a focus on **extreme monsoon events and flood years**.  
This project is an entry point into the field of **GeoAI / Environmental Intelligence** — combining data science with climate and geospatial analysis.

---

## Project Objectives
- Analyze **seasonal and annual rainfall trends** (JJAS monsoon, OND retreating monsoon, Annual totals).  
- Identify **extreme rainfall years** using statistical thresholds (95th percentile).  
- Compare **flood years vs non-flood years** in terms of rainfall intensity.  
- Study **decadal monsoon trends** to understand long-term changes in rainfall.  

---

## Dataset
1. **Kerala-Rainfall-Historical.csv**  
   - Source: [IMD / Climate Data Portal]  
   - Columns: Monthly rainfall, seasonal aggregates (JJAS, OND, ANNUAL).  

2. **kerala.csv**  
   - Contains **annual rainfall + flood year labels** (YES/NO).  

---

## Tools & Libraries
- **Python**   
- **Pandas** – data cleaning & analysis  
- **Matplotlib / Seaborn** – visualization  
- **Jupyter Notebook** – interactive exploration  

---

## Key Insights
- Kerala experiences strong variability in monsoon rainfall.  
- Extreme rainfall years (e.g., **2018 flood year**) stand out significantly above the 95th percentile threshold.  
- Retreating monsoon (OND) often contributes disproportionately to **flood-linked years**.  
- Decadal analysis shows **changing monsoon intensity** over time.  

---

## Repository Structure
Kerala-Rainfall-Analysis/
│
├── Kerala_Rainfall_Analysis_Week1.ipynb # Jupyter Notebook with EDA
├── Kerala-Rainfall-Historical.csv # Historical rainfall data
├── kerala.csv # Rainfall + flood labels
└── README.md # Project documentation


---

## Next Steps
- Integrate **geospatial datasets** (district boundaries, DEMs, river basins).  
- Use **satellite rainfall data (NASA GPM, IMD gridded rainfall)**.  
- Build **predictive ML models** to forecast flood risk.  

---

## 🌍 About This Project
This project is part of my journey into **GeoAI / Environmental Intelligence** — building systems that combine data, AI, and environmental science to solve real-world challenges like **climate risk, floods, and extreme weather events**.  

