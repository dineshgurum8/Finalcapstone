# Predicting Remaining Useful Life of Aircraft Engines Using Machine Learning and Sensor Data

### Dinesh Gurumoorthy - Final Capstone Project

## Project Overview

This project focuses on predicting the Remaining Useful Life (RUL) of aircraft turbofan engines using machine learning techniques and the NASA C-MAPSS Turbofan Engine Degradation Simulation Dataset.

The goal is to build a predictive maintenance pipeline capable of identifying degradation trends in engine sensor data and estimating how many operational cycles remain before engine failure.

Predictive maintenance reduces unexpected downtime, improves safety, lowers maintenance costs, and supports data-driven decision-making in aerospace systems.

---

# Dataset

This project uses the NASA Prognostics Data Repository – Turbofan Engine Degradation Simulation Dataset (C-MAPSS).

### Dataset Source

- NASA Prognostics Data Repository
- C-MAPSS Turbofan Engine Dataset

Dataset Link:

https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan

---

# Project Objectives

- Load and preprocess NASA turbofan engine sensor data
- Perform exploratory data analysis (EDA)
- Engineer predictive features
- Build machine learning models for RUL prediction
- Compare multiple regression algorithms
- Evaluate model performance using regression metrics
- Visualize degradation behavior and prediction results

---

# Project Workflow

```text
Raw Sensor Data (.txt files)
        ↓
Data Preprocessing
(cleaning, normalization, RUL calculation)
        ↓
Exploratory Data Analysis (EDA)
(patterns, trends, correlations)
        ↓
Feature Engineering
(rolling mean, trend extraction, selection)
        ↓
Model Training
(machine learning algorithms)
        ↓
Model Testing
(evaluation on unseen data)
        ↓
RUL Prediction Output
```

---

# Technologies Used

## Programming Language

- Python

## Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Development Environment

- Jupyter Notebook
- Visual Studio Code
- GitHub

---

# Machine Learning Models Used

The following regression models are implemented and compared:

### Linear Regression

Used as a baseline model to establish initial predictive performance.

### Random Forest Regressor

An ensemble learning method that handles nonlinear relationships and improves prediction accuracy.

### Gradient Boosting Regressor

Builds sequential trees to reduce prediction errors and improve performance.

### Optional Future Models

- XGBoost Regressor
- LightGBM
- LSTM Neural Networks
- Transformer-based Models

---

# Project Structure

```text

```

---

# Data Features

### Independent Variables

- Operational Settings (3 variables)
- Sensor Measurements (21 variables)
- Engine Cycle Information

### Dependent Variable

- Remaining Useful Life (RUL)

---

# Exploratory Data Analysis

EDA includes:

- Engine lifetime distribution
- Remaining Useful Life distribution
- Sensor variance analysis
- Feature correlation with RUL
- Scatter analysis
- Degradation trend visualization
- Health Index construction
- Data drift comparison

---

# Evaluation Metrics

The regression models are evaluated using:

### Mean Absolute Error (MAE)

Measures average prediction error.

### Root Mean Square Error (RMSE)

Penalizes large prediction errors.

### R-Squared (R²)

Measures how well the model explains variance in the target variable.

---

# Example Results

| Model | MAE | RMSE | R² Score |
|------|------|------|------|
| Linear Regression | 25.1 | 33.4 | 0.72 |
| Random Forest | 15.2 | 21.6 | 0.88 |
| Gradient Boosting | 13.8 | 19.9 | 0.91 |

---

# Visualizations Included

- Engine Lifetime Distribution
- RUL Distribution
- Feature Correlation
- Sensor Variance
- Feature vs RUL Scatter Plot
- Engine Degradation Curves
- Health Index Trend
- Actual vs Predicted RUL
- Feature Importance

---

# How to Run the Project

## Step 1: Clone Repository

```bash
git clone https://github.com/dineshgurum8/Finalcapstone.git
```

## Step 2: Navigate to Folder

```bash
cd Finalcapstone
```

## Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

## Step 4: Run Notebook

Open Jupyter Notebook or VS Code.

Run:

```bash
Final_Capstone_Project.ipynb
```

---

# Future Improvements

- Add deep learning models
- Add time-series sequence learning
- Deploy predictive API
- Create dashboard using Streamlit or Shiny
- Integrate live sensor monitoring

---

# References

1. NASA Prognostics Data Repository — C-MAPSS Dataset
2. NASA Ames Research Center
3. Scikit-learn Documentation
4. Predictive Maintenance Research Papers

---

# GitHub Repository

Repository Link:

https://github.com/dineshgurum8/Finalcapstone

---

# Author

**Dinesh Gurumoorthy**  
Northwest Missouri State University  
Master’s in Data Analytics

---
