# **MODULE 14: LOGISTIC REGRESSION**

## **PROJECT DESCRIPTION**
This repository contains a Google Colab notebook titled **"Module 14: Logistic Regression"**, which provides a comprehensive introduction to logistic regression.  
The notebook progresses from theoretical foundations to real-world implementation and evaluation, with a strong focus on classification metrics and decision thresholds.

---

## **OBJECTIVE**
The goal of this notebook is to:
- Explain how logistic regression works
- Demonstrate probability-based classification
- Apply logistic regression to real datasets
- Evaluate classification performance using multiple metrics
- Analyze the impact of decision thresholds on model behavior

---

## **PROJECT STRUCTURE**

### **SECTION 0: SETUP**
- Import required libraries:
  - `NumPy`
  - `Pandas`
  - `Matplotlib`
  - `scikit-learn`
- Configure the environment for data analysis and visualization

---

### **SECTION 1: INTRODUCTION TO LOGISTIC REGRESSION (TOY EXAMPLE)**
- Use a simple toy dataset:
  - **Feature:** hours studied
  - **Target:** pass / fail exam
- Train a logistic regression model
- Demonstrate that logistic regression:
  - Predicts **probabilities**
  - Produces **binary classifications** using a threshold
- Compare logistic regression behavior with linear regression

---

### **SECTION 2: SIGMOID FUNCTION & CLASSIFICATION INTUITION**
- Define the **sigmoid function**
- Visualize how the sigmoid maps real values to probabilities between **0 and 1**
- Explain:
  - Probability interpretation
  - Decision thresholds
  - How probabilities are converted into class labels

---

### **SECTION 3: LOGISTIC REGRESSION ON A REAL DATASET**
- Use the **Breast Cancer dataset** from `scikit-learn`
- Perform:
  - Data loading
  - Exploratory Data Analysis (EDA)
- Scale features for model training
- Train a logistic regression classifier
- Evaluate model performance using:
  - Accuracy
  - Confusion matrix
  - Classification report

---

### **SECTION 4: EVALUATION METRICS & THRESHOLD EFFECTS**
- Calculate and analyze:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Explore how changing the **classification threshold** affects:
  - Precision–Recall trade-off
- Present results using:
  - Tabular comparisons
  - Visualizations of metric changes across thresholds

---

## **DATASETS USED**
- **Toy Dataset** (synthetic example for intuition)
- **Breast Cancer Dataset**
  - Source: `sklearn.datasets.load_breast_cancer`

---

## **TECHNOLOGIES USED**
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **scikit-learn**
- **Google Colab**

---

## **HOW TO RUN**
1. Open the notebook in **Google Colab** or **Jupyter Notebook**.
2. Run all cells sequentially.
3. No external data downloads are required.

---

## **LEARNING OUTCOMES**
By completing this notebook, you will understand:
- How logistic regression performs binary classification
- The role of the sigmoid function in probability estimation
- How evaluation metrics differ for classification problems
- Why adjusting the classification threshold matters in real-world applications
