# 📊 E-Commerce User Behavior Analysis

A detailed exploratory data analysis (EDA) on user session data from an e-commerce platform.  
The goal is to uncover trends in user behavior, session engagement, and purchase patterns — and to draw meaningful business insights through visual exploration.

---

## 📁 Dataset Overview

Each row in the dataset represents a user session and includes:

- `user_id`: Unique identifier for each user
- `gender`: User's gender
- `age`: User’s age
- `platform_used`: App or Website
- `session_duration`: Duration of the session (in minutes)
- `pages_visited`: Number of pages visited during the session
- `purchase_amount`: Amount spent during the session
- `region`: Geographic region of the user
- `returned_customer`: Whether the user is a returning customer

---

## 📌 Analysis Breakdown

The notebook includes a series of focused questions, each backed by visualizations and observations:

1. **Session Duration** — Which platform keeps users engaged longer: the App or the Website?
2. **Time vs Spending** — Do longer sessions lead to higher purchase amounts?
3. **Platform Spending** — Which platform has higher average spending?
4. **Returning vs New Customers** — Who brings in more revenue?
5. **Geographic Trends** — Which regions have the highest spenders?
6. **Personal Exploration**:
   - Does age affect purchase behavior?
   - Do females spend more than males?

Each section includes a short interpretation of the findings to guide business understanding.

---

## 🧰 Tools Used

- **Python**
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn` for visualizations
- **Google Colab** for development

---

## 📂 All steps and findings are inside `ecommerce-user-behavior-analysis.ipynb`

---

## 📎 How to Use

You can open the notebook directly in Google Colab or download it as a `.ipynb` file and run it locally using Jupyter Notebook.
