#
---
# **Naive Bayes Classifier & K-Nearest Neighbours (KNN) Notes & Implementation**
---

This repository offers a comprehensive guide to understanding and implementing the Naive Bayes Classifier and K-Nearest Neighbours (KNN) algorithms using Python. It includes detailed notes, key concepts, and practical implementations.

## **Contents**

### **1. Introduction to Naive Bayes Classifier**
- **Overview**
  - Naive Bayes is a supervised learning algorithm based on **Bayes' Theorem**, which calculates the probability of a hypothesis given prior knowledge.
  - The algorithm assumes that the features are independent, a condition often referred to as "naive" but effective in practice.

- **Bayes' Theorem Formula**
  $$P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}$$
  - This formula calculates the probability of event A given that B is true.

- **Working**
  1. **Frequency Tables** Calculate the frequency of class labels for each feature.
  2. **Likelihood Tables** Compute the likelihood of each feature value given a class label.
  3. **Prediction** Apply Bayes' Theorem to predict the class with the highest posterior probability.

### **2. Introduction to K-Nearest Neighbours (KNN)**
- **Overview**
  - KNN is a simple, yet powerful, supervised learning algorithm used primarily for classification by considering the majority vote of a data point's nearest neighbors.

- **How KNN Works**
  - The algorithm calculates the distance (usually Euclidean) between the query point and all other data points.
  - The query point is classified into the class that is most common among its k nearest neighbors.

- **Choosing k**
  - The choice of k is critical, a small k can lead to overfitting, while a large k can cause underfitting. The optimal k is usually determined by testing different values.

## **Getting Started**
To replicate the implementations in this repository, make sure you have Python installed along with the required libraries. You can install them using the following command

```bash
pip install numpy pandas matplotlib scikit-learn seaborn
```

Explore the repository to gain a thorough understanding of Naive Bayes and KNN, their implementations, and practical use cases.

---

<div align="center">
    Created by Ankit Dimri  
    © 2024
</div>
