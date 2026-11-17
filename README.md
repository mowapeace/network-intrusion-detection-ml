# Network Intrusion Detection System (ML Comparative Analysis)

## Project Overview

This project compares multiple machine learning algorithms for detecting network intrusions using the UNSW-NB15 dataset.

## Algorithms Implemented

- Logistic Regression
- Decision Tree
- Random Forest
- KNN
- Gradient Boosting
- Naive Bayes

## Methodology

- Data preprocessing and feature selection
- Multiple train-test splits (60/40, 70/30, 80/20, 90/10)
- Cross-validation
- Evaluation using Accuracy, Precision, Recall, F1-score
- Confusion matrices and ROC curves

## Tools Used

- Python
- Scikit-learn
- Pandas
- Matplotlib

  ## Results

**Best model: Random Forest**

| Metric | Score |
|---|---|
| Accuracy | 99.46% |
| Precision | 98.76% |
| Recall | 98.59% |
| F1-score | 98.67% |

**Key findings:**
- Random Forest, Decision Tree and Gradient Boosting all performed strongly, with scores of about 98–99% across all metrics.
- KNN performed well on accuracy (about 97%) but had a lower F1-score (about 92%).
- Logistic Regression and Naive Bayes performed worst. Naive Bayes had high recall but very low precision, meaning it raised many false alarms.

## How to Run

1. Open `Intrusion_detection_project.ipynb` in Google Colab.
2. Download the UNSW-NB15 dataset (files `UNSW-NB15_1.csv` to `UNSW-NB15_4.csv`) from the official UNSW website.
3. Upload the CSV files to a Google Drive folder at `MyDrive/IDSDataset`.
4. Install the required libraries: `pip install -r Requirement.txt`
5. Run all cells.

## Author

Adeboye Mowafoluwa peace
