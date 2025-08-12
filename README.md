# K-Nearest Neighbors (KNN) Classification 💐

This project provides a practical implementation of the K-Nearest Neighbors (KNN) algorithm for multi-class classification. Using the classic **Iris dataset**, the goal is to build a classifier that can distinguish between different species of iris flowers based on their sepal dimensions.

The project emphasizes hyperparameter tuning, the importance of feature scaling, and the visualization of model decision boundaries.

---

## ## Project Workflow

1.  **Data Preparation**: The Iris dataset was loaded, and for clear visualization, the first two features (sepal length and sepal width) were selected. The features were then **scaled** using `StandardScaler`, a critical step for distance-based algorithms like KNN.

2.  **Hyperparameter Tuning (Finding K)**: To find the optimal number of neighbors, the model was trained and evaluated on a range of K values (from 1 to 25). The accuracies were plotted, allowing for the selection of a K value that provides the best performance on unseen data.

3.  **Final Model Training**: A final `KNeighborsClassifier` was trained using the optimal K value determined in the previous step.

4.  **Evaluation**: The final model's performance was assessed using an accuracy score and a confusion matrix to understand its predictive capabilities.

5.  **Decision Boundary Visualization**: The model's decision regions were plotted on a 2D graph. This provides a clear, intuitive visualization of how the KNN algorithm partitions the feature space to classify the different Iris species. 

---

## ## Key Concepts Learned

* The core intuition behind the **K-Nearest Neighbors** algorithm.
* The critical importance of **feature scaling** for distance-based models.
* A practical method for **hyperparameter tuning** by iterating through different K values.
* The technique for visualizing **decision boundaries** to understand a model's behavior.

---

## ## Tools Used

* Python
* Scikit-learn
* Pandas
* Matplotlib & Seaborn
* NumPy
