# Kids Screen Time Analysis — Exploratory Data Analysis with Python

## 📌 Project Overview

Excessive screen exposure among children is an important digital-wellness concern. This project performs an end-to-end **Exploratory Data Analysis (EDA)** on children's screen-time data to identify patterns in screen usage, device preferences, demographic characteristics, and reported health impacts.

The analysis focuses on understanding how **age, gender, device type, urban/rural location, screen-time duration, and educational-to-recreational usage** relate to screen-time behavior and reported health concerns.

The project was developed using **Python in Jupyter Notebook** and applies practical data-analysis techniques that are relevant to real-world Business Analyst and Data Analyst roles.

---

## 🎯 Business / Analytical Objective

The primary objective is to transform raw children's screen-time data into actionable insights that can help stakeholders understand:

* Which age groups have higher screen exposure?
* Which devices are associated with higher average screen time?
* How does screen usage differ between urban and rural children?
* How many children exceed recommended screen-time limits?
* Which health impacts are reported most frequently?
* Is excessive screen time associated with anxiety and sleep problems?
* Are there observable differences across gender and age groups?
* What interventions could encourage healthier digital habits?

---

## 📊 Dataset

**Dataset:** `Kids_Screen_Time.csv`

The dataset contains variables including:

* Gender
* Age
* Primary Device
* Average Daily Screen Time (hours)
* Exceeded Recommended Limit
* Educational-to-Recreational Ratio
* Health Impacts
* Urban or Rural classification

The dataset covers children approximately **8–18 years old**.

---

## 🛠️ Technology Stack

| Category                  | Tools                |
| ------------------------- | -------------------- |
| Programming               | Python               |
| Development Environment   | Jupyter Notebook     |
| Data Manipulation         | Pandas               |
| Numerical Analysis        | NumPy                |
| Visualization             | Matplotlib           |
| Statistical Visualization | Seaborn              |
| Dataset                   | Kids Screen Time CSV |
| Documentation             | Markdown             |

---

## 🔎 Analytical Approach

### 1. Data Understanding

* Loaded the dataset using Pandas
* Examined dataset structure
* Reviewed column names and data types
* Studied categorical and numerical variables
* Checked the distribution of major variables

### 2. Data Quality Assessment

* Checked missing values
* Reviewed data types
* Examined categorical values
* Validated numerical fields
* Assessed overall data readiness

The project documentation reports minimal or no missing values in key columns.

### 3. Exploratory Data Analysis

The analysis explored:

* Age distribution
* Gender distribution
* Urban vs. rural distribution
* Primary device usage
* Daily screen-time patterns
* Recommended-limit status
* Educational vs. recreational screen usage
* Health-impact patterns

### 4. Relationship Analysis

Key relationships investigated include:

**Age → Screen Time**

Older children, particularly those in the 13–17 age range, tend to report higher screen usage.

**Device → Screen Time**

Smartphone users show the highest average screen-time levels among the primary-device groups analyzed.

**Urban/Rural → Screen Time**

Urban children generally report higher screen usage than rural children.

**Screen-Time Limit → Health Impact**

Children exceeding recommended screen-time limits show higher reported instances of anxiety and sleep-related problems.

**Device → Health Impact**

Smartphone users are reported to have more multiple health-impact observations than TV or tablet users.

---

## 💡 Key Insights

### 📱 1. Smartphones are the dominant device

Smartphones emerge as the primary screen device and are associated with the highest average screen-time levels.

### 👦 2. Teenagers show greater screen exposure

Children aged approximately 13–17 tend to spend more time on screens than younger children.

### 🏙️ 3. Urban children show higher screen usage

Urban participants generally report higher screen time, potentially reflecting greater access to digital devices and engagement.

### ⏰ 4. A significant number exceed recommended limits

The analysis identifies a substantial group of children whose daily screen time exceeds the recommended threshold.

### 😴 5. Sleep and anxiety are important health concerns

