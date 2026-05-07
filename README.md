# classification_learning_SSE_XRD
Physics-Informed Machine Learning from Limited XRD Data for Discovery of Room-Temperature Superionic Conductors

## Overview
This project implements multiple machine learning algorithms to classify materials based on X-ray Diffraction (XRD) features. The system compares three different classifiers: Random Forest, Gradient Boosting, and Support Vector Machine (SVM) to determine the most effective approach for material kind classification.

**Multiple ML Models**: 
  - Random Forest Classifier
  - Gradient Boosting Classifier
  - Support Vector Machine (SVM)
  - catboost

**Comprehensive Evaluation**: 
  - Accuracy scoring
  - Classification reports
  - Confusion matrices with visualizations

## Dataset Requirements
The project requires two CSV files:
- `cleaned_x_data_XRDa_featuresNoise.csv`: Contains XRD features for classification
- `y_data_kind.csv`: Contains target labels (material kinds)


class

├── main.py                                   
├── cleaned_x_data_XRDa_featuresNoise.csv     
├── y_data_kind.csv                          
├── requirements.txt                          
└── README.md                                 



## Dependencies
pandas >= 1.3.0
scikit-learn >= 0.24.0
matplotlib >= 3.4.0
seaborn >= 0.11.0
