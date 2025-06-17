# Kyphosis Disease Prediction using Random Forest

This project aims to predict the presence of **Kyphosis**, a spinal disorder, using a supervised machine learning approach. The dataset includes information about patients who have undergone corrective spinal surgery.

---

## 📊 Dataset

The dataset contains the following features:
- `Age`: Age of the patient (in months)
- `Number`: Number of vertebrae involved
- `Start`: Starting vertebrae of the curve
- `Kyphosis`: Target label — "present" or "absent"

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn (Random Forest, preprocessing, metrics)
- Imbalanced-learn (optional for SMOTE)

---

## 🧠 ML Approach

- Preprocessing:
  - Label encoding of target
  - Feature scaling (StandardScaler)
- Model:
  - `RandomForestClassifier` with class balancing
- Evaluation:
  - Accuracy, Confusion Matrix, Classification Report
- (Optional) Used `SMOTE` to handle class imbalance

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/kyphosis-prediction.git
   cd kyphosis-prediction
