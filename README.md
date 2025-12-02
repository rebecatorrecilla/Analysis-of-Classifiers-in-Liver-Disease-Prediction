# Analysis of Classifiers for the Detection of Liver Diseases in the ILPD Dataset

## Project Overview
This project was developed for a Kaggle Machine Learning competition. The goal is to build a binary classifier capable of predicting whether a patient suffers from liver disease based on clinical and demographic data.

The project involves the entire machine learning pipeline: exploratory data analysis (EDA), feature engineering, handling class imbalance, model selection, and hyperparameter tuning. The final solution is evaluated via a **Kaggle InClass**.

## Problem Description
Liver disease cases are increasing due to factors such as excessive alcohol consumption, environmental toxins, and diet. The objective of this model is to assist doctors in reducing the burden of diagnosis by utilizing patient records collected from North East Andhra Pradesh, India.

## Dataset
The data is sourced from the **UCI Machine Learning Repository** (ILPD - Indian Liver Patient Dataset). It has been preprocessed to remove missing values and encode categorical features.

*   **Training Set:** 463 samples (Features + Labels).
*   **Test Set:** 116 samples (Features only).
*   **Features (10):** Age, Gender, Total Bilirubin (TB), Direct Bilirubin (DB), Alkaline Phosphotase, Alamine Aminotransferase (Sgpt), Aspartate Aminotransferase (Sgot), Total Proteins (TP), Albumin (ALB), and Albumin/Globulin Ratio (A/R).
*   **Target:** 
    *   `0`: Liver Patient (Ill)
    *   `1`: Healthy Subject

## Methodology
The development process followed strict academic guidelines (IEEE report format) and included:
1.  **Feature Analysis:** Analysis of correlations and feature importance.
2.  **Class Imbalance Handling:** The dataset contains significantly more liver patients than healthy subjects. Techniques were applied to address this unbalance.
3.  **Classification Models:** Implementation and comparison of various algorithms (e.g., Random Forest, Boosting techniques).
4.  **Evaluation:** The primary metric for the competition is the **F1-Score**, chosen to balance Precision and Recall due to the uneven class distribution.

## Tools & Technologies
*   **Language:** Python
*   **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib/Seaborn.
*   **Platform:** Kaggle InClass.
