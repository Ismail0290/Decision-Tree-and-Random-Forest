# Decision Trees & Random Forests - Heart Disease Dataset

## 📌 Objective
Implement tree-based models (Decision Tree & Random Forest) for classification using the Heart Disease dataset, visualize the decision tree, analyze overfitting, and evaluate model performance.

## 🛠 Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (DecisionTreeClassifier, RandomForestClassifier, cross_val_score)
- Graphviz (Tree visualization without node overlap)

## 📂 Steps Performed
1. **Data Loading & Preprocessing**
   - Loaded dataset from CSV.
   - Checked for missing values and separated features (X) and target (y).

2. **Model Training**
   - Trained a Decision Tree Classifier and visualized it using both Matplotlib and Graphviz.
   - Controlled overfitting by setting `max_depth`.

3. **Random Forest Classifier**
   - Trained and compared accuracy with Decision Tree.
   - Extracted and plotted feature importances.

4. **Evaluation**
   - Used accuracy score, classification report, and confusion matrix.
   - Performed 5-fold cross-validation for reliable performance measurement.

## 📊 Results Summary
- **Decision Tree**: Easily interpretable but prone to overfitting if not pruned.
- **Random Forest**: Better accuracy and generalization.
- **Feature Importances**: Help identify most relevant predictors for heart disease.

