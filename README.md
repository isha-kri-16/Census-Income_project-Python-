# Census-Income_project

Census Income Classification

📌 Project Overview

This project aims to classify individuals based on their income level (greater than or less than $50K per year) using demographic and occupational data. Machine learning models were implemented to predict income categories, helping in financial and social analysis.

📂 Dataset

The dataset is sourced from the UCI Machine Learning Repository (Adult Census Dataset).

Features include age, education, occupation, gender, hours-per-week, marital status, and native country.

Target Variable: Income Category (>50K or <=50K).

🔧 Data Preprocessing

Handled missing values and removed duplicates.

Encoded categorical variables using LabelEncoder.

Identified and removed outliers using the Interquartile Range (IQR) Method.

Normalized numerical features for better model performance.

📊 Exploratory Data Analysis (EDA)

Used bar plots, histograms, scatter plots, and count plots to visualize data distribution.

Analyzed relationships between variables to understand income determinants.

⚡ Machine Learning Models Implemented

Logistic Regression (Best Model: Achieved 80.06% accuracy)

Decision Tree Classifier

Random Forest Classifier

📈 Model Evaluation

Performance Metrics Used: Accuracy, Precision, Recall, F1-score, Confusion Matrix.

Best Model: Logistic Regression (80.06% accuracy)

🏆 Key Findings

Education level, working hours, and occupation significantly impact income classification.

Logistic Regression performed best in terms of accuracy and interpretability.

🚀 How to Run the Project

Prerequisites

Ensure you have the following libraries installed:

pip install pandas numpy scikit-learn matplotlib seaborn

Running the Project

1. Clone the repository:

git clone https://github.com/yourusername/Census-Income-Classification.git

2.Navigate to the project folder:

cd Census-Income-Classification

3.Run the Jupyter Notebook or Python script:
jupyter notebook Census_Income_project.ipynb

Feedback & Support
If you have any suggestions or questions, feel free to open an issue or connect with me on LinkedIn. Contributions and feedback are always welcome!
