
# 🏥 Healthcare Patient Data Analysis (PySpark + Pandas + Visualization)

## 📌 Overview

This project analyzes a **heart disease dataset** using **PySpark** for big data processing and **Pandas/Matplotlib/Seaborn** for visualization.
It demonstrates how to:

* Perform **ETL** (Extract, Transform, Load) with PySpark.
* Run **data analytics** on healthcare data.
* Generate **visual insights** (graphs) from medical records.

The dataset used is the [Heart Disease UCI Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset) with **1025 patients** and attributes like age, gender, blood pressure, cholesterol, max heart rate, and presence of heart disease.

---

## 📂 Project Structure

```
Healthcare-Patient-Analysis/
│── heart.csv                 # Dataset (input)
│── healthcare_analysis.py    # PySpark analysis script
│── visualizations.py         # Pandas/Seaborn visualization script
│── HighRiskPatients.csv      # Exported high-risk patients
│── README.md                 # Project documentation
```

---

## ⚙️ Requirements

Install the following dependencies:

```bash
pip install pyspark pandas matplotlib seaborn
```

---

## 🚀 How to Run

1. **Start PySpark Analysis**

   ```bash
   python healthcare_analysis.py
   ```

   This will:

   * Load `heart.csv`
   * Compute patient statistics
   * Export **high-risk patients** (age > 50, cholesterol > 240, heart disease = 1)

2. **Generate Visualizations**

   ```bash
   python visualizations.py
   ```

   This will create:

   * Age distribution histogram
   * Heart disease by gender countplot
   * Cholesterol vs heart disease boxplot
   * Average max heart rate by age group barplot
   * Correlation heatmap of medical features

---

## 📊 Analytics Performed

* **Total Patients**
* **Average Age, Cholesterol, Blood Pressure**
* **Patients by Gender** (Male/Female)
* **Heart Disease Cases** (Yes/No)
* **High Cholesterol & High BP Patients**
* **Age Group Analysis** (20–30, 31–40, etc.)
* **Correlation Insights** (Heart rate vs Heart disease, Cholesterol vs Chest pain type)

---

## 📈 Visualizations

1. **Age Distribution of Patients**
2. **Heart Disease by Gender**
3. **Cholesterol Levels vs Heart Disease**
4. **Average Max Heart Rate by Age Group**
5. **Correlation Heatmap of Medical Features**

---

## 🗂️ Outputs

* `HighRiskPatients.csv` → Contains patients **over 50 years old, with cholesterol > 240, and heart disease**.
* Graphs are displayed in the notebook/script for analysis.

---

## 🧑‍💻 Tech Stack

* **PySpark** → Big data analytics
* **Pandas** → Data manipulation
* **Matplotlib/Seaborn** → Visualization

---

## ✅ Use Cases

* Early detection of **high-risk patients**
* Insights for **preventive healthcare**
* Demonstration of **data engineering + analytics + visualization** pipeline


