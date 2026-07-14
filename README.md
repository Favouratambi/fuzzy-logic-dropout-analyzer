# 🎓 Fuzzy Logic-Based Analyzer for Evaluating Student Dropout Risk

A Mamdani Fuzzy Logic-based Decision Support System developed to evaluate the risk of student dropout using academic, financial, and socio-economic factors. This project was completed as a Bachelor's degree project in Computer Science at Dominion University, Ibadan.

---

## 📌 Project Overview

Student dropout is a major challenge in higher education, affecting students, institutions, and society. Traditional methods often rely on rigid thresholds that may not accurately reflect the uncertainty involved in identifying at-risk students.

This project addresses this challenge by implementing a **Mamdani Fuzzy Inference System (FIS)** that models expert reasoning using linguistic rules instead of fixed numerical thresholds. The system analyzes selected student-related factors and classifies each student into a dropout risk category, helping stakeholders identify students who may require early intervention.

---

## 🎯 Objectives

The objectives of this project are to:

- Develop a Mamdani Fuzzy Logic-based system for evaluating student dropout risk.
- Analyze key factors contributing to student dropout.
- Generate an interpretable dropout risk score using fuzzy inference.
- Present results through interactive dashboards and visualizations.
- Support decision-making for early intervention strategies.

---

## ⚙️ Methodology

The project follows these stages:

1. Data Collection
2. Data Preprocessing
3. Selection of Input Variables
4. Definition of Fuzzy Membership Functions
5. Development of IF–THEN Rule Base
6. Mamdani Fuzzy Inference
7. Defuzzification
8. Risk Classification
9. Data Visualization and Dashboard Generation

---

## 🧠 Fuzzy Logic Inputs

The system evaluates student dropout risk using factors such as:

- Academic Performance
- Financial Challenges
- Family Background
- Motivation Level
- Social Support

These variables are converted into fuzzy linguistic values such as:

- Low
- Medium
- High

before applying the fuzzy rule base.

---

## 📊 Outputs

The system produces:

- Individual student dropout risk scores
- Risk classifications
- Interactive dashboards
- Membership function visualizations
- Statistical summaries

---

## 📂 Repository Structure

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

## 📈 Sample Visualizations

The repository includes:

- Membership Function Plots
- Executive Dashboard
- Faculty Dashboard
- Factor Analysis Dashboard

These visualizations help explain how the fuzzy system evaluates and classifies dropout risk.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Fuzzy
- Plotly
- Matplotlib
- OpenPyXL

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Favouratambi/fuzzy-logic-dropout-analyzer.git
```

### 2. Navigate into the project

```bash
cd fuzzy-logic-dropout-analyzer
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

Launch Jupyter Notebook and open:

```
Notebooks/FuzzyLogic_Final.ipynb
```

Run all cells to reproduce the analysis and visualizations.

---

## 📋 Key Features

- Data preprocessing
- Mamdani Fuzzy Inference System
- Fuzzy membership function generation
- Rule-based decision making
- Dropout risk classification
- Interactive dashboards
- Result visualization
- Exportable analysis results

---

## 📚 Academic Information

**Project Title**

**Fuzzy Logic-Based Analyzer for Evaluating Student Dropout Risk from University Undergraduate Programs: A Case Study of Dominion University, Ibadan**

Submitted in partial fulfillment of the requirements for the award of the Bachelor of Science (B.Sc.) degree in Computer Science.

---

## 👨‍💻 Author

**Atambi Favour Olor**

B.Sc. Computer Science

Dominion University, Ibadan

GitHub: https://github.com/Favouratambi

---

## 📄 License

This project is provided for educational and research purposes.

Please cite or acknowledge the author appropriately if you use any part of this work.