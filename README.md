# 🎓 Student Performance Cleaned Dataset  

---

## 📖 About the Dataset  
This dataset is designed for learners who want to **practice real-world data cleaning, exploratory data analysis (EDA), and machine learning (ML)**.  
It contains student demographics, study habits, and academic performance in **Python** and **Database (DB)** courses.  

Unlike raw datasets, this version is **cleaned and standardized** so you can directly focus on **analysis and modeling** 🚀  

---

## 📋 What’s Inside?  
- 👩‍🎓 **Demographics** → Age, Gender, Country, Residence  
- 📚 **Academics** → Entry Exam Score, Previous Education  
- ⏰ **Study Habits** → Weekly Study Hours  
- 🐍 **Python Scores** (0–100)  
- 🗄️ **DB Scores** (0–100)  
- 🏆 **Engineered Features** → *Performance Index*, *Study Efficiency*  

---

## 🧹 Cleaning Performed  
✔ Standardized inconsistent values (`M/F → Male/Female`, `Rsa → RSA`, etc.)  
✔ Fixed typos in `prevEducation` and `country`  
✔ Imputed missing values in **Python** & **DB** scores  
✔ Handled extreme outliers to improve data quality  

---

## 🚀 Use Cases  
🔹 **Regression** → Predict academic scores  
🔹 **Classification** → Identify high vs low performers  
🔹 **EDA & Visualization** → Trends, distributions, correlations  
🔹 **Interview Prep** → Perfect practice dataset for data science case studies  

---

## 📂 File Name  
**`Student_Performance_Cleaned.csv`**  

---

## 🌟 Why Use This Dataset?  
- Beginner-friendly 🏁 (77 rows, 11+ columns)  
- Covers **end-to-end data workflow** → Cleaning → EDA → Feature Engineering → ML  
- Realistic: Mimics the challenges of working with **raw, messy data**  
- Useful for **portfolio projects** 💼 and **interview practice**  

---

## 🔖 Suggested Kaggle Tags  
`education`, `students-performance`, `data-cleaning`,  
`exploratory-data-analysis`, `feature-engineering`,  
`machine-learning`, `regression`, `classification`, `tabular-data`  

---
---

## 🔄 Data Workflow (Flow Chart)

```mermaid
flowchart TD
    A[📂 Raw Dataset] --> B[🧹 Data Cleaning]
    B --> C[📊 Exploratory Data Analysis (EDA)]
    C --> D[🏗️ Feature Engineering]
    D --> E[🤖 Machine Learning Models]
    E --> F[📈 Insights & Predictions]

👉 This will render a **flowchart** like:  

📂 Raw Dataset → 🧹 Data Cleaning → 📊 EDA → 🏗️ Feature Engineering → 🤖 ML Models → 📈 Insights  

---

⚡ Tips:  
- Kaggle’s Markdown renderer **supports Mermaid** (so this will work directly).  
- You can also add emojis inside boxes to make it more attractive.  

Do you want me to make **two versions** of the flow chart:  
1. **Simple (like above)**  
2. **Detailed (showing missing values handling, gender fixing, etc.)** so it matches your cleaning process?


