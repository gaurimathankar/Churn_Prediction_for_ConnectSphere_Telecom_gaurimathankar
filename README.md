

# Churn Prediction for ConnectSphere Telecom

## Project Overview

This project predicts whether a telecom customer will **churn (leave the company)** or not using an **Artificial Neural Network (ANN)**.
The dataset was provided during a live class session and slightly modified for experimentation.

---

## Business Context

**ConnectSphere Telecom**, a regional telecom provider, faces high customer churn, which directly impacts revenue.
To reduce churn, this project develops a **binary classification model** that identifies potential churners using customer account details and usage patterns.

The model supports the business by:

* Detecting customers with a high likelihood of leaving.
* Enabling **targeted retention strategies**.
* Improving customer satisfaction and reducing revenue loss.

---

## Objectives

* Develop an ANN-based binary classification model for churn prediction.
* Use features such as **call duration, data usage, and contract length**.
* Evaluate the model using **Accuracy and F1-Score**.
* Generate a list of **high-risk customers** for proactive retention.

---

## Dataset

* **Source**: Provided during live class session.
* **Features**: Call duration, Data usage, Contract length, Monthly charges, etc.
* **Target**: Churn (Yes / No).

---

## Technologies Used

* **Programming Language**: Python
* **Libraries**: Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Matplotlib, Seaborn
* **Platform**: Google Colab
* **Version Control**: GitHub

---

## Methodology

1. **Data Loading & Cleaning**

   * Handled missing values.
   * Encoded categorical variables.
   * Scaled numerical features for ANN input.

2. **Model Building**

   * ANN architecture with multiple **Dense layers**.
   * **ReLU activation** for hidden layers, **Sigmoid activation** for output layer.

3. **Training & Evaluation**

   * **Loss Function**: Binary Cross-Entropy.
   * **Optimizer**: Adam.
   * Evaluated using **Accuracy, F1-Score, and Confusion Matrix**.

4. **Output**

   * Model predicts **churn probability** for each customer.
   * Generated a **list of at-risk customers** for the business.

---

## Results

* **Accuracy**: 79.13%
* **F1-Score**: \~0.79 (balanced performance between precision and recall).
* **Confusion Matrix**: Showed strong ability to detect churn cases.
* Produced a **high-risk customer list** for proactive retention.

---

## Conclusion & Future Work

The ANN-based churn prediction model is effective in identifying at-risk customers and provides a strong foundation for churn management.

**Future Enhancements:**

* Hyperparameter tuning for better performance.
* Incorporating additional features (e.g., billing history, customer support logs).
* Deploying the model as a **real-time dashboard or API** for business use.

---

**Prepared by:**
Gauri Prashant Mathankar
(Completed as part of **YBI Foundation Internship Project**)


