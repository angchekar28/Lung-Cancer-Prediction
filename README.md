# 📌 Lung Cancer Prediction: Model Comparison

## 📝 Project Overview
This project builds and compares multiple machine learning models to predict lung cancer presence based on patient data. The objective is to determine the most effective model for early diagnosis.

## 📊 Dataset
- **Source:** Medical dataset with patient attributes
- **Columns:**
  - `Age`, `Gender`, `Smoking`, `Yellow Fingers`, `Anxiety`, `Peer Pressure`, `Chronic Disease`
  - `Wheezing`, `Alcohol`, `Coughing`, `Shortness of Breath`
  - `Swallowing Difficulty`, `Chest Pain`
  - `Lung Cancer` (Target variable: Yes/No)

## ⚙️ Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling (if required)

2. **Exploratory Data Analysis (EDA)**
   - Correlation analysis of symptoms
   - Class distribution visualization

3. **Model Implementation**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
   - K-Nearest Neighbors (KNN)

4. **Model Evaluation**
   - Accuracy, Precision, Recall, and F1-Score
   - ROC Curve and AUC Score for classification performance

## 🛠️ Installation & Usage
```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# Clone the repository
git clone <repo_url>
cd <repo_folder>

# Open Jupyter Notebook
jupyter notebook lung-cancer-analyze-predict-model-comparison.ipynb
```
## Conclusion:
- This study helps in identifying an optimal predictive model for lung cancer diagnosis.
- It can assist in early detection and improve patient outcomes.
