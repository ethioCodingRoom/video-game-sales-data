# Tableau Video Game Sales Practice

This repository contains a **practice project for Tableau data visualization** using a public video game sales dataset. The goal is to create insightful dashboards and charts demonstrating data analysis skills.

---

## Contents

- `data/video_game_sales.csv` — Original dataset used for analysis  
- `data/video_game_sales_cleaned.csv` — Cleaned dataset ready for Tableau  
- `notebooks/01_data_cleaning.ipynb` — Jupyter Notebook for data cleaning and exploration  
- `tableau/video_game_sales_workbook.twbx` — Tableau workbook  
- `images/dashboard_screenshot.png` — Optional screenshots of dashboards  
- `README.md` — Project description and instructions  

---

## Purpose

- Practice data cleaning and visualization in Tableau  
- Build a strong portfolio for freelance projects on Upwork  
- Showcase ability to create meaningful data stories from raw data  

---

## How to Use

1. Download or clone this repository.  
2. Open the CSV dataset in Tableau or your preferred tool.  
3. Explore the dashboards and customize as needed.  
4. Use this project as a reference for your own Tableau work or proposals.  

---

## Overview

This project is a **data analytics and visualization practice** using the Video Game Sales dataset. The workflow includes:

1. Cleaning, exploring, and preparing the data in Python.  
2. Visualizing insights in Tableau dashboards.  

It is ideal for **practicing a full data analytics workflow**, creating dashboards, and showcasing skills for portfolios or Upwork projects.

---

## Project Structure


```Tableau-video-game-sales-practice/
│
├── data/
│ ├── video_game_sales.csv # Original dataset
│ └── video_game_sales_cleaned.csv # Cleaned dataset ready for Tableau
│
├── notebooks/
│ └── 01_data_cleaning.ipynb # Jupyter Notebook for data cleaning and exploration
│
├── tableau/
│ └── video_game_sales_workbook.twbx # Tableau workbook
│
├── images/
│ └── dashboard_screenshot.png # Optional dashboard screenshots
│
└── README.md # Project description
```


---

## Steps in the Project

1. **Data Import & Libraries**  
   Load the dataset using Python (`pandas`, `numpy`) and import visualization libraries (`matplotlib`, `seaborn`).

2. **Data Cleaning**  
   - Check for missing values  
   - Remove duplicates  
   - Rename columns  
   - Handle missing or inconsistent data

3. **Exploratory Data Analysis (EDA)**  
   - Summary statistics  
   - Distribution of sales  
   - Correlation between features  
   - Total sales by platform, publisher, and genre  

4. **Feature Engineering**  
   - Create total regional sales column  
   - Identify top-performing games  

5. **Data Export**  
   Export the cleaned dataset as `video_game_sales_cleaned.csv` for Tableau.

6. **Visualization in Tableau**  
   - Import the cleaned data  
   - Create dashboards:  
     - Global sales by platform  
     - Sales trends over the years  
     - Regional sales breakdown  

---

## Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook  
- Tableau Desktop  
- Git & GitHub  

---

## How to Run

1. Clone the repository:  
```bash
git clone https://github.com/<your-username>/tableau-video-game-sales-practice.git


