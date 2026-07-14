# 🎓 Fuzzy Logic-Based Analyzer for Evaluating Student Dropout Rate from University Undergraduate Programmes

A Mamdani Fuzzy Logic-based Decision Support System developed to evaluate student dropout risk using historical administrative records from Dominion University, Ibadan.

---

## 📖 About the Project

Student dropout remains one of the major challenges affecting higher education institutions. Many traditional evaluation methods rely on rigid thresholds that do not adequately represent the uncertainty associated with students' withdrawal decisions.

This project presents a **Fuzzy Logic-Based Analyzer** that evaluates dropout risk using a Mamdani Fuzzy Inference System. Rather than predicting dropout using black-box machine learning models, the system applies interpretable fuzzy rules to analyse administrative dropout records and generate meaningful dropout risk classifications.

The study was conducted using Dominion University undergraduate programmes as a case study.

---

## 🎯 Aim of the Study

To develop a fuzzy logic-based analytical system for evaluating student dropout rate from undergraduate programmes using administrative institutional records.

---

## ✅ Objectives

- Collect and preprocess historical student dropout records.
- Construct proxy risk indicators from administrative data.
- Design and implement a Mamdani Fuzzy Inference System.
- Generate dropout risk scores through fuzzy reasoning.
- Classify students into linguistic risk categories.
- Present the results through dashboards and visualizations for institutional decision support.

---

## 📊 Dataset

The dataset consists of historical administrative dropout records obtained from Dominion University.

The available records include:

- Programme of Study
- Gender
- Academic Session
- Documented Reason for Withdrawal

Since continuous indicators such as CGPA and attendance were not consistently available, the study adopted a proxy-based modelling approach.

---

## 🧠 Proxy Risk Variables

The administrative records were transformed into three fuzzy input variables:

- Academic Risk
- Programme Risk
- Gender Risk

These proxy variables were used as inputs to the fuzzy inference system.

---

## ⚙️ Methodology

The project follows the workflow below:

1. Administrative Dropout Data Collection
2. Data Cleaning and Standardisation
3. Proxy Risk Mapping
4. Fuzzy Membership Function Design
5. IF–THEN Rule Base Development
6. Mamdani Fuzzy Inference
7. Centroid Defuzzification
8. Dropout Risk Score Generation
9. Risk Classification
10. Dashboard and Result Visualisation

---

## 🔄 System Flow

Administrative Dropout Records

↓

Data Cleaning & Coding

↓

Proxy Risk Mapping

- Academic Risk
- Programme Risk
- Gender Risk

↓

Mamdani Fuzzy Inference System

↓

Centroid Defuzzification

↓

Dropout Risk Score (0–100)

↓

Risk Classification

- Low Risk
- Moderate Risk
- High Risk
- Critical Risk

↓

Interactive Dashboards

---

## 📈 Output

The developed system produces:

- Dropout Risk Score (0–100)
- Risk Category
- Executive Dashboard
- Faculty Dashboard
- Factor Analysis Dashboard
- Membership Function Visualizations

---

## 🖼 Repository Structure

```
Fuzzy-Logic-Dropout-Analyzer
│
├── Data/
│   ├── Finalcldataset.csv
│   └── Pre-processed Drop out data.xls
│
├── Images/
│   ├── dashboard_executive.png
│   ├── dashboard_faculty.png
│   ├── dashboard_factors.png
│   └── membership_functions.png
│
├── Notebooks/
│   └── FuzzyLogic_Final.ipynb
│
├── Results/
│   └── fuzzy_dropout_results_clean.csv
│
└── README.md
```

---

## 💻 Technologies Used

- Python
- Jupyter Notebook
- Microsoft Excel
- Pandas
- NumPy
- Scikit-Fuzzy
- Plotly
- Matplotlib

---

## 🚀 Running the Project

Clone the repository

```bash
git clone https://github.com/Favouratambi/fuzzy-logic-dropout-analyzer.git
```

Open the notebook

```
Notebooks/FuzzyLogic_Final.ipynb
```

Run all notebook cells to reproduce the fuzzy inference process and generate the dashboards.

---

## 🎯 Key Features

- Administrative data preprocessing
- Proxy risk construction
- Mamdani Fuzzy Inference System
- Rule-based decision support
- Centroid defuzzification
- Dropout risk evaluation
- Dashboard generation
- Result visualization

---

## 📚 Academic Contribution

This project demonstrates how fuzzy logic can be applied to educational decision support by modelling uncertainty in student dropout evaluation. Unlike conventional threshold-based methods, the system provides transparent reasoning through linguistic rules and interpretable risk categories, making it suitable for institutional monitoring and evidence-based intervention planning.

---

## 👨‍🎓 Author

**Atambi Favour Olor**

Bachelor of Science (B.Sc.) in Computer Science

Dominion University, Ibadan

GitHub: https://github.com/Favouratambi

---

## 📄 Citation

If you use this work for academic or research purposes, please cite the project appropriately.

---

## 📜 License

This repository is intended for educational and research purposes.