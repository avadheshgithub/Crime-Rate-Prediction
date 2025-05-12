# 🔍 Crime Prediction using Machine Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![ML Project](https://img.shields.io/badge/Machine%20Learning-Crime%20Prediction-green)
![Random Forest](https://img.shields.io/badge/Model-Random%20Forest-orange)
![Flask](https://img.shields.io/badge/API-Flask-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📖 Overview

Crime Rate Predictor is an application that uses machine learning techniques to predict crime rates in 19 Indian metropolitan cities. The goal of this project is to assist law enforcement agencies in understanding crime patterns and allocating resources effectively to reduce crime rates as well as improve public safety.

> 📈 **Performance Highlights:**  
> - **MAE:** 2.49143  
> - **R² Score:** 0.93201  
> - **Response Time:** ~1.5 seconds (Flask API)

---

## 🔧 Tech Stack

| Category            | Tools Used                          |
|---------------------|-------------------------------------|
| 📊 ML Models        | Random Forest, RNN-GRU, SVM, KNN, LSTM, Clustering |
| 💻 Language         | Python 3.8+                         |
| 🛠️ Libraries        | Pandas, Scikit-learn, NumPy, Flask, Matplotlib |
| 🌐 Framework        | Flask (REST API)                    |
| 📁 Dataset Source   | National Crime Records Bureau (NCRB) India |
| 📈 Visualization    | Matplotlib, Seaborn                 |

---

## 🧠 ML Models Compared

A variety of ML models were evaluated for crime prediction:

| Model         | Accuracy / MAE | Notes |
|---------------|----------------|-------|
| **Random Forest** (CrimeNavigator) | MAE: 2.49, R²: 0.93 | Fast, scalable, handles 19 cities |
| RNN-GRU       | ~85% Accuracy | Temporal, scalability issues |
| SVM           | 70–80%        | High computation |
| KNN           | ~75%          | Simple, low precision |
| Clustering    | ~80%          | Spatial hotspots only |
| LSTM          | -             | Sequential potential |

📊 **See Figure 1 below for visual comparison of all models.**

---

# Web Interface
![Model](https://github.com/user-attachments/assets/4dd07cdb-ca7e-4097-ad9d-ac4eaeade436)

## About the Application

Crime rate prediction has become an important tool for law enforcement agencies to help them better understand patterns of crime and anticipate where crime is likely to occur. By predicting future crime trends, law enforcement agencies can better allocate resources to areas that are likely to experience increases in criminal activity. This could lead to a decrease in crime overall, as well as an increase in public safety. Additionally, crime rate prediction can help police departments develop better strategies for responding to crime as it happens.

The system uses scikit-learn's Random Forest Regression model, which takes year, city name, and crime type data as inputs. Random Forest Regression is a type of ensemble learning technique that can be used to predict continuous values from a collection of data. It works by creating a large number of "decision trees," each predict the target variable. Then it averages all the predictions to come up with a final prediction. This makes it more accurate than a single decision tree. The model predicts the crime rate with an accuracy of 93.20% on the testing dataset.

## Features

- Crime rate prediction for 10 different categories of crime
- Prediction for 19 Indian metropolitan cities
- Historical crime data from 2014 to 2021
- Random Forest Regression model for accurate predictions
- Model accuracy of 93.20% on testing dataset

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/avadheshgithub/Crime-Rate-Prediction.git

2. Navigate to the project directory:

   ```shell
   cd Crime-Rate-Prediction

3. Install the required dependencies:

   ```shell
   pip install -r requirements.txt
   
4. Run the application:

   ```shell
   python app.py


## Contact

If you have any questions, suggestions, or issues regarding this project, please feel free to [contact me](mailto:avadheshumarshah578@gmail.com).
