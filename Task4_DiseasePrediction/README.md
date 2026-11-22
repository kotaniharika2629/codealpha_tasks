
# Disease Prediction from Medical Data

## CodeAlpha Machine Learning Internship — Task 4

### Project Overview
This project uses machine learning algorithms to classify breast tumor samples as malignant or benign based on diagnostic measurements.

### Dataset
- Name: Breast Cancer Wisconsin (Diagnostic)
- Source: Scikit-learn / UCI Machine Learning Repository
- Total Samples: 569
- Features: 30
- Classes: Malignant and Benign

### Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Google Colab

### Machine Learning Algorithms
1. Logistic Regression
2. Support Vector Machine (SVM)
3. Random Forest

### Model Performance

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---|---|---|---|---|
| Logistic Regression | 98.25% | 0.9762 | 0.9762 | 0.9762 | 0.9954 |
| SVM | 98.25% | 0.9762 | 0.9762 | 0.9762 | 0.9950 |
| Random Forest | 95.61% | 0.9512 | 0.9286 | 0.9398 | 0.9939 |

### Best Performing Model
Logistic Regression achieved 98.25% accuracy and an ROC-AUC score of 0.9954.

The evaluation metrics use malignant tumors as the positive class.

### Project Features
- Data preprocessing and feature scaling
- Exploratory data analysis
- Model training and comparison
- Accuracy, Precision, Recall and F1-Score
- ROC-AUC evaluation
- Confusion matrices
- ROC curve visualization
- Sample predictions
- Model saving using Joblib

### Sample Prediction
- Actual Class: Malignant
- Predicted Class: Malignant

### How to Run
1. Open Disease_Prediction_Model.ipynb in Google Colab.
2. Install the required libraries.
3. Execute all notebook cells in order.
4. View the evaluation metrics and graphs.
5. Run the sample prediction.

### Limitations
This project is for educational purposes only.
It is not intended for medical diagnosis or clinical decision-making.

### Internship
CodeAlpha Machine Learning Internship — Task 4
