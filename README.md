# Dollar Tree Operations & Predictive Models

This repository combines two major projects developed for **Dollar Tree** operations and workforce optimization:

1. **Workforce Scheduling Optimization** using **OR-Tools** (Prescriptive Analytics).  
2. **Turnover Prediction Model** using **Machine Learning** (Predictive Analytics).  

The goal is to provide **data-driven decision support** for Dollar Tree’s operations by optimizing workforce schedules and anticipating employee turnover risks.

---

## 📊 Workforce Scheduling Optimization

The scheduling model was built with **Google OR-Tools** to optimize shifts for managers, cashiers, and stockers while respecting operational and fairness constraints.  

### ✅ Key Features:
- Store manager always works **Monday to Friday**.  
- **Cashier coverage** guaranteed for every shift.  
- Balanced workload distribution among employees.  
- Shift fairness enforced to avoid overloading specific workers.  


---

## 🤖 Turnover Prediction Model

The turnover model was developed using **Random Forest** on synthetic HR data.  
It predicts which employees are most likely to leave the company, enabling **proactive HR actions**.

### 🔑 Variables:
- Length of tenure (months)  
- Average weekly hours  
- Job satisfaction score  
- Frequency of weekend assignments  
- Store turnover rate  

---

## 🎯 Objective

- **Scheduling Model:** Optimize labor allocation while ensuring fairness and coverage.  
- **Turnover Model:** Anticipate attrition risks with a balance of precision and recall.  

Together, these projects demonstrate the integration of **Prescriptive Analytics** (optimization) and **Predictive Analytics** (machine learning) to support operational decision-making at scale.

---

## 🛠️ Tech Stack

<p align="left">
  <img align="center" alt="python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img align="center" alt="pandas" src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img align="center" alt="seaborn" src="https://img.shields.io/badge/Seaborn-2E7D32?style=for-the-badge&logo=python&logoColor=white" />
  <img align="center" alt="ortools" src="https://img.shields.io/badge/OR--Tools-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img align="center" alt="sklearn" src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
</p>

