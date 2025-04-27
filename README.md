# Iris-Flower-Classification

## Overview: 
This project focuses on classifying Iris flowers into three species — Iris-setosa, Iris-versicolor, and Iris-virginica — using machine learning techniques.
Built a classification model using a Decision Tree Classifier, performed exploratory data analysis (EDA), identified the most significant features, and achieved 100% accuracy on test data.
<br>

## Dataset
Source: Kaggle - Iris Flower Dataset

### Attributes:
-sepal_length (in cm)
- sepal_width (in cm)
- petal_length (in cm)
- petal_width (in cm)
- species (target label)

## Project Workflow
### 1. Data Loading and Preprocessing: 
Imported the dataset using pandas.
Checked for missing values and dataset imbalance.

### 2. Exploratory Data Analysis (EDA):
Generated pairplots and heatmaps to understand feature relationships.
Observed that petal length and petal width are highly correlated with species.

### 3. Feature Importance:
Plotted feature importance using the Decision Tree model.
Found that petal length and petal width are the most influential features.

### 4. Model Building:
Used DecisionTreeClassifier from scikit-learn.
Split dataset into training and testing sets (70-30 split).

### 5. Model Evaluation
Achieved 100% accuracy on test data.
Generated a classification report with perfect precision, recall, and F1-score.
Plotted a confusion matrix to visualize the predictions.


## Results

- Metric	Score
- Accuracy	100%
- Precision	100%
- Recall	100%
- F1-Score	100%
- Confusion Matrix showed that all test samples were correctly classified.
- Decision boundaries between species were clearly captured by the model.


## Technologies Used
- Python 
- Pandas for data manipulation
- NumPy for numerical computations
- Matplotlib and Seaborn for data visualization
- Scikit-learn for model building and evaluation


## Conclusion
The Decision Tree model proved highly effective for the Iris flower classification task, achieving perfect accuracy with minimal preprocessing.
This project showcases how even simple algorithms can deliver powerful results with well-structured datasets.


## Future Enhancements
Try other classification algorithms (e.g., Random Forest, SVM, KNN).
Hyperparameter tuning to improve model generalization.
Deploy the model using Flask or Streamlit for real-world use.

## Contact
For queries or collaborations:
[Somya Anand] | [somyaanand77@gmail.com] | [https://www.linkedin.com/in/somya-a-9229a1220/]











