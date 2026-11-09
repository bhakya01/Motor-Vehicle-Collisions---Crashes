# 🚦 Predictive Traffic Telemetry and Crash Forensics
### Motor Vehicle Crash Data Analysis Using Python (2024–2026)
## 📌 1. Introduction

This project focuses on analyzing Motor Vehicle Crash Data from 2024 to 2026 using Python to understand road accident patterns, identify major contributing factors, and evaluate accident severity.

The dataset contains information about crash dates and times, geographic locations, vehicle types, contributing factors, and the number of people injured or killed.

The analysis helps identify accident trends, high-risk locations, vehicle involvement, and crash severity to support better road safety awareness and data-driven decision-making.

## 🎯 2. Project Objectives

- Identify accident trends across different years.
- Analyze accident frequency during Morning, Afternoon, Evening, and Night.
- Identify major contributing factors behind vehicle crashes.
- Analyze pedestrian, cyclist, and motorist injuries.
- Examine vehicle types involved in accidents.
- Evaluate crash severity and fatality patterns.
- Identify high-risk locations and accident trends.
- Generate meaningful insights for road safety improvement.

## 📂 3. Dataset Information

| Attribute | Details |
|---|---|
| Data Source | NYC Open Data |
| Dataset | Motor Vehicle Collisions - Crashes |
| Domain | Transportation / Road Safety |
| Geographic Coverage | New York City, USA |
| Years | 2024–2026 |
| File Format | CSV / Excel |
| Environment | Google Colab |
| Programming Language | Python |

## 📊 4. Dataset Structure

The dataset contains the following categories:

| Category | Important Columns |
|---|---|
| Date & Time | CRASH DATE, CRASH TIME |
| Geographic Details | BOROUGH, ZIP CODE, LATITUDE, LONGITUDE, LOCATION |
| Road Details | ON STREET NAME, CROSS STREET NAME, OFF STREET NAME |
| Casualties | NUMBER OF PERSONS INJURED, NUMBER OF PERSONS KILLED |
| Crash Factors | CONTRIBUTING FACTOR VEHICLE 1, CONTRIBUTING FACTOR VEHICLE 2 |
| Vehicle Details | VEHICLE TYPE CODE 2, VEHICLE TYPE CODE 3, VEHICLE TYPE CODE 4 |

## 🧹 5. Data Cleaning

The dataset was cleaned and prepared before performing Exploratory Data Analysis (EDA).

**Data Cleaning Activities:**

- Removed unnecessary columns such as VEHICLE TYPE CODE 2, ZIP CODE, and unused unnamed columns.
- Identified missing values using `isnull()`.
- Checked missing values before and after cleaning.
- Removed irrelevant columns to improve dataset quality.
- Reviewed column names and data types.
- Prepared the dataset for further analysis.

## ⚙️ 6. Feature Engineering

Feature engineering was performed to create useful columns for analysis.

**Column Renaming:**
- Renamed the relevant unnamed column as `Vechicle name 2`.
- Renamed `VEHICLE TYPE CODE 4` as `Vechicle name 1`.

**Crash Time Classification:**

Crash time was divided into four categories:

| Crash Hour | Time Period |
|---|---|
| 05:00 – 11:59 | Morning |
| 12:00 – 16:59 | Afternoon |
| 17:00 – 20:59 | Evening |
| 21:00 – 04:59 | Night |

**Crash Severity Classification:**

Crash severity was categorized into three types:

- No Reported Injury or Death: 11,774
- Injury: 8,825
- Fatal: 52

**Date Extraction:**

The CRASH DATE column was used to extract:
- Crash Year (2024–2026)
- Crash Month (1–12)
- Crash Day (1–31)

## 📈 7. Exploratory Data Analysis (EDA)

The following analyses and visualizations were performed:

1. Year-wise Crash Count Analysis
2. Monthly-wise Crash Distribution
3. Crash Time Period vs Crash Count
4. Vehicle Type vs Number of Crashes
5. Vehicle Collision and Injury Analysis
6. Vehicle Combination vs Motorist Deaths
7. Daily Motorist Fatality Analysis

