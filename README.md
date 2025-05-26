# NEO-Watcher-Project
# 🚀 Near-Earth Object Watcher

This project connects to NASA’s Near-Earth Object (NEO) API to fetch daily asteroid approach data and outputs a styled Excel report.

## 📌 What It Does

- Fetches yesterday's NEO data from NASA
- Extracts:
  - Object name
  - Estimated diameter (min & max in meters)
  - Distance from Earth (km)
  - Relative velocity (km/hr)
  - Hazardous flag
- Generates an Excel report:
  - `Summary` sheet with total & hazardous counts
  - `NEO_Data` sheet with detailed rows
  - Hazardous rows are highlighted in red

## 📂 Files

- `NEO_Watcher.ipynb`: Jupyter notebook with full code
- `neo_report.xlsx`: Sample Excel output
- `README.md`: Project overview

## 💻 Tech Stack

- Python 3
- `requests`
- `pandas`
- `xlsxwriter`
- NASA’s [NeoWs API](https://api.nasa.gov/)

## 🌍 Real-World Use Cases

- Daily briefings for astronomers or science educators
- Teaching data extraction from public APIs
- Freelance Excel automation projects with real science data

---

Created by Shemar Ricketts · Freelance Python & Data Analyst
