# Machine Learning Algorithm Test

This is a simple machine learning algorithm test taken from the tutorial (here)[https://machinelearningmastery.com/machine-learning-in-python-step-by-step/].

It uses the (Iris flower dataset)[https://en.wikipedia.org/wiki/Iris_flower_data_set] and applies some data analytics to the dataset. An example is included in this repo.

It then uses the data as a validation set to train 6 different algorithms:
* Logistic Regression (LR)
* Linear Discriminant Analysis (LDA)
* K-Nearest Neighbors (KNN)
* Classification and Regression Trees (CART)
* Gaussian Naive Bayes (NB)
* Support Vector Machines (SVM)

## How to use
1. Install the packages listed in requirements.txt using pip. I suggest using a venv for this and python3.
 * ```
    python3 -m venv venv
   ```
 * ```
    pip install -r requirements.txt
   ```
2. Once packages are installed, run using the following code
```
python3 main.py
```
3. If everythong is installed correctly, you should see a classifcation report that provides a breakdown of each class by precision, recall, f1-score and support.