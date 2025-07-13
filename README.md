# iris_classification
# 🌸 Iris Flower Classification Project

A complete **data analysis and machine learning** project using Python and Jupyter Notebook. This project uses the classic **Iris dataset** to classify iris flowers into three species — Setosa, Versicolor, and Virginica — using a K-Nearest Neighbors (KNN) classifier.

---

## 🧠 What the Model Does

- Loads and explores the **Iris dataset** (from `sklearn.datasets`).
- Performs **exploratory data analysis (EDA)** using `pandas`, `seaborn`, and `matplotlib`.
- Splits and **scales the data** using `StandardScaler`.
- Trains a **K-Nearest Neighbors (KNN)** classification model.
- Evaluates model performance using **confusion matrix** and **classification report**.

---

## 📊 Key Results

- **Accuracy**: ~96% on test data
- **Model**: KNN with `k=3`
- **Data Insights**:
  - Petal length and width are the most important features.
  - Visual separation between species is strong in pair plots.
- Confusion matrix and heatmap show very few misclassifications.

---

## 💻 How to Run the Code

1. Clone or download the repository:

   git clone https://github.com/your-username/iris-classification.git
   cd iris-classification
   
2. Install required libraries (if not already installed):
   pip install pandas numpy matplotlib seaborn scikit-learn

3.Launch the Jupyter Notebook:
   jupyter notebook
   
4.Open the notebook file:
   iris_classification.ipynb
   
5.Run the cells one by one to see analysis, visualizations, and predictions.



