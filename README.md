#  Kidney Stone Prediction using Machine Learning

##  Overview
This project applies **Machine Learning (ML)** techniques to predict whether a patient has kidney stones based on medical features.  
The goal is to assist in **early detection and prevention** by analyzing health data and providing a data-driven prediction.

##  Dataset
- The dataset contains patient information such as:
  - Age
  - Gender
  - Blood Pressure
  - Urine Calcium Level
  - Serum Creatinine
  - Other relevant health indicators
- The target variable is whether the patient has **Kidney Stones (Yes/No)**.

*(Add dataset source here if available, e.g., Kaggle or hospital dataset)*

## ⚙️ Technologies Used
- Python 
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

##  Models Implemented
- Decision Tree
- Random Forest
- Logistic Regression
  

Models are evaluated based on:
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC Curve

##  Results
- Best performing model: **(Random Forest Classifier,  Random Forest with 83% accuracy)**
- and AUC = 0.81

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Kidney-Stone-Prediction.git
   cd Kidney-Stone-Prediction
2.Install dependencies:
pip install -r requirements.txt

3.Run the notebook:
jupyter notebook Kidney-Stone-Prediction-using-ML.ipynb

## Future Improvements
-Collect larger and more diverse dataset.
-Hyperparameter tuning for better accuracy.
-Deploy model using Flask/Streamlit for real-time prediction.
-Add feature selection & explainability with SHAP/ELI5.

## Developed by Your Name- NirmalanSK
 GitHub: https://github.com/NirmalanSK
