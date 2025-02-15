# ✈️ Airline Passenger Forecasting: Chronos AI vs ARIMA

## 📝 Project Overview
This project presents a comprehensive comparison between **Chronos AI** (Amazon's T5-based model) and **ARIMA** (Auto-Regressive Integrated Moving Average) for forecasting airline passenger numbers. The analysis focuses on both short-term and long-term forecasting capabilities using the classic Airline Passengers dataset.

## 📊 Model Comparison
![Comparison Between ARIMA and Chronos AI](Results/Comparision%20Between%20Arima%20And%20Chronos.png)

### 🤖 Models Evaluated
1. **Chronos AI**
   - Based on Amazon's T5 Transformer architecture
   - Specialized in time series forecasting
   - Handles complex patterns and seasonality

2. **ARIMA**
   - Traditional statistical approach
   - Well-established forecasting method
   - Based on auto-regression and moving averages

## 🎯 Key Findings

### Chronos AI Performance
- Superior performance in long-term forecasting (5 & 10 years)
- Better capture of seasonal patterns
- More robust to trend changes

![Chronos AI 5-Year Forecast](Results/Chronos%20AI%205%20year%20Forecast.png)

### ARIMA Performance
- Strong short-term forecasting capabilities
- Tendency to flatten out in long-term predictions
- Limited ability to capture complex patterns

![ARIMA Forecast vs Actual](Results/ARIMA%20Forecast%20VS%20Actual.png)

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Required packages listed in `requirements.txt`

### Installation
1. Clone the repository:
```bash
git clone https://github.com/anshh-arora/arima-vs-chronos-forecast
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook:
```bash
jupyter notebook airline_forecasting_chronos_vs_arima.ipynb
```

## 📁 Repository Structure
```
├── airline_forecasting_chronos_vs_arima.ipynb
├── README.md
├── Requirements.txt
├── Data
│   └── AirPassengers.csv
└── Results
    ├── ARIMA Forecast VS Actual.png
    ├── Arima VS Chronos AI Forecast(5&10 Years).png
    ├── Chronos AI 10 year Forecast.png
    ├── Chronos AI 5 year Forecast.png
    └── Comparision Between Arima And Chronos.png
```

## 🤝 Connect With Me
- **Email**: [ansharora.cs@gmail.com](mailto:ansharora.cs@gmail.com)
- **LinkedIn**: [Ansh Arora](https://www.linkedin.com/in/ansh-arora-data-scientist/)
- **Kaggle**: [Ansh1529](https://www.kaggle.com/ansh1529)

