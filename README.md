# Amazon Consumer Behaviour EDA 📦📊

A comprehensive **Exploratory Data Analysis (EDA)** on Amazon consumer behaviour using Python, Pandas, Plotly, Seaborn, and Matplotlib to uncover insights across the customer journey - from browsing to purchase, satisfaction, and retention.

---

## 🌟 Features

### Core Features

* **Data Cleaning & Preprocessing:** Handling missing values, duplicates, and data type conversions.
* **Customer Behaviour Analysis:** Study browsing, cart, checkout, and purchase completion patterns.
* **Demographic Insights:** Analyze age and gender trends influencing shopping behaviour.
* **Recommendation & Pricing Impact:** Evaluate how personalization and pricing affect purchase decisions.
* **Satisfaction & Review Analysis:** Understand the relationship between satisfaction, reviews, and repeat purchases.
* **Visualization:** Interactive and static plots using Plotly, Seaborn, and Matplotlib.

---

## ❓ Key Questions Explored

* How do age and gender influence shopping behaviour and engagement on Amazon?
* Which stages of the shopping journey (browsing, cart, checkout) contribute most to drop-offs?
* Do occasional shoppers represent a larger growth opportunity than frequent buyers?
* How effective are product recommendations in influencing purchase decisions?
* What role does pricing perception play in cart abandonment and comparison behaviour?
* How do customer support responsiveness and delivery reliability affect satisfaction and trust?
* How do reviews and post-purchase experience influence future purchase intent?
* Which satisfaction drivers most strongly impact repeat purchases and loyalty?

---

## 🗂 Project Structure

```text
Amazon_Consumer_Behaviour_EDA/
├── Amazon_Survey.csv               # Consumer behaviour dataset
├── Amazon_Consumer_Behaviour.ipynb # Jupyter Notebook with full EDA
├── requirements.txt                # Python dependencies
└── venv/                           # Virtual environment
```

---

## 🏗️ EDA Architecture

```text
+----------------------+  
|      DATA LAYER      |  
|  Raw consumer data   |  
|  (CSV / Excel)       |  
+----------+-----------+  
           ↓  
+-------------------------+  
|  ANALYSIS LAYER         |  
|  - Data Cleaning        |  
|  - Demographic Analysis |  
|  - Browsing Behaviour   |  
|  - Cart & Checkout      |  
|  - Satisfaction & Trust |  
+----------+--------------+  
           ↓  
+---------------------------------------+  
| VISUALIZATION LAYER                   |  
|  - Interactive Dashboards (Plotly)    |  
|  - Static Plots (Seaborn & Matplotlib)|  
|  - Bar, Count, Heatmaps               |  
+---------------------------------------+  
```

---

## 🛠 Tech Stack

* **Language:** Python 3.8+
* **Libraries:**

  * **Data Manipulation:** Pandas, NumPy
  * **Visualization:** Matplotlib, Seaborn, Plotly
* **Environment:** Jupyter Notebook
* - **Data Source:** [Kaggle – Google Play Store Apps](https://www.kaggle.com/datasets/swathiunnikrishnan/amazon-consumer-behaviour-dataset)

---

## 📊 Dataset Overview

* **Focus Areas:** Demographics, browsing behaviour, purchase frequency, recommendations, pricing perception, satisfaction, reviews

**Context:**
This dataset provides insights into Amazon consumer behaviour across the full shopping lifecycle, enabling identification of friction points, growth opportunities, and loyalty drivers.

**Inspiration:**
Understanding consumer behaviour helps e-commerce platforms optimize personalization, pricing strategies, user experience, and long-term retention.

---

## 🚀 Quick Start

### 1. Clone Repository

```bash
git clone https://github.com/TejasMJ/Aamazon_Consumer_Behaviour_EDA.git
cd Amazon_Consumer_Behaviour_EDA
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Virtual Environment

**Windows**

```bash
.\venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run Notebook

```bash
jupyter notebook
```

---

## 👨‍💻 Author

**Tejas Jadhav**

* GitHub: [@TejasMJ](https://github.com/TejasMJ)
* LinkedIn: [Tejas Jadhav](https://www.linkedin.com/in/tejas-m-jadhav/)
