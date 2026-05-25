# 🏏 T20 Cricket Match Outcome Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the outcome of T20 International cricket matches using Machine Learning and Deep Learning algorithms. The system analyzes real-time match features such as target score, innings runs, wickets, balls remaining, and batter performance to predict whether a team will successfully chase the target.

The project also forecasts match scores and compares the performance of multiple machine learning models.

---

## 🚀 Features

* Predicts T20 match outcomes
* Forecasts target scores
* Performs data preprocessing and normalization
* Compares multiple ML and DL algorithms
* Visualizes dataset distribution and model performance
* Generates accuracy, precision, recall, and F1-score metrics

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras

---

## 📂 Dataset

Dataset used:

* `ball_by_ball_it20.csv`

The dataset contains:

* Target Score
* Runs From Ball
* Innings Runs
* Innings Wickets
* Balls Remaining
* Batter Runs
* Non-Striker Runs
* Batter Balls Faced
* Match Result (Chased Successfully)

---

## 🤖 Algorithms Used

### Machine Learning Models

* K-Nearest Neighbors (KNN)
* Random Forest Classifier
* Random Forest Regressor

### Deep Learning Models

* Artificial Neural Network (ANN)
* Convolutional Neural Network (CNN2D)

---

## 📊 Project Workflow

### 1️⃣ Data Collection

* Imported T20 cricket ball-by-ball dataset

### 2️⃣ Data Preprocessing

* Removed irrelevant columns
* Handled missing values
* Feature selection
* Data normalization using MinMaxScaler

### 3️⃣ Data Visualization

* Match chase success analysis
* Class distribution graphs

### 4️⃣ Model Training

* Trained multiple ML and DL models
* Used 80% training data and 20% testing data

### 5️⃣ Performance Evaluation

Metrics used:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### 6️⃣ Prediction

* Predicted match outcomes
* Forecasted target scores

---

## 📈 Results

The models were evaluated and compared based on performance metrics. Random Forest and Deep Learning models achieved strong prediction accuracy for match outcome forecasting.

---

## 📁 Project Structure

```bash id="qh9x1x"
T20-Cricket-Match-Prediction/
│
├── sports_outcome_ipy.ipynb
├── ball_by_ball_it20.csv
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash id="8h49yq"
git clone https://github.com/your-username/T20-Cricket-Match-Prediction.git
```

Install required libraries:

```bash id="1h7g8k"
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash id="r7x5fa"
jupyter notebook
```

---

## 📌 Future Improvements

* Live match prediction system
* Web deployment using Streamlit
* Real-time API integration
* Advanced Deep Learning optimization
* Interactive dashboard using Power BI

---

## 🎯 Skills Demonstrated

* Data Preprocessing
* Machine Learning
* Deep Learning
* Predictive Analytics
* Sports Analytics
* Data Visualization
* Model Evaluation

---

## 👨‍💻 Author

**Syed Saad**

Aspiring Data Analyst | Machine Learning Enthusiast
