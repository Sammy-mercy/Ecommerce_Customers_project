# 🛍 Ecommerce Linear Regression Analysis

---

## 📑 Table of Contents
- 📌 Project Overview
- 📂 Dataset Information
- 🎯 Objectives
- 🛠️ Tools & Libraries
- 🔍 Workflow
- 📈 Key Findings
- 📦 Installation & Usage
- 📌 Future Improvements
- 📜 License

---

## 📌 Project Overview
This project analyzes data from an **Ecommerce company in New York City** that sells clothing online and provides **in-store personal styling sessions**. Customers can meet a stylist, then purchase clothes through the **mobile app** or **website**.

The company wants to decide whether to **focus on improving the mobile app or the website experience**.  
We approach this using **Linear Regression** and data analysis.

---

## 📂 Dataset Information
The dataset contains:
- **Avg. Session Length** – Average session length (in minutes)
- **Time on App** – Average time spent on the mobile app
- **Time on Website** – Average time spent on the website
- **Length of Membership** – How long the user has been a customer
- **Yearly Amount Spent** – Target variable (customer’s yearly spending)

---

## 🎯 Objectives
- Perform **EDA** to find relationships between features and the target variable.
- Train a **Linear Regression Model** to predict yearly customer spending.
- Analyze coefficients to understand which features impact revenue the most.
- Provide a **data-driven recommendation**: focus on **App or Website** improvements.

---

## 🛠️ Tools & Libraries
- **Python 3.8+**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Visualization
- **Scikit-learn** – Machine learning
- **Jupyter Notebook**

---

## 🔍 Workflow
1. **Exploratory Data Analysis (EDA)**  
   - Pairplots & heatmaps to visualize correlations  
2. **Model Building**
   - Train-test split  
   - Linear Regression using Scikit-learn  
3. **Model Evaluation**
   - R² Score  
   - Mean Absolute Error  
   - Mean Squared Error  
4. **Coefficient Analysis**
   - Interpret impact of `Time on App` vs. `Time on Website`  
   - Unexpected insights discovered  

---

## 📈 Key Findings
- **Length of Membership** had the strongest positive effect on yearly spending.
- **Time on App** influenced spending more than **Time on Website**.
- Recommendation: **Invest in improving the mobile app experience** for better ROI.

---

## 📦 Installation & Usage
```bash
# 1️⃣ Clone the Repository
git clone https://github.com/Sammy-mercy/

# 2️⃣ Navigate to the Project Folder
cd Ecommerce_Customers_project

# 3️⃣ Install Dependencies
pip install -r requirements.txt

# 4️⃣ Launch Jupyter Notebook
jupyter notebook
```
---

## 📌 Future Improvements
- Apply regularization techniques (Ridge, Lasso)
- Add interaction terms for deeper feature analysis
- Test non-linear models for better accuracy
- Deploy the model with Flask or Streamlit
  
---

## 📜 License
This project is licensed under the MIT License.

