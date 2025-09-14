# Kernel SVMs Comparison on Iris Dataset (Breast Cancer Dataset)

This project explores and compares the performance of **Kernel Support Vector Machine (SVM)** models using different kernels—**RBF**, **Polynomial**, and **Sigmoid**—on the **Iris dataset**.

---

## 🎯 Objective

To train and evaluate SVM classifiers with different kernels and compare their performance in terms of accuracy, confusion matrices, and decision boundaries.

---

## 🧩 Steps Covered

1. **Import Required Libraries**
2. **Load the Iris Dataset**
3. **Preprocess the Data**
   - Feature selection (sepal length and width)
   - Train-test split (80-20)
   - Feature scaling using `StandardScaler`
4. **Train SVM Models with Different Kernels**
   - RBF
   - Polynomial
   - Sigmoid
5. **Evaluate Models**
   - Confusion Matrix
   - Accuracy Score
   - Classification Report
   - Visualization via Heatmaps
6. **Visualize Decision Boundaries** (Optional)
7. **Compare Kernels**
   - Summary table of accuracy and observations
   - Discussion on best-performing kernel and potential overfitting/underfitting

---

## 📊 Results

| Kernel     | Accuracy | Observations                          |
|------------|----------|---------------------------------------|
| Polynomial | 96.67%   | High accuracy, minor misclassifications |

### Best Performing Kernel:
The **Polynomial kernel** achieved the highest accuracy (96.67%) with minimal misclassifications.

### Overfitting/Underfitting:
- No significant overfitting observed.
- All models generalized well on the test set.

---

## 🛠️ Dependencies

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 📌 Notes

- The dataset is split into 80% training and 20% testing.
- Feature scaling is applied for better SVM performance.
- Decision boundary plots are included for visual comparison (if applicable)

