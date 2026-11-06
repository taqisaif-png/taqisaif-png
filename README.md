# Hi, I'm Taqi Abusaif 👋

Master of Health Informatics @ University of Michigan | Clinical AI & NLP

## 🔬 Featured Projects

### [Cardiac Arrest Prediction](https://github.com/taqisaif-png/cardiac-arrest-prediction)
XGBoost model predicting in-hospital cardiac arrest from ED presentations, with a label audit that removes patients who arrested before arrival.
- **Data:** MIMIC-IV (19k patients) + eICU (86k) external validation
- **Label audit:** NLP arrest-time extraction (regex, Stanza) + 104 hand-reviewed notes + TF-IDF OHCA/IHCA filter (AUC 0.963)
- **Results:** IHCA-only AUC=0.814 vs ~0.51 for MEWS/NEWS early-warning scores
- **Tech:** Python, XGBoost, PyTorch, sentence-transformers, scikit-learn

### [Tweet Physical-Activity Classification](https://github.com/taqisaif-png/tweet-physical-activity-classification)
1st place in a class Kaggle NLP competition (LHS 712).
- **Results:** validation macro-F1 0.743 → 0.852 | Kaggle test macro-F1 0.888
- **Tech:** PyTorch, Twitter-RoBERTa, Hugging Face Transformers, TensorFlow

### [Omega Hospital Service Line Analysis](https://github.com/taqisaif-png/omega-hospital-service-line-analysis)
Team project (HMP 669): cleaned and joined a multi-table inpatient database (~16.8K admissions) to compare service lines.
- **Tech:** R (tidyverse), Python (pandas), automated pipeline verification

### [accdb-to-csv](https://github.com/taqisaif-png/accdb-to-csv)
Converts every table in a Microsoft Access database to CSV on macOS/Linux.

## 🛠️ Tech Stack
- **Languages:** Python, R, SQL
- **ML/DL:** XGBoost, scikit-learn, PyTorch, TensorFlow, Hugging Face
- **Clinical:** MIMIC-IV, eICU, Medical NLP, Class imbalance handling
- **Tools:** BigQuery, Git, Jupyter, R Markdown

## 📫 Connect
- **Email:** taqisaif@umich.edu
- **LinkedIn:** https://linkedin.com/in/taqi-abusaif-786903256
