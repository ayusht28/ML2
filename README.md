 # 💳 UPI Fraud Detection using Machine Learning

This project analyzes UPI transactions and uses machine learning algorithms to detect and classify fraudulent transactions.

---

## 📊 Project Highlights

- ✅ Detects UPI fraud in real-time using trained ML models
- ✅ Compares performance of multiple classifiers
- ✅ Visualizes metrics like F1 score, accuracy, confusion matrix
- ✅ Interactive visualization using Plotly

---

## 🧠 Machine Learning Models Used

Random Forest, XGBoost, Decision Tree, Gradient Boosting

Each model's performance is evaluated using metrics such as Accuracy, Precision, Recall, F1 Score, and ROC AUC.

---

## 🧰 Libraries & Tools

matplotlib, numpy, pandas, plotly, scikit-learn, seaborn, xgboost

---

## 📂 How to Run

1. Clone this repository and open `upi_fraud_detection.ipynb` in Jupyter or VS Code.
2. Ensure your system has required packages installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn plotly xgboost joblib
   ```
3. Place your dataset in the working directory (e.g., `upi_transactions.csv`).
4. Run all cells to train, evaluate, and visualize model performance.

---

## 📌 Dataset

A labeled dataset with UPI transaction metadata and a target `is_fraud` column is used.
Example features: amount, UPI handle age, location, category, etc.

---

## 📊 Sample Output

- 📈 F1 Score comparison bar chart (Plotly)
- 📉 Confusion matrix heatmaps (Seaborn)
- 🏆 Model selection based on performance

---
![fraud vs count](https://github.com/user-attachments/assets/25db358f-eda8-4ab7-9dcb-1546c6cd31de)


![Visualising entire dataset](https://github.com/user-attachments/assets/82ef9360-bbf1-488f-936d-9e91ef0cdbcd)

![F1 Score vs Models](https://github.com/user-attachments/assets/39bce75f-aa4e-49fd-b036-050b54e42281)


## 👨‍💻 Author


Created for hackathons and academic demonstration.

