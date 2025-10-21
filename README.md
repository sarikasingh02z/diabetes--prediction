Diabetes prediction project
This Machine learning project predicts whether a person is likely to have diabetes based on medical diagnostic measurement such as glucose level, blood pressure, BMI , insulin, DiabetesPedigreeFunction. it uses a ml model trained on real world  health data to provide accurate prediction and assis in early diagnosis.

Objective:
To build an accurate prediction model that can identify potential diabetes cases

Algorithm used:
- K-nearest Neighbors(KNN)
- Support Vector Machine(SVM)
- Logistic regression
  
Model Selection:
- After comparing multiple algorithms on diabetes dataset
- Evaluated based on accuracy, precision, and recall
- **Logistic Regression** performed best for this medical prediction task
- Final model saved using joblib for deployment
  
 Features:
- **Real-time Predictions** – Instant diabetes risk assessment  
- **Gradio Web Interface** – User-friendly medical tool  
- **Multiple Health Parameters** – Glucose, BMI, Insulin, Blood Pressure, etc.
  
Technical implementation:
- **Real-time Predictions** – Instant diabetes risk assessment  
- **Gradio Web Interface** – User-friendly medical tool  
- **Multiple Health Parameters** – Glucose, BMI, Insulin, Blood Pressure, etc.  
- **Model Persistence** – Trained model saved and reloaded efficiently

Project Structure:

- `diabetes_ml.ipynb` - Main Jupyter notebook with full implementation
- Trained model files - Best performing logistic regression model
- Gradio app - Web interface for easy usage
