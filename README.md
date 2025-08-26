# Data and Text Mining Projects

This repository includes two individual data-driven projects demonstrating time series forecasting and text mining techniques using R and Python. Detailed project descriptions, code, and methodology are provided below.

---

## 1. Time-series Forecasting for Environmental Data (Python)

**Description**  
Forecasts environmental variables using classical and regression-based time series methods.

**Tech Stack**  
- Python 3  
- Libraries: `pandas`, `numpy`, `statsmodels`, `scikit-learn`, `matplotlib`, `seaborn`

**Key Steps**  
1. **Data Collection**  
   - Collected ~3,650 daily environmental readings (10-year time series).  
2. **Preprocessing**  
   - Handled missing data, performed seasonal decomposition, and stationarity checks.  
3. **Modeling Approaches**  
   - Applied **ARIMA**, **Exponential Smoothing (ETS)**, **Time Smoothing**, and **Multiple Regression**.  
4. **Model Evaluation**  
   - Evaluated models using RMSE and MAE; ARIMA achieved best performance with RMSE reduced from 18.5 to 16.3 (~12% improvement).  
5. **Visualization**  
   - Generated trend plots, forecast charts, and residual diagnostics for interpretability.

**Usage**  
```bash
# Clone the repo
git clone https://github.com/Frankie-go/Data-and-Text-Mining.git

# Navigate to project folder
cd Data-and-Text-Mining/time_series_forecasting

# Install dependencies (e.g., via conda/pip)
pip install -r requirements.txt

# Run forecasting script
python forecast.py --data_path data/environmental_data.csv --output_path results/forecasts.png


