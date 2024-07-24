# HEART-DISEASE-PREDICTION-USING-MACHINE-LEARNING
Overview
This project is a Heart Disease Prediction System developed using machine learning. The system predicts the likelihood of heart disease based on user inputs related to various health parameters. The model used for prediction is trained on a heart disease dataset and can help in early detection and prevention.

Features
User-friendly GUI for inputting health parameters.
Predicts the likelihood of heart disease based on user inputs.
Provides clear results indicating whether there is a possibility of heart disease or not.
Requirements
Python 3.x
tkinter
joblib
Scikit-learn
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction

Create a virtual environment and activate it:
python -m venv venv
source venv/bin/activate # On Windows use `venv\Scripts\activate`

Install the required packages:
pip install -r requirements.txt

Usage
Ensure you have the trained model saved as model_joblib_heart in the project directory.

Run the heart_disease_prediction.py script to launch the GUI:
python heart_disease_prediction.py

Enter the required health parameters and click on the 'Predict' button to get the result.

Health Parameters
The following health parameters need to be entered:

Age
Gender (1 = Male, 0 = Female)
CP (Chest Pain type)
Trestbps (Resting Blood Pressure)
Chol (Serum Cholesterol)
Fbs (Fasting Blood Sugar > 120 mg/dl, 1 = True, 0 = False)
Restecg (Resting Electrocardiographic results)
Thalach (Maximum Heart Rate achieved)
Exang (Exercise Induced Angina, 1 = Yes, 0 = No)
Oldpeak (ST depression induced by exercise relative to rest)
Slope (Slope of the peak exercise ST segment)
CA (Number of major vessels colored by fluoroscopy)
Thal (Thalassemia)

Model Training
If you want to train the model yourself, follow these steps:

Download the heart disease dataset.
Train the model using your preferred machine learning algorithm.

Save the trained model using joblib:
import joblib
joblib.dump(model, 'model_joblib_heart')

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
