# 🦈 SharkSafe Marine Travel & Adventure Agency

## 📌 Project Overview

**SharkSafe Marine Travel & Adventure Agency** is a data analytics project designed to explore historical shark incident data and transform it into actionable insights for the marine tourism industry.

SharkSafe organizes ocean recreation experiences such as **surfing, scuba diving, and shark-watching tours**. The company wants to develop a more **data-informed product and safety strategy** by understanding how recorded shark incidents vary across destinations, activities, seasons, and time periods.

Using historical shark incident data, this project analyzes:

* Incident frequency
* Fatality and severity
* Geographic location
* Activity type
* Shark species
* Seasonality
* Time patterns

The objective is not to predict individual shark encounters, but to identify historical patterns that can support **safer tour planning, destination selection, scheduling, and customer communication**.

---

## 🎯 Business Case

SharkSafe already sells marine tourism packages and wants to create a more **data-informed product and safety strategy**.

The objective of this project is to analyze historical shark incidents and identify patterns that could help the company make better decisions about:

* Destinations
* Marine activities
* Shark-watching locations
* Tour scheduling
* Customer safety communication

---

## 🔬 Main Hypothesis

> **Shark incident frequency and severity vary significantly according to location, activity, and season, and have decreased over time.**

---

## ❓ Key Business Questions

### 🌍 Which destinations are the safest for water sports?

Which countries and coastal regions show lower recorded incident frequency and fatality percentages?

### 🦈 Where should we investigate shark-watching tours?

Which locations show repeated shark encounters but relatively low historical fatality percentages?

### 🏄 Which activities have the highest number of recorded incidents?

How do activities such as surfing and swimming compare with submerged activities such as scuba diving?

### 🕐 When should tours and lessons be scheduled?

Are there particular months, seasons, or times of day associated with more recorded incidents?

### 📉 Is ocean recreation getting safer over time?

Have recorded shark incidents and fatality percentages decreased over the past decade?

---

# 🧪 Hypotheses

## H1 — Destination

**Recorded shark incidents and fatality percentages differ across countries and coastal regions.**

**Data used:**

* Country
* State / region
* Incident percentage
* Fatal incidents
* Fatality percentage

---

## H2 — Activity

**Surface activities such as surfing have a higher recorded incident frequency but a lower fatality percentage than submerged activities such as scuba diving.**

**Data used:**

* Activity
* Incident percentage
* Fatal incidents
* Fatality percentage

---

## H3 — Shark-Watching Destinations

**Some locations show repeated shark encounters but relatively low historical fatality percentages, making them candidates for further investigation as controlled shark-watching destinations.**

**Data used:**

* Country / region
* Species
* Incident percentage
* Fatality percentage

---

## H4 — Risk Reduction Over Time

**Global unprovoked shark attacks have decreased over the past decade, reducing recorded incident risk for ocean tourists.**

**Data used:**

* Year
* Fatality
* Incident type

---

## H5 — Seasonality

**Shark incidents show seasonal patterns, with some months or seasons having higher recorded incident frequencies.**

**Data used:**

* Month
* Season
* Incident frequency

---

# 📊 Visualizations

The project includes visualizations focused on translating the analysis into business insights:

* 🏄 Comparison of destinations and marine activities
* 📉 Historical trend of incidents and fatality percentages
* 🦈 Potential shark-watching locations
* 📅 Seasonal distribution of incidents
* 🛟 Safety insights for activities with higher recorded severity
* 🥥 Bonus: comparison of shark fatalities with unusual risks such as falling coconuts

---

# 🧹 Data Cleaning

The dataset is cleaned and transformed using **Python and Pandas**.

Main steps include:

* Handling missing values
* Removing unnecessary columns
* Standardizing column names
* Cleaning country and region values
* Standardizing fatality classifications
* Cleaning activity categories
* Converting dates and years
* Creating month and season variables
* Identifying incident types
* Standardizing shark species information where possible
* Checking duplicated records

---

# 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **Jupyter Notebook**
* **GitHub**

---

# 📈 Project Workflow

### 1. Data Understanding

Explore the original dataset, columns, missing values, duplicates, and data quality.

### 2. Data Cleaning

Clean and standardize the variables required for analysis.

### 3. Exploratory Data Analysis

Investigate patterns across destinations, activities, fatalities, seasons, and years.

### 4. Hypothesis Analysis

Evaluate hypotheses H1–H5 using the cleaned dataset.

### 5. Data Visualization

Create business-friendly charts and maps.

### 6. Business Insights

Translate analytical results into recommendations for SharkSafe's tourism strategy.

---

# ⚠️ Data Limitations

Historical shark incident data should be interpreted carefully.

A higher number of recorded incidents does **not necessarily mean that a destination or activity is more dangerous**.

Important limitations include:

* Tourism exposure differs significantly between locations.
* Popular beaches may record more incidents because more people enter the water.
* Reporting practices vary between countries and historical periods.
* Some records contain missing or uncertain information.
* Shark species identification may not always be confirmed.
* Incident counts alone cannot determine an individual's probability of experiencing a shark encounter.

For this reason, the project focuses primarily on **recorded historical patterns rather than absolute individual risk**.

---

# 💼 Business Value

The analysis can help SharkSafe:

* 🌍 Compare marine tourism destinations
* 🏄 Understand activity-related incident patterns
* 🦈 Investigate potential shark-watching destinations
* 📅 Improve tour scheduling
* 🛟 Develop activity-specific safety recommendations
* 📊 Communicate shark risk using data
* 💡 Build more data-informed tourism products

---

# 📚 Data Source

**Global Shark Attack File (GSAF)**

Historical shark incident data used for educational data analysis purposes.

---

## 👩‍💻 Author

**Berta Nieto Romero | Juliana Therezo | Sofija Šarafejeva | Yurii Slobodchukov**

Data Analytics Project

`Python` • `Pandas` • `Data Cleaning` • `EDA` • `Data Visualization` • `Business Analysis`
