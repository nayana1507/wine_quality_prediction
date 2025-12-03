# 🍷 Wine Quality Prediction using Random Forest Classifier

## 📌 Project Overview
This project builds a machine learning model to predict the **quality of red wine** based on its physicochemical properties.  
The prediction is **binary**:

- **Good Quality** → quality score **≥ 7**
- **Not Good Quality** → quality score **< 7**

The model is developed using a **Random Forest Classifier**.

---

## 📊 Dataset Details
- **File:** winequality-red.csv  
- **Rows:** 1599  
- **Columns:** 12 (11 features + 1 target)
- **Target:** quality (score between 3–8)
- **Converted Label:** `quality_label` (Good / Not Good)
- **Source:** UCI Wine Quality Dataset

---

## 🧪 Methodology

### 🔹 1. Data Exploration & Preprocessing
- Verified dataset has **no missing values**
- Converted multiclass quality into **binary target**
- Performed basic EDA:
  - Summary statistics
  - Correlation understanding (heatmap)

### 🔹 2. Model Development
- **Algorithm:** Random Forest Classifier
- Train-test split used for evaluation
- Model trained to classify `quality_label`

### 🔹 3. Evaluation Metrics
- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-score)

---

## 📂 Project Files
| File Name | Description |
|----------|-------------|
| `wine_quality.ipynb` | Notebook with EDA, training, evaluation & prediction |
| `winequality-red.csv` | Dataset file used for the model |

---

## 🛠 Requirements
Install dependencies using pip:

    pip install numpy pandas matplotlib seaborn scikit-learn

---

## ▶️ How to Run
1️⃣ Ensure both the notebook and dataset are in the same folder  
2️⃣ Open the notebook using Jupyter:

    jupyter notebook "wine_quality.ipynb"

3️⃣ Run all cells to:
- Explore the dataset
- Train the model
- Generate accuracy results
- Predict new wine sample quality

Output Example:  
Model classifies wine as **Good** or **Not Good**
