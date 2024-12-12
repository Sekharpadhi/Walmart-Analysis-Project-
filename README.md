# Walmart Sales Forecasting

This project analyzes Walmart sales data to identify trends, seasonality, and factors influencing sales performance. It then uses predictive modeling techniques, specifically ARIMA and SARIMAX, to forecast sales for individual stores over the next 12 weeks.

## Project Goals

* **Exploratory Data Analysis (EDA):** Understand the dataset, identify trends, and uncover relationships between variables like unemployment rate, CPI, temperature, and weekly sales.
* **Sales Forecasting:** Build predictive models to forecast weekly sales for individual stores over the next 12 weeks.
* **Store Performance Analysis:** Identify top and bottom performing stores and quantify the significance of the difference in their performance.
## Predictive Modeling

* **SARIMAX:** Time series model  SARIMAX  used to forecast sales for individual stores, leveraging historical data and identified patterns.
* **Hidden Seasonality:** SARIMAX models are employed to address potential hidden seasonality and improve forecast accuracy.

## Data

* The project uses the 'Walmart.csv' dataset containing historical sales data for multiple Walmart stores.

## Libraries

* pandas
* numpy
* matplotlib
* seaborn
* statsmodels
* pmdarima
* scikit-learn

## Usage

1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter Notebook to perform the analysis and generate forecasts.

## Contributing

Contributions are welcome! Please open an issue or pull request to suggest improvements or add features.

## License

This project is licensed under the MIT License.
