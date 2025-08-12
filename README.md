K-Nearest Neighbors (KNN) Classification

📌 Objective:
The goal of this task is to understand and implement KNN for classification problems. You will learn how to:

Normalize features for distance-based algorithms

Experiment with different K values

Evaluate model performance

Visualize decision boundaries

📂 Dataset:
We used the Iris dataset (Iris.csv) containing 150 samples of iris flowers with the following features:

SepalLengthCm

SepalWidthCm

PetalLengthCm

PetalWidthCm

Species (target variable with classes: Iris-setosa, Iris-versicolor, Iris-virginica)

🛠 Tools & Libraries:
Python 3.x

Pandas – Data handling

Matplotlib – Visualization

Scikit-learn – KNN implementation, scaling, evaluation

NumPy – Numerical operations

🚀 Steps Implemented:
1. Load Dataset
Loaded Iris.csv into a pandas DataFrame

Removed unnecessary Id column

2. Feature Normalization
Applied StandardScaler to scale features so that all have equal weight in distance calculations.

3. Train-Test Split
Split dataset into 80% training and 20% testing.

4. Model Training & K Selection
Used KNeighborsClassifier from scikit-learn

Tested with K = 3, 5, 7 to compare accuracy

5. Model Evaluation
Calculated accuracy score

Plotted confusion matrix

6. Decision Boundary Visualization
Used only first two features to visualize decision boundaries

Created a mesh grid to plot regions classified by the KNN model

📊 Results:
Best Accuracy was obtained for K = 5 (can vary based on random split).

Confusion matrix showed perfect/near-perfect classification for Iris dataset.

📷 Output Examples:
Accuracy for each K value

Confusion Matrix plot

Decision Boundary plot

▶ How to Run:
Install dependencies:

pip install pandas matplotlib scikit-learn numpy
Place Iris.csv in the project directory.

Run the Python script or Jupyter Notebook:

python knn_classification.py
or
jupyter notebook TASK6.ipynb

📌 Notes:
Feature scaling is crucial for KNN since it’s distance-based.

Choosing K is a trade-off:

Small K → more sensitive to noise

Large K → smoother decision boundaries
