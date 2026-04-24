# Lab-9
# Loan Classification using Decision Tree & Random Forest

## Overview

This project predicts whether a loan will be fully paid or not using:

* Decision Tree
* Random Forest

---

## Steps

* Load and explore the dataset
* Perform basic data visualization (EDA)
* Convert categorical features (`purpose`) into dummy variables
* Split data into training and testing sets
* Train both models
* Evaluate using confusion matrix and classification report

---

## Results

* **Decision Tree**: Better at detecting unpaid loans (class 1)
* **Random Forest**: Higher overall accuracy but poor recall for class 1

Example Confusion Matrix (Random Forest):

```
[[2427    4]
 [ 438    5]]
```

---

## Conclusion

Although Random Forest achieved higher accuracy, the Decision Tree performed better for identifying unpaid loans, making it more useful for this task.

---

## Tools Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
