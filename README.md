# 📈 Stock Market Prediction and Forecasting Using Stacked LSTM

This project implements a deep learning model using **stacked Long Short-Term Memory (LSTM)** layers to predict stock market prices based on historical data. The goal is to explore temporal patterns in stock price movements and build a model capable of forecasting future prices with improved accuracy. Built using Python, Keras, and TensorFlow, this project is ideal for financial time series analysis.

---

## 📁 Repository Contents

- `Untitled3.ipynb` – Main Jupyter Notebook with preprocessing, model training, and evaluation  
- `README.md` – Project documentation  

---

## 🎯 Objectives

- Analyze historical stock data to identify patterns and trends  
- Build a stacked LSTM model for forecasting stock prices  
- Evaluate the model’s predictive performance  
- Visualize actual vs predicted stock prices  

---

## 📦 Dataset Description

The dataset consists of historical stock prices and includes the following features:
- Date
- Open price
- High price
- Low price
- Close price
- Volume

> Note: Ensure the dataset is added in the correct path as used in the notebook.

---

## 🔧 Tools & Libraries

- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Keras (with TensorFlow backend)  
- Jupyter Notebook  

---

## 📊 Methodology

1. **Data Preprocessing**  
   - Handling missing values  
   - Normalizing data with Min-Max scaling  
   - Creating time-step sequences for LSTM input  

2. **Model Architecture**  
   - Multiple LSTM layers stacked sequentially  
   - Dense output layer for final prediction  

3. **Model Training**  
   - Optimizer: Adam  
   - Loss Function: Mean Squared Error (MSE)  

4. **Evaluation Metrics**  
   - Root Mean Squared Error (RMSE)  
   - Mean Absolute Error (MAE)  

5. **Visualization**  
   - Predicted vs Actual Stock Prices plotted for interpretation  

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/achyuthkumarmiryala/STOCK-MARKET-PREDICTION-AND-FORECASTING-USING-STACKED-LSTM.git
   cd STOCK-MARKET-PREDICTION-AND-FORECASTING-USING-STACKED-LSTM
   ```

2. **Install Dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn tensorflow keras
   ```

3. **Run the Notebook**
   ```bash
   jupyter notebook Untitled3.ipynb
   ```

---

## ✅ Results

The model successfully learned historical trends and produced future stock price predictions. The visual plots show strong alignment between predicted and actual values, especially in short-term windows.

---

## 👨‍💻 Author

**Achyuth Kumar Miryala**  
Master’s in Data Science | University of North Texas  
📍 Denton, TX  
📫 [achyuthkumar286@gmail.com](mailto:achyuthkumar286@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/achyuthkumarmiryala/) | [GitHub](https://github.com/achyuthkumarmiryala)

---

## 📜 License

This project is licensed for academic and educational use only. Please contact the author if you plan to reuse or extend it.

---

If you find this project helpful, please ⭐ the repo and share feedback!
