# 🚧 Road Accident Severity Analyzer

## 📌 Project Overview

This project presents a data-driven analysis of road accident data to understand patterns in accident severity, identify high-risk regions, and analyze factors contributing to fatalities and injuries. The goal is to extract meaningful insights and build a predictive model for accident impact.

---

## 🎯 Objectives

* Analyze road accident data across regions and years
* Identify high-risk states and conditions
* Understand factors affecting accident severity
* Perform exploratory data analysis (EDA)
* Build a predictive model for injuries based on accident data

---

## 🧹 Data Preprocessing

* Removed duplicate records
* Handled missing values using appropriate techniques
* Cleaned column names (removed extra spaces)
* Converted data types (e.g., Year → integer)
* Created new features:

  * **Fatal** (1 = fatal accident, 0 = non-fatal)
  * **Fatality Rate** (deaths per accident)

---

## 📊 Exploratory Data Analysis (EDA)

Performed multiple visualizations:

* 📈 Year-wise trend of accidents, injuries, and deaths
* 📊 Top 10 states with highest accidents
* 🥧 Pie chart of major accident causes
* 🌦️ Weather condition analysis
* 🌙 Light condition analysis (day/night)
* 🔥 Correlation heatmap
* 🔗 Pairplot for feature relationships
* 📦 Boxplot to detect outliers

---

## 🔍 Key Insights

* Certain states consistently report higher accident rates
* Strong correlation between total accidents and injuries
* Weather and light conditions significantly affect accidents
* Fatal accidents are a smaller portion but highly impactful
* Some regions show disproportionately high risk

---

## 🤖 Machine Learning Model

**Model Used:** Linear Regression

### Features Used:

* Total Accidents

### Target:

* Persons Injured

### Data Split:

* 80% Training
* 20% Testing

---

## 📈 Model Performance

* **R² Score:** (your value here)
* **MAE:** (your value here)
* **MSE:** (your value here)

---

## 📚 Learnings

* Real-world datasets require proper cleaning
* Visualization helps uncover hidden patterns
* Feature engineering improves analysis quality
* Even simple models can give strong predictions

---

## ⚠️ Limitations

* Limited features used for prediction
* Dataset may not include all real-world factors
* Missing values handling can affect accuracy

---

## 🚀 Future Improvements

* Use advanced ML models (Random Forest, XGBoost)
* Include more features (road type, driver behavior, etc.)
* Perform multi-year trend analysis
* Build an interactive dashboard

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Project Structure

road-accident-severity-analyzer/
│
├── data/
├── notebook/
├── visuals/
├── README.md

---

## 👨‍💻 Author

**Aru (B.Tech CSE - Data Analytics)**
Lovely Professional University
