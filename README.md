# 🏠 House Price Prediction using Linear Regression  

## 📌 Overview  
This project predicts house prices based on property features using **Linear Regression**.  
It covers the complete machine learning workflow — from **data preprocessing** to **model evaluation** — with visualizations and a ready-to-use saved model.  

---

## 📊 Dataset  
The dataset contains the following columns:  

- **Avg. Area Income** – Average income of residents in the area  
- **Avg. Area Number of Rooms** – Average number of rooms per house  
- **Avg. Area Number of Bedrooms** – Average number of bedrooms per house  
- **Price** – Target variable (house selling price)  

📂 **Source:** USA Housing Dataset  

---

## ⚙ Features Implemented  
- Data loading and exploration  
- Scatter plots for **Price vs Area** and **Price vs Bedrooms**  
- Train/test split for model validation  
- **Linear Regression** model training  
- Model evaluation using:  
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - R² Score  
- Save and load trained model with **Joblib**  
- Function to make predictions on new data  

---

## 📂 Project Structure  

```
house-price-prediction/
│
├── data/
│   └── USA_Housing.csv                # Dataset
│
├── notebooks/
│   └── House_Price_Prediction.ipynb   # Colab notebook with code
│
├── models/
│   └── house_price_model.pkl          # Saved trained model
│
├── scripts/
│   └── train_model.py                 # Script for training the model
│   └── predict.py                     # Script for making predictions
│
├── requirements.txt                   # Python dependencies
├── README.md                          # Project documentation
└── LICENSE                            # License file
```

---

## 🚀 How to Run  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/<your-username>/house-price-prediction.git
cd house-price-prediction
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Training Script  
```bash
python scripts/train_model.py
```

### 4️⃣ Make Predictions  
```bash
python scripts/predict.py
```

---

## 📈 Example Output  
- **MAE:** 82,345.67  
- **MSE:** 1.07e+10  
- **R² Score:** 0.92  

---

## 📜 License  
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  


