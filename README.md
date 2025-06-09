# Predictive-Analysis-and-Forecasting-of-Global-Electric-Vehicle-Sales
Predictive analysis and forecasting of global electric vehicle sales involve utilizing models like ARIMA and LSTM to achieve high accuracy. Factors such as economic conditions, policy changes, and consumer sentiment play crucial roles in shaping these forecasts.


`README.md`

# Global Electric Vehicle Sales Analysis & Forecasting

This project provides a comprehensive analysis and forecasting framework for global electric vehicle (EV) sales. It integrates data analytics, advanced machine learning models, policy impact analysis, and infrastructure optimization to deliver accurate predictions and actionable insights aimed at accelerating EV adoption worldwide.

---

## Overview

Electric vehicles are a core solution for sustainability, helping reduce greenhouse gas emissions and dependence on fossil fuels. This project investigates EV sales trends globally, evaluates economic and policy factors affecting adoption, and compares predictive models to identify the most suitable forecasting techniques. Additionally, it explores infrastructure optimization using Vehicle-to-Grid (V2G) technology and consumer sentiment analysis from social media data.

---

## Features

- **EV Sales Trends Analysis:** Examines historical sales data for Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) across multiple countries.
- **Economic & Policy Evaluation:** Studies the effects of fuel prices, government incentives, subsidies, and regional infrastructure on EV market growth.
- **Forecasting Models:** Implements and compares traditional statistical models (ARIMA) and cutting-edge machine learning models (LSTM, hybrid ensembles) focusing on accuracy measured by MAE and MSE.
- **Infrastructure Optimization:** Proposes optimal locations for V2G-enabled charging stations that balance grid stability, traffic density, and local load.
- **Consumer Behavior Insights:** Uses Natural Language Processing (NLP) techniques to analyze social media sentiment regarding EV adoption and infrastructure.
- **Policy Impact Simulation:** Allows scenario analyses to understand how different subsidy and fuel pricing policies influence EV uptake.

---

## Technology Stack

- Python for data processing, analysis, and model training
- Machine Learning libraries: TensorFlow (LSTM), Statsmodels (ARIMA)
- Data visualization via Matplotlib
- Dataset: Electric car sales share data from 2010 to 2023 for various regions worldwide
- Sentiment analysis tools leveraging social media hashtags related to EVs

---

## Getting Started

### Prerequisites

- Python 3.x
- Required Python packages: pandas, numpy, matplotlib, tensorflow, statsmodels, scikit-learn

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/global-ev-sales.git
   cd global-ev-sales
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Prepare dataset:
   - Place the `electric-car-sales-share.csv` file in the project root or update the file path in the notebook scripts.

### Usage

- Run the Jupyter notebooks provided in the `ML_Codes/` directory to:
  - Explore and preprocess EV sales data
  - Train and evaluate forecasting models
  - Calculate forecasting errors (MAE, MSE)
  - Perform infrastructure optimization and policy impact analysis

---

## Results

- The hybrid LSTM-ARIMA model outperforms individual models with consistently lower Mean Absolute Error (MAE) across multiple countries.
- Optimized V2G charging infrastructure improves grid stability and cost efficiency, particularly in high-demand urban regions.
- Policy simulations highlight the positive impact of combined subsidies and fuel pricing incentives on EV adoption rates.

---

## Contributing

Contributions are welcome to enhance forecasting models, extend infrastructure simulations, or incorporate additional data such as real-time consumer sentiment and emerging energy technologies.

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## Contact

For questions or collaborations, please reach out to the authors:

- Sanchay Awana: 22bcs109@iiitdwd.ac.in  
- Rachakonda Shrutik Sai: 22bcs096@iiitdwd.ac.in  
- Navneet Priyadarshi: 22bcs074@iiitdwd.ac.in  
- S Dakshish Murthy: 22bcs102@iiitdwd.ac.in  
- Sunil C K: sunilck@iiitdwd.ac.in

---

## Visual Preview

The project includes rich graphical analyses comparing actual vs. predicted EV sales, infrastructure layouts, and policy impact charts to support decision-making.

---

*This README file is designed with clarity and elegance, focusing on developer experience consistent with a high-end modern open-source project.*
