# 🛍️ Retail Sales Forecasting for Multi-Store Chains

This project predicts **daily sales for multiple retail stores** using a **neural network model**.  
It helps businesses plan better for inventory, staffing, and promotions by learning from past sales data.

---

## 📘 What This Project Does

- Reads and prepares sales data for multiple stores  
- Trains a neural network to predict future sales  
- Evaluates how well the model forecasts unseen data  
- Visualizes performance with plots and metrics  

---

## 🧠 Model Overview

A simple deep learning model is used with fully connected layers:  
- Input features: previous sales, store info, holidays, etc.  
- Hidden layers: ReLU activation and dropout for regularization  
- Output: predicted sales for the next period  

---

## 📂 Project Structure

```
Retail Sales Forecasting for Multi-Store Chains/
│
├── Data/                  # Contains datasets (train/test/store info)
├── Notebook.ipynb         # Jupyter notebook with all code
├── README.md              # Project explanation
└── .gitignore             # Files to ignore
```

---

## ⚙️ How to Use

1. **Clone this repository**
   ```bash
   git clone git@github.com:Yahiamady312/Retail-Sales-Forecasting-for-Multi-Store-Chains.git
   cd "Retail Sales Forecasting for Multi-Store-Chains"
   ```

2. **Install requirements**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook Notebook.ipynb
   ```

4. **View results**
   - Training loss  
   - Actual vs Predicted sales graphs  
   - Error metrics (MAE, RMSE)

---

## 🧰 Tools Used

- Python 3  
- TensorFlow / Keras  
- Pandas, NumPy, Matplotlib, Scikit-learn  

---

## ✨ Future Improvements

- Use LSTM or GRU models for better time-series forecasting  
- Add weather or promotion data  
- Deploy the model as an app or API  

---

## 👨‍💻 Author

**Yahia Mady**  
University of Essex  
