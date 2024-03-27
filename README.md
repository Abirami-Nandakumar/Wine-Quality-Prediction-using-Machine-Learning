# Wine-Quality-Prediction-using-Machine-Learning
This project focuses on predicting the quality of wines based on various physicochemical properties. We employed two classical machine learning algorithms, Logistic Regression (LR) and Support Vector Machine (SVM), to build predictive models.
Dataset
The dataset used in this project is the "Wine Quality" dataset, which is publicly available and has been sourced from Kaggle. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).Your task is to predict the quality of wine using the given data.

Approach
1. Data Preprocessing
Before building the predictive models, extensive data preprocessing steps were undertaken, including handling missing values, feature scaling, and encoding categorical variables.

2. Model Building
a. Logistic Regression
LR was chosen as one of the baseline models due to its simplicity and interpretability. We trained the LR model using the preprocessed dataset to predict the wine quality.

b. Support Vector Machine
SVM, a powerful classification algorithm, was selected for its ability to handle complex decision boundaries. We trained the SVM model to classify the wines into different quality categories.

3. Model Evaluation
Both LR and SVM models were evaluated using various performance metrics such as accuracy, precision, recall, and F1-score. Additionally, we employed techniques like cross-validation to ensure the robustness of the models.

4. Results and Insights
The performance of LR and SVM models was compared, and insights were drawn regarding the effectiveness of each model in predicting wine quality. Visualizations were used to showcase important features and decision boundaries.

Usage
The code provided in this repository can be used to reproduce the results and further explore the dataset and models. Detailed instructions are provided in the Jupyter Notebook.

Requirements
Python 3.x
Jupyter Notebook
Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
References
Dataset: Wine Quality Data from Kaggle
Scikit-learn Documentation: Logistic Regression, Support Vector Machine



