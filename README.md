# 🧠 Diabetes Prediction Using Machine Learning

This project predicts whether a person is diabetic based on medical diagnostic data using supervised machine learning models — Logistic Regression and Decision Tree Classifier.

## 📊 Dataset

The dataset is from the **Pima Indians Diabetes Database** and includes features like:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (1 = Diabetic, 0 = Not Diabetic)

## 🔍 Problem Statement

To build a classification system that can predict the probability of a person being diabetic based on key health parameters.

## ✅ Models Used

- Logistic Regression
- Decision Tree Classifier

Both models were evaluated using metrics like:
- Accuracy
- Confusion Matrix
- ROC AUC Score
- ROC Curve

## 📈 Performance

| Model               | Accuracy | ROC AUC Score |
|--------------------|----------|---------------|
| Logistic Regression| 75.32%   | 0.8147        |
| Decision Tree      | 74.68%   | 0.7424        |

## 🔮 Features

- Exploratory Data Analysis (EDA)
- Feature Correlation Heatmap
- ROC Curve Visualization
- Decision Tree Visualization
- Single-Person Prediction System

## 🛠️ Project Structure

- `notebook/`: Jupyter notebook with full analysis and modeling
- `data/`: Original dataset
- `outputs/`: Plots and model outputs
- `prediction/`: Script to test on custom input
- `src/`: Utility functions (optional)
- `README.md`: Project overview and usage guide

## ▶️ How to Use

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/diabetes-prediction-ml.git
cd diabetes-prediction-ml
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
```bash
jupyter notebook notebook/diabetes_prediction.ipynb
```

### 4. Predict on new data
Edit `predict_single_input.py` and run:
```bash
python prediction/predict_single_input.py
```

## 📌 Technologies

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- scikit-learn

## 📬 Contact

For queries or collaboration, feel free to connect:

**Shatadal Chakraborty**  
🔗 [LinkedIn](https://www.linkedin.com/in/shatadal-chakraborty-569903212)  
📧 shatadalchakraborty167@gmail.com  

---

⭐ Star this repo if you find it helpful!
