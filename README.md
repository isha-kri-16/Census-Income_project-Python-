# Census-Income_project-Python-Census Income Classification
Overview
This project aims to predict whether an individual earns more than $50K per year based on demographic and occupational data. Using machine learning algorithms, the model classifies individuals into income groups based on factors such as age, education, occupation, work hours, and marital status.

Dataset
Source: UCI Machine Learning Repository – Census Income Dataset
Attributes:
Demographic features: Age, Gender, Education, Marital Status
Occupational features: Workclass, Occupation, Hours per week
Financial indicator: Income category (<=50K or >50K)
Technologies & Tools Used
Programming Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Machine Learning Models: Logistic Regression, Decision Tree, Random Forest
Data Preprocessing
Handled missing values and duplicates
Encoded categorical variables using LabelEncoder
Identified and removed outliers using IQR method
Scaled numerical features for better model performance
Exploratory Data Analysis (EDA)
Visualized income distribution using histograms and count plots
Analyzed feature relationships with bar charts and scatter plots
Identified key features affecting income level
Model Training & Evaluation
Model	Accuracy
Logistic Regression	80.06%
Decision Tree	78.4%
Random Forest	79.8%
Best Model: Logistic Regression (80.06% Accuracy)
Evaluated using Confusion Matrix, Precision, Recall, and F1-score
Results & Insights
Education level, occupation, and work hours significantly impact income classification.
Logistic Regression outperformed Decision Tree and Random Forest in terms of accuracy.
Feature importance analysis helped optimize model performance.
How to Run the Project?
Clone the repository:
bash
Copy
Edit
git clone https://github.com/yourusername/Census-Income-Classification.git
cd Census-Income-Classification
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook:
bash
Copy
Edit
jupyter notebook
Open Census_Income_Classification.ipynb and execute the cells.
Future Improvements
Implement XGBoost and SVM for better classification accuracy.
Address class imbalance with SMOTE or undersampling techniques.
Deploy model as a web application using Flask or FastAPI.
