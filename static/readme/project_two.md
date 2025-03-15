
# 📊 Exploring Relationships Between Quantitative Variables

In this project, I explore various ways to examine **associations between two quantitative variables** using **scatter plots, covariance, and correlation**. 

---

## 📝 Key Concepts Covered

### 📌 1. Understanding Variables
A **variable** stores data that a program can use, such as:
- **Numbers (Integers, Floats)**
- **Strings (Text)**
- **Boolean (True/False)**
- **Lists & Other Data Types**

### ⚠️ Rules for Python Variables:
- A variable name **must start** with a **letter or an underscore (`_`)**.
- A variable name **cannot start with a number**.
- Variable names **are case-sensitive** (`num`, `Num`, and `NUM` are different).
- Names **can only contain** letters, numbers, and underscores (`A-z`, `0-9`, `_`).

---

## 🔍 Examining Relationships Between Variables

### 📌 2. Using Scatter Plots 📈
- We **plotted two numerical variables** on a scatter plot to **visually inspect their relationship**.
- Example: **Comparing flipper length (`flipper_length_mm`) vs. body mass (`body_mass_g`)** in penguins.

### 📌 3. Covariance Calculation 🔢
- **Covariance** measures **how two variables change together**:
  - **Positive covariance** → Variables **increase together**.
  - **Negative covariance** → One variable **increases** while the other **decreases**.
  - **Near zero** → No relationship.

### 📌 4. Correlation Calculation 🔄
- **Correlation** standardizes covariance to a **range from -1 to 1**:
  - **1.0** → Perfect **positive** correlation (strong relationship).
  - **-1.0** → Perfect **negative** correlation (inverse relationship).
  - **0.0** → No relationship.

### 🧐 Does the correlation match what we see in the scatter plot?
- If **correlation is high**, the points should form a **clear linear trend**.
- If **correlation is low**, the points should be **scattered randomly**.

---

## 📂 Dataset Information

This project used **datasets from Kaggle**, including:
- 🐧 **Penguins Dataset**: Contains flipper length, body mass, and other measurements.

---

## 🚀 How to Run This Project
### **1️⃣ Install Dependencies**
Make sure you have **Python** and required libraries installed:
```bash
pip install pandas matplotlib seaborn

