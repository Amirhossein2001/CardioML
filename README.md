🫀 Heart Disease Prediction with Machine Learning

This project uses a Random Forest Classifier to predict the presence of heart disease based on clinical data. The goal is to assist with early diagnosis and highlight important medical features that contribute to the prediction.


📊 Dataset:
The dataset includes 14 clinical features for 297 patients. The condition column indicates the presence (1) or absence (0) of heart disease.
Features:
Feature	Description
age	Age of the patient
sex	Sex (1 = male, 0 = female)
cp	Chest pain type (0–3)
trestbps	Resting blood pressure (mm Hg)
chol	Serum cholesterol (mg/dl)
fbs	Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
restecg	Resting electrocardiographic results
thalach	Maximum heart rate achieved
exang	Exercise-induced angina (1 = yes; 0 = no)
oldpeak	ST depression induced by exercise
slope	Slope of the peak exercise ST segment
ca	Number of major vessels colored by fluoroscopy
thal	Thalassemia (0 = normal; 1 = fixed defect; 2 = reversible defect)
condition	Target (1 = disease; 0 = no disease)


⚙️ Methods:
    Data preprocessing: Handling null values, feature scaling, splitting into train/test sets.

    Model: RandomForestClassifier from scikit-learn.

    Evaluation:

        Accuracy, Precision, Recall, F1-score

        ROC Curve

        Feature Importance Plot

📈 Results:
    Achieved ~70% accuracy on the test set.

    Key features contributing to predictions included:

        thalach (max heart rate)

        thal

        ca

        oldpeak


🛠 Requirements:

    Python 3.8+

    pandas

    numpy

    matplotlib

    scikit-learn

    seaborn






