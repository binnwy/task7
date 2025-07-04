# Task 6: K-Nearest Neighbors (KNN) Classification

## 📄 Objective

The objective of this task is to understand and implement the K-Nearest Neighbors (KNN) algorithm for classification problems using the Iris dataset.

---

## 🧰 Tools & Libraries

- **Python**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **kagglehub** (for downloading dataset)

---

## 💾 Dataset

- **Name:** Iris Dataset
- **Source:** [UCI Machine Learning Repository (via Kaggle)](https://www.kaggle.com/datasets/uciml/iris)
- **Features:**
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
- **Target:** Species (Setosa, Versicolor, Virginica)

---

## ✅ Steps

1. **Download Dataset**

   Using `kagglehub`, download and load the Iris dataset CSV file.

2. **Data Preprocessing**

   - Extract feature columns.
   - Standardize (normalize) features using `StandardScaler`.

3. **Train-Test Split**

   - Split data into training (80%) and testing (20%) sets.

4. **Model Training & Evaluation**

   - Train KNN classifiers for different values of k (1, 3, 5, 7, 9).
   - Evaluate models using accuracy score, confusion matrix, and classification report.

5. **Visualization**

   - Plot decision boundaries using first two features to visually understand class separation.

---

## 📊 Results

- Accuracy improves with optimal choice of k (commonly around 5).
- Visualization clearly shows regions predicted for each class and real data points.

---

## 💡 Usage

### 🏃‍♂️ Run

```bash
pip install pandas numpy matplotlib scikit-learn kagglehub
