# Explainable AI (XAI) for Clinical Decision Support

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## 1. Overview

This project explores the critical intersection of machine learning and explainability in high-stakes environments. It features a Python-based implementation of a machine learning model to predict cardiovascular disease, followed by a deep-dive analysis using two leading Explainable AI (XAI) frameworks: **SHAP** and **LIME**.

The goal is to demonstrate how we can move beyond "black box" predictions and provide transparent, human-interpretable insights into why a model makes a particular decision. This is essential for building trust, ensuring accountability, and satisfying regulatory requirements in fields like healthcare.

## 2. Key Features

- **Predictive Model:** A `RandomForestClassifier` trained on the UCI Heart Disease dataset to predict the presence of heart disease.
- **Global Explanations:** Uses **SHAP (SHapley Additive exPlanations)** to analyze overall model behavior and identify the most influential features across all predictions.
- **Local Explanations:** Implements both **SHAP** and **LIME (Local Interpretable Model-agnostic Explanations)** to explain the rationale behind individual predictions for a single patient.
- **Data-Driven Insights:** Validates that the model learns clinically relevant patterns, aligning its logic with established medical knowledge.
- **Governance Context:** The project is framed within the context of emerging AI governance standards like the EU AI Act and NIST AI RMF, where transparency is a legal and ethical requirement.

## 3. Tech Stack & Dependencies

- Python 3.9+
- pandas
- numpy
- scikit-learn
- shap
- lime
- matplotlib
- jupyter

## 4. Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/XAI-Heart-Disease-Prediction.git](https://github.com/your-username/XAI-Heart-Disease-Prediction.git)
    cd XAI-Heart-Disease-Prediction
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required packages:**
    ```bash
    pip install pandas numpy scikit-learn shap lime matplotlib jupyter
    ```

## 5. Usage

All the code and analysis are contained within the Jupyter Notebook.

1.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
2.  **Open the notebook file:**
    Click on `XAI_Heart_Disease_Prediction.ipynb` to open and run the cells sequentially.
