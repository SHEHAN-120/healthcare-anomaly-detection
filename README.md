# Outlier Detection in Healthcare Data using Isolation Forest

This project focuses on detecting outliers in a healthcare dataset using the Isolation Forest algorithm from scikit-learn and visualizing them with Matplotlib.

---

## 🧰 Tools & Libraries Used

* **Python 3.11**
* **pandas**: For loading and processing the CSV data.
* **matplotlib**: For 2D data visualization (scatter plots).
* **scikit-learn**: For applying the Isolation Forest model.
* **numpy**: For handling array indexing.

---

## 📌 Project Description

* Load a 2D healthcare dataset from a CSV file.
* Apply Isolation Forest to detect anomalies/outliers.
* Visualize inliers and outliers with a clear color distinction.
* Highlight anomalies using red-edge scatter points.

---

## 📊 Dataset

* **File Name**: `healthcare.csv`
* **Expected Format**: Two numerical columns.
* **Usage**: The data is treated as 2D input for visualization and outlier detection.

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install dependencies
3. Run the script


---

## 📌 Key Features

* Easy-to-understand 2D visualization of outliers.
* Uses unsupervised machine learning for real-world data.
* Helps in detecting potential data issues or edge cases in medical datasets.

---

## ⚠️ Challenges Faced

* Dataset shape limitations — focused only on 2D for visualization simplicity.
* Setting an appropriate contamination level for the Isolation Forest algorithm.

---

## 🔍 Sample Code Snippet

```python
from sklearn.ensemble import IsolationForest
clf = IsolationForest(contamination=0.2)
clf.fit(df)
predictions = clf.predict(df)
```

---


## 📄 License

This project is licensed under the MIT License.

---

## 🙋 Contact

Maintained by Shehan.
