# AI MarketPulse – Module E Submission Links

## Notebook (.ipynb)
https://colab.research.google.com/github/madhavsinghal88/AI-MarketPulse/blob/main/marketpulse.ipynb

## Project Report (Google Docs)
https://docs.google.com/document/d/1Ncleuk5rwNhWLFXp-OOQa7S_wV8arNiS8msop0XFDy8/edit?usp=sharing





# AI MarketPulse – AI for Market Trend Analysis

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📌 Project Overview

**AI MarketPulse** is an end-to-end AI system for analyzing retail/store sales data to generate actionable market insights and sales predictions. This project demonstrates:

- **Trend Analysis**: Identifies rising, falling, and stable market trends
- **Sales Forecasting**: Predicts future sales using Random Forest regression
- **Pricing Insights**: Analyzes the impact of price and discounts on sales
- **Cold-Start Handling**: Implements fallback strategies for new products/stores

### Key Features

✅ Automated data download from public datasets  
✅ Comprehensive data preprocessing and feature engineering  
✅ Month-over-Month (MoM) trend analysis with visualizations  
✅ Machine learning-based sales forecasting  
✅ Business recommendations using rule-based insights  
✅ Edge case handling for cold-start scenarios  
✅ Ethical AI considerations and responsible use guidelines  

## 📁 Folder Structure

```
marketpulse/
├── marketpulse.ipynb      # Primary notebook (run this!)
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

## 🚀 How to Run

### Prerequisites

- Python 3.8 or higher
- pip package manager
- Jupyter Notebook or JupyterLab

### Installation Steps

1. **Clone or download this repository**
   ```bash
   cd marketpulse
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook marketpulse.ipynb
   ```

5. **Run all cells**
   - Click `Kernel` → `Restart & Run All`
   - Or run cells sequentially from top to bottom

## 📊 Demo Steps

1. **Data Loading**: The notebook automatically downloads a retail sales dataset. If download fails, synthetic data is generated.

2. **Data Exploration**: View dataset statistics, distributions, and data quality checks.

3. **Trend Analysis**: Observe MoM growth analysis with Top 10 Rising and Falling trends visualized.

4. **Forecasting**: Train the Random Forest model and view actual vs predicted plots.

5. **Insights**: Review automatically generated business recommendations.

6. **Edge Cases**: Examine cold-start handling demonstration.

## 📈 Sample Outputs

- **Trend Visualization**: Line plots showing sales trends for top products
- **Forecast Accuracy**: MAE, RMSE, MAPE metrics
- **Prediction Chart**: Actual vs Predicted sales comparison
- **Business Insights**: 5-10 actionable recommendations

## ⚠️ Known Limitations

- Synthetic fallback data may not represent real-world patterns
- Forecasting accuracy depends on data quality and feature relevance
- Cold-start products use baseline predictions (less accurate)
- Seasonal patterns may require more historical data

## 🔒 Ethical Considerations

- No personal/identifiable information is used
- Predictions should not be the sole basis for business decisions
- Model fairness across different product categories should be monitored
- Transparency: This project uses AI/ML for educational demonstration

