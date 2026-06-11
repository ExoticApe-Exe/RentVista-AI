# 🏠 RentVista-AI: Fair Market Rental Price Estimator for Indian Housing

## Overview

RentVista-AI is a machine learning-powered rental price prediction platform designed to help tenants estimate the fair market rent of residential properties in India. The system uses property features such as city, locality, house type, area, bedrooms, bathrooms, balconies, and furnishing status to generate accurate rental price predictions.

By leveraging real Indian housing market data and advanced machine learning techniques, RentVista-AI provides transparency in rental pricing and helps users make informed housing decisions.

---

# Problem Statement

The Indian rental housing market often lacks pricing transparency. Similar properties in the same locality may be listed at significantly different rental prices, making it difficult for tenants to determine whether a quoted rent is reasonable.

RentVista-AI addresses this challenge by providing data-driven rental estimates based on actual housing market trends. The platform empowers tenants with reliable rental valuations before negotiating with landlords.

---

# Objectives

* Predict fair monthly rent for residential properties.
* Improve transparency in the rental housing market.
* Help tenants avoid overpaying for rentals.
* Provide accurate rent estimates using machine learning.
* Offer a simple and user-friendly web interface.

---

# Features

✅ Fair market rent prediction

✅ AI-powered valuation system

✅ Interactive web interface

✅ Fast and accurate predictions

✅ Real Indian housing market dataset

✅ Tenant-focused pricing insights

---

# Dataset

### Source

Kaggle – Indian House Rent Prediction Dataset

### Dataset Size

* 7,691 Property Records

### Features

* City
* Locality
* House Type
* Furnishing Status
* Area (sq ft)
* Bedrooms (BHK)
* Bathrooms
* Balconies
* Rent

---

# Machine Learning Model

## Algorithm

CatBoost Regressor

### Why CatBoost?

* Handles categorical features efficiently
* High prediction accuracy
* Minimal preprocessing required
* Excellent performance on tabular data

---

# Model Performance

| Metric                    | Value              |
| ------------------------- | ------------------ |
| R² Score                  | 0.9351             |
| Mean Absolute Error (MAE) | ₹3,860             |
| Algorithm                 | CatBoost Regressor |
| Iterations                | 2500               |
| Depth                     | 10                 |
| Learning Rate             | 0.045              |

---

# Technology Stack

## Programming Language

* Python

## Data Analysis

* Pandas
* NumPy

## Machine Learning

* CatBoost
* Scikit-Learn

## Data Visualization

* Matplotlib
* Seaborn

## Web Application

* Gradio / Streamlit

---

# Project Workflow

### Step 1: Data Collection

Collect Indian rental housing data from Kaggle.

↓

### Step 2: Data Cleaning

* Handle missing values
* Remove duplicates
* Prepare dataset

↓

### Step 3: Exploratory Data Analysis (EDA)

Analyze:

* Rent distribution
* City-wise rent trends
* Area vs Rent
* Furnishing impact

↓

### Step 4: Feature Engineering

Create:

* Area Buckets
* Rent Per Square Foot Buckets
* Encoded Categorical Features

↓

### Step 5: Model Training

Train CatBoost Regressor using housing features.

↓

### Step 6: Prediction

Predict fair monthly rental value.

↓

### Step 7: Deployment

Deploy model using Streamlit or Gradio.

---

# System Architecture

```text
User Input
     │
     ▼
Web Interface
     │
     ▼
Feature Engineering
     │
     ▼
CatBoost Regressor
     │
     ▼
Rental Price Prediction
     │
     ▼
Results Dashboard
```

# Input Parameters

Users provide:

* City
* Locality
* House Type
* Area (sq ft)
* Number of Bedrooms
* Number of Bathrooms
* Number of Balconies
* Furnishing Status

---

# Output

The system generates:

* Predicted Monthly Rent (₹)
* Fair Market Rental Value
* Property Rental Insights

---

# Example Prediction

### Input

```text
City: Chennai
Locality: Velachery
Area: 1200 sq ft
BHK: 2
Bathrooms: 2
Balconies: 1
Furnishing: Semi-Furnished
```

### Output

```text
Estimated Monthly Rent:
₹18,500 - ₹21,000
```

---

# Installation

Clone Repository

```bash
git clone https://github.com/yourusername/RentVista-AI.git
```

Move into Project Folder

```bash
cd RentVista-AI
```

Install Dependencies

```bash
pip install -r requirements.txt
```

Run Application

```bash
streamlit run app.py
```

---

# Future Enhancements

* Property Recommendation System
* Rental Trend Forecasting
* Interactive Housing Analytics Dashboard
* City-Wise Rental Heatmaps
* AI-Powered Negotiation Suggestions
* Mobile Application Integration

---

# Applications

* Rental Property Valuation
* Housing Market Analytics
* Real Estate Technology
* Tenant Decision Support
* Property Price Transparency

---

# Project Outcome

RentVista-AI provides a reliable and transparent method for estimating rental prices using machine learning. The platform helps tenants make informed housing decisions while reducing information asymmetry in India's rental market.

---

# Author

**Sharma S**

AI Engineer | Data Scientist | Machine Learning Enthusiast

---

# License

This project is licensed under the MIT License.
