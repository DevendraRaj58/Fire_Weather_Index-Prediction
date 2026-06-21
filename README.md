# 🔥 Forest Fire Weather Index (FWI) Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow)


## 📌 Project Overview

Forest fires are a major environmental hazard causing damage to ecosystems, wildlife, and human settlements.

This project focuses on predicting the **Forest Fire Weather Index (FWI)** using machine learning techniques based on weather and environmental parameters.

A regression model is trained on historical weather data and deployed using a Flask web application where users can enter input values and get real-time FWI predictions.


---

# 🚀 Project Features

✅ Machine Learning based FWI prediction  
✅ Data preprocessing and feature scaling  
✅ Regression model implementation  
✅ Flask web application deployment  
✅ User-friendly prediction interface  
✅ Model serialization using Pickle  
✅ Real-time prediction from user inputs  


---

# 🛠️ Tech Stack


## Programming Language

- Python


## Machine Learning

- Scikit-Learn
- Pandas
- NumPy


## Model Used

- Ridge Regression


## Backend

- Flask


## Frontend

- HTML
- CSS


## Deployment Tools

- Pickle
- VS Code


---

# 📂 Project Structure


```
FWI-Prediction
│
├── application.py
│
├── requirements.txt
│
├── README.md
│
├── models
│     ├── ridge.pkl
│     └── scaler.pkl
│
├── notebooks
│     └── FWI_prediction.ipynb
│
└── templates
      └── index.html

```


---

# 🔄 Project Workflow


```
                Dataset
                   |
                   |
                   v

        Exploratory Data Analysis
                   |
                   |
                   v

        Data Cleaning & Processing
                   |
                   |
                   v

        Feature Selection
                   |
                   |
                   v

        Feature Scaling
          (StandardScaler)
                   |
                   |
                   v

        Model Training
        (Ridge Regression)
                   |
                   |
                   v

        Model Evaluation
        (MAE , R2 Score)
                   |
                   |
                   v

        Save Model
        (pickle)
                   |
                   |
                   v

        Flask Web Application
                   |
                   |
                   v

        User Input
                   |
                   |
                   v

        FWI Prediction

```


---

# 📊 Machine Learning Pipeline


## 1. Data Collection

The dataset contains weather-related parameters responsible for fire behavior.

Input features:

| Feature | Description |
|-|-|
| Temperature | Temperature value |
| RH | Relative Humidity |
| Ws | Wind Speed |
| Rain | Rainfall |
| FFMC | Fine Fuel Moisture Code |
| DMC | Duff Moisture Code |
| ISI | Initial Spread Index |
| Classes | Fire classification |
| Region | Region identifier |



Target Variable:

```
FWI (Forest Fire Weather Index)
```


---

# 🧹 Data Preprocessing


Steps performed:


- Handling missing values
- Feature analysis
- Data visualization
- Encoding categorical features
- Feature scaling using StandardScaler


---

# 🤖 Model Development


The project uses:

## Ridge Regression


Ridge Regression is a linear regression technique with L2 regularization that reduces overfitting and improves model performance.


The trained model is saved:

```
models/ridge.pkl
```


Scaler is saved:

```
models/scaler.pkl
```


---

# 📈 Model Evaluation


The model performance is evaluated using:


### Mean Absolute Error (MAE)

Measures average prediction error.


### R² Score

Measures how well the model explains the variation in data.



---

# 🌐 Flask Application Workflow


```

User
 |
 |
 v

HTML Form

 |
 |
 v

Flask Backend

 |
 |
 v

Load Trained Model

 |
 |
 v

Scale Input Data

 |
 |
 v

Generate Prediction

 |
 |
 v

Display FWI Result


```


---

# 💻 Installation & Setup


Clone repository:


```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```


Move into project directory:


```bash
cd FWI-Prediction
```


Install dependencies:


```bash
pip install -r requirements.txt
```


Run application:


```bash
python application.py
```


Open browser:


```
http://127.0.0.1:5000
```


---

# 📸 Application Preview


(Add your screenshots here)


Example:

```
Input Weather Parameters
          |
          v
FWI Prediction Output

```


---

# 📦 Requirements


```
Flask
numpy
pandas
scikit-learn
```


---

# 👨‍💻 Author


**Devendra Rajpurohit**


LinkedIn:

https://www.linkedin.com/in/devendraraj58/



GitHub:

https://github.com/DevendraRaj58


---

# ⭐ If you found this project useful

Give it a star ⭐ on GitHub!