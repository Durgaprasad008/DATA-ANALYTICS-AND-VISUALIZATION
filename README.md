# 📊 Assignment Title

**Time Series Analysis and Forecasting of NSE Stock using ARIMA**

---

## (1) Problem Statement

The objective of this assignment is to analyze historical stock price data of a publicly traded company listed on the NSE and build a time series forecasting model. The task involves understanding stock price behavior and predicting future closing prices using statistical techniques.

---

## (2) Objective

* To preprocess and clean stock price data
* To analyze trends and patterns in historical data
* To test stationarity using the ADF test
* To determine optimal ARIMA parameters using ACF and PACF plots
* To build an ARIMA model for forecasting
* To predict the next 30 days of stock prices

---

## (3) Dataset

* **Source:** NSE Historical Data
* **Stock:** Bosch Ltd
* **Features:**

  * Date
  * Open
  * High
  * Low
  * Close
  * Volume
  * VWAP and other trading metrics
* **Size:** ~1 year of daily stock price data

---

## (4) Methodology

### 1. Data Preprocessing

* Converted date column to datetime format
* Cleaned numerical columns (removed commas)
* Sorted data chronologically
* Handled missing values using forward fill

### 2. Exploratory Data Analysis (EDA)

* Visualized closing price trends over time
* Identified volatility and price fluctuations

### 3. Model Building

* Performed Augmented Dickey-Fuller (ADF) test for stationarity
* Applied differencing to make the series stationary
* Used ACF and PACF plots to determine ARIMA parameters (p, d, q)
* Trained ARIMA model on closing price data

### 4. Evaluation

* Analyzed residuals of the model
* Checked model performance using summary statistics
* Compared historical and forecasted values visually

---

## (5) Results

* The stock price series was initially **non-stationary** and became stationary after differencing
* The ARIMA model successfully captured short-term patterns
* Forecast results indicate **relative stability with slight upward movement**
* The model smooths extreme fluctuations but reflects recent trends

---

## (6) How to Run

```bash
pip install -r requirements.txt
python main.py
```

---

## (7) Conclusion

The ARIMA model proved effective for short-term forecasting of stock prices. The analysis shows that the stock is likely to remain relatively stable with a mild upward trend in the near future. However, due to inherent market volatility, predictions should be interpreted with caution.

---

## (8) Student's Details

* **Name:** Durga Prasad Pallagorla
* **Roll No:** 38
* **UIN:** 211A058
* **Year:** TE-AIDS 2025-26

---

If you want, I can also:

* 🔥 Add **images of your plots into README**
* 📁 Create a **requirements.txt file**
* 🚀 Make your GitHub look **professional & standout for placements**
