# customer_churn_analysis
Analyze customer churn vs other variables


## 💖 Customer Churn Prediction:

### 🌸 Overview

This project predicts **which customers are likely to churn** using **Random Forest** and **XGBoost** models — so businesses can stop saying *“we’ll do better next quarter”* and actually *do better now*.



---

### 🎯 Project Goals

* Predict customer churn using ML models
* Understand key drivers of churn (tenure, monthly charges, etc.)
* Visualize customer behavior with fun, intuitive graphs
* Suggest actionable retention strategies based on predictions

---

### 🧠 Key Features

* 🧩 **Feature Engineering** — we crafted and transformed variables for maximum insight
* 📊 **Data Analysis & Visualization** — histograms, pie charts, and correlation heatmaps galore
* 🌳 **Random Forest Model** — for robust churn classification
* ⚡ **XGBoost Model** — for an extra performance boost
* 💬 **Retention Recommendation Engine** — gives smart (and slightly sassy) business tips
* 💾 **Model Saving** — export trained models as `.pkl` files for reuse
* 🧷 **Flowchart & Feature Importance Plots** — visualize how decisions are made

---

### 📂 Project Structure

```
customer_churn_project/
│
├── churn_data.csv                # Dataset (generated)
├── customer_churn.ipynb          # Jupyter Notebook
├── random_forest_model.pkl       # Saved Random Forest model
├── xgboost_model.pkl             # Saved XGBoost model
├── requirements.txt              # Dependencies
└── README.md                     # This cute file
```

---

### 🧪 Tech Stack

* **Language:** Python 🐍
* **Libraries:** pandas, numpy, seaborn, matplotlib, scikit-learn, XGBoost
* **Model Types:** Classification (Binary)
* **Environment:** Jupyter Notebook

---

### 🕹️ How to Run

1. **Clone the repo**

   ```bash
   git clone https://github.com/Sudeshna22/customer-churn-cute.git
   ```
2. **Navigate to the project folder**

   ```bash
   cd customer-churn-cute
   ```
3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```
4. **Run the notebook**
   Open `customer_churn.ipynb` in Jupyter or VS Code and execute cells in order.

---

### 📈 Results & Insights

* High churn likelihood found among users with:

  * Short tenure
  * High monthly charges
  * Low service usage
* Feature Importance plots reveal **“tenure”** and **“contract type”** as major churn indicators.
* The **Retention Engine** recommends better discounts, loyalty offers, and personalized follow-ups.

---

### 💡 Business Impact

This project can help a telecom company:

* 🧍 Reduce churn rates by 10-20%
* 💰 Increase retention revenue
* 🤝 Improve customer satisfaction through proactive engagement

---

### 💋 Author

**Sudeshna** ✨

> “Turning churn into charm — one model at a time.”

