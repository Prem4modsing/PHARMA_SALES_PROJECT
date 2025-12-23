# 📊 Pharma Sales Forecasting

A comprehensive time series analysis and forecasting project for pharmaceutical drug sales data (2014-2019).

## 🎯 Problem Statement

This project addresses the challenges of time series analysis and forecasting in the pharmaceutical sales domain. Sales data can often be highly uncertain and appear to follow random patterns. The objective is to:

- Analyze historical sales data from 2014 to 2019
- Identify trends and seasonal patterns
- Develop forecasting models to predict future sales with greater accuracy
- Improve the precision of monthly sales predictions for pharmaceutical drugs

## 📁 Dataset

- **Source**: [Kaggle - Pharma Sales Data](https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data)
- **File**: `salesdaily.csv`
- **Time Period**: 2014 - 2019
- **Focus Drug**: N02BA (Analgesic medication)

## 🔬 Analysis Performed

### 1. Exploratory Data Analysis
- Data loading and preprocessing
- Monthly sales aggregation
- Time series visualization

### 2. Statistical Tests
- **Mann-Kendall Test**: Trend detection
- **ADF Test**: Augmented Dickey-Fuller test for stationarity
- **KPSS Test**: Kwiatkowski-Phillips-Schmidt-Shin test for stationarity

### 3. Time Series Decomposition
- Additive decomposition
- Multiplicative decomposition
- Trend, seasonality, and residual analysis

### 4. Feature Engineering
- Rolling averages (7-day, 30-day moving averages)
- Differencing for stationarity

### 5. Forecasting Models
- **SARIMAX**: Seasonal ARIMA with exogenous variables
- **Prophet**: Facebook's forecasting library
- ACF/PACF analysis for parameter selection

## 📈 Key Visualizations

- Monthly sales trends
- Seasonal decomposition plots
- Rolling mean analysis
- Forecast predictions

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **Statsmodels** - Statistical modeling (SARIMAX, seasonal decompose)
- **Prophet** - Time series forecasting
- **Scikit-learn** - Model evaluation metrics
- **PyMannKendall** - Trend analysis

## 📦 Installation

```bash
pip install pandas numpy matplotlib seaborn statsmodels prophet scikit-learn pymannkendall
```

## 🚀 Usage

1. Clone the repository:
```bash
git clone https://github.com/Prem4modsing/PHARMA_SALES_PROJECT.git
```

2. Navigate to the project directory:
```bash
cd PHARMA_SALES_PROJECT
```

3. Open the Jupyter notebook:
```bash
jupyter notebook PHARMA_SALES_A035_A033_A027_A048.ipynb
```

## 📊 Results

The project provides insights into:
- Sales trends over time
- Seasonal patterns in pharmaceutical drug sales
- Accurate forecasts for future sales periods

## 👥 Team Members

- A035
- A033
- A027
- A048

## 📚 References

- [Kaggle Dataset](https://www.kaggle.com/datasets/milanzdravkovic/pharma-sales-data)
- [Pharma Sales Data Analysis and Forecasting](https://www.kaggle.com/code/milanzdravkovic/pharma-sales-data-analysis-and-forecasting)
- [Prophet Documentation](https://facebook.github.io/prophet/)

## 📄 License

This project is for educational purposes.

---

⭐ If you found this project helpful, please give it a star!
