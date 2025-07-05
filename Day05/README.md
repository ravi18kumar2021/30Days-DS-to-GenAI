# 📅 Day 5: Supervised ML – Classification

## ✅ Topics Covered
- Binary classification overview
- Logistic Regression intuition and implementation
- Sigmoid function and decision boundaries
- Evaluation metrics:
  - Confusion Matrix
  - Accuracy, Precision, Recall, F1 Score
- Handling imbalanced data (intro)
- Model training with Scikit-learn

---

## 🛠 Tools Used
- Python 3.x
- NumPy, Pandas
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 💡 Mini Project: Diabetes Prediction

### 📁 Dataset
- **Source:** PIMA Indian Diabetes Dataset
- **Features:** Glucose, BMI, Age, Pregnancies, BloodPressure, etc.
- **Target:** `Outcome` (0 = no diabetes, 1 = diabetes)

---

## 🔍 Key Tasks

### 1️⃣ Data Preparation
- Split data into training and test sets (stratified)
- Standardized features using `StandardScaler`

### 2️⃣ Model Building
- Trained **Logistic Regression** using Scikit-learn (`LogisticRegression`)
- Increased `max_iter` to ensure convergence (in case data is not scaled)

### 3️⃣ Evaluation Metrics
- Predicted labels and probabilities
- Calculated:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC Score
- Confusion matrix to inspect model performance

---

## ✅ Results Snapshot
| Metric     | Value   |
|------------|---------|
| Accuracy   | ~70–73% |
| Precision  | ~60–63% |
| Recall     | ~62–65% |
| F1 Score   | ~60–65% |
| AUC Score  | ~78–82% |

---

## 🔧 Learning Outcomes
- Understood how logistic regression classifies binary outcomes
- Learned how to evaluate model effectiveness beyond accuracy
- Developed workflow for building and testing a classification model
- Gained awareness of convergence issues and data scaling

---

## 🔄 To Improve Later (After Day 8)
- Visualize confusion matrix using `Seaborn`
- Plot ROC curve
- Explore model interpretability using feature coefficients
