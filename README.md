# 📊 Customer Support Data Analysis & CSAT Prediction

A comprehensive data science project that analyzes customer support interactions and builds a machine learning model to predict Customer Satisfaction (CSAT) scores. The goal is to help organizations like Flipkart enhance their customer service strategies, improve agent performance, and proactively address dissatisfaction.  

---

## 🚀 Project Overview

This project dives into an extensive dataset of customer support tickets to:  

✅ Explore and understand key factors driving CSAT.  
✅ Perform feature engineering and data preprocessing.  
✅ Visualize insights with 15+ meaningful charts.  
✅ Validate hypotheses using statistical testing.  
✅ Build and evaluate multiple machine learning models.  
✅ Deliver actionable insights for business impact.  

The final XGBoost model predicts CSAT with **~89.2% accuracy**, enabling businesses to optimize their customer support operations.

---

## 📂 Table of Contents

- [Project Overview](#-project-overview)  
- [Dataset](#-dataset)  
- [Key Insights](#-key-insights)  
- [ML Models](#-machine-learning-models)  
- [Business Impact](#-business-impact)  
- [Installation](#-installation)  
- [Usage](#-usage)  
- [Tech Stack](#-tech-stack)  
- [Author](#-author)  

---

## 📦 Dataset

The dataset contains **85,907** customer support records with features like:  

- 🕐 Timestamps (issue reported/responded)  
- 🧑‍💻 Agent details (name, shift, tenure)  
- 📦 Issue categories & sub-categories  
- ⏱ Response times  
- ✍️ Customer feedback (text)  
- 🎯 Target: `CSAT Score` (1 = poor, 5 = excellent)  

---

## 📊 Key Insights

🔹 **Response Time vs. CSAT:** Longer response times correlate with lower CSAT.  
🔹 **Agent Tenure:** Agents with >90 days tenure score higher CSAT.  
🔹 **Shifts:** Evening shifts show slightly better CSAT.  
🔹 **Issue Categories:** Returns & technical issues take longest to resolve.  
🔹 **Text Analysis:** Common words in negative feedback include “delay” and “poor.”  

15+ visualizations (boxplots, heatmaps, pair plots, bar charts) uncover patterns in agent performance, customer sentiment, and issue types.

---

## 🤖 Machine Learning Models

We experimented with:  

- Logistic Regression  
- Random Forest Classifier  
- XGBoost Classifier (Final Model)  
- Support Vector Machines (SVM)  

**Final Model: XGBoost Classifier**  
- 🎯 Accuracy: **89.2%**  
- 📈 F1-Score: **0.89**  
- 🏷 Feature Importance (via SHAP): Agent Shift, Tenure, Issue Category, Response Time  

Class imbalance was handled using **SMOTE (Synthetic Minority Oversampling Technique).**

---

## 💼 Business Impact

✅ Predict customer dissatisfaction proactively.  
✅ Optimize agent training and shift allocations.  
✅ Improve response time for high-impact categories.  
✅ Increase overall customer loyalty and retention.  

---

## ⚙️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Daniel-Bavisetti/Flipkart_Customer_Satisfaction.git
cd Flipkart_Customer_Satisfaction
```

## ⚙️ Installation

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Start Jupyter Notebook
```bash
jupyter notebook
```
Open and run the notebooks in the notebooks/ folder.

## 🚀 Usage

- Run `EDA_and_Feature_Engineering.ipynb` to explore and preprocess the data.  
- Run `Model_Building_and_Evaluation.ipynb` to train and evaluate ML models.  
- Explore `Visualization_Insights.ipynb` for 15+ charts and insights.  

---

## 🛠 Tech Stack

- **Languages:** Python 3.9  
- **Libraries:** pandas, NumPy, scikit-learn, XGBoost, matplotlib, seaborn, SHAP, NLTK  
- **Tools:** Jupyter Notebook, Git, VS Code  

---

## 👨‍💻 Author

Bavisetti Daniel  
🔗 [GitHub](https://github.com/Daniel-Bavisetti)  
🔗 [LinkedIn](https://www.linkedin.com/in/daniel-bavisetti/)  

---

## 🔗 Links

- 📂 [Project Repository](https://github.com/Daniel-Bavisetti/Flipkart_Customer_Satisfaction)


