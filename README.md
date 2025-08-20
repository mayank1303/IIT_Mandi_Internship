---

## 🧠 Problem Background

In supervised classification, performance depends heavily on whether data is **separable** (a perfect linear boundary exists) or **non-separable** (classes overlap). This project explores both regimes on:
- **Image datasets** — high-dimensional features that often require non-linear decision boundaries.
- **Numerical/tabular datasets** — linear models can excel when classes are well separated.

---

## 🧪 Methods (high-level)

- **Linear baselines:** Logistic Regression, Linear SVM  
- **Non-linear models:** Kernel SVM, shallow Neural Networks  
- **Metrics:** Accuracy, Precision, Recall, F1-score, Confusion matrices  
- **Setup:** Train/validation/test splits, standardization; image augmentation (if used)

> For full details, see the [Final Internship Report](./Final%20Internship%20Report.pdf).

---

## 📈 Key Findings

- Linear models perform strongly on **linearly separable** data with wide margins.  
- **Non-separable** cases benefit from added capacity or kernel methods with appropriate regularization.  
- There is a dataset-dependent trade-off between margin maximization and overfitting.

---


