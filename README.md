# Assignment-4
# Breast Cancer Classification using K-Nearest Neighbors (KNN)

## Objective

The objective of this project is to develop a K-Nearest Neighbors (KNN) classification model to predict whether a breast tumor is **Malignant (M)** or **Benign (B)** based on diagnostic measurements. The project demonstrates data preprocessing, feature scaling, model training, and performance evaluation using machine learning techniques.

---

## Dataset

**Breast Cancer Wisconsin Diagnostic Dataset**

Kaggle Link:
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

---

## Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Methodology

1. Load the dataset using Pandas.
2. Explore the dataset and understand its structure.
3. Remove unnecessary columns (`id` and `Unnamed: 32`).
4. Encode the target variable (`diagnosis`).
5. Split the dataset into training and testing sets (80:20).
6. Standardize the feature values using `StandardScaler`.
7. Train a K-Nearest Neighbors (KNN) classifier with **K = 5**.
8. Predict the class labels for the test dataset.
9. Evaluate the model using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

---

## Results

The KNN classifier successfully classified breast tumors into malignant and benign categories. Feature scaling improved the model's performance because KNN relies on distance calculations. The evaluation metrics showed high classification accuracy, and the confusion matrix indicated that most samples were correctly classified.

---

## Conclusion

The K-Nearest Neighbors (KNN) algorithm proved to be an effective classification technique for the Breast Cancer Wisconsin Diagnostic Dataset. After preprocessing and feature scaling, the model achieved high prediction accuracy with good precision, recall, and F1-score. Feature scaling is important because KNN uses distance-based calculations, making all features contribute equally to the prediction. Although KNN performs well on this dataset, one limitation is that prediction becomes slower as the size of the training dataset increases. Overall, KNN is a simple and reliable algorithm for medical classification problems such as breast cancer diagnosis.

---

## Repository Structure

```
Assignment-4/
│── Assignment-4.ipynb
│── README.md
```

---

## Author

**Unnati Gupta**

Registration Number: 23MIM10191
