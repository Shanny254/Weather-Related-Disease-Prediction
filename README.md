# Weather-Related Disease Prediction using Machine Learning

**Supporting SDG 3 – Good Health and Well-being**

This project applies machine learning to predict disease outbreaks caused by weather patterns such as temperature, humidity, and rainfall. It is designed to help policymakers, healthcare agencies, and NGOs make data-driven decisions for early intervention and preparedness in Kenya and beyond.

---

## Problem Statement

Weather changes significantly influence the outbreak of diseases such as malaria, cholera, and typhoid in many parts of Kenya. This project uses historical weather and disease data to predict outbreaks and support early warning systems, contributing to **UN Sustainable Development Goal 3**: Ensure healthy lives and promote well-being for all at all ages.

---

## Objectives

- Predict the type of weather-related disease based on weather parameters and location.
- Identify the most important features that influence disease outbreaks.
- Support proactive planning by health authorities.

---

## Dataset

A synthetic dataset was generated with 300 records across 6 Kenyan regions:

**Features:**

- `Date`: Date of observation  
- `Region`: Kenyan county/region  
- `Temperature`: Daily average in °C  
- `Humidity`: % level of humidity  
- `Rainfall`: mm of rainfall  
- `Disease`: Reported disease (Malaria, Cholera, Typhoid, None)

---

## Technologies Used

- Python  
- Scikit-learn  
- Pandas & NumPy  
- Seaborn & Matplotlib  
- Jupyter Notebook (.ipynb)  
- Google Colab (optional for cloud use)

---

## Machine Learning Approach

**Model:** Random Forest Classifier  
**Task:** Multiclass Classification  
**Target:** Type of disease outbreak (or 'None')

### Workflow

1. Load and explore dataset  
2. Encode categorical variables  
3. Split into train/test sets  
4. Train a Random Forest classifier  
5. Evaluate performance using:  
   - Confusion matrix  
   - Classification report  
6. Visualize feature importance

---

## Results

- The model demonstrated high accuracy in identifying patterns leading to outbreaks.  
- Key influencing factors: Rainfall and Humidity  
- Confusion Matrix and feature importance plots included in the notebook.

---

## Ethical & Social Reflection

- The model is only as good as the data used. Synthetic data was used here due to limited access to real, granular health records.  
- A real-world deployment should include diverse datasets from rural and urban areas to ensure fairness.  
- The solution promotes **early disease detection**, improving resource planning in underserved communities.

---
## Screenshots 
![Confusion Matrix](C:\Users\sharl\OneDrive\Pictures\Screenshots/confusion_matrix.png)  
*Figure: Disease prediction accuracy*

![Feature Importance](C:\Users\sharl\OneDrive\Pictures\Screenshots/feature_importance.png)  
*Figure: Which weather variables matter most*


## Getting Started

### Clone the Repo

```bash
git clone https://github.com/your-username/weather-disease-prediction.git
cd weather-disease-prediction

##
