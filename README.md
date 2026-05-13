# IBM Data Analyst Professional Certificate – Course 8 Part 2: Dashboard with Plotly and Dash

**Project Title:** Automobile Sales Statistics Dashboard – Interactive Data Visualization

This is Part 2 of the final project for **Course 8** of the IBM Data Analyst Professional Certificate on Coursera.

## Overview

- Built an interactive dashboard using **Plotly** and **Dash** to visualize automobile sales statistics during recession and non-recession periods
- Implemented dropdown menus to allow dynamic switching between two report types
- Created callback functions to update visualizations in real-time based on user input
- Displayed four charts per report in a clean 2x2 grid layout

## Technologies Used

- Python
- Dash
- Plotly Express
- Plotly Graph Objects
- pandas

## Dashboard Features

### Yearly Statistics Report
- Line chart showing average automobile sales for the entire period
- Line chart displaying total monthly automobile sales for the selected year
- Bar chart comparing average vehicles sold by vehicle type in the selected year
- Pie chart showing total advertising expenditure by vehicle type for the selected year

### Recession Period Statistics Report
- Line chart showing average automobile sales fluctuation during recession periods
- Bar chart displaying average vehicles sold by vehicle type during recessions
- Pie chart representing total advertising expenditure share by vehicle type during recessions
- Bar chart analyzing the effect of unemployment rate on vehicle type and sales during recessions

## Key Features of the App

- Two interactive dropdown menus — one for report type selection and one for year selection
- Year dropdown dynamically enables and disables based on the selected report type
- Real-time chart updates powered by Dash callback functions
- Responsive 2x2 chart grid layout for clean data presentation

## Files

- `DV0101EN-Final-Assign-Part-2-Questions.py` – Main dashboard application

## How to Run

```bash
pip3.8 install setuptools
python3.8 -m pip install packaging
python3.8 -m pip install pandas dash
pip install more-itertools
python3.8 DV0101EN-Final-Assign-Part-2-Questions.py
```

Then open the app in your browser at `http://127.0.0.1:8050/`

## About

Interactive dashboard built with Plotly and Dash to visualize automobile sales statistics during recession and non-recession periods – Final project Part 2 for Course 8 of the IBM Data Analyst Professional Certificate

---

**Part of the full IBM Data Analyst Professional Course Series
