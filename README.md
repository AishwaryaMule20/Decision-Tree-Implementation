# Decision-Tree-Implementation

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: AISHWARYA MULE

*INTERN ID*: CT12WV90

*DOMAIN*: MACHINE LEARNING

*DURATION*: 12 WEEKS

*MENTOR*: NEELA SANTOSH



## Decision Tree Classification with Scikit-learn

This repository contains a machine learning classification project implemented using the Decision Tree Classifier from Python’s scikit-learn library. The project was developed as part of my internship at CODETECH IT SOLUTIONS, with the goal of gaining hands-on experience in data preprocessing, model training, evaluation, and visualization.

📌 Project Overview

The task involves classifying iris flowers into one of three species — Setosa, Versicolor, or Virginica — based on four measurable features:

Sepal length

Sepal width

Petal length

Petal width


The dataset used is the classic Iris dataset, which is included in scikit-learn and is widely used for introductory machine learning applications. It is a multiclass classification problem with a relatively small and clean dataset, making it suitable for evaluating basic algorithms like decision trees.

⚙️ Tools and Technologies

Programming Language: Python

Libraries Used:

scikit-learn for model building and evaluation

pandas for data handling

matplotlib for visualization



🔍 Methodology

1. Dataset Loading:
The Iris dataset was loaded using the load_iris() function from sklearn.datasets.


2. Data Preparation:
The feature matrix (X) and label vector (y) were extracted and structured into a DataFrame to facilitate easier manipulation and visualization.


3. Train-Test Split:
The data was split into training and testing sets in a 70:30 ratio using train_test_split(). This helps evaluate the model’s ability to generalize to unseen data.


4. Model Creation:
A DecisionTreeClassifier was created using 'entropy' as the splitting criterion to maximize information gain. A maximum depth of 3 was set to control complexity and avoid overfitting.


5. Training:
The model was trained using the training data (fit() method).


6. Prediction and Evaluation:
Predictions were made on the test set, and performance was assessed using accuracy_score(). The model achieved high accuracy, demonstrating effective learning and prediction.


7. Visualization:
The decision tree was visualized using plot_tree() from sklearn.tree. This graphical representation displays the structure of splits, thresholds, and class labels, offering valuable interpretability.



📈 Key Learnings

This project helped me understand the end-to-end workflow of a supervised machine learning task. I gained practical experience in preparing data, training a classifier, evaluating its performance, and understanding the internal logic through visual inspection. The Decision Tree algorithm proved useful not only for its predictive power but also for its explainability, a feature often desired in real-world applications.

📁 Repository Contents

decision_tree_classifier.py – Main script for model training and evaluation

requirements.txt – Lists required Python libraries

README.md – Project description and setup instructions

#OUTPUT

![Image](https://github.com/user-attachments/assets/4e80a7fd-2828-435d-a629-bd047201f234)




