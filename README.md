# 🏥 Predicting Medical Expenses Using Linear Regression (Single Feature)

## 📘 Project Overview
Developed a **simple linear regression model** to predict an individual's **annual medical expenses** based on their **age**.  
The dataset originates from **ACME Insurance Inc.**, a publicly available dataset commonly used for educational and research purposes.  

This project was designed to strengthen my understanding of **regression modeling** and demonstrate how **explainable models** can support **data-driven decision-making** in the insurance industry.

---

## 🎯 Objective
The goal of this project was to:
- **Model** the relationship between a customer's **age** and their **annual medical charges**.  
- **Build** a transparent, interpretable model that satisfies **regulatory requirements**.  
- **Establish** a baseline understanding before progressing to multiple-variable regression.

---

## 🧩 Dataset Description
The dataset (`insurance.csv`) contains demographic and lifestyle factors influencing medical costs.

| Feature | Description |
|----------|--------------|
| `age` | Age of the insured individual |
| `sex` | Gender (male/female) |
| `bmi` | Body Mass Index – measure of body fat |
| `children` | Number of dependents covered |
| `smoker` | Smoking status (yes/no) |
| `region` | Residential region in the U.S. |
| `charges` | Annual medical expenses (target variable) |

For this project, the **`age`** variable was used as the independent feature and **`charges`** as the dependent variable.

---

## 🔬 Methodology

### 1️⃣ Data Understanding & Preparation
- **Loaded** and inspected the dataset using **Pandas**.  
- **Checked** for missing values and verified data integrity.  
- **Filtered** the data to include only **non-smokers** to isolate the effect of age.

### 2️⃣ Exploratory Data Analysis (EDA)
- **Visualized** the distribution of age and charges using **Matplotlib**, **Seaborn**, and **Plotly**.  
- **Observed** a positive linear trend — older individuals tend to incur higher medical costs.

### 3️⃣ Model Development
- **Defined** the regression equation:  
  \[
  \text{Predicted Charges} = w \times \text{Age} + b
  \]
- **Trained** the model using **scikit-learn’s `LinearRegression`** class.  
- **Generated** predictions and plotted the regression line to compare with actual data.

### 4️⃣ Model Evaluation
- **Calculated** the **Root Mean Squared Error (RMSE)** to evaluate model accuracy.  
- **Visualized** predicted vs. actual values to assess performance and model fit.

---

## 📈 Results & Observations
- A **strong positive correlation** was found between **age** and **medical expenses**.  
- The regression line captured the general upward trend, confirming the linear relationship.  
- Some variance remained unexplained, indicating that factors like **smoking** and **BMI** significantly affect costs.  
- The model serves as a **simple, interpretable baseline** for further predictive modeling.

---

## ⚙️ Tools and Technologies
| Category | Tools |
|-----------|-------|
| **Programming Language** | Python |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn |
| **Environment** | Jupyter Notebook |

---

## 💡 Key Insights
- **Age** alone is a meaningful predictor, but **multi-feature models** provide stronger accuracy.  
- **Explainable models** are crucial for compliance and trust in healthcare and insurance analytics.  
- This project illustrates how **simple regression** can be a strong foundation for **interpretable AI systems**.

---

## 🚀 Next Steps
- Extend to **Multiple Linear Regression** with additional variables like BMI and smoker status.  

## 🧩 Usage

### 🔧 Prerequisites
Ensure you have the following dependencies installed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly

## 📞 Contact +233 551411848 / +233 502990126
- 📧 paakwesiprah20@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/prince-paakwesi-prah/)
