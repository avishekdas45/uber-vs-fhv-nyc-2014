# 🚕 🚕  Uber- New York 2014
Python-based Business Analytics project on Uber ride patterns in NYC (Apr–Sep 2014). Includes a July 2014 comparison vs traditional FHV cabs.


<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/cc/Uber_logo_2018.png" alt="Uber" width="200"/>
</p>


## 📚 Table of Contents

- [🚕 About Uber](#-about-uber)
- [🚖 Uber NYC Trip Analysis & FHV Comparison (2014)](#-uber-nyc-trip-analysis--fhv-comparison-2014)
- [📊 Project Overview](#-project-overview)
- [🧹 Data Cleaning](#-data-cleaning)
- [🗽 Uber NYC Analysis (Apr–Sept 2014)](#-uber-nyc-analysis-aprseptember-2014)
- [🔍 Comparative Analysis: Uber vs Traditional FHV (July 2014)](#-comparative-analysis-uber-vs-traditional-fhv-july-2014)
- [📝 Conclusion](#-conclusion)
- [🌍 Visualizations](#-visualizations)
- [📸 Snapshots](#-snapshots)
- [📂 Files](#-files)
- [🛠 Technologies Used](#-technologies-used)
- [💡 Business Analytics Skills Demonstrated](#-business-analytics-skills-demonstrated)
- [🚀 Run Locally](#-run-locally)
- [🙌 Acknowledgements](#-acknowledgements)
- [📬 Contact](#-contact)

---

## 🚕 About Uber

[Uber](https://www.uber.com) is a global ride-hailing platform that revolutionized urban transportation through its app-based model. Launched in 2009, Uber quickly gained popularity by offering convenient, on-demand rides and redefining personal mobility. New York City became one of Uber’s early major markets, setting the stage for significant shifts in the taxi and for-hire vehicle industry.

---

## 🚖 Uber NYC Trip Analysis & FHV Comparison (2014)

This project presents a detailed **exploratory and comparative analysis** of Uber pickups in NYC, focused on:  
✔ Uber ride demand patterns  
✔ Seasonality trends  
✔ Hourly and weekly behaviors  
✔ Market share Uber vs traditional For-Hire Vehicles (FHV)  



## 📊 Project Overview

This analysis consists of two parts:

1️⃣ **Uber NYC Trip Analysis (April - September 2014)**  
2️⃣ **Comparative Analysis: Uber vs Traditional FHV Providers (July 2014)**  

Both analyses were done using Python (Pandas, Matplotlib, Seaborn) in Jupyter Notebooks.

---

## 🧹 Data Cleaning

Performed initial cleaning and preprocessing including:

- Removing duplicates and handling missing values.
- Converting `date_added` to datetime format.
- Extracting year and month from the date field.

---

## 🗽 Uber NYC Analysis (Apr–Sept 2014)

### Key Findings
---

- Demand peaks at **17:00 hours** (336,190 trips) — aligning with NYC’s end-of-workday traffic.  
- **82% increase in trips from April to September** driven by warmer weather, tourism, and outdoor events.  
- Weekday trips are **~20% higher on average** than weekend trips.
- Mon-Fri: High demand between **16:00–22:00**, peaking at **17:00**.  
- Friday-Saturday: Extended demand into late night / early morning hours.

---

## 🔍 Comparative Analysis: Uber vs Traditional FHV (July 2014)

### Key Findings
---

- **Uber captured 79.1%** of total trips in July 2014.  raditional providers like Carmel, Dial7, and Firstclass lagged far behind.
- Uber consistently outperformed other providers across all weekdays. Carmel was second, but with a large gap.
- Uber handled **79.2% of weekday trips** and **78.5% of weekend trips**.  
- Uber also maintained demand overnight (12 AM–6 AM), unlike traditional providers.

---

## 📝 Conclusion

Uber’s dominance in NYC during 2014 was driven by:

- Operational scalability and 24/7 service
- App-based convenience and flexibility
- Strong market penetration across all time segments

**Recommendation:**  
Traditional FHV providers should:
- Extend service hours
- Embrace digital platforms
- Introduce dynamic pricing or loyalty schemes  

---

## 🌍 Visualizations

Visuals created using `Matplotlib`, `Seaborn`, and `WordCloud` include:

- Bar Charts.
- Heatmaps.
- Pie Charts.
- Scatterplot.
- Time analysis

---
## 📸 Snapshots

<img width="1166" alt="1" src="https://github.com/user-attachments/assets/b0ff9b87-c668-4882-808c-c457aaf4d4da" />

<img width="1167" alt="2" src="https://github.com/user-attachments/assets/453611c0-df46-4e64-bbbd-4077306bc9bb" />

<img width="1130" alt="combine" src="https://github.com/user-attachments/assets/0beb5f6c-18e2-455b-a37c-75a60fd695b0" />
<img width="1153" alt="Screenshot 2025-06-23 at 20 37 32" src="https://github.com/user-attachments/assets/922e2d72-0f7d-422e-82ca-083e80f2d7ec" />
<img width="989" alt="Heatmap" src="https://github.com/user-attachments/assets/d0fcb8ac-c7cc-4812-9972-e6b4b9b5e801" />
<img width="899" alt="Latlong" src="https://github.com/user-attachments/assets/4540c99b-f811-427e-a53b-1f307887b5b5" />


---

## 📂 Files

| File | Description |
|-------|-------------|
| `UberNYC_analysis.ipynb` | Exploratory analysis of Uber trip patterns from April to September 2014 |
| `Final Combine Analysis.ipynb` | Comparative analysis of Uber vs traditional FHV cabs (July 2014) |

---

## 🛠 Technologies Used

| Tool | Purpose |
|------|---------|
| **Python** | Core programming language |
| **Pandas** | Data cleaning & manipulation |
| **Matplotlib / Seaborn** | Data visualization |
| **Jupyter Notebook** | Interactive data analysis |

- Data: [Kaggle - Uber Pickups in NYC](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city)

---

## 💡 Business Analytics Skills Demonstrated

- Data cleaning & transformation  
- Feature engineering (hour, weekday, month, provider)  
- Data visualization (pie, bar, heatmaps, scatter plots)  
- Trend & competitive analysis  
- Generating actionable business insights  

---

## 🚀 Run Locally

Clone the repository:
```
git clone https://github.com/avishekdas45/uber-vs-fhv-nyc-2014.git
cd uber-vs-fhv-nyc-2014
jupyter notebook
```

---

## 🙌 Acknowledgements

- Dataset Source: [Kaggle - Uber Pickups in NYC](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city)

---

## 📬 Contact

**Avishek Das**  
Email: contact.avishek45@gmail.com  
GitHub: [avishekdas45](https://github.com/avishekdas45)

---


