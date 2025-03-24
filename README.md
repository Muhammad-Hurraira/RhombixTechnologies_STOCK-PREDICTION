# RhombixTechnologies_STOCK-PREDICTION
# 📈 Pakistan Stock Exchange (KSE 100) Prediction

## 🚀 Project Overview
This project applies **machine learning** to predict whether the **KSE 100 Index** stock prices will **increase or decrease**. Using **LSTM (Long Short-Term Memory) neural networks**, the model analyzes historical stock data to make future predictions.

### Objectives:
✅ **Preprocess and clean** Pakistan Stock Exchange (KSE 100) historical data  
✅ **Train an LSTM model** to predict future stock price movements  
✅ **Visualize trends** and model accuracy  
✅ **Deploy the model** for real-time stock prediction  

---

## 📂 Dataset
The dataset consists of **historical stock prices** from the **KSE 100 Index in Pakistan**, sourced from an online CSV file. It includes the following attributes:

- **Date (Timestamp)**
- **Open Price**
- **High Price**
- **Low Price**
- **Close Price**
- **Change**
- **Trading Volume**

### 📌 Data Source:
Pakistan Stock Exchange (KSE 100) CSV

---

## ⚙️ Technologies Used
- 🔹 **Python**
- 🔹 **Pandas & NumPy** (for data manipulation)
- 🔹 **Scikit-Learn** (for data preprocessing)
- 🔹 **TensorFlow/Keras** (LSTM model)
- 🔹 **Matplotlib & Seaborn** (for visualization)

---

## 🏗️ Project Workflow

### 1️⃣ Data Preprocessing
- Load the dataset from an online source
- Convert price and volume columns to **numeric format**
- Handle missing values and **scale features** using `MinMaxScaler`

### 2️⃣ Model Building (LSTM Neural Network)
- Define an **LSTM-based Sequential model** with dropout layers
- Train the model using **Adam optimizer**
- Use **train-test split** for validation

### 3️⃣ Model Evaluation & Visualization
- Generate **accuracy metrics**
- Plot **actual vs. predicted price trends**
- Fine-tune **hyperparameters** for better performance

---

## 📊 Results
✅ The **LSTM model** successfully predicts stock movements with good accuracy  
✅ The **trend graphs** show that the model captures **market fluctuations effectively**  
✅ Further improvements can be made by incorporating **more technical indicators**  

---

## 🛠️ Future Enhancements
✅ Add **Sentiment Analysis** using news headlines  
✅ Incorporate **technical indicators** like RSI, MACD, and Bollinger Bands  
✅ Build a **real-time prediction dashboard**  

---

## 📜 License
This project is **open-source** under the **MIT License**.

---

## Contact ☎️
For any questions or inquiries, please feel free to approach me through the following account:
- LinkedIn: https://www.linkedin.com/in/muhammad-hurraira-0993a4346/
