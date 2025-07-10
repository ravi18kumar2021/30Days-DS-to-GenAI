# 📅 Day 6: Exploratory Data Analysis (EDA Deep Dive)

## ✅ Topics Covered
- Understanding dataset structure and schema
- Summary statistics using `.describe()` and `.value_counts()`
- Detecting and handling missing or invalid values
- Identifying outliers using logic-based checks
- Analyzing feature-target relationships
- Computing feature correlations
- Grouping and aggregating data

---

## 🛠 Tools Used
- Python 3.x
- Pandas
- NumPy
- Google Colab / Jupyter Notebook

---

## 💡 Mini Project: Auto MPG EDA

### 📁 Dataset
- **Source:** UCI Auto MPG Dataset
- **Sample Columns:** `mpg`, `cylinders`, `displacement`, `horsepower`, `weight`, `acceleration`, `model year`, `origin`, `car name`
- **Target:** `mpg` (Miles Per Gallon - continuous)

---

## 🔍 Key Tasks Performed

### 1️⃣ Dataset Exploration
- Checked shape, column types, and missing/null values using `info()` and `isnull()`
- Used `.describe()` and `.value_counts()` to understand distributions

### 2️⃣ Invalid Data Handling
- Identified `horsepower`, `weight`, and `displacement` with zero or placeholder values
- Replaced zero entries with median values for accurate modeling

### 3️⃣ Correlation Analysis
- Used `.corr()` to identify relationship between features and the target (`mpg`)
- Found `weight`, `displacement`, and `horsepower` negatively correlated with `mpg`

### 4️⃣ Feature-Target Grouping
- Used `groupby()` to analyze:
  - Average `mpg` per `cylinders` count
  - Average `mpg` by `origin` (U.S., Europe, Japan)
- Found fewer cylinders and non-U.S. origin associated with higher fuel efficiency

---

## 📌 Key Insights

- Cars with higher weight or more cylinders generally have lower MPG
- The `origin` feature is a useful categorical indicator of fuel efficiency trends
- `horsepower` may contain invalid strings like `'?'` and requires preprocessing
- The dataset shows multicollinearity risk between `weight`, `horsepower`, and `displacement`
- Basic EDA can uncover actionable patterns without visualizations

---

## 🧠 Learning Outcomes

- Gained hands-on experience with data inspection and logic-based exploration
- Practiced identifying and cleaning invalid data entries
- Understood how to extract meaningful insights using Pandas-only techniques
- Developed intuition on relationships that impact fuel efficiency
