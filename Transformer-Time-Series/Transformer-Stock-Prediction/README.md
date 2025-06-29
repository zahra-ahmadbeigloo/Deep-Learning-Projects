### Transformer for Time Series Forecasting built with:  
- **TensorFlow/Keras** for model architecture and training  
- **Multi-Head Attention** and **Positional Encoding** from scratch  
- **Custom Encoder-Decoder** transformer blocks  
- **Stock price time series** as the training dataset  
- **Regression output** for next-step stock price prediction  

---

# Transformer for Stock Price Prediction (Time Series Forecasting)

This project implements an advanced **Transformer architecture from scratch** using TensorFlow/Keras to perform **time series forecasting** on stock price data. The model is trained to predict the next value in a stock price sequence based on prior values. All components — including multi-head attention, positional encodings, and feedforward layers — are manually implemented for educational clarity and precision.

---

## Key Features

- Full **Transformer architecture** (encoder-decoder) implemented from scratch  
- Works on **stock price time series data** (not text)  
- Uses **custom Positional Encoding** based on sine and cosine functions  
- Supports **sequence-to-sequence forecasting** via masked attention  
- Outputs continuous values (regression), not discrete tokens  

---

## Sample Prediction Output

> **Input Sequence:** `[121.0, 122.5, 123.1, 124.7, 125.3]`  
> **Predicted Next Price:** `126.02`

---

## Dependencies

```bash
pip install tensorflow numpy matplotlib
````

---

## Dataset

* CSV file containing historical **stock prices** (manually loaded and normalized)

---

## License

This project is licensed under the MIT License.
