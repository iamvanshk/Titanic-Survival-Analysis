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

## Chances of Survival
- The survival of passengers was biased on factors like gender,socio-economic status, etc.
  <img width="869" height="587" alt="image" src="https://github.com/user-attachments/assets/ecdedf08-9a27-4016-9bd0-2b01626fb942" />


## 📈 Key Insights

<img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/6ab055ca-831e-4fd9-8d3c-02ae8cae3ff3" />
<img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/7d2fc38a-71a3-4ebf-b44d-dfc1f313c876" />

- Female passengers had significantly higher survival rates (~74%) compared to males (~19%), suggesting that women were given higher priority in rescues
- Passengers in higher classes had better survival outcomes, indicating socioeconomic advantage
- Age distribution shows us that majority of the passengers comprised of young adults
  <img width="714" height="569" alt="image" src="https://github.com/user-attachments/assets/73b5eb56-5c23-4a25-89c2-c662642df5ef" />
 
- Children had higher survival rates, supporting the "women and children first" protocol
- Small families had better survival rates compared to solo travelers or large groups

  
  <img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/303dd8f6-8378-49e5-8ad6-3680b55eb564" />
  <img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/82d7fbcd-3d96-4db1-a207-41caca26197c" />


- Even in upper classes, gender also decided the survival of people.
  <img width="711" height="569" alt="image" src="https://github.com/user-attachments/assets/66df7afb-b1d1-48f4-8902-99af5176be62" />

- Survival rate was also noticed upon the Embarkation point, as most of the upper class people embarked from Cherbourg(C)
   <img width="707" height="564" alt="image" src="https://github.com/user-attachments/assets/5ea3c90b-36d8-43da-8df5-614d3ff95926" />

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
