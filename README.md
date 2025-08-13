# 🏥 Hospital Admissions – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project explores **patient admission patterns** in a city hospital using anonymized data from [Kaggle – Hospital Admissions Data](https://www.kaggle.com/datasets/ashishsahani/hospital-admissions-data).  
The primary objective is to uncover insights that can help improve **scheduling, reduce waiting times, and optimize resource allocation**.

Through **Pandas-based analysis** and **Matplotlib/Seaborn visualizations**, we aim to:
- Understand patient demographics.
- Analyze admission trends.
- Identify high-demand departments and room types.
- Explore relationships between variables.

---

## 📂 Dataset Information
**Dataset Name:** Hospital Admissions Data  
**Source:** [Kaggle – Hospital Admissions Data](https://www.kaggle.com/datasets/ashishsahani/hospital-admissions-data)  

**Columns:**
- `patientid` → Unique patient identifier.
- `age` → Age of the patient.
- `gender` → Patient gender (Male/Female/Other).
- `admission_type` → Emergency, Scheduled, or Trauma.
- `department` → Hospital department (General, Surgery, etc.).
- `room_type` → General, Private, Semi-Private.
- `admission_day` → Day of the week.
- `previous_visits` → Number of prior visits.

---

## 🎯 Analysis Objectives
1. Total number of admissions.
2. Gender distribution among patients.
3. Most common age groups for admissions.
4. Distribution of admission types.
5. Departments with the highest number of admissions.
6. Most frequently assigned room types.
7. Most common admission days.
8. Percentage of patients with previous visits.
9. Admission type differences across genders.
10. Additional patterns and visual insights.

---

## 📊 Key Findings
- **Total Admissions:** `15757`
- **Gender Distribution:** `Male 9990`, `Female 5767`
- **Most Common Age Group:** `'60-79' years`
- **Top Admission Type:** `Emergency` / `OPD` 
- **Busiest Day for Admissions:** `Monday`
- **Returning Patients:** `16.48%` have visited before.

---

## 🛠 Tools & Libraries
- **Python**
- **Pandas** → Data wrangling & preprocessing.
- **Jupyter Notebook** → Interactive analysis.

---

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/hospital-eda.git
   cd hospital-eda
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/ashishsahani/hospital-admissions-data) and place it in the project directory.
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Hospital_EDA.ipynb
   ```

---

## 📌 Conclusion
This analysis provides a data-driven perspective on hospital admission patterns, which can be used to:
- **Improve scheduling**
- **Allocate resources efficiently**
- **Reduce patient waiting times**
- **Enhance hospital management strategies**
