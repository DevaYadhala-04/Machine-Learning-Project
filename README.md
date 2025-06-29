# Machine-Learning-Project
Weather Prediction using Time Series Analysis


# 🌤️ Weather Prediction Using Time Series

## 📌 Overview

This project applies **machine learning** to predict weather conditions such as **rain, sun, drizzle, snow, and fog** using historical weather data. By analyzing features like **temperature, precipitation, wind speed**, and more, the model offers accurate weather forecasting in a **user-friendly** environment.

> ✅ Final model used: **XGBoost** with ~88.34% accuracy.

---

## 👥 Team

- **Deva Yadhala**
- [Add your teammates here if applicable]

---

## 🧠 Key Features

- Time-series based weather prediction
- Supports user input for real-time predictions
- Handles missing values, outliers, and categorical encoding
- Models used: **KNN**, **SVM**, **Gradient Boosting**, **XGBoost**
- Final UI accepts precipitation, wind speed, and temperature
- Interactive data visualization for EDA and results

---

## 📊 Technologies Used

| Area               | Tools/Libraries                                       |
|--------------------|-------------------------------------------------------|
| Language           | Python                                                |
| Data Handling      | pandas, NumPy                                          |
| Visualization      | matplotlib, seaborn, missingno                        |
| ML Models          | scikit-learn (KNN, SVM, GBC), XGBoost                 |
| Web Deployment     | Flask or Django (for UI integration)                 |
| Version Control    | Git, GitHub                                           |
| Dataset            | `seattle-weather.csv` (CSV format)                   |

---

## 🔁 Workflow

1. **Data Collection**  
   - Import historical weather data  
2. **Data Preprocessing**  
   - Handle missing values, encode categorical data, remove outliers  
3. **EDA (Exploratory Data Analysis)**  
   - Visualize trends, distribution, and correlations  
4. **Model Training**  
   - Train using KNN, SVM, Gradient Boosting, and XGBoost  
5. **Prediction**  
   - Use best model (XGBoost) for prediction  
6. **Deployment**  
   - Web interface for user inputs and results  

---

## 📈 Results

| Model              | Accuracy |
|--------------------|----------|
| KNN                | ~80%     |
| SVM                | ~84%     |
| Gradient Boosting  | ~86%     |
| **XGBoost**        | **88.34%** ✅ |

---

## 📦 Setup Instructions

### Prerequisites
- Python 3.7+
- pip
- `seattle-weather.csv` dataset

### Installation

```bash
git clone https://github.com/DevaYadhala-04/weather-prediction-project
cd weather-prediction-project
pip install -r requirements.txt

Create a requirements.txt including:

txt
Copy
Edit
numpy
pandas
matplotlib
seaborn
scikit-learn
xgboost
missingno
Run the Project
bash
Copy
Edit
python app.py
# or if using a Jupyter Notebook:
jupyter notebook weather_prediction.ipynb


🚀 Future Improvements
Add features like humidity, pressure, visibility

Use RNNs / LSTMs for better temporal predictions

Deploy using Flask/Django to cloud (AWS/GCP)

Integrate live weather APIs for real-time prediction

📄 Report
Read the full Project Report (DOCX) for details on architecture, implementation, and results.

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

📬 Contact
GitHub: @DevaYadhala-04
