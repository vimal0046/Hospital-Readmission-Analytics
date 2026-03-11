# 🏥 Hospital Readmission Analytics – Diabetic Patients

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Python](https://img.shields.io/badge/Python-EDA-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

This project analyzes hospital readmission patterns among diabetic patients using **Python (EDA)** and **Power BI (Dashboard)**. The goal is to identify key factors — such as age, medications, hospital stay duration, and diagnoses — that influence whether a patient is readmitted within 30 days.

---

## 📊 Dashboard Preview

> *Hospital Readmission Analytics Dashboard built in Power BI*


<img width="1277" height="717" alt="Healthcare_dashboard_screenshot png" src="https://github.com/user-attachments/assets/8b717e24-ad36-465a-82fa-02fb85219637" />


---

## 🔍 Key Insights

- 📌 **Patients aged 60–80** show the highest hospital readmission rates
- 📌 **Average hospital stay** is **4.4 days** (most patients: 2–6 days)
- 📌 **Certain medications** (repaglinide, troglitazone, tolbutamide) show higher readmission correlation
- 📌 **Gender** does not significantly influence readmission rates
- 📌 **Caucasian** patients form the largest group in the dataset
- 📌 Patients with **more diagnoses** tend to have higher readmission likelihood

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy, Matplotlib) | Data cleaning & Exploratory Data Analysis |
| Jupyter Notebook | EDA documentation |
| Power BI | Interactive dashboard & visualization |
| GitHub | Version control & project hosting |

---

## 📁 Project Structure

```
Hospital-Readmission-Analytics/
│
├── diabetic_patient_analysis.ipynb            # Python EDA Notebook
├── diabetic_patient_analysis_dashboard.pbix   # Power BI Dashboard file
├── diabetes_cleaned.csv                       # Cleaned dataset (if shareable)
├── dashboard_screenshot.png                   # Dashboard preview image
└── README.md                                  # Project documentation
```

---

## 🧹 Data Cleaning (Python)

Steps performed in the Jupyter Notebook:

- Replaced `?` values with `NaN`
- Dropped irrelevant columns: `weight`, `payer_code`, `medical_specialty`, `max_glu_serum`, `A1Cresult`
- Filled missing values in `race`, `diag_1`, `diag_2`, `diag_3` with `"Unknown"`
- Removed invalid gender entries (`Unknown/Invalid`)
- Created binary readmission column: `readmitted_binary` (1 = readmitted within 30 days)

---

## 📈 EDA Analysis Performed

- Readmission Distribution by **Age Group**
- Readmission by **Gender**
- Readmission by **Race**
- **Hospital Stay Duration** analysis
- **Number of Medications** vs Readmission
- **Number of Diagnoses** vs Readmission

---

## 📊 Power BI Dashboard Features

- **KPI Cards**: Total Patients (2.34M), Readmitted (261.21K), Avg Stay (4.40 days), Rate (11.16%)
- **Stacked Bar Chart**: Readmission Distribution by Age Group
- **Donut Chart**: Patients by Gender
- **Bar Chart**: Patient by Race
- **Histogram**: Distribution of Hospital Stay Duration
- **Horizontal Bar Chart**: Top 5 Medications by Readmission Status
- **Slicers**: Age filter, Race filter, Gender filter
- **Insights Bubble**: Summary of key findings

---

## 🚀 How to Run

### Python Notebook
1. Clone this repository
```bash
git clone https://github.com/YOUR_USERNAME/Hospital-Readmission-Analytics.git
```
2. Install dependencies
```bash
pip install pandas numpy matplotlib jupyter
```
3. Open the notebook
```bash
jupyter notebook diabetic_patient_analysis.ipynb
```

### Power BI Dashboard
1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/)
2. Open `power_diabeties.pbix`
3. Refresh the data source if needed

---

## 📂 Dataset

- **Source**: [UCI Machine Learning Repository – Diabetes 130-US Hospitals](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)
- **Records**: ~100,000 patient records
- **Features**: 50 attributes including demographics, diagnoses, medications, and readmission status

---

## 👤 Author

**Vimalraj P**
- 📧 [Vimalraj0046@gmail.com]
- 💼 [[linkedin.com/in/vimalraj0046](https://www.linkedin.com/in/vimalraj0046/)]
- 🐙 [(https://github.com/vimal0046)]

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
