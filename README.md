🧾 Project Overview
This project explores the historical stock performance of Tesla, Inc. from January 1, 2015, to January 17, 2024, with the goal of building predictive models to estimate future stock prices. The dataset, sourced from Kaggle, includes essential monthly stock metrics such as opening, closing, high, low, and trading volume.

We apply time series analysis and machine learning techniques to understand market behavior, extract trends, and generate future price simulations—valuable for investors, analysts, and researchers.

📊 Dataset Details
Source: Kaggle

Time Frame: Jan 2015 – Jan 2024

Frequency: Monthly

Total Records: 2,274 rows

Columns:

Date: Monthly record date

Open: Opening price

High: Highest price that month

Low: Lowest price that month

Close: Closing price

Volume: Number of shares traded

This dataset offers a decade-long perspective on Tesla’s market behavior and serves as a strong foundation for financial forecasting and investment research.

🧠 Project Workflow
1. Data Preprocessing
Parsing and formatting dates

Handling missing/null values

Sorting time-series data chronologically

2. Exploratory Data Analysis (EDA)
Trendline plots for Open/Close prices

Correlation matrix for numerical features

Visualization of monthly volume and volatility

Rolling averages and SMA/EMA indicators

3. Feature Engineering
Time-based lag features

Technical indicators (e.g., Moving Averages, MACD, RSI)

Trend-based flags (bullish/bearish windows)

4. Modeling Approaches
Linear Regression

Random Forest Regressor

ARIMA for univariate time series forecasting

XGBoost Regressor for boosting performance

5. Evaluation Metrics
Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

6. 2025 Simulation
A simulated forecast of Tesla stock prices for the year 2025 is stored in tesla_2025_simulated_predictions.xlsx

📁 File Structure
File	Description
Tasla_Stock_Updated_V2.csv	Cleaned dataset used for training and analysis
tesla stocks pred..ipynb	Jupyter notebook with EDA, modeling, and forecasting
main.py	Python script for reproducible model training and predictions
tesla_2025_simulated_predictions.xlsx	Simulated forecast for future Tesla stock prices
.idea/	IDE workspace files (ignore for execution)

🚀 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/rahulraimau/tesla-stock-prediction.git
cd tesla-stock-prediction
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Notebook
Launch the notebook:

bash
Copy
Edit
jupyter notebook "tesla stocks pred..ipynb"
Or execute script:

bash
Copy
Edit
python main.py
📈 Visuals Included
Stock trendlines (Open vs. Close)

Monthly price change heatmaps

Volume vs. Price scatter plots

Forecast vs. Actual comparison

Model evaluation plots

🔮 Future Enhancements
Add LSTM-based deep learning model for sequential predictions

Integrate live stock data API (e.g., Yahoo Finance or Alpha Vantage)

Deploy a Streamlit dashboard to visualize predictions interactively

📄 License
This project is open-source and free to use under the MIT License. The dataset used is publicly available on Kaggle.
