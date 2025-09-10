# Spotify-Stream-Analysis
This project transforms raw Spotify streaming data into actionable insights by combining data cleaning, feature engineering, and platform engagement metrics — all Python-powered and Power BI-ready
Spotify 2024 Data Cleaning & Feature Engineering with Python

# 🎵 Spotify 2024 Data Cleaning & Feature Engineering with Python

This repository contains a **complete Python workflow** for cleaning, transforming, and analyzing the *"Most Streamed Spotify Songs 2024"* dataset using **Google Colab**. The goal is to prepare a **Power BI–ready dataset** while demonstrating advanced Python data analysis skills.

---

## 🛠 What’s Included

### **1. Data Loading & Encoding Handling**
- Read CSV/Excel files from Google Drive.  
- Automatic handling of encoding issues (`UTF-8`, `latin1`, `cp1252`) to avoid errors.

### **2. Data Cleaning**
- Removed unwanted columns (e.g., ISRC, playlist counts from multiple platforms, TIDAL popularity).
- Handled missing values by dropping or filling as appropriate.  
- Converted string numbers with commas to numeric types.  
- Converted `release_date` to datetime.  
- Renamed columns to **Power BI–friendly format** (lowercase, underscores, no spaces or special characters).


![Removing unwanted cokumns](https://github.com/davidbashyr/Spotify-Stream-Analysis/blob/9766b06917d8dbacc8aca4a345a3a8f1eba73eda/images/Screenshot%2025-09-10%122746.png)
![Removing unwanted cokumns](https://github.com/davidbashyr/Spotify-Stream-Analysis/blob/9766b06917d8dbacc8aca4a345a3a8f1eba73eda/images/Screenshot%2025-09-10%122805.png)
![Removing unwanted cokumns](https://github.com/davidbashyr/Spotify-Stream-Analysis/blob/9766b06917d8dbacc8aca4a345a3a8f1eba73eda/images/Screenshot%2025-09-10%122846.png)

### **3. Feature Engineering & Insights**
- **Streams per Day:** Track streaming velocity relative to release date (up to end of 2024).  
- **Platform Engagement Metrics:**  
  - YouTube likes per 1,000 views  
  - TikTok likes per post  
  - Spotify streams per playlist  
  - Pandora streams per station  
  - Overall streams per playlist across multiple platforms  
- **Artist Analysis:**  
  - Total streams per artist  
  - Each track’s share of the artist’s total streams  
- **Explicit vs. Clean Tracks:** Average streams comparison


![Removing unwanted cokumns](https://github.com/davidbashyr/Spotify-Stream-Analysis/blob/9766b06917d8dbacc8aca4a345a3a8f1eba73eda/images/Screenshot%2025-09-10%123039.png)
![Removing unwanted cokumns](https://github.com/davidbashyr/Spotify-Stream-Analysis/blob/9766b06917d8dbacc8aca4a345a3a8f1eba73eda/images/Screenshot%2025-09-10%123103.png)
![Removing unwanted cokumns](https://github.com/davidbashyr/Spotify-Stream-Analysis/blob/9766b06917d8dbacc8aca4a345a3a8f1eba73eda/images/Screenshot%2025-09-10%123126.png)

### **4. Export & Integration**
- Saved cleaned, feature-rich dataset as CSV for **direct use in Power BI**.  
- Downloadable from Google Colab with a single command.



![Removing unwanted cokumns](https://github.com/davidbashyr/Spotify-Stream-Analysis/blob/9766b06917d8dbacc8aca4a345a3a8f1eba73eda/images/Screenshot%2025-09-10%122336.png)
![Removing unwanted cokumns](https://github.com/davidbashyr/Spotify-Stream-Analysis/blob/9766b06917d8dbacc8aca4a345a3a8f1eba73eda/images/Screenshot%2025-09-10%122406.png)

### **5. Best Practices & Showcase**
- Demonstrates **data cleaning, transformation, and feature engineering skills** in Python.  
- Ready for **LinkedIn portfolio**, highlighting reproducibility and Power BI integration.

---

## 💻 Technologies Used
- Python, Pandas, NumPy  
- Google Colab  
- CSV/Excel for data export  
- Power BI (for visualization after export)

CSV/Excel for data export

Power BI (for visualization after export)
