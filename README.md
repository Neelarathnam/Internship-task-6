# Internship-task-6
This project uses the KNN algorithm to classify data from a CSV file. The data is cleaned, labels are converted to numbers, and values are scaled. The model is tested with different K values to find the best one. A graph shows the accuracy for each K. Finally, the best K is used to check how well the model works.
#  Task 6: K-Nearest Neighbors (KNN) Classification

This project demonstrates how to implement the K-Nearest Neighbors (KNN) algorithm for classification using a CSV dataset in Google Colab.

---

##  Dataset

- A CSV file was uploaded manually in Google Colab.
- The target column used: **`Species`**
- Features were separated and scaled using `StandardScaler`.

---

##  What I Did

- Uploaded and explored the dataset.
- Encoded target labels using `LabelEncoder`.
- Normalized feature values.
- Split the dataset into training and testing sets.
- Tested K values from 1 to 20 using `KNeighborsClassifier`.
- Plotted **Accuracy vs. K** to find the best K.
- Trained the final model using the best K.
- Evaluated the model with accuracy, confusion matrix, and classification report.

---

##  Output

- Best **K** value was selected automatically.
- Printed final accuracy and evaluation metrics.
- Plotted a line graph showing how accuracy changes with K.

---

##  Libraries Used

- `pandas`
- `scikit-learn`
- `matplotlib`
- `LabelEncoder`, `StandardScaler`, `KNeighborsClassifier`

---

##  How to Run

1. Open the notebook in **Google Colab**.
2. Run the first cell to **upload your CSV file**.
3. Run all remaining cells in order.

---

##  Note

- Replace `'Species'` with your actual target column name if your dataset is different.
- Make sure your dataset contains numeric or clean categorical values.


