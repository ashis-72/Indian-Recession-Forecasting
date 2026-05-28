# Indian-Recession-Forecasting
Time-series forecasting project for predicting recession trends in India using ARIMA and SARIMA models.
# Indian Recession Forecasting

A data-driven economic forecasting project focused on analyzing and predicting recession trends in India using time-series econometric models.

This project applies statistical forecasting techniques such as ARIMA and SARIMA to Indian macroeconomic data in order to study GDP movement, identify economic slowdowns, and forecast future recessionary patterns.

---

## Project Objective

The primary objective of this project is to forecast potential recessionary trends in the Indian economy over the next eight quarters after Q3 2026 using time-series forecasting techniques. By analyzing historical GDP growth data, the project aims to identify economic slowdown patterns and generate forward-looking forecasts using ARIMA and SARIMA models.

---

## Key Features

* Economic trend analysis using GDP data
* Recession pattern identification
* Time-series preprocessing and transformation
* Stationarity testing using the Augmented Dickey-Fuller Test
* ACF and PACF analysis for parameter selection
* ARIMA forecasting implementation
* SARIMA forecasting implementation
* Forecast visualization and comparison
* Statistical interpretation of economic trends

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Plotly
* Seaborn
* Statsmodels
* Scikit-learn

---

## Methodology

The project follows a structured econometric forecasting framework:

### Data Collection and Cleaning

 

The GDP growth rate data used in this project was collected from multiple official sources. The observation for `2023-10-01` was sourced from the Ministry of Statistics and Programme Implementation (MoSPI), Government of India. The remaining quarterly GDP growth observations were obtained from the Federal Reserve Economic Data (FRED) database maintained by the Federal Reserve Bank of St. Louis.

Data Source:

* MoSPI (Government of India)
* Federal Reserve Economic Data (FRED)

FRED Dataset:
[FRED GDP Dataset](https://fred.stlouisfed.org/graph/fredgraph.csv?id=LORSGPORINQ659S&utm_source=chatgpt.com)

  

Macroeconomic time-series data is cleaned, transformed, and converted into a suitable format for forecasting analysis. 

### Exploratory Data Analysis

Historical GDP trends are visualized to understand economic cycles, volatility, and recessionary behavior.

### Stationarity Testing

The dataset is tested for stationarity using the Augmented Dickey-Fuller (ADF) Test. Differencing techniques are applied where necessary.

### Model Building

ARIMA and SARIMA models are developed after selecting optimal parameters through ACF and PACF analysis.

### Forecasting

Future economic trends are forecasted and interpreted to assess possible recessionary risks.

---

## Repository Structure

```bash
Indian-Recession-Forecasting/
│
├── Indian_Recession_Forecasting.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Indian-Recession-Forecasting.git
```

Navigate to the project directory:

```bash
cd Indian-Recession-Forecasting
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch the Jupyter Notebook:

```bash
jupyter notebook Indian_Recession_Forecasting.ipynb
```

The notebook contains the complete forecasting workflow, including preprocessing, visualization, modeling, and prediction.

---

## Forecasting Models

### ARIMA

ARIMA (AutoRegressive Integrated Moving Average) is used for modeling non-seasonal time-series data after transforming it into a stationary series.

### SARIMA

SARIMA extends ARIMA by incorporating seasonal components, making it suitable for cyclical macroeconomic datasets.

---

## Insights

* Economic slowdowns can be identified through GDP growth patterns.
* Stationarity plays a critical role in accurate forecasting.
* Time-series models provide meaningful insights into macroeconomic behavior.
* Forecasting techniques can support policy analysis and financial research.

---

## Future Scope

* Integration of inflation, unemployment, and industrial production data
* Implementation of machine learning forecasting models
* Development of interactive forecasting dashboards
* Real-time macroeconomic data integration
* Comparison with deep learning models such as LSTM

---

## Author

Ashis Pal

Economics and data analytics enthusiast focused on macroeconomic research, forecasting, and financial analysis.

---

## License

This project is licensed under the MIT License.

Feel free to fork, modify, and contribute to the repository.
