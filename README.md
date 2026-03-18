Customer Purchase Prediction using Logistic Regression
 Project Overview

This project predicts whether a customer will purchase a product based on their **Age** and **Estimated Salary** using a **Machine Learning model (Logistic Regression)**.

It is a beginner-friendly data science project demonstrating the complete pipeline:

* Data loading
* Preprocessing
* Model training
* Prediction
* Evaluation

---

 Problem Statement

Given customer data, predict:

> Will the customer buy the product or not?

---

 Dataset

* File: `ad_dataset.csv`
* Features:

  * Age
  * Estimated Salary
* Target:

  * Purchased (0 = No, 1 = Yes)

---

 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---
 Workflow

 1. Data Loading

Dataset is loaded using Pandas.

2. Data Preprocessing

* Split into input (X) and output (Y)
* Train-test split (75% training, 25% testing)

3. Feature Scaling

Standardization using `StandardScaler`

4. Model Training

* Algorithm: Logistic Regression
* Library: Scikit-learn

5. Prediction

* Predict for:

  * New customer input
  * Test dataset

6. Evaluation

* Accuracy Score
* Confusion Matrix

---

How to Run

Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/customer-purchase-prediction.git
cd customer-purchase-prediction
```

Step 2: Install Dependencies

```bash
pip install pandas numpy scikit-learn
```

Step 3: Run the Script

```bash
python main.py
```

---

Example Input

```text
Enter New Customer Age: 35
Enter New Customer Salary: 50000
```

Output

```text
Customer will Buy
```

---

 Sample Output

Predicted vs Actual:

```
[[1 1]
 [0 0]
 [1 1]
 [0 0]]
```

---

 Model Performance

* Accuracy: ~85% (depends on dataset)

---



