# 📈 Visualizing Stock Market Predictions — *StockVistaIQ*

**StockVistaIQ** is an interactive Streamlit web application that visualizes and predicts stock market data using **machine learning (Prophet)** and **real-time market APIs (Yahoo Finance)**.  
It allows users to compare multiple stocks, view real-time price movements, and forecast future prices with powerful interactive dashboards.

---

## 🚀 Features

### 🔹 1. Stocks Performance Comparison
- Compare multiple company stocks simultaneously  
- Visualize **cumulative returns**, **closing prices**, and **volumes**  
- Choose from different chart types: *Line*, *Area*, or *Bar charts*  
- Fetches data dynamically using **Yahoo Finance API**

### 🔹 2. Real-Time Stock Price
- View **up-to-date** stock prices with Open, High, Low, Close, and Volume  
- Choose between **Line Chart** and **Candlestick Chart** visualizations  
- Interactive charts powered by **Plotly**

### 🔹 3. Stock Price Prediction
- Predict future stock prices using **Facebook Prophet**  
- Visualize forecast and its components (trend, seasonality, etc.)  
- Choose forecast horizon (1–4 years)  
- Fully interactive charts with zoom and hover features

### 🔹 4. About
- Displays team credits and project background information  

---

## 🧠 Technology Stack

| Component | Technology |
|------------|-------------|
| **Frontend** | [Streamlit](https://streamlit.io) |
| **Data Source** | [Yahoo Finance (yfinance)](https://pypi.org/project/yfinance/) |
| **Forecasting Model** | [Facebook Prophet](https://facebook.github.io/prophet/) |
| **Visualization** | [Plotly](https://plotly.com/python/) |
| **Data Handling** | Pandas |
| **Language** | Python 3.9+ |

---

## 📂 Project Structure

```
📦 Visualizing-Stock-Market-Predictions
│
├── 📄 app.py                     # Main Streamlit application
├── 📄 StockStreamTickersData.csv # List of companies & ticker symbols
├── 📁 Images/
│   └── StockStreamLogo1.webp     # Application logo
├── 📄 requirements.txt           # Dependencies
└── 📄 README.md                  # Project documentation
```

---

## ⚙️ Installation & Setup

### 🪄 Step 1: Clone the repository
```bash
git clone https://github.com/<your-username>/Visualizing-Stock-Market-Predictions.git
cd Visualizing-Stock-Market-Predictions
```

### 🪄 Step 2: Install dependencies
```bash
pip install -r requirements.txt
```

### 🪄 Step 3: Run the Streamlit app
```bash
streamlit run app.py
```

### 🪄 Step 4: Open in your browser  
The app will automatically open at:  
👉 [http://localhost:8501](http://localhost:8501)

---

## 🧩 Dependencies

Your `requirements.txt` should include:

```
streamlit
pandas
yfinance
datetime
plotly
prophet
streamlit-option-menu
```

*(You can adjust versions as needed for deployment.)*

---

## 🧮 Example Outputs

### **1️⃣ Stock Performance Comparison**
Compare multiple companies like Apple, Tesla, and Microsoft:
- See how their relative returns evolve over time
- View trading volumes and adjusted closing prices interactively  

### **2️⃣ Real-Time Price Visualization**
Display real-time stock data:
- Line charts for trends
- Candlestick charts for intraday analysis  

### **3️⃣ Predictive Forecasting**
Forecast stock prices for the next **1–4 years** using Prophet:
- Interactive forecast plot  
- Component breakdowns (trend, weekly, yearly effects)

---

## 📊 Screenshots

| Feature | Preview |
|----------|----------|
| Home Page | ![Home](Images/StockStreamLogo1.webp) |
| Performance Comparison | *(Add a screenshot here)* |
| Forecasting | *(Add a screenshot here)* |

---

## 🧑‍💻 Authors

**Team StockVistaIQ — Final Year Project**  
- 🧠 **Suraj Raut**  
- 💡 **Chaitanya Deokar**  
- 📊 **Piyusha Shinde**  
- 🔍 **Mrunal Shrigan**  

---

## 🪪 License

This project is licensed under the **MIT License** — free to use and modify with proper attribution.

---

## 🌟 Acknowledgements

- [Streamlit Documentation](https://docs.streamlit.io/)
- [Facebook Prophet](https://facebook.github.io/prophet/)
- [Yahoo Finance Python API](https://pypi.org/project/yfinance/)
- [Plotly Graphing Library](https://plotly.com/python/)
