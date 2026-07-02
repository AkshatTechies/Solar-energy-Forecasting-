# ☀️ AI-Powered Solar Energy Generation Forecasting

An end-to-end machine learning project that predicts solar energy generation using historical weather and solar plant data. The project combines data preprocessing, exploratory data analysis, feature engineering, model training, explainable AI (SHAP), and real-time weather forecasting using the OpenWeather API—all within a single Jupyter Notebook.

---

## 🚀 Project Overview

Accurate solar power forecasting is essential for improving renewable energy integration, grid stability, and efficient energy management. This project leverages machine learning models and real-time weather information to forecast solar energy generation with high accuracy.

The notebook provides a complete workflow from raw data analysis to deployment-ready real-time prediction.

---

## ✨ Features

- Historical solar power data analysis
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning model training and evaluation
- Hyperparameter tuning
- Explainable AI using SHAP
- Error analysis and visualization
- Real-time weather forecasting using OpenWeather API
- Interactive visualizations using Plotly and Matplotlib

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib
- Plotly
- OpenWeather API

---

## 📂 Project Structure

```
Solar-Energy-Forecasting/
│
├── Solar_Energy_Forecasting.ipynb
├── dataset/
├── README.md
├── requirements.txt
├── .env.example
└── .gitignore
```

---

## 📊 Workflow

1. Dataset Loading
2. Data Cleaning
3. Missing Value Handling
4. Exploratory Data Analysis
5. Feature Engineering
6. Model Training
7. Hyperparameter Optimization
8. Model Evaluation
9. Explainable AI (SHAP)
10. Real-Time Solar Power Prediction

---

## 📈 Machine Learning Pipeline

- Data Preprocessing
- Feature Selection
- Model Training
- Hyperparameter Tuning
- Performance Evaluation
- SHAP Explainability
- Real-Time Forecasting

---

## 🔑 OpenWeather API Setup

Create a `.env` file in the project directory:

```env
OPENWEATHER_API_KEY=YOUR_OPENWEATHER_API_KEY
```

Install dependencies:

```bash
pip install python-dotenv
```

Load the API key inside the notebook:

```python
from dotenv import load_dotenv
import os

load_dotenv()

API_KEY = os.getenv("OPENWEATHER_API_KEY")
```

> **Note:** Never upload your actual API key to GitHub.

---

## 📊 Evaluation Metrics

The model is evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

along with prediction comparison plots, residual analysis, and SHAP feature importance visualizations.

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/solar-energy-forecasting.git
```

2. Install the required packages

```bash
pip install -r requirements.txt
```

3. Create a `.env` file and add your OpenWeather API key.

4. Open the notebook in Jupyter Notebook or JupyterLab.

5. Run all cells sequentially.

---

## 🎯 Future Improvements

- Deploy as a web application using Streamlit or Flask
- Support multiple solar plant locations
- Integrate additional weather APIs
- Automate periodic real-time forecasting
- Containerize using Docker
- Cloud deployment for production use

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is intended for educational and research purposes.

---

## 👨‍💻 Author

**Akshat Jaiswal**

If you found this project useful, consider giving it a ⭐ on GitHub.
