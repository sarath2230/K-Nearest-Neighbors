# Task 6 – KNN Classification on Iris Dataset (CSV)

This task focuses on implementing the **K-Nearest Neighbors (KNN)** algorithm using the Iris dataset loaded from a CSV file. KNN is an intuitive classification algorithm based on instance similarity. It is particularly effective on smaller, clean datasets like Iris.

## 📌 Objective
- Implement KNN for classification
- Visualize accuracy for different K values
- Plot decision boundaries using two features
- Evaluate using confusion matrix and cross-validation

## 📊 Key Steps
- Loaded dataset from CSV
- Encoded the `species` column using `LabelEncoder`
- Selected `sepal_length` and `petal_length` for 2D visualization
- Scaled features using `StandardScaler`
- Trained and evaluated `KNeighborsClassifier` from Scikit-learn
- Tested values of K from 1 to 10
- Plotted decision boundaries
- Evaluated performance using cross-validation

## 🔍 Libraries Used
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## ✅ Conclusion
KNN performed exceptionally well on the Iris dataset. Using only two features for simplicity, we achieved high classification accuracy across multiple values of K. Cross-validation confirmed model reliability, and visualizing decision boundaries provided a clear understanding of how KNN works in feature space.

---

