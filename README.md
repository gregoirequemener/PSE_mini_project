# Programming mini-project

## 🎥 Project Overview
This project is used to assess the skills and knowledge of the SIA master's programming course (ENPC / PSE). 

This work focuses on the film industry, and in particular on the influence of a film's budget on its profitability, and thus determine a significant correlation. The idea is to help production companies estimate the performance of films according to their characteristics (genre, release date, number of Oscar-winning actors, etc.). This forecasting model uses a machine learning model of the linear regression type, known for its simplicity of use and interpretation. 

## 📊 Data Sources
This work is based on a database of 283 films. The following variables were analyzed:
- Name
- Revenues 
- Number of viewers
- Budget
- Allociné rating 
- Year of release 
- Month of release 
- Release season 
- Genre
- Number of Oscar winners
- Country of production

Data was particularly difficult to obtain on a large number of films. Traditional methods such as API queries or webscrapping were inconclusive:
- Pay API
- Web scrapping difficult because data not present on a single site (need to multiply agents)

The solution used here is the use of an AI agent and manual supervision. Results were obtained quickly and successfully.

## 🧑‍💻 How it works
### Prerequisites
Initializing Jupyter notebook and clone the repo
```bash
jupyter notebook
```
```bash
git clone (https://github.com/gregoirequemener/PSE_mini_project.git)
```

### Dependancies
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `statsmodels`
- `sklearn`

### Project structure
pse_mini_project/
│

├── notebook/

│   └── mini_project_notebook.ipynb

│

├── data/

│   └── V1dataframe_films.xlsx

│

├── instructions/

│   └── Python mini projet GQ version anticipée.pptx

│   └── README.md

│

└── .gitignore

### Work structure
1. Project and database initialization
2. Descriptive statistics
3. Regression model
4. Prediction exercise
5. Conclusion

## 📈 Model Performance
The linear regression model (OLS) is a powerful tool for predicting the influence of budget on a film's profitability. 
```
The coefficient of the budget variable = 5.9964
t-stat = 2.533 (abs value)
...
R2 adjusted = 0.799
Residual distribution = follows a normal distribution with mean 0
```

## 💡 Future Improvements
- Realize this model with a database richer in observations (number of films) and variables (characteristics)
- Use other more complex prediction models (random forest...)

## 📧 Contact
personal e-mail: gregoirequem@gmail.com
student e-mail: gregoire.quemener@psemail.eu

Thank you for reading.
