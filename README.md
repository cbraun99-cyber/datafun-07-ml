# datafun-07-ml
# Module 7 - Machine Learning

### Author: Chris Braun

## 📚 Project Overview

This project demonstrates comprehensive machine learning techniques including linear regression, model evaluation, and predictive analysis across multiple datasets. The analysis covers both time series forecasting and multivariate regression problems.

## 🎯 Project Components

### Part 1: Chart a Straight Line
- Celsius to Fahrenheit conversion visualization
- Linear equation fundamentals

### Part 2: NYC Temperature Prediction (SciPy)
- Historical NYC January temperature analysis (1895-2018)
- Linear regression using SciPy's `linregress`
- 2024 temperature prediction

### Part 3: NYC Temperature Prediction (scikit-learn)
- Machine learning approach with train/test split
- Model validation and performance metrics
- Comparison with Part 2 methodology

### Part 4: Method Comparison
- Professional evaluation of both modeling approaches
- Insights into methodological trade-offs

### Part 5: California Housing Analysis (Bonus)
- Multivariate regression on California housing dataset
- Multiple algorithm comparison (Linear, Ridge, Lasso, ElasticNet)
- Feature importance and business insights

## 🚀 Quick Start

```bash
# Create virtual environment
py -m venv .venv

# Activate virtual environment
.venv\Scripts\activate

# Install dependencies
py -m pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook

Then open your ```chrisbraun_ml.ipynb``` and run all cells

## 📋 Requirements

Create ```requirements.txt``` with:
```text 
jupyter>=1.0.0
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.5.0
seaborn>=0.11.0
scipy>=1.7.0
scikit-learn>=1.0.0
```
## 📊 Key Results

### NYC Temperature Analysis
* **Warming Trend:** ~1.5°F per century increase

* **2024 Prediction:** ~37.2-37.3°F

* **Model Performance:** R² ~0.65

### California Housing Analysis
* **Best Model:** Ridge Regression

* **Prediction Accuracy:** ~$50,000 MAE

* **Key Drivers:** Income & geographic location

## 🛠️ Project Structure
```text
datafun-07-ml/
│
├── yourname_ml.ipynb          # Main analysis notebook
├── README.md                  # Project documentation
├── requirements.txt           # Python dependencies
└── images/                    # Generated visualizations
```

## 💡 Key Insights
* Income is the dominant factor in California housing prices

* Geographic location creates clear price clusters (coastal premium)

* Regularized models (Ridge/Lasso) provide more robust predictions

* Both SciPy and scikit-learn approaches yield similar predictions

* Train/test splitting is crucial for model validation

## 🔧 Usage
1. Run the complete analysis by executing all cells in yourname_ml.ipynb

2. Follow the narrative through markdown explanations and code

3. Review visualizations for data insights

4. Examine model comparisons and performance metrics

## 📈 Visualizations Included
* Temperature trend lines and scatter plots

* Residual analysis plots

* Feature correlation heatmaps

* Geographic distribution maps

* Model performance comparisons

## 🤝 Git Workflow
Remember to regularly:
```bash
git add .
git commit -m "Descriptive commit message"
git push origin main
```

## 📝 Notes
* All data is loaded from reliable online sources

* Code includes comprehensive error handling

* Analysis follows industry best practices

* Visualizations are customized for clarity

## 🎓 Learning Outcomes
* Linear regression implementation

* Model evaluation techniques

* Data visualization skills

* Professional documentation

* Comparative analysis methods