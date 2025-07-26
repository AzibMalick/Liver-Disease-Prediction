# 🩺 Liver Disease Prediction Using Machine Learning

This project uses clinical patient data to predict the likelihood of liver disease using **SVM** and **Naive Bayes** models. It is part of a 15-project ML learning sprint aimed at developing healthcare-focused predictive models.

## Project Highlights
- Clinical data preprocessing & scaling
- Support Vector Machine (SVM) and Naive Bayes models
- Accuracy comparison with confusion matrices
- Medical interpretation of model outcomes
- Recommendations for future improvements

## Dataset
- Source: [Liver Disease UCI Repository or Kaggle version]
- Features include age, bilirubin levels, enzymes, proteins, and diagnosis

## Results

| Model          | Accuracy |
|----------------|----------|
| SVM            | 71.55%   |
| Naive Bayes    | 61.21%   |

SVM outperformed Naive Bayes, likely due to its robustness in handling correlated clinical features.

## Medical Insight

The model identifies **Total Bilirubin**, **Alkaline Phosphotase**, and **Albumin** as critical markers in liver disease prediction. Such models can assist in early diagnosis or decision support in clinical settings.

## Files

- `liver-disease-prediction.ipynb` – Jupyter notebook source code  
- `liver_patient_dataset.csv` – Dataset used  
- `requirements.txt` – Required libraries  
- `liver-disease-report.pdf` – (optional) Final formatted report

## Future Improvements

- Use SMOTE for imbalance  
- Tune SVM with RBF or polynomial kernels  
- Try ensemble models (XGBoost, Gradient Boosting)

## Author

Developed by **Azib Malick**  
© 2025 Azib Malick. All rights reserved.
