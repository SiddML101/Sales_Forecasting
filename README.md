🛒 Store Sales Forecasting

A machine learning and time series analysis project to predict store sales using historical transactions, oil prices, holidays, and promotions. The project applies feature engineering, statistical modeling, and machine learning techniques to generate accurate sales forecasts.

📌 Features

📊 Data Sources: Sales transactions, oil prices, holiday calendars, store metadata.

🔍 EDA: Exploratory data analysis with visualizations for trends, seasonality, and outliers.

🛠 Feature Engineering: Created lag features, rolling averages, and date-based features.

📈 Time Series Models: ARIMA, SARIMA, and other statistical forecasting methods.

🤖 Machine Learning Models: Tree-based regression models for complex patterns.

📉 Evaluation: Metrics include RMSE and RMSLE for model performance comparison.

🛠 Tech Stack

Python 3.x

Pandas, NumPy for data handling

Matplotlib, Seaborn, Plotly for visualization

Statsmodels, pmdarima for time series models

Scikit-learn for ML models

Category Encoders for categorical variables


⚙ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/your-username/store-sales-forecasting.git
cd store-sales-forecasting


2️⃣ Create a virtual environment

python -m venv venv
source venv/bin/activate    # Mac/Linux
venv\Scripts\activate       # Windows


3️⃣ Install dependencies

pip install -r requirements.txt


4️⃣ Add the dataset
Place CSV files into a data/ folder. These should include:

train.csv

test.csv

transactions.csv

oil.csv

holidays_events.csv

stores.csv

5️⃣ Run the notebook

jupyter notebook final_model.ipynb

🧠 Workflow

Load & Merge Data – Combine sales data with oil prices, holidays, and store info.

EDA – Identify trends, seasonality, and anomalies in sales patterns.

Feature Engineering – Create new time-based and lag features.

Modeling – Apply SARIMA and ML models for forecasting.

Evaluation – Compare models using RMSE/RMSLE and choose the best performer.

📊 Results

Best model: SARIMA / hybrid approach.

Achieved low RMSE & RMSLE values, indicating accurate forecasts.

Captured both seasonal spikes and trend shifts influenced by holidays & oil prices.

⚠ Disclaimer

This project is for educational purposes only and is based on historical sales datasets.