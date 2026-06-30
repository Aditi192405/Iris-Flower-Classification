# 🚗 Car Price Prediction using Machine Learning

A web-based Machine Learning application that predicts the selling price of a used car based on various features such as manufacturing year, present price, kilometers driven, fuel type, transmission, owner count, and seller type.

## 📌 Features

- Predicts the selling price of a used car
- User-friendly web interface using Streamlit
- Data preprocessing and feature engineering
- Machine Learning model trained on historical car data
- Real-time price prediction
- Simple and responsive UI

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Joblib

---

## 📂 Project Structure

```
Car-Price-Prediction/
│── car_app.py
│── car-price-prediction.ipynb
│── car_data.csv
│── model.pkl
│── requirements.txt
│── README.md
│── images/
```



## 📊 Dataset

The dataset contains information about used cars, including:

- Car Name
- Year
- Present Price
- Selling Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

**Target Variable:**

- Selling Price





## ▶️ Run the Application

```bash
streamlit run car_app.py
```

The application will open in your browser at:


http://localhost:8501
```



## 📈 Machine Learning Workflow

- Data Collection
- Data Cleaning
- Feature Engineering
- Label Encoding
- Train-Test Split
- Model Training
- Model Evaluation
- Model Saving
- Deployment with Streamlit

---

## 📊 Model Used

- Random Forest Regressor

Evaluation Metrics:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)




## ⭐ Support

If you found this project useful, don't forget to ⭐ the repository.
