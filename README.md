fMRI-Emotion-Detection
Overview
Project to detect emotions (Positive, Negative, Neutral) from fMRI data using machine learning. Analyzes BOLD signals from Right Cerebral Cortex. Models: Logistic Regression, SVM, Random Forest, KNN. Accuracy: 43.75%.
Dataset

OpenNeuro: ds005047 (Naturalistic Facial Expressions Dataset)
BIDS-compliant; focused on sub-01.

Requirements

Python 3.12+
Libraries: nibabel, nilearn, pandas, numpy, scikit-learn, matplotlib, seaborn

Install: pip install nibabel nilearn pandas numpy scikit-learn matplotlib seaborn
Files

emotion_fmri_analysis-checkpoint.ipynb: Main code for data processing, feature extraction, and ML models.
minor_project_report.pdf: Detailed project report.

Usage

Download dataset via DataLad.
Run notebook cells sequentially.
Adjust paths in Cell 2.

Future Work

Add more subjects.
Ensemble models.
Refine features.

License
MIT8sgive a small description of projectThought for 1m 41sThis project classifies emotional states (Positive, Negative, Neutral) from fMRI brain data using machine learning models (Logistic Regression, SVM, Random Forest, KNN), achieving 43.75% accuracy. It processes BOLD signals from the Right Cerebral Cortex with Python, scikit-learn, and nilearn, based on OpenNeuro dataset ds005047.82.1s
