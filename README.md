[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rileybarka/Lab-3-Airbnb-Modeling-Classification/blob/main/notebooks/Lab3.ipynb)

# Lab 3: Classification Modeling with Decision Trees and KNN

This lab continues the machine learning lifecycle using the Airbnb NYC listings dataset. The focus is on the **modeling phase**: training and comparing Decision Tree and K-Nearest Neighbors (KNN) classifiers to solve a classification problem.

---

## Dataset Used

| Dataset | Description |
|---------|-------------|
| **Airbnb Listings NYC (Dec 2021)** | Modified Airbnb dataset from prior labs; used here to build labeled examples and train classification models. |

---

## Objectives

- Define the classification target (label) and select features  
- Prepare the data (one-hot encoding, train/test split)  
- Train multiple Decision Tree classifiers with varying `max_depth`  
- Train multiple KNN classifiers with different `k` values  
- Evaluate and compare model accuracies  
- Analyze which model/hyperparameters perform best and why  

---

## Methodology

1. **Data Loading & Label Definition**  
   - Load Airbnb listings  
   - Define what is being predicted (e.g., binary classification of high vs. low price, availability category, etc.)  
   - Choose relevant features  

2. **Data Preparation**  
   - One-hot encode categorical variables  
   - Construct labeled examples  
   - Split into training and test sets  

3. **Model Training**  
   - Decision Trees: train multiple classifiers varying `max_depth`  
   - KNN: train multiple classifiers varying `k`  

4. **Evaluation & Visualization**  
   - Compute accuracy (and optionally precision/recall/F1 if imbalanced)  
   - Plot accuracy vs. hyperparameter (`max_depth` for DT, `k` for KNN)  
   - Compare best-performing models  

5. **Analysis**  
   - Identify the best performing algorithm and hyperparameter settings  
   - Discuss additional factors or experiments that could improve the model (e.g., feature scaling, class balancing, other metrics)

---

## Key Findings (to fill after running)

- Best Decision Tree depth: ... (accuracy: ...)  
- Best KNN `k`: ... (accuracy: ...)  
- Preferred model and reasoning  
- Ideas for further improvement  

---

## Setup Instructions

### Option 1: Open in Google Colab  
Click the badge above.

### 🖥Option 2: Run Locally

```bash
git clone https://github.com/rileybarka/Lab-3-Airbnb-Modeling-Classification.git
cd Lab-3-Airbnb-Modeling-Classification/notebooks
jupyter notebook Lab3.ipynb
