# VibAnalyzer

This project leverages machine learning techniques to classify faults in induction motors, aiming to improve predictive maintenance and enhance industrial reliability. The model diagnoses 10 distinct machine states (including healthy) with high accuracy using real-time signal data.

## 🔍 Key Features

- Achieved **up to 93% accuracy** across 10 machine states using advanced ML classifiers.
- Employed **5 statistical features** and **spectral analysis** for automated feature extraction.
- Utilized **Random Forest** and **Gradient Boosting** models with **5-fold cross-validation** for reliable performance.
- Applied a **sliding window technique** to augment training data without using synthetic oversampling (e.g., SMOTE).
- Demonstrated effective fault detection in cases like **imbalance, misalignment, broken bars, and bearing faults**.

## 🧠 Technologies Used

- Python
- Scikit-learn
- NumPy
- Matplotlib
- Gradient Boosting
- Spectral Analysis (via SciPy)


