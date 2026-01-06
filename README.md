# 📊 Banking Data Analysis Project

## 📌 AIM
The aim of this project is to perform **exploratory data analysis (EDA)** on a banking marketing dataset to understand:
- Customer demographic distributions
- Financial behavior patterns
- Campaign effectiveness
- Factors influencing subscription to term deposits

The insights derived can help banks optimize marketing strategies and customer targeting.

---

## 📂 Dataset Description
The dataset contains information on bank clients, including:
- Demographics (age, job, marital status, education)
- Financial attributes (balance, loans, credit default)
- Marketing campaign details
- Target variable indicating subscription to a term deposit

---

## 🔍 Methodology
- Data cleaning and preprocessing
- Univariate and bivariate analysis
- Visualization of distributions
- Correlation analysis with subscription outcome
- Statistical interpretation of patterns

---

## 📈 Key Results & Visualizations

### 🔹 Age Distribution of Clients
![Age Distribution](plots/age_distribution.png)

**Insight:**  
Most clients fall in the **30–50 age group**, indicating this demographic dominates the customer base.

---

### 🔹 Marital Status Distribution
![Marital Status](plots/marital_status.png)

**Insight:**  
Married clients form the largest group, followed by single and divorced clients.

---

### 🔹 Education Level Distribution
![Education Level](plots/education_distribution.png)

**Insight:**  
Clients with **secondary education** form the majority.

---

### 🔹 Term Deposit Subscription Outcome
![Subscription Distribution](plots/subscription_distribution.png)

**Insight:**  
A significantly smaller proportion of clients subscribed to term deposits, highlighting the challenge in conversion.

---

## 📊 Statistical Analysis

### 🔹 Correlation with Term Deposit Subscription

| Feature     | Correlation |
|-------------|------------|
| Duration    | **0.39**   |
| Pdays       | 0.10       |
| Previous    | 0.09       |
| Balance     | 0.05       |
| Age         | 0.02       |
| Campaign    | -0.07      |

**Key Finding:**  
Call **duration** shows the strongest positive correlation with subscription, indicating longer interactions increase conversion probability.

---

## 🛠 Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ▶️ How to Run the Project
```bash
git clone https://github.com/your-username/banking-data-analysis.git
cd banking-data-analysis
pip install -r requirements.txt
jupyter notebook
