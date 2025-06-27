# 📊 Customer Lifetime Value Prediction

Predicting the future value of a customer is essential for targeted marketing and resource optimization. This project uses **RFM Analysis** and **XGBoost** to segment customers and predict their **Customer Lifetime Value (CLV)**.

---

## 📌 Table of Contents

* [What is Customer Lifetime Value?](#what-is-customer-lifetime-value)
* [Why is CLV Important?](#why-is-clv-important)
* [Role of Machine Learning](#role-of-machine-learning)
* [RFM Segmentation](#rfm-segmentation)
* [Model Used - XGBoost](#model-used---xgboost)
* [Project Structure](#project-structure)
* [How to Run](#how-to-run)
* [Dependencies](#dependencies)
* [Results](#results)
* [License](#license)

---

## What is Customer Lifetime Value?

**Customer Lifetime Value (CLV)** is a prediction of the **net profit** attributed to the entire future relationship with a customer. Understanding CLV helps businesses focus on long-term customer relationships instead of short-term profits.

---

## Why is CLV Important?

* Helps allocate customer acquisition budgets effectively.
* Assists in building better customer personas.
* Aids in assessing the long-term effects of business decisions.
* Allows evaluation of the **profitability per customer**.

---

## Role of Machine Learning

Machine learning helps by:

* Predicting the approximate CLV for new and existing customers.
* Estimating transaction values and purchase intervals.
* Using historical transaction data for better forecasting.

---

## RFM Segmentation

RFM stands for:

* **Recency** – How recently a customer made a purchase.
* **Frequency** – How often they purchase.
* **Monetary Value (Revenue)** – How much they spend.

Using clustering (unsupervised learning), customers are grouped into:

* 🟥 Low Value
* 🟨 Mid Value
* 🟩 High Value

![RFM](https://github.com/basel-ay/Customer-Lifetime-Value-Prediction/assets/64821137/eac0f80a-6ac2-405f-8282-0186bbfa2729)

---

## Model Used - XGBoost

**XGBoost** (Extreme Gradient Boosting):

* Fast, efficient, and regularized boosting algorithm.
* Performs well with tabular data.
* Uses gradient descent to optimize the loss function.

![XGBoost](https://github.com/basel-ay/Customer-Lifetime-Value-Prediction/assets/64821137/f3a4e25e-4108-4ce1-9471-ee9292df25b4)

---

## 🗂 Project Structure

```
Customer-Lifetime-Value-Prediction/
├── data/                  # Dataset files
├── notebooks/             # Jupyter notebooks for EDA and modeling
├── src/                   # Source code
│   ├── preprocessing.py   # RFM calculation & clustering
│   └── model.py           # XGBoost model training & prediction
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── main.py                # Main pipeline script
```

---

## ▶️ How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/Customer-Lifetime-Value-Prediction.git
   cd Customer-Lifetime-Value-Prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the main script:

   ```bash
   python main.py
   ```

4. To explore or modify:

   * Use `notebooks/` to perform EDA and fine-tune models.

---

## 🧾 Dependencies

* Python 3.8+
* pandas
* numpy
* scikit-learn
* xgboost
* matplotlib
* seaborn
* jupyter

Install using:

```bash
pip install -r requirements.txt
```

---

## 📈 Results

* Customers segmented into value tiers using RFM & clustering.
* CLV predicted with high accuracy using XGBoost.
* Actionable insights for marketing & customer retention strategies.
