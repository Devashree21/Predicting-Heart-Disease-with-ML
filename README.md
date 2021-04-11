

## Here is a short FAQ about this repository

**1) What is this repository about?**

This repository is contains a Machine Learning model for predicting Heart Diseases.

It includes the jupyter notebook (.ipynb), PDF file created from the jupyter notebook with results and a readme.

**2) Which dataset has been used and where to find it?**

The actual dataset used here is from UCI Machine Learning repository and you can find it on kaggle also.

https://archive.ics.uci.edu/ml/datasets/heart+disease

https://www.kaggle.com/ronitf/heart-disease-uci (This is the .csv version which I have used in this project)

**3) What does the dataset contain?**

This dataset contains 303 entries and 14 attributes related to heart health.

**4) Which type of ML model is it and what has been the approach to build it?**

This is a classification type of ML model. Initially an EDA has been done to understand the features and later different ML algorithms have been applied to train the model. Top 3 algorithms with accuracy >75% were selected and the model has been cross-validated on these.

Since the dataset is unbalanced (approx. 70:30 ratio of gender distribution in the dataset), a new dataframe has been created for female population. Later, the most accurate algorithm from earlier results has been applied to confirm the accuracy of the model.

**5) Which tool and which libraries have been used in this project?**

This project has been entirely completed in Jupyter IDE with Python 3.8.5 and the model has been trained using scikit-learn framework. 

Libraries used: Pandas, NumPy, Matplotlib and Seaborn
