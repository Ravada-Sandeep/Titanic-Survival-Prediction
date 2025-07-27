# Titanic-Survival-Prediction

<img src="https://images8.alphacoders.com/405/405029.jpg">



This machine learning project predicts the survival of passengers aboard the Titanic using supervised classification models. The project is based on the classic [Kaggle Titanic dataset](https://www.kaggle.com/competitions/titanic/overview), which includes information about passenger demographics, ticket details, and travel class.
Using Machine learning algorithm on the famous Titanic Disaster Dataset for Predicting the survival of the passenger

##  Dataset Overview

The dataset contains information about passengers, including:

| Column        | Description                            |
|---------------|----------------------------------------|
| `PassengerId` | Unique identifier                      |
| `Pclass`      | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)|
| `Name`        | Passenger name                         |
| `Sex`         | Gender                                 |
| `Age`         | Age in years                           |
| `SibSp`       | # of siblings / spouses aboard         |
| `Parch`       | # of parents / children aboard         |
| `Fare`        | Ticket fare                            |
| `Embarked`    | Port of embarkation                    |
| `Survived`    | Target (0 = No, 1 = Yes)               |

                                                                    


Dependencies:

    Python3
    Numpy
    Pandas
    Matplotlib
    Supervised Learning
    Machine Learning Algorithm
    Classification Algorithms
    


##  Project Highlights

-  Performed end-to-end exploratory data analysis (EDA)
-  Cleaned and preprocessed missing & categorical values
-  Trained and evaluated multiple ML models (Logistic Regression, Decision Tree, Random Forest)
-  Chose the best-performing model based on accuracy & F1-score
-  Made survival predictions on test data


Data Analysis:

Supervised Machine learning Techniques:  Logit Regression Model + Support Vector Machine (SVM) using 3 kernels + KNN + Decision Tree Classifier

---
###  Evaluation Metrics
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

##  Model Performance

| Model                         | Accuracy Score |
|-------------------------------|----------------|
| Logistic Regression           | 76%            |
| Support Vector Machine (SVM)  | 62%            |
| K-Nearest Neighbors (KNN)     | 69%            |
| Decision Tree Classifier      | **83%**        |

---

##  Final Conclusion

Among all the models tested, the **Decision Tree Classifier** achieved the highest accuracy of **83%**, making it the best-performing model on the Titanic dataset.

-  **Decision Trees** are especially effective in capturing complex non-linear relationships and can handle categorical features without requiring feature scaling.
-  **Logistic Regression** provided a strong baseline at **76%**, but may not have fully captured deeper patterns in the data.
-  **SVM** and **KNN** underperformed, likely due to:
  - Sensitivity to feature scaling
  - The curse of dimensionality
  - Difficulty in handling overlapping classes and noise

This comparison highlights the importance of evaluating multiple models and understanding their assumptions and limitations when working with real-world datasets.

