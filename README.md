# 📊 Customer Database — Exploratory Data Analysis (EDA)

An end-to-end **Exploratory Data Analysis** project on a real customer dataset, using Python to clean raw data and extract meaningful business insights through visualizations.

---

## 🔍 Project Overview

This project analyzes a sample of **100 customers** to answer three key business questions:

- 🌍 **Where** are our customers located?
- 📈 **When** did subscription growth peak?
- 🔒 **How secure** are customer websites? (HTTP vs HTTPS)

---

## 📸 Key Findings

| Question | Finding |
|---|---|
| 🌍 Top customer locations | Solomon Islands, Dominican Republic, Bulgaria |
| 📈 Peak subscription year | **2021** had the highest new subscriptions |
| 🔒 Security gap | **57% HTTP** vs **43% HTTPS** — a significant security concern |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Python 3** | Core language |
| **Pandas** | Data loading, cleaning, manipulation |
| **Matplotlib** | Charts and visualizations |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 📁 Project Structure

```
my_E.D.A/
│
├── __main__.ipynb       # Full EDA notebook with code + visualizations
└── customers-100.csv    # Raw dataset (100 customer records)
```

---

## 📋 Analysis Workflow

**1. Data Loading & Inspection**
- Load CSV with Pandas
- Check shape, dtypes, and basic statistics
- Identify missing values

**2. Data Cleaning**
- Handle missing values
- Convert date columns to proper datetime format for time-series analysis

**3. Geographic Analysis**
- Group customers by country
- Plot top 10 countries by customer count (bar chart)

**4. Subscription Trends**
- Extract year from subscription date
- Plot new subscriptions per year (2020–2022)
- Identify peak growth period

**5. Security Audit**
- Parse customer website URLs
- Classify each as HTTP or HTTPS
- Calculate adoption rate (pie chart / count)

---

## ⚙️ How to Run

```bash
# Clone the repository
git clone https://github.com/kwstassrp6991/my_E.D.A.git
cd my_E.D.A

# Install dependencies
pip install pandas matplotlib jupyter

# Launch the notebook
jupyter notebook __main__.ipynb
```

---

## 🧠 What I Learned

| Concept | How I used it |
|---|---|
| **Data cleaning** | Handling nulls, fixing date formats with `pd.to_datetime()` |
| **GroupBy & aggregation** | Counting customers per country and per year |
| **String operations** | Parsing URLs to check for HTTPS with `.str.startswith()` |
| **Matplotlib** | Bar charts and pie charts for visual storytelling |
| **Data storytelling** | Turning raw numbers into actionable insights |

---

## 🚀 Future Improvements

- [ ] Add more visualizations (heatmaps, time-series lines)
- [ ] Expand dataset beyond 100 customers
- [ ] Add statistical analysis (correlation, distribution tests)
- [ ] Build an interactive dashboard with Plotly or Seaborn

---

*This project was built as part of my Python Data Analysis learning journey.*
