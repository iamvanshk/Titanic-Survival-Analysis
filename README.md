# 🚢 Titanic Survival Analysis

## 📌 Overview
This project performs an exploratory data analysis (EDA) on the Titanic dataset to identify key factors that influenced passenger survival.

---

## 🎯 Objective
- Analyze survival patterns among passengers  
- Understand the impact of gender, age, and socioeconomic status  
- Extract meaningful insights from real-world data  

---

## 📊 Dataset
- Source: Kaggle Titanic Dataset  
- Records: 891 passengers  
- Features include age, gender, ticket class, fare, and survival status  

---

## 🧹 Data Cleaning
- Filled missing values in `Age` using median  
- Dropped `Cabin` due to excessive missing values  
- Filled missing values in `Embarked` using mode  

---

## ⚙️ Feature Engineering
- **FamilySize**: Total family members aboard  
- **IsAlone**: Indicator for solo travelers  
- **AgeGroup**: Grouped ages into categories for better analysis  

---

## 📈 Key Insights

- Female passengers had significantly higher survival rates (~74%) compared to males (~19%)  
- Passengers in higher classes had better survival outcomes, indicating socioeconomic advantage  
- Children had higher survival rates, supporting the "women and children first" protocol  
- Small families had better survival rates compared to solo travelers or large groups  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📌 Conclusion
The analysis reveals that survival on the Titanic was strongly influenced by gender, age, and passenger class. Social and economic factors played a critical role in determining survival outcomes.

---

## 🚀 Future Work
- Apply machine learning models for survival prediction  
- Perform deeper feature engineering  
- Explore additional datasets for comparison  

---

## 👤 Author
- Vansh Khandelwal
- Email id - iamvanshk11@gmail.com
