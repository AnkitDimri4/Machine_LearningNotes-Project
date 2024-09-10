#
---
# **Apriori Algorithm and Evaluation Techniques**
---
This repository delves into the **Apriori Algorithm** and various **Evaluation and Validation Techniques** used in machine learning. It covers the fundamental concepts of the Apriori algorithm, its applications, and provides detailed examples. Additionally, it includes insights into evaluation metrics and validation techniques used to assess and improve model performance.

## **Apriori Algorithm**

### **Introduction**
The Apriori Algorithm is a prominent method for frequent pattern mining. It iterates through the dataset to generate itemsets using a bottom-up approach, leveraging prior knowledge about frequent itemsets.

#### **Applications**
- **Retail**: Bundling products like onions and potatoes to boost sales based on frequent co-purchases.
- **Healthcare**: Identifying adverse drug reactions by analyzing combinations of medications and patient characteristics.
- **Supermarkets**: Grouping items like bread, butter, and jam for convenience and to increase sales.

#### **Key Components**
- **Support**: Frequency of an itemset in the dataset.
- **Confidence**: Likelihood of items being purchased together.
- **Lift**: Measure of the increase in purchase likelihood of an item when another item is purchased.

#### **Example Calculation**
Consider 2000 transactions with 200 containing jam and 300 containing bread, including 100 with both.
- **Support (Jam)**: $$200 / 2000 = 0.10$$ (10%)
- **Confidence (Bread and Jam)**: $$100 / 200 = 0.50$$ (50%)
- **Lift**: $$Confidence(Bread and Jam) / Support(Jam) = 0.50 / 0.10 = 5$$

This indicates a 5 times greater likelihood of purchasing both items together compared to purchasing jam alone.

#### **How It Works**
The Apriori Algorithm operates through a series of steps:
1. Generate frequent itemsets using the support threshold.
2. Generate association rules based on confidence and lift.
3. Use these rules to find interesting patterns and relationships.

### **Flowchart of Apriori Algorithm**
Refer to the flowchart to visualize the step-by-step process of the Apriori algorithm.

### **Subset Creation**
Understand how subsets are created and filtered based on support thresholds and item frequency.

---

## **Evaluation and Validation Techniques**

### **Model Evaluation Dashboard**
This project involves creating a dashboard to evaluate and compare multiple machine learning models. It utilizes metrics like Accuracy, Precision, Recall, and F1-Score to provide a comprehensive view of model performance.

#### **Purpose**
- **Accuracy**: Measures the overall correctness of the model.
- **Precision and Recall**: Precision indicates the accuracy of positive predictions, while recall measures the ability to identify all relevant instances.
- **F1-Score**: Combines precision and recall into a single metric, useful for uneven class distributions.

#### **Application**
Use the Iris dataset to train and evaluate models such as Logistic Regression, SVM, and Decision Tree. Visualize the evaluation metrics to compare the performance of these models.

---

## **Additional Projects**

### **Market Basket Analysis**
Analyze transaction data using the Apriori algorithm to identify frequent itemsets and generate association rules. Applications include retail and healthcare, where understanding item co-purchases can provide actionable insights.

### **Model Evaluation Dashboard**
Create a dashboard to evaluate and compare machine learning models using default datasets like Iris. This helps in understanding model performance through metrics and visualizations.

### **Getting Started**

To run the code examples in this repository, make sure you have Python and the following libraries installed
```bash
pip install torch torchvision numpy matplotlib scikit-learn pandas mlxtend
```

This includes
- **torch** and **torchvision** for neural networks (if needed).
- **numpy** and **matplotlib** for numerical operations and plotting.
- **scikit-learn** for machine learning algorithms and evaluation metrics.
- **pandas** for data manipulation.
- **mlxtend** for the Apriori algorithm and association rules.

These installations will cover the requirements for both the Apriori Algorithm project and the Model Evaluation Dashboard project.
---

<div align="center">
    Created by Ankit Dimri  
    © 2024
</div>
