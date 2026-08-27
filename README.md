```markdown
# 📊 Customer Churn Prediction & Web App

An end-to-end Machine Learning pipeline and Flask web application built to analyze customer behavior, identify churn patterns, and predict future churn risk in real-time.

---

## 🎯 Overview
Customer retention is vital for sustainable business growth. This project addresses the churn problem by:
1. Conducting in-depth Exploratory Data Analysis (EDA) to find churn drivers.
2. Training and fine-tuning predictive machine learning models.
3. Deploying the final model via an interactive Flask web interface for real-time predictions.

---

## 🛠️ Tech Stack
* **Analysis & Modeling:** Python, Pandas, NumPy, Scikit-Learn
* **Visualization:** Matplotlib, Seaborn
* **Web Deployment:** Flask, HTML/CSS (Jinja2 Templates)
* **Model Serialization:** Pickle (`model.sav`)

---

## 📁 Repository Structure
```text
Customer_Churn_Analysis/
│
├── templates/               # HTML UI files for Flask frontend
├── EDA.ipynb                # Comprehensive Exploratory Data Analysis
├── Model_Building.ipynb     # Data preprocessing, feature engineering & model training
├── app.py                   # Flask web server for churn inference
├── model.sav                # Saved trained classification model
├── .gitignore               # Ignored environments, cache, and system files
└── README.md                # Project documentation

```

---

## 🔍 Key Findings from EDA

* **Contract Length:** Month-to-month subscribers present the highest risk of churn compared to long-term contract holders.
* **Customer Tenure:** Churn rates drop significantly as customer tenure increases past the initial onboarding period.
* **Payment Methods & Services:** Electronic payment methods and lack of tech support/online security features strongly correlate with higher churn.

---

## ⚙️ How to Run Locally

1. **Clone the repository:**
```bash
git clone [https://github.com/sonu786786/Customer_Churn_Analysis.git](https://github.com/sonu786786/Customer_Churn_Analysis.git)
cd Customer_Churn_Analysis

```


2. **Set up a virtual environment (Recommended):**
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

```


3. **Install required libraries:**
```bash
pip install flask scikit-learn pandas numpy matplotlib seaborn

```


4. **Launch the Flask web application:**
```bash
python app.py

```


Open your browser and navigate to `http://127.0.0.1:5000/` to test predictions.

---

## 👤 Author

**Sonu Kumar**

* [GitHub](https://www.google.com/search?q=https://github.com/sonu786786)

```

```
