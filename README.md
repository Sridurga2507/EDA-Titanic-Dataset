# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to discover patterns that influenced passenger survival.  
The dataset contains information such as passenger demographics, class, family size, and survival status.  

The main goal is to uncover insights about survival factors and prepare the dataset for potential machine learning tasks.

---

## 🚀 Steps Performed
1. **Data Loading**  
   - Imported Titanic dataset from Kaggle / Seaborn library.

2. **Data Cleaning & Preprocessing**  
   - Handled missing values (e.g., Age, Cabin, Embarked).  
   - Converted categorical variables (Sex, Embarked) into numerical codes.  
   - Created new features (e.g., FamilySize, IsAlone).  

3. **Exploratory Analysis**  
   - Univariate analysis: distribution of age, fare, class.  
   - Bivariate analysis: relation between survival and features (sex, class, age).  
   - Correlation heatmap.  

4. **Visualization**  
   - Used Seaborn and Matplotlib to create bar plots, histograms, and box plots.  
   - Compared survival rate by gender, passenger class, and embarkation port.  

---

## 📊 Key Insights
- **Women had higher survival rate** compared to men.  
- **First-class passengers** were more likely to survive than those in second and third class.  
- **Children and younger passengers** had better chances of survival.  
- Traveling with family increased survival chances compared to being alone.  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 📂 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/titanic-eda.git
