
# Task 5 - Decision Trees and Random Forests

## 📌 Objective
This project implements **Decision Tree** and **Random Forest** classifiers using the Heart Disease dataset.  
The goal is to understand tree-based models, evaluate their performance, and visualize their decision-making process.

## 📂 Files in This Repository
- `task5_decision_tree_random_forest.ipynb` → Jupyter Notebook with complete code and explanations
- `decision_tree_graph.png` → Graphviz visualization of the Decision Tree
- `feature_importance.png` → Feature importance plot from Random Forest
- `heart.csv` → Dataset used for training and testing

## 🛠 Tools & Libraries
- Python 3
- pandas, numpy, matplotlib
- scikit-learn
- graphviz

## 📊 Steps Performed
1. **Load & Explore Data**
   - Loaded `heart.csv` into pandas DataFrame
   - Checked data types, missing values, and summary statistics

2. **Train Decision Tree Classifier**
   - Split dataset into training and testing sets (80%-20%)
   - Trained a Decision Tree Classifier using scikit-learn
   - Visualized the tree using Graphviz

3. **Overfitting Analysis**
   - Compared performance of Decision Tree with different `max_depth` values
   - Observed train vs test accuracy to understand overfitting

4. **Train Random Forest Classifier**
   - Trained with 100 estimators
   - Compared accuracy with Decision Tree

5. **Feature Importances**
   - Extracted feature importances from Random Forest
   - Plotted the importance ranking

6. **Cross-validation**
   - Performed 5-fold cross-validation to get reliable performance estimates

## 📈 Results
- **Decision Tree Accuracy (Test)**: ~ (depends on run, see notebook)
- **Random Forest Accuracy (Test)**: ~ (depends on run, see notebook)
- Random Forest performed better and generalized more effectively
- Most important features (Random Forest):
  1. `cp` (Chest Pain type)
  2. `thalach` (Maximum Heart Rate)
  3. `oldpeak` (ST depression)

## 📷 Visualizations
- Decision Tree Graph → `decision_tree_graph.png`
- Feature Importance Plot → `feature_importance.png`
