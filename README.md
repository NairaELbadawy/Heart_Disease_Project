# Heart Disease Prediction Project

## Overview
This project analyzes the UCI Heart Disease Dataset.  
We applied:
- Data preprocessing
- Dimensionality reduction (PCA)
- Feature selection
- Supervised learning models (Logistic Regression, Random Forest, SVM)
- Unsupervised learning models (KMeans, Hierarchical Clustering)
- Hyperparameter tuning

The final optimized model is saved as `final_model.pkl`.

---

## Project Structure
Heart_Disease_Project/  
│── data/  
│   └── heart_disease.csv  
│── notebooks/  
│   ├── 01_data_preprocessing.ipynb  
│   ├── 02_pca_analysis.ipynb  
│   ├── 03_feature_selection.ipynb  
│   ├── 04_supervised_learning.ipynb  
│   ├── 05_unsupervised_learning.ipynb  
│   └── 06_hyperparameter_tuning.ipynb  
│── models/  
│   └── final_model.pkl 
│   └── preprocessor.pkl
│── results/  
│   └── evaluation_metrics.txt  
│── ui/  
│   └── app.py  
│── deployment/  
│   └── ngrok_setup.txt (optional, not included)  
│── README.md  
│── requirements.txt  

---

## How to Run
1. Install the required libraries:
   ```bash
   pip install -r requirements.txt

---

## Deliverables
- Cleaned dataset  
- PCA results  
- Feature selection analysis  
- Supervised learning models  
- Unsupervised learning models  
- Hyperparameter tuning results  
- Final saved model (`final_model.pkl`)  
- Evaluation metrics (`results/evaluation_metrics.txt`)  
- Streamlit UI for real-time predictions (**Bonus**) 