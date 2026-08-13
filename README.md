# ⚡ Electric Vehicle Population Analysis

<p align="center">

### 🚗 Exploring EV Adoption, Market Trends & Vehicle Insights

**Python • Pandas • NumPy • Matplotlib • Seaborn**

<br>

<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Seaborn-Visualization-4C72B0?style=for-the-badge"/>

</p>

---

## 📌 About The Project

This project performs **Exploratory Data Analysis (EDA)** on **153,830 electric vehicle records** to understand EV adoption patterns, vehicle types, manufacturers, models, geographic concentration, and pricing-related trends.

The project follows a complete data analysis workflow:

**Data Understanding → Data Cleaning → EDA → Visualization → Insights**

---

## 📊 Project at a Glance

<p align="center">

|  📁 Records | 📌 Features | 🏭 Manufacturers | 🚗 Models | 🏙️ Cities |
| :---------: | :---------: | :--------------: | :-------: | :--------: |
| **153,830** |    **20**   |      **37**      |  **127**  |   **684**  |

</p>

---

## 🎯 Business Questions

🔋 **EV Type**
Which is more common: **BEV or PHEV?**

📈 **Adoption Trend**
How has EV representation changed across model years?

🏭 **Market Presence**
Which manufacturers have the highest representation?

🚗 **Popular Models**
Which EV models appear most frequently?

🌎 **Geographic Distribution**
Which states, counties, and cities have the highest EV concentration?

⚡ **Range vs Price**
What relationship exists between **Electric Range** and **Base MSRP**?

---

## 🛠️ Tech Stack

```text
🐍 Python
🐼 Pandas
🔢 NumPy
📊 Matplotlib
📈 Seaborn
📓 Jupyter Notebook
💻 PyCharm
🌐 Git & GitHub
```

---

## 🧹 Data Cleaning

The dataset was prepared before analysis by:

* 🔍 Checking data types and dataset structure
* ❌ Identifying missing values
* 📊 Calculating missing-value percentages
* 🔁 Checking duplicate records
* 🧩 Handling categorical missing values using **Mode**
* 🔢 Handling numerical missing values using **Mean**

---

# 📈 Analysis & Visualizations

### 🔋 01. BEV vs PHEV

| Vehicle Type                       |     Records |     Share |
| :--------------------------------- | ----------: | --------: |
| 🔋 Battery Electric Vehicle        | **119,396** | **77.6%** |
| 🔌 Plug-in Hybrid Electric Vehicle |  **34,434** | **22.4%** |

> **Insight:** BEVs clearly dominate the dataset.

---

### 🏭 02. Top EV Manufacturers

| Rank | Manufacturer |   Vehicles |
| :--: | :----------- | ---------: |
|  🥇  | **Tesla**    | **69,601** |
|  🥈  | Nissan       |     13,649 |
|  🥉  | Chevrolet    |     12,242 |
|  4️⃣ | Ford         |      7,817 |
|  5️⃣ | BMW          |      6,620 |

> **Insight:** Tesla has a significantly higher representation than other manufacturers in this dataset.

---

### 📅 03. EV Trends by Model Year

The analysis compares **BEV and PHEV representation across model years** to understand how EV presence has changed over time.

---

### 🌎 04. Geographic Analysis

Analyzed EV concentration across:

**State → County → City**

> **Insight:** Washington (WA) represents the overwhelming majority of records in this dataset.

---

### ⚡ 05. Electric Range vs Base MSRP

A scatter plot was used to explore the relationship between:

**Electric Range ↔ Base MSRP**

This helps investigate whether higher-range vehicles tend to have higher listed prices.

---

## 💡 Key Insights

> 🔋 **BEVs represent ~77.6%** of all records.

> 🏭 **Tesla leads** the dataset with **69,601 vehicles**.

> 📈 Recent model years contain substantially more EV records than earlier years.

> 🌎 **Washington dominates** the geographic distribution of this dataset.

> 🚗 A small group of EV models has significantly higher representation.

> ⚡ Range and MSRP were analyzed to explore pricing-related patterns.

---

## 📸 Project Preview

> **Add your best notebook screenshots here**

### 🔋 EV Type Distribution

<!-- Add screenshot -->

### 🏭 Top EV Manufacturers

<!-- Add screenshot -->

### 📈 EV Type by Model Year

<!-- Add screenshot -->

### ⚡ Electric Range vs Base MSRP

<!-- Add screenshot -->

---

## 📂 Project Structure

```text
Electric-Vehicle-Population-Analysis/
│
├── 📓 Electric_Vehicle_Population_Analysis.ipynb
├── 📊 Electric_Vehicle_Population_Data.csv
├── 📄 README.md
├── 📦 requirements.txt
└── 🚫 .gitignore
```

---

## 🚀 Future Improvements

🔹 Interactive **Streamlit Dashboard**
🔹 Power BI Dashboard
🔹 Interactive EV Maps
🔹 Year-over-Year Growth Analysis
🔹 Manufacturer Market Share Analysis

---

## 👨‍💻 Author

<p align="center">

### **Raushan Abhishek**

**Computer Science & Engineering | Data Science**

🎯 Aspiring Data Analyst

`Python` • `SQL` • `Excel` • `Pandas` • `NumPy` • `Matplotlib` • `Seaborn`

</p>

---

<p align="center">

⭐ **If you found this project useful, consider giving it a star!**

</p>
