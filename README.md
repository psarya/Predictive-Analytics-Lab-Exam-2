# Binary Classification Project: Feature Analysis and Decision Tree Modeling

This project demonstrates a complete machine learning workflow for solving a binary classification problem using a Decision Tree Classifier. It covers data preprocessing, exploratory data analysis (EDA), model training, evaluation, and visualization.

---

## 🚀 Features

* Data cleaning and preprocessing
* Handling missing values and outliers
* Feature visualization using scatter plots
* Decision Tree model training
* Model evaluation with detailed metrics
* Decision boundary visualization

---

## 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

Navigate to the project directory:

```bash
cd your-repo-name
```

Install required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Usage

Run the Jupyter Notebook:

```bash
jupyter notebook Lab2.ipynb
```

Execute all cells sequentially to reproduce the analysis and results.

---

## 📂 Dataset

**File:** `Lab_Exam_binary_classification_dataset.csv`

### Columns:

* `Feature1` – Numerical feature
* `Feature2` – Numerical feature
* `Target` – Binary label (`Yes` / `No`)

---

## 🔍 Workflow

### 1. Data Preprocessing

* Removed rows with missing target values
* Encoded target labels (`Yes → 1`, `No → 0`)
* Removed extreme outlier (`Feature1 = 10000`)

### 2. Exploratory Data Analysis (EDA)

* Scatter plot of `Feature1` vs `Feature2`
* Visualized class distribution and separability

### 3. Train-Test Split

* 70% training, 30% testing
* `random_state = 42` for reproducibility

### 4. Model Training

* Algorithm: Decision Tree Classifier
* Captures non-linear relationships
* Easy to interpret and visualize

### 5. Model Evaluation

* **Accuracy:** 0.9433
* Strong performance across both classes
* High recall for the positive class

### 6. Visualization

* Decision boundary plotted for better interpretability of model behavior

---

## 🧪 Results Summary

| Metric     | Value  |
| ---------- | ------ |
| Accuracy   | 0.9433 |
| Class 0 F1 | 0.96   |
| Class 1 F1 | 0.87   |

The model performs very well overall, achieving high accuracy and effectively identifying both classes.

---

## 📦 Project Structure

```
your-repo-name/
│
├── Lab2.ipynb
├── Lab_Exam_binary_classification_dataset.csv
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a pull request

##
