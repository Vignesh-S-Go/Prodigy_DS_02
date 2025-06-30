# Prodigy InfoTech Data Science Internship — Task 02

## 📄 Task Overview
**Task 02:** Perform **data cleaning** and **exploratory data analysis (EDA)** on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.

---

## 📊 Dataset
The dataset used for this task is the famous **Titanic Dataset** from [Kaggle](https://www.kaggle.com/c/titanic).

It contains information about the passengers aboard the Titanic, including:
- Personal details like Name, Age, Gender
- Socioeconomic status (`Pclass`, `Fare`)
- Travel details (`SibSp`, `Parch`, `Ticket`, `Cabin`, `Embarked`)

---

## 🛠️ Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## 🔍 Exploratory Data Analysis (EDA)

### ✔️ Data Cleaning
- Handled missing values:
  - Filled missing `Age` with the **median**.
  - Filled missing `Embarked` with the **mode**.
  - Filled missing `Cabin` with `'Unknown'`.
- Checked for and handled potential data quality issues.

---

### ✔️ Univariate Analysis
- Distribution of:
  - **Passenger Class (`Pclass`)**
  - **Gender (`Sex`)**
  - **Age**
  - **Fare**
  - **Embarkation Port (`Embarked`)**

---

### ✔️ Bivariate and Multivariate Analysis
- Relationship between:
  - **Passenger Class (`Pclass`)** and **Fare**
  - **Age distribution** across **passenger classes**
  - **Gender distribution** by class
  - **Fare vs. Age** with passenger class differentiation
  - **Embarkation point** vs. **Fare**

---

## 📈 Visualizations Created
- Count plots for categorical features
- Histograms and KDE plots for continuous features
- Box plots to compare age across classes
- Bar plots to examine fare differences across embarkation points
- Scatter plots for age vs. fare

---

## 📌 Key Insights
- Most passengers belonged to **3rd class**, suggesting affordability.
- **Males were more than females** aboard the ship.
- **Median age** was around **30 years**.
- Higher class passengers paid significantly **higher fares**.
- Missing cabin information is more prevalent in **lower classes**.

---

## 🎯 Conclusion
This exploratory data analysis provided valuable insights into the Titanic dataset. It revealed relationships between features such as age, class, fare, and embarkation points. The analysis is an essential foundation for further predictive modeling, such as survival prediction.

---

## 🙏 Thank You
Thank you for reviewing my submission for **Task 02** of the Prodigy InfoTech Data Science Internship.

