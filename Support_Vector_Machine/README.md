#
---
# **Support Vector Machine**

---
This repository provides an introduction to Support Vector Machines (SVM), covering their theoretical aspects, implementation in Python using **scikit-learn**, and practical applications. The SVM algorithm outputs an optimal hyperplane to classify new data points and is widely used for classification tasks.

## **Contents**

### **Introduction to Support Vector Machine (SVM)**
- A Support Vector Machine (SVM) is a discriminative classifier that works by finding the optimal hyperplane separating data into different classes.
- SVM is widely used in classification tasks, including **face detection**, **text categorization**, **handwriting recognition**, and more.

- **Choosing the Optimal Hyperplane**
  - SVM finds the hyperplane that maximizes the margin between different classes. Various kernels help in finding the ideal hyperplane for both linear and non-linear data.

### **Kernels in SVM**
- **Linear Kernel**
- **Non-Linear Kernel**
- **Radial Basis Function (RBF)**
- **Sigmoid**
- **Polynomial**
- **Exponential**

### **Advantages of SVM**
- Works well with a clear margin of separation.
- Effective in high-dimensional spaces and when the number of dimensions exceeds the number of samples.
- Memory efficient as it uses a subset of training points (support vectors).

### **Disadvantages of SVM**
- Training time is high for large datasets.
- Less effective with noisy datasets and overlapping target classes.
- Probability estimates require costly five-fold cross-validation.

### **Applications of SVM**
- **Face Detection**
- **Text and Hypertext Categorization**
- **Image Classification**
- **Bioinformatics**
- **Handwriting Recognition**
- **Protein Fold Detection**

## **Implementation of Support Vector Machine in Python**
This section provides the steps to implement SVM in Python using the **breast cancer dataset** from **scikit-learn**. 

- **Dataset** The dataset used is the breast cancer dataset from **sklearn.datasets**.
- **Preprocessing** The dataset is standardized using **StandardScaler()** to improve the model's performance.
- **Model** The Support Vector Classifier (**SVC()**) is used with a linear kernel to classify the data.
- **Evaluation** The model's performance is measured using **accuracy score** from the **metrics** module.

### **Required Libraries**
Make sure that you have Python installed along with the following libraries

```bash
pip install numpy pandas matplotlib scikit-learn
```
---

<div align="center"> Created by Ankit Dimri © 2024 </div> 