## 🔍 8. Key Insights

### 8.1 Year-wise Crash Analysis

- 2024 recorded approximately 20,000 crashes.
- 2025 recorded approximately 350 fewer crashes compared with 2024.
- No crash records were available for 2026 in the analyzed dataset.
- The comparison indicates a slight decrease in recorded crashes in 2025.

### 8.2 Monthly-wise Crash Distribution

- Higher accident counts were observed during May and June.
- October and November also showed increased accident activity.
- January and February recorded comparatively lower accident counts.

### 8.3 Crash Time Period Analysis

| Time Period | Crash Count |
|---|---:|
| Afternoon | 5,809 |
| Morning | 5,718 |
| Night | 4,824 |
| Evening | 4,290 |

**Key Findings:**
- Afternoon recorded the highest number of crashes.
- Morning recorded the second-highest number.
- Evening recorded the lowest number of crashes.
- Higher crash counts during morning and afternoon may be associated with peak-hour traffic.

### 8.4 Vehicle Type Analysis

- Sedan recorded more than 8,000 crashes.
- Station Wagon / Sport Utility Vehicle recorded fewer than 7,000 crashes.
- Taxi, Pickup Truck, and Bus recorded approximately 1,500 crashes.
- Bike, Box Truck, and Motorcycle recorded approximately 500 crashes.
- Moped, Tractor, and Truck Diesel recorded approximately 100 crashes.

### 8.5 Vehicle Collision and Injury Analysis

- Sport Utility Vehicles recorded approximately 1,211 injuries.
- Sedans recorded approximately 1,794 injuries.
- Vehicle collision combinations contributed to motorist injury patterns.

### 8.6 Vehicle Combination vs Motorist Fatalities

- Sedan and Station Wagon / Sport Utility Vehicle recorded the highest displayed fatality count, with 5 motorist deaths.
- Other vehicle combinations, including Tractor Truck Diesel and Motorcycle, recorded 1 death.
- Most displayed vehicle combinations recorded zero or one death.

**Possible Risk Factors:**

Vehicle size, weight, visibility, collision speed, and impact direction may influence crash severity.

### 8.7 Daily Motorist Fatality Analysis

- January 2024 recorded the highest daily motorist death count, with 5 deaths on a single date.
- Most recorded dates showed zero or one motorist death.
- The graph showed mostly zero deaths on recorded dates during 2025 and early 2026.

## 🛠️ 9. Tools and Technologies

| Tools / Technologies | Purpose |
|---|---|
| Python | Programming and data analysis |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical calculations |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts and graphs |
| Google Colab | Development and execution environment |
| Excel / CSV | Dataset storage and handling |

## 📌 10. Final Outcome

The project successfully transforms raw motor vehicle crash data into meaningful insights using Python-based data analytics.

It helps understand:
- Accident trends across different years.
- Vehicle involvement in road accidents.
- Major contributing factors.
- Injury and fatality patterns.
- High-risk accident time periods.
- Vehicle collision and crash severity patterns.

These findings can support better road safety awareness, traffic management, and accident prevention strategies.

## 💡 11. Conclusion and Recommendations

This analysis highlights how traffic accidents in New York City are associated with commuting periods, seasonal patterns, vehicle types, and collision characteristics.

**Recommendations:**

1. **Targeted Traffic Monitoring:** Increase traffic monitoring and enforcement during peak afternoon hours.
2. **Seasonal Safety Campaigns:** Promote road safety awareness before the higher-crash months of May, June, October, and November.
3. **Vehicle Safety Awareness:** Encourage defensive driving, safe following distances, and seatbelt usage.
4. **Accident Prevention:** Focus on identifying major contributing factors and high-risk locations.
5. **Data-Driven Decisions:** Use crash analysis to support effective traffic management and road safety planning.

The project demonstrates the importance of Python-based data analytics in understanding road accident patterns and supporting informed road safety decisions.

## 👩‍💻 12. Author

**Bhakya M**

Data Analytics Learner | Python | SQL | Excel | Power BI

**GitHub:** https://github.com/bhakya01



