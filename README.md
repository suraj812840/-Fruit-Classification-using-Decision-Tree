# -Fruit-Classification-using-Decision-Tree
This project focuses on building a Fruit Classification System using a Decision Tree Classifier. The model predicts the type of fruit (such as apple, banana, or orange) based on simple physical attributes like weight, texture, and color score.  Using the scikit-learn library, we train a decision tree on a labeled dataset and visualize here.
# 🍎🍌🍇 Fruit Classification using Decision Tree

## 📌 Project Overview

This project demonstrates how to use a **Decision Tree Classifier** to identify the type of fruit (like Apple, Banana, Orange, etc.) based on various features such as weight, texture, and color score. It is a beginner-friendly machine learning project that introduces classification using **scikit-learn**.

---

## 🎯 Objective

To build a machine learning model that can classify fruits using a **Decision Tree algorithm** based on their physical characteristics.

---

## 🧠 Machine Learning Algorithm Used

- **Decision Tree Classifier** from `scikit-learn`
- Simple, interpretable model that is perfect for visualization and understanding how decisions are made.

---

## 🧺 Dataset Details

- **Features Used:**
  - Weight (in grams)
  - Texture (Smooth = 1, Bumpy = 0)
  - Color Score (numeric value)

- **Target Labels:**
  - 0 = Apple
  - 1 = Orange
  - 2 = Banana
  - 3 = Other Fruit (optional)

- The dataset can be either synthetic or downloaded from [Kaggle] or created manually for learning purposes.

---


fruit-decision-tree/
├── fruit_data.csv              # Dataset used
├── decision_tree_fruit.ipynb   # Jupyter notebook with full ML pipeline
├── model/                      # Trained model files (optional)
├── images/                     # Plots and tree visualization
├── requirements.txt            # List of Python dependencies
└── README.md                   # Project documentation
