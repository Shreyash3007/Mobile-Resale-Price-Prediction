#Smartphone Resale Price Estimator (Regression Model)

This project predicts the resale price of smartphones based on their specs using a Random Forest machine learning model.

---

## 🧠 Features Used

- RAM
- Internal Storage
- Battery Capacity
- Camera Megapixels (Rear + Front)
- Processor (Encoded)
- Brand (Encoded)
- Spec Score

---

## 🛠️ Technologies

- Python 3.11+
- Pandas, NumPy
- scikit-learn
- matplotlib, seaborn

---

## 📈 Model Performance

- **R² Score**: ~0.85
- **RMSE**: ₹10,000 (approx)
- **Algorithm**: Random Forest Regressor

---

## 🚀 How To Run

1. Clone this repo  
2. Install requirements
   pip install -r requirements.txt
3. Make sure data/cleaned_final.csv is in place
4. Run the predictor:
   python scripts/predictor.py

