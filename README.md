# task-6-kNN
k-Nearest Neighbors 
# Task 6 - K-Nearest Neighbor (KNN) Classifier Iris Dataset

**Objective**
Construct a K-Nearest Neighbors (KNN) classifier on Iris dataset, optimize the **K** hyperparameter and check the performance of such classifier as well as the decision boundaries.

## Dataset
IRIS dataset (UCI) https://www.kaggle.com/datasets/uciml/iris
We can also find in `sklearn.datasets`

##  Tools & Libraries
-NumPy, Python, Pandas
- scikit -learn (KNN, train_test_split, metrics)
Matplotlib (Accuracy vs K and decision boundary)

Summary of workflow In accordance with the principle of multiplicity, work should flow in such a way that it can be controlled by activities. workshop activities Prework The identified activities used in this project will be described in detail in the section on activities.

### 1 Step 1: Load & Explore
- Import `iris` data set using `sklearn`
Verified shape and class distribution

Step 2: Preprocessing
- Normalized the data using **StandardScaler** (KNN is distance based)

### Step 3: Train-Test Split- Initial Model
Applied `train_test_split` (80 / 20)
The first process is to train KNN using `k=3`

### 4. Accuracy vs. K
Tested values of k between 1 to 20
Recorded the best accuracy (100%) with ` k = 2 to 17`
Final model best `k = 3`

**Step 5: Visualization of Decision Boundary**
Has used just **Petal Length & Width** on 2D visualization
Illustrated the result of KNN that classifies the input space into 3 classes and uses curved regions to do this

## Outcomes
- Accuracy: **100 %** (`k = 3`)
KNN provides **perfect separation** to Setosa class
- a little overlap in the comparison between Versicolor and Virginica - as should be in the Iris

## Files In Included
- `task6_knn_classifier.ipynb`
- `README.md`
- `knn_decision_boundary.png`

## Author
Sy Mallikarjun AI / ML Intern
