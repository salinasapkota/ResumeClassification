# Resume Classification (ML with Jupyter Notebook)

A machine learning model that classifies resumes into job categories.

## 🚩 Problem
Recruiters spend hours sorting resumes. This project automates classification using **NLP + ML** techniques.

## 🛠️ Approach
- Preprocessed text (tokenization, stopword removal, TF-IDF).
- Trained multiple classifiers (Logistic Regression, SVM).
- Selected the best model based on accuracy and F1 score.
- Evaluated performance using confusion matrix and metrics.

## ⚙️ Tech Stack
- Python (scikit-learn, pandas, NumPy, nltk)
- Jupyter Notebook

## ▶️ Run Locally
```bash
# Clone the repository
git clone https://github.com/salinasapkota/ResumeClassification
cd ResumeClassification

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook ResumeClassification.ipynb


# Launch demo
streamlit run app.py
