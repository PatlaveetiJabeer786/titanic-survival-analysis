# titanic-survival-analysis
A machine learning project exploring the factors that influenced survival rates on the Titanic using Python and Scikit-Learn.

# Titanic: Machine Learning from Disaster

**GitHub:** [https://github.com/PatlaveetiJabeer786](https://github.com/PatlaveetiJabeer786)  
**Portfolio:** [https://jabeer.lovable.app/](https://jabeer.lovable.app/)

## 🚀 Project Overview (STAR Method)

### Situation
The sinking of the Titanic is one of the most infamous shipwrecks in history. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

### Task
The goal is to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

### Action
- **Data Cleaning:** Handled missing values in 'Age' and 'Embarked' columns.
- **Feature Engineering:** Created new features such as 'FamilySize' and extracted titles from names to improve model accuracy.
- **Exploratory Data Analysis (EDA):** Visualized correlations between survival rates and features like Pclass and Sex.
- **Modeling:** Implemented algorithms including Logistic Regression and Random Forest using Scikit-Learn.

### Result
- Achieved an accuracy score of [ 80%] on the test set.
- Identified that 'Sex', 'Pclass', and 'Age' were the most significant predictors of survival.

## 🛠️ Technologies Used
- Python (Pandas, NumPy)
- Matplotlib & Seaborn (Visualization)
- Scikit-Learn (Machine Learning)

## 📂 Project Structure
- `data/`: Contains train.csv and test.csv
- `notebooks/`: Jupyter notebook with step-by-step analysis
- `models/`: Saved model files
