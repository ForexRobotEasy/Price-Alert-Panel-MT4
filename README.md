# Price Alert Panel MT4

## Developer: Forex Robot Easy Team
## Website: forexroboteasy.com

---

**Disclaimer: ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.**

---

## Description

Price Alert Panel MT4 is a custom indicator that detects specific candlestick patterns on the selected timeframe. It provides real-time alerts when the defined candlestick pattern is detected.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-price-alert-panel-mt4-the-candle-stick-patterns-finder/).

---

## How It Works

The Price Alert Panel MT4 indicator works by analyzing the price data of the selected timeframe and checking for the presence of a specific candlestick pattern. It uses the `CheckCandlestickPattern` function to determine if the pattern is detected at a given index.

The main functions of the code are as follows:

### OnInit()

This function is executed during the initialization of the custom indicator. It sets up the indicator buffers and parameters.

### OnCalculate()

This function is executed on each new tick or bar. It iterates through the candlesticks and checks for the selected timeframe. If the timeframe matches the selected timeframe, it calls the `CheckCandlestickPattern` function to check for the candlestick pattern. If the pattern is detected, it calls the `SendAlert` function to send a real-time alert.

### CheckCandlestickPattern()

This function is responsible for checking for the presence of the candlestick pattern at the given index. The actual code to detect the pattern is not provided in the sample code and should be implemented by the user.

### SendAlert()

This function is responsible for sending a real-time alert to the user. The specific implementation of sending the alert is not provided in the sample code and can be customized by the user.

---

For more information on how to use this code and to access detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/review-price-alert-panel-mt4-the-candle-stick-patterns-finder/).

---

**Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.**
