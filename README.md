# 🧠 AI Developer Productivity Analysis

This project explores the productivity patterns of AI developers based on various daily habits and working behaviors such as coding hours, coffee intake, sleep, distractions, AI tool usage, and more.

---

## 📁 Dataset Overview

**File:** `ai_dev_productivity.csv`  
**Rows:** 500  
**Target Column:** `task_success` (0 = Not Successful, 1 = Successful)

### 🔢 Key Features:
- `hours_coding`: Daily coding time in hours
- `coffee_intake_mg`: Daily caffeine intake (mg)
- `distractions`: Count of distractions during work
- `sleep_hours`: Total sleep in a day
- `commits`: Git commits made
- `bugs_reported`: Bugs reported in code
- `ai_usage_hours`: AI tool usage time (hrs)
- `cognitive_load`: Self-reported cognitive load (1-10)
- `task_success`: Whether the developer’s task was successful

---

## 📊 Exploratory Data Analysis (EDA)

### Statistical Summary:
- **Average Coding Time:** ~5 hrs/day
- **Average Sleep:** ~7 hrs/night
- **Average AI Tool Usage:** ~1.5 hrs/day
- **Mean Task Success Rate:** ~60%

### Key Insights from Pair Plot:
- Positive correlation between `hours_coding`, `commits`, and `task_success`
- Higher `distractions` and `bugs_reported` lower the success rate
- Balanced `ai_usage_hours` and `sleep_hours` tend to correlate with higher productivity

---

## 🔍 Objectives

- Analyze which behavioral traits are linked to successful task completion
- Understand the impact of AI tool usage on productivity
- Provide insights into habits that boost developer efficiency

---

## 🧪 Tools & Technologies

- **Language:** Python
- **Notebook:** JupyterLab
- **Libraries:** Pandas, Seaborn, Matplotlib, NumPy

---

## 📈 Future Work

- Feature engineering & scaling
- Classification modeling (Logistic Regression, Random Forest, etc.)
- Hyperparameter tuning & model evaluation
- Dashboard creation (Streamlit or Dash)

---

## ✍️ Author
Uzma Khatun – AI/ML Enthusiast & Data Science Student
