#
---
# **Decision Tree Notes & Implementation**
---
This repository offers a comprehensive guide to understanding and implementing the **Decision Tree** algorithm using Python. It includes detailed notes, key concepts, and practical implementations for building classification models with decision trees.

---

## **1. Introduction to Decision Tree**
- **Decision Trees** are non-parametric supervised learning methods used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features.

---

## **2. Step-by-Step Example for Decision Tree**
- A **numerical example** demonstrating how a decision tree algorithm works is illustrated through a sequence of steps:
  - **Step 1** Start with the full dataset and calculate the entropy.
  - **Step 2** Split the dataset based on the feature with the highest information gain.
  - **Step 3-9** Repeat the process, splitting further, until the data is perfectly classified or meets a stopping criterion.
  - **Final Step** Result in a tree where each node represents a decision, and each leaf node represents a classification outcome.

---

## **3. Implementation of Decision Tree using Python**
1. **Dataset Preparation**
   - Import the dataset and split it into training, validation, and test sets using **train_test_split** from **sklearn**.

2. **Model Creation**
   - Use the **DecisionTreeClassifier** from **sklearn** with **entropy** as the criterion to train the model and predict outcomes on the validation set.
   - Repeat the process using **gini** as the criterion.

3. **Accuracy Check**
   - Evaluate the accuracy of both models using **accuracy_score**.

4. **Tree Visualization**
   - Visualize the trained decision trees using **plot_tree** from **matplotlib**.

---

## **Getting Started**
To run the code examples, make sure you have the required libraries installed:

```bash
pip install numpy pandas scikit-learn matplotlib
```
---

<div align="center"> Created by Ankit Dimri © 2024 </div>
---