Anxiety, eye strain, and poor sleep are among the most frequently reported health impacts.

### 📱 6. Excessive screen time and health concerns move together

Children exceeding recommended limits report higher instances of anxiety and sleep problems. This should be interpreted as an **observed association in the dataset, not proof of causation**.

### 👁️ 7. Eye strain is prominent among early-to-mid teens

Eye strain is particularly common among children aged 13–15, who are also frequent smartphone users.

---

## 📈 Recommended Visualizations

The project can be presented through:

* Age Distribution Chart
* Gender Distribution
* Urban vs. Rural Comparison
* Primary Device Distribution
* Average Screen Time by Device
* Average Screen Time by Age
* Recommended Limit Comparison
* Health Impact Distribution
* Screen Time vs. Health Impact
* Device vs. Health Impact
* Urban/Rural vs. Screen Time
* Educational-to-Recreational Ratio Analysis

---

## 🎯 Recommendations

Based on the analysis, potential interventions include:

1. Encourage structured daily screen-time limits.
2. Promote outdoor activities, reading, hobbies, and other screen-free alternatives.
3. Create awareness programs around digital wellness.
4. Establish device-free periods such as mealtimes and before bedtime.
5. Monitor smartphone usage through parental controls.
6. Develop targeted digital-wellness initiatives for teenagers.
7. Introduce digital-health programs in urban schools.
8. Encourage early identification of sleep, anxiety, and vision-related concerns.
9. Promote healthy screen habits through parental role modeling.
10. Introduce screen-awareness education and non-digital breaks in schools.

These recommendations are aligned with the project's documented recommendations.

---

## 💼 Business Analyst Perspective

Although this is a Python EDA project, it demonstrates several transferable Business Analyst skills:

**Problem Definition → Data Understanding → Data Validation → Exploratory Analysis → Pattern Identification → Insight Generation → Stakeholder Recommendations**

The project demonstrates the ability to convert raw data into meaningful findings rather than simply producing charts.

---

## 🧠 Skills Demonstrated

* Exploratory Data Analysis
* Data Cleaning
* Data Validation
* Descriptive Analysis
* Categorical Analysis
* Numerical Analysis
* Data Visualization
* Correlation / Relationship Analysis
* Pattern Identification
* Insight Generation
* Recommendation Development
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Analytical Storytelling

---

## 📁 Repository Structure

```text
Kids-Screen-Time-EDA/
│
├── 📂 data/
│   └── Kids_Screen_Time.csv
│
├── 📂 notebook/
│   └── EDA_with_Kids_Screen_Time_Data_Advanced.ipynb
│
├── 📂 reports/
│   └── EDA_with_Screentime_Data.pdf
│
├── 📂 images/
│   └── charts_and_visualizations/
│
└── README.md
```

---

## 🚀 How to Run the Project

### Step 1 — Clone the repository

```bash
git clone https://github.com/yourusername/Kids-Screen-Time-EDA.git
```

### Step 2 — Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3 — Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 4 — Open

```text
EDA_with_Kids_Screen_Time_Data_Advanced.ipynb
```

### Step 5 — Run the notebook cells sequentially.

---

## 📌 Project Outcome

This project demonstrates how exploratory data analysis can be used to identify behavioral patterns and potential digital-wellness concerns in children's screen-time data.

The most important analytical takeaway is that **screen-time behavior varies by age, device, and location, while higher screen exposure is associated with greater reporting of certain health concerns within the dataset**.

---

## 👩‍💻 Author

**Neha Bhatt**

Aspiring Business Analyst | Data Analytics | Python | SQL | Excel | Power BI | Tableau

---

## ⭐ Portfolio Value

This project demonstrates the ability to:

> **Ask the right analytical questions → analyze data → identify patterns → communicate insights → recommend actionable interventions.**

That analytical thinking is the core value I aim to demonstrate through my Business Analyst portfolio.
