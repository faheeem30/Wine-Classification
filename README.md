

---

# Wine Classification (with Random Forest + GridSearchCV)

This project builds a **Wine Classification Model** using the famous **Wine Dataset** from Scikit-Learn.
It demonstrates a **complete real-world ML workflow**, including:

✔ Preprocessing
✔ Pipeline
✔ Random Forest Model
✔ Hyperparameter Tuning (GridSearchCV)
✔ Evaluation
✔ Saving the trained model

---

##  **Project Objective**

To classify wine into **one of three classes** (0, 1, 2) such as:

alcohol  ,malic_acid   ,ash  ,alcalinity_of_ash , magnesium  ,total_phenols
<img width="1226" height="730" alt="image" src="https://github.com/user-attachments/assets/c1078968-479a-4685-b0f4-6356b26f5f57" />
  

---

## **Dataset Information**

From the built-in Wine dataset:

```python
from sklearn.datasets import load_wine
```

### **Dataset Summary**

| Property | Value                         |
| -------- | ----------------------------- |
| Rows     | **178**                       |
| Features | **13 numerical**              |
| Classes  | **3**                         |
| Type     | **Multiclass Classification** |

---

## 🧠 **Technologies Used**

| Component                  | Purpose                   |
| -------------------------- | ------------------------- |
| **Python**                 | Core language             |
| **Scikit-Learn**           | ML models & preprocessing |
| **Pipeline**               | Automates scaling + model |
| **GridSearchCV**           | Hyperparameter tuning     |
| **RandomForestClassifier** | Final ML model            |
| **StandardScaler**         | Feature scaling           |
| **joblib**                 | Save trained model        |

---

## 🛠️ **Model Used**

This project uses:

### ✅ **RandomForestClassifier**

A powerful ensemble tree-based model widely used in industry because:

* Works well on tabular data
* Handles nonlinear patterns
* Robust to noise
* Does not require scaling (but pipeline includes it safely)

### And we use **GridSearchCV** to find BEST parameters automatically.

---

## 📈 **Results**

Accuracy typically reaches:

```
Accuracy: 1.00  
```

---

## 💾 **Saved Model**

The trained pipeline is saved as:

```
wine_pipeline.pkl
```
<img width="1185" height="772" alt="image" src="https://github.com/user-attachments/assets/65afe3d7-0423-4fc5-88fc-4e16a06f7755" />

