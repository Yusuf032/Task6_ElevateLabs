# Task 6: K-Nearest Neighbors (KNN) Classification on Iris Dataset

## 📌 Objective
The objective of this task is to understand and implement the K-Nearest Neighbors (KNN) algorithm for solving classification problems using the Iris dataset.

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📊 Dataset Used
- Iris Dataset
- The dataset contains 150 samples of iris flowers belonging to three different species:
  - Iris-setosa
  - Iris-versicolor
  - Iris-virginica

---

## ⚙ Steps Performed
1. Loaded the Iris dataset.
2. Removed unnecessary columns.
3. Normalized the feature values using StandardScaler.
4. Implemented KNN algorithm using sklearn.
5. Selected optimal K value using 5-fold Cross Validation.
6. Trained the final model with the best K value.
7. Evaluated the model using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
8. Visualized the decision boundary using first two features.

---

## 📈 Results
- Achieved approximately 97% accuracy on the test dataset.
- Iris-setosa was classified perfectly.
- Minor misclassification occurred between Iris-versicolor and Iris-virginica due to feature overlap.

---

## 🧠 Conclusion
The KNN algorithm performed effectively on the Iris dataset after feature normalization. The decision boundary visualization indicated that the model can successfully classify well-separated classes, making it a suitable algorithm for small and structured datasets.

---

## 👨‍💻 Author
Mohd Yusuf Khan
