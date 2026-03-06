# Caffeine Degradation Prediction using Machine Learning

This repository contains a Jupyter Notebook that analyzes and predicts **caffeine degradation in aqueous environments** using various machine learning regression models. The project explores how experimental conditions such as oxidant dosage, reaction time, pH, and caffeine concentration influence degradation efficiency.

The notebook performs **data preprocessing, exploratory data analysis, regression modeling, dimensionality reduction, and performance comparison across multiple machine learning algorithms**.

---

## Project Overview

Caffeine is one of the most widely detected micropollutants in aquatic environments due to its extensive use in beverages, pharmaceuticals, and personal care products. Conventional wastewater treatment processes often struggle to completely remove caffeine from water systems.

This project applies **machine learning techniques to predict caffeine degradation efficiency** under different treatment conditions in a **thermal-activated persulfate oxidation system**.

The main objectives of this project are:

- Analyze relationships between experimental variables and caffeine degradation.
- Apply multiple regression models to predict degradation efficiency.
- Compare model performance using standard evaluation metrics.
- Identify the most reliable predictive model.

---

## Dataset Variables

The dataset used in this study includes the following experimental parameters:

- **Conc. Of Persulfate** – Oxidant concentration used in the treatment process  
- **Time** – Reaction time in minutes  
- **pH** – Acidity level of the solution  
- **Concentration of Caffeine** – Initial caffeine concentration  
- **Response (%)** – Experimental response variable  
- **Caffeine degradation amount** – Target variable representing degradation efficiency  

---

## Machine Learning Models Used

Multiple regression models were implemented and compared, including:

- Linear Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting Regression
- Support Vector Regression (SVR)
- K-Nearest Neighbors (KNN)
- Gaussian Process Regression
- Neural Network (TensorFlow/Keras)

In addition to individual models, **hybrid ensemble approaches** combining predictions from multiple models were also explored.

---

## Data Analysis Techniques

The notebook also performs exploratory and multivariate analysis, including:

- Feature correlation analysis
- Scatter plot visualization
- Distribution analysis
- Outlier detection
- Principal Component Analysis (PCA)
- Principal Coordinate Analysis (PCoA)

These techniques help identify patterns and relationships between variables.

---

## Model Evaluation Metrics

Model performance is evaluated using standard regression metrics:

- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R-squared Score (R²)**
- **Explained Variance Score (EVS)**

These metrics help determine the most accurate predictive model for caffeine degradation.

---

## Results

The experimental results indicate that **ensemble-based models provide the best predictive performance**.

Key observations include:

- Random Forest Regression achieved near-perfect prediction accuracy.
- Gradient Boosting Regression also demonstrated strong predictive capability.
- Neural network models effectively captured nonlinear relationships.
- Ensemble approaches improved model robustness.

Overall, **ensemble learning methods provided the most reliable predictions for caffeine degradation efficiency**.

---

## Requirements

To run this project, install the following Python packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn scipy tensorflow jupyter
