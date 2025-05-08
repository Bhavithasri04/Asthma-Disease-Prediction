Asthma Disease Prediction

This project uses machine learning techniques to analyze and predict the presence and severity of asthma using patient data. The analysis is performed using Python and Google Colab, with a dataset loaded from Google Drive.

📁 Project Overview

The notebook walks through the full data science pipeline:

Data exploration and visualization

Data preprocessing and normalization

Model training using:

Logistic Regression (for classification)

Linear Regression (as a baseline regressor)

Model evaluation using metrics such as accuracy, confusion matrix, MAE, MSE, RMSE, and R² score

📊 Dataset

The dataset includes features like:

Age groups (e.g., 10–19, 20–24, etc.)

Gender (Male, Female)

Symptoms: Nasal Congestion, Difficulty in Breathing, Dry Cough, Sore Throat, etc.

Severity indicators: Mild, Moderate, None

The CSV file is stored on Google Drive and accessed via pandas.read_csv.

📌 Key Features

Data Cleaning: Handling duplicates and checking for null values

Normalization: Applied to symptom-related columns

Visualization: Matplotlib and seaborn for trend and distribution analysis

Classification: Logistic Regression used to predict Severity_None

Evaluation: Reports accuracy and detailed classification metrics

📈 Model Accuracy

Logistic Regression achieved an accuracy of ~X% (replace X with your actual result).

Linear Regression was also tested for comparison, though classification is more suitable.

🔧 Libraries Used

pandas, numpy

matplotlib, seaborn

scikit-learn (for model training and evaluation)

warnings, Google Colab Drive integration

📂 How to Use

Open the Colab notebook.

Mount Google Drive and ensure the dataset path is correct.

Run all cells to see exploratory analysis, model results, and evaluation.

📌 Note

This notebook was created using Google Colab and is saved directly to this GitHub repository.



