# Mushroom-Classification-and-Analysis
Machine Learning model to classify mushrooms as edible or poisonous using physical features. Built with Python, Scikit-Learn &amp; Streamlit.
# 🍄 Mushroom Classification and Analysis

An end-to-end Machine Learning project to classify mushrooms as **Edible or Poisonous** based on their physical characteristics.

### 📌 Problem Statement
Eating a poisonous mushroom by mistake can be fatal. This project analyzes mushroom features like cap-shape, odor, gill-color, etc., and predicts whether a mushroom is safe to eat.

### 📊 Dataset
- Source: UCI Mushroom Dataset
- 8124 instances, 22 categorical features
- Target Column: `class` (e = edible, p = poisonous)

### ⚙️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Models Used:** Logistic Regression, Decision Tree, Random Forest, XGBoost
- **Deployment:** Streamlit / Flask (optional)

### 🔬 Workflow
1.  **Data Cleaning & EDA** - Checked null values, balanced data, visualized feature distribution
2.  **Encoding** - Label Encoding for all categorical columns
3.  **Model Training** - Trained and compared multiple classifiers
4.  **Evaluation** - Accuracy, Precision, Recall, Confusion Matrix
5.  **Prediction** - Model predicts Edible vs Poisonous

### 📈 Results
- **Best Model:** Random Forest Classifier
- **Accuracy:** ~100% on test data
- Key features affecting result: odor, spore-print-color, gill-size

### 🚀 How to Run Locally
```bash
# Clone the repo
git clone https://github.com/your-username/Mushroom-Classification.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook / app
jupyter notebook
# or
streamlit run app.py
