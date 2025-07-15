🚗 Used Car Price Prediction Web App

This is my **2nd internship project** for **InternPe** — a machine learning-based web app that predicts the estimated price of a used car based on key inputs like brand, manufacturing year, kilometers driven, and fuel type.

## 🔍 Project Overview

The goal of this project is to build and deploy a regression model that can accurately predict car prices using structured data. The final model is deployed using a **Gradio interface** for user interaction.

---

## 🛠️ Technologies Used

- **Python** (Data & ML)
- **Pandas**, **NumPy** (Data preprocessing)
- **Scikit-learn** (ML pipeline + Linear Regression)
- **Gradio** (Web interface)
- **Google Colab** (Training environment)
- **Pickle** (Model serialization)

---

## 📁 Project Structure

car-price-predictor/
├── app.py # Gradio web app
├── LinearRegressionModel.pkl # Trained ML pipeline (pickled)
├── requirements.txt # Python dependencies
├── Cleaned_Car_data.csv # (Optional) Cleaned dataset
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🚀 How to Run

### 🔗 Option 1: Run on Google Colab

1. Open the notebook or `app.py` in Google Colab
2. Upload `LinearRegressionModel.pkl` (trained model)
3. Install Gradio:  
   `!pip install gradio`
4. Run the app:
   ```python
   import gradio as gr
   # Launch via app.py code or directly in cell
🌐 Option 2: Deploy on Hugging Face Spaces
Create a free Hugging Face account

Go to https://huggingface.co/spaces

Create a new Gradio space

Upload:

app.py

requirements.txt

LinearRegressionModel.pkl

Hugging Face will host it and provide a public link

📌 Features
Predict used car price based on 5 fields

Real-time web interface using Gradio

End-to-end machine learning pipeline

Cleaned and processed real-world dataset

Beginner-friendly, lightweight, and interactive

📈 Future Improvements
Add multiple regression models (e.g. Random Forest, XGBoost)

Include model evaluation (R² score, MAE, MSE)

Deploy with Streamlit or Flask

Add data visualizations or SHAP explanations

