Crop Recommendation System Using Machine Learning

Project Overview:

The Crop Recommendation System is a Machine Learning project that predicts the most suitable crop based on soil nutrients and environmental conditions.

The model uses soil parameters such as Nitrogen (N), Phosphorus (P), Potassium (K), and pH, along with temperature, humidity, and rainfall.

Project Objectives:

- Analyze agricultural soil and weather data.
- Perform Exploratory Data Analysis (EDA).
- Train and compare multiple Machine Learning models.
- Predict suitable crops using user-provided inputs.
- Identify the best-performing model.

Dataset:

Dataset: Crop Recommendation Dataset

Source: "Kaggle – Crop Recommendation Dataset" (https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)

- Total Records: 2,200
- Total Features: 7
- Target Variable: "label"
- Crop Classes: 22

Technologies Used:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Joblib

Machine Learning Algorithms:

1. Decision Tree Classifier
2. Random Forest Classifier
3. Support Vector Machine (SVM)

Project Workflow:

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature and Target Separation
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Model Comparison
9. Best Model Selection
10. Crop Prediction

Model Evaluation

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

The best-performing model was selected based on test accuracy.

Sample Prediction:

The system was tested with sample soil and environmental values and predicted Rice as the recommended crop.

Project Structure:

Crop_Recommendation_ML/
│
├── dataset/
├── notebooks/
│   └── Crop_Recommendation_Analysis.ipynb
├── models/
│   └── best_crop_model.pkl
├── reports/
│   └── Crop_Recommendation_Analysis.html
├── graphs/
│   ├── confusion_matrix.png
│   └── model_accuracy_comparison.png
└── README.md

How to Run the Project,

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open Jupyter Notebook.
4. Open "Crop_Recommendation_Analysis.ipynb".
5. Run the notebook cells in order.

Install Dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn joblib jupyter

Conclusion:

This project demonstrates how Machine Learning can help recommend suitable crops based on soil nutrients and environmental conditions. It provides a basic data-driven approach to agricultural crop selection.

Note: This project is developed for educational purposes. Predictions should not replace professional agricultural advice.
