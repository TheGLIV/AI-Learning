Day 4 took me two days apparently. *sighs *

# Day 4: Machine Learning Basics with the Iris Dataset

## Goal

Learned and implemented the foundational concepts of supervised machine learning using the Iris dataset. Understood classification, model training, evaluation, and saving models.

---

## Dataset Used

**Dataset**: Iris Dataset (from `sklearn.datasets`)

It's about classifying flowers, already built-in.

## Steps Covered

### 1. Dataset Loading and Overview
- Loaded the Iris dataset from sklearn.
- Converted it to a pandas DataFrame.
- Displayed basic info using `.head()`, `.describe()`, and `.value_counts()`.

### 2. Feature and Target Selection
- Split the dataset into input features (`X`) and output target (`y`).

### 3. Model Selection and Training
- Chose `DecisionTreeClassifier` from `sklearn.tree`.
- Trained the model on the full dataset.

### 4. Model Prediction
- Used `.predict()` to make predictions on `X`.
- Displayed sample outputs and prediction logic.

### 5. Model Evaluation
- Used `accuracy_score` to calculate accuracy on the training set.
- Interpreted accuracy percentage.

### 6. Confusion Matrix
- Generated a confusion matrix using `confusion_matrix`.
- Displayed it visually using `ConfusionMatrixDisplay`.
- Understood true positives, false positives, and class-specific accuracy.

### 7. Cross-Validation
- Performed 5-fold cross-validation using `cross_val_score`.
- Computed and interpreted mean CV accuracy.

### 8. Model Saving
- Saved the trained model using `joblib`.
- Demonstrated how to load the saved model later for reuse.

---


---

## EOD Thoughts

This notebook covered the complete pipeline of supervised learning:
- Understanding the dataset
- Choosing a model
- Training and evaluation
- Using cross-validation for generalization
- Saving the model for deployment

We've built the foundation now.
Not beginners anymore.
Cheers!


---

Day 4 has been the most intensive yet. If you're reading this to get an overview ( it's good for an overview ), I suggest pausing and internalizing all that we've done today. I gotta take some time off too.

Cheers.