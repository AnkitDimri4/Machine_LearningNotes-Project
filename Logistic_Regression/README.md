#
---
# **Logistic Regression Notes & Projects**

---
This repository offers a comprehensive guide to understanding and implementing Logistic Regression, both with **scikit-learn** and from scratch using Python. It includes detailed notes, code examples, and practical applications.

## **Contents**

### **1. Understanding the Cost Function for Logistic Regression**
- **Cost Function in Linear Regression**
  - Explanation of the Mean Squared Error (MSE) as used in linear regression, comparing it with logistic regression's cost function.
  
- **Cost Function in Logistic Regression**
  - Introduction to **Log Loss** or **Binary Cross-Entropy** used in logistic regression, emphasizing its role in penalizing incorrect predictions.

- **Final Cost Function**
  - Overview of the cross-entropy loss function, with emphasis on minimizing it using the **gradient descent** algorithm.

### **2. Implementation of Logistic Regression using sklearn in Python**
- **Importing Libraries**
  - Overview of libraries required for data visualization and model creation, including **matplotlib.pyplot**, **seaborn**, and **LogisticRegression** from **scikit-learn**.

- **Dataset Preparation and Visualization**
  - Loading the **Iris dataset** and visualizing feature relationships through scatter plots.

- **Model Creation, Training, and Evaluation**
  - Steps to create, train, and evaluate a logistic regression model using **LogisticRegression()**, with a focus on metrics like accuracy, precision, recall, and F1-score.

### **3. Implementation of Logistic Regression without using sklearn in Python**
- **Sigmoid Function**
  - Introduction to the sigmoid function for converting model outputs into probabilities.

- **Loss Function**
  - Explanation of the square loss function, with notes on cross-entropy as a more commonly used alternative.

- **Gradient Descent**
  - Detailed implementation of gradient descent to update weights and biases, supported by mathematical formulas and examples.

- **Prediction**
  - Process for making predictions on the test set using the trained model.

## **Getting Started**
To replicate the code examples in this repository, make sure you have Python installed along with the required libraries. You can install them using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn
```

Explore the different sections to gain a thorough understanding of Logistic Regression and how to implement it for various datasets and scenarios.

---

<div align="center">
    Created by Ankit Dimri  
    © 2024
</div>