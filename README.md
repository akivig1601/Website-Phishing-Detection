# 🕵️‍♀️ Phishing Website Detection using Machine Learning

This project uses supervised machine learning to detect phishing websites based on real data from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/327/phishing+websites). Built using Python, scikit-learn, and trained in Google Colab.

---

## 📦 Dataset

- **Source**: UCI ML Repository  
- **Dataset Name**: Phishing Websites Dataset  
- **Accessed via**: `ucimlrepo` Python package  
- **Number of Features**: 30  
- **Target Variable**: `Result` →  
  - `-1` or `0`: Phishing website  
  - `1`: Legitimate website

---

## 🧪 Project Objectives

- Detect phishing websites using supervised learning.
- Train and compare models (Random Forest, etc.).
- Evaluate accuracy and generate confusion matrix.

---

## 📊 Model Performance

| Model             | Accuracy  |
|------------------|-----------|
| Random Forest     | ✅ ~93%   |

- Balanced precision/recall
- Low false positives
- Excellent for binary classification

---

## 🛠️ Tech Stack

- Python 3
- Google Colab
- `ucimlrepo`
- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`

---

## 📈 Outputs

- Confusion Matrix
- Classification Report
- Accuracy Score
- Feature/target preview
- Cleaned code in `.ipynb` format

---

## 🚀 How to Use

1. Clone this repository or download the notebook
2. Run the notebook in [Google Colab](https://colab.research.google.com/)
3. Install the dataset loader:
   ```bash
   pip install ucimlrepo
