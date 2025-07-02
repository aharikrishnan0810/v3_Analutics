# COVID-19 India Analysis and Predictive Modeling

This project provides a detailed analysis of the COVID-19 situation in India using publicly available datasets. It includes exploratory data analysis (EDA), visualizations, data cleaning, and predictive modeling to understand the factors influencing COVID-19 spread and mortality.

## 📁 Datasets Used

- **COVID-19 Case Records**: Daily case counts from different Indian states and union territories.
- **Vaccination Data**: State-wise vaccination efforts including dose distribution by gender and age group.
- **Testing Details**: Daily state-level testing statistics.

> Data Sources:  
> - Ministry of Health & Family Welfare, India  
> - covid19india.org  
> - [Travel history dataset](https://www.kaggle.com/dheerajmpai/covidindiatravelhistory)  
> - Wikipedia (for population info)

---

## 🔍 Exploratory Data Analysis (EDA)

The project includes:
- Distribution plots of confirmed cases, deaths, vaccinations, and testing.
- State-wise comparison of COVID impact.
- Gender-wise and age-wise vaccine distribution.
- Heatmaps and pairplots to understand feature relationships.

---

## 🔮 Predictive Modeling

A **Linear Regression model** was trained to predict the number of deaths based on confirmed and cured cases. Model evaluation metrics:
- **R² Score**: 0.85
- **MSE**: ~19M

The model serves as a basic starting point for further forecasting and modeling tasks.

---

## 📊 Visualizations

- Histograms & boxplots for case statistics
- Bar plots for state comparisons
- Heatmaps for correlations
- Actual vs Predicted scatter plots

---

## ⚙️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📁 Project Structure

```bash
├── COVID19_India_Analysis_and_Modeling.ipynb   # Colab notebook
├── README.md                                   # Project documentation
├── covid_19_india.csv                          # COVID case data
├── covid_vaccine_statewise.csv                 # Vaccination data
└── StatewiseTestingDetails.csv                 # Testing data
