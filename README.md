# Classification-Using-Decision-Tree-A-Supervised-Learning-Project.

This project demonstrates how to use the **Decision Tree** algorithm for classification tasks using Python. It covers everything from loading and preparing data to training, predicting, and evaluating a machine learning model.

---

## 📊 Project Overview

In this project, we:
- Preprocess and explore a dataset
- Build a decision tree model using `sklearn`
- Visualize the decision tree structure
- Evaluate the classification performance using multiple metrics

---## 🛠 Tools & Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **Libraries**:
  - `pandas`, `numpy` – data handling
  - `matplotlib`, `seaborn` – data visualization
  - `sklearn` – model building and evaluation

## 🚀 Workflow

1. **Import Libraries**  
   Imported all necessary packages.

2. **Load Dataset**  
   Used `pandas` to read the dataset (CSV, Excel, or in-built dataset).

3. **Data Exploration**  
   - Checked for null values
   - Explored class distribution
   - Visualized key features and relationships

4. **Data Preprocessing**  
   - Handled missing values
   - Encoded categorical variables (if any)
   - Performed train-test split

5. **Model Building**  
   - Trained a `DecisionTreeClassifier` from `sklearn.tree`
   - Tuned parameters like `max_depth`, `criterion`, etc.

6. **Model Evaluation**  
   - Evaluated using:
     - **Accuracy**
     - **Precision, Recall, F1-Score**
     - **Confusion Matrix**
     - **ROC-AUC Curve** (if binary classification)

7. **Visualization**  
   - Plotted the decision tree structure using `plot_tree`  
   - Showed feature importance

## 📈 Example Results (replace with your real values)
- **Accuracy**: 91%
- **F1-Score**: 0.89
- **Top Features**: Age, Income, Marital Status
