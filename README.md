# 🏠 Housing Price Prediction

Predicting housing prices using **regression models** on the California Housing dataset — full EDA, feature engineering, and model evaluation pipeline.

## 📋 Problem Statement

Predicting house prices based on property characteristics and location is a classic regression problem with real-world applications in:
- Real estate valuation
- Investment analysis
- Property market understanding

This project builds a complete ML pipeline from data exploration to model evaluation.

## 📊 Dataset

- **Source:** California Housing dataset (scikit-learn / Kaggle)
- **Records:** ~20,000 housing blocks in California
- **Features:**
  - Geographic: longitude, latitude
  - Demographic: population, median income
  - Structural: housing median age, average rooms, bedrooms, bedrooms ratio
  - Location: proximity to ocean
- **Target:** Median house value (in $100,000s)

## 🔧 Approach

### 1. Exploratory Data Analysis (EDA)
- Data distribution analysis
- Feature correlation study
- Geographic visualization of housing prices
- Identification of key price drivers

### 2. Data Preparation
- Handling missing values
- Feature scaling where appropriate
- Train/test split for evaluation

### 3. Modeling
- Regression model training
- Feature importance analysis
- Model performance evaluation

## 📖 Notebook Structure

The notebook (`Housing_Price_Prediction.ipynb`) follows a complete ML workflow:

1. **Data Loading** — Fetch and load the California housing dataset
2. **EDA** — Visual exploration of distributions, correlations, and geography
3. **Preprocessing** — Clean and prepare features
4. **Modeling** — Train regression models
5. **Evaluation** — Assess model performance

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Visualization (including geographic plots) |
| Seaborn | Statistical visualizations |
| Scikit-learn | ML models and evaluation |
| Jupyter | Development environment |

## 🚀 How to Run

```bash
# Clone
git clone https://github.com/Abhi-pacific/housing_price_prediction.git
cd housing_price_prediction

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Run the notebook
jupyter notebook Housing_Price_Prediction.ipynb
```

## 💡 Key Insights

1. **Geographic location** is a strong predictor — coastal proximity and regional factors drive price variation
2. **Median income** of the block group correlates strongly with housing prices
3. **House age** and **-room counts** provide additional predictive power
4. The California housing dataset demonstrates how demographic and geographic features combine to explain real estate values

## 📈 Model Evaluation

- Regression metrics applied to assess prediction accuracy
- Feature importance identified key drivers of housing prices

## 👨‍💻 Author

**Abhishek Chauhan** — Data Analyst @ Netimpact Solutions  
[LinkedIn](https://linkedin.com/in/abhishek-chauhan-28c) | [Email](mailto:Chauhan.a.abhishek@icloud.com)

---

*Part of my machine learning portfolio. Check out my other projects on [GitHub](https://github.com/Abhi-pacific).*
