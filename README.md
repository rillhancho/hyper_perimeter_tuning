# 🔍 GridSearchCV: Hyperparameter Tuning with SVM & Random Forest

This repository contains a Jupyter Notebook (`gridsearchcv.ipynb`) that demonstrates how to use `GridSearchCV` and `RandomizedSearchCV` from `scikit-learn` to fine-tune hyperparameters for two classification models:

- Support Vector Machine (SVM)
- Random Forest Classifier

## 📂 File Structure

```
📦gridsearchcv_project/
 ┣ 📄gridsearchcv.ipynb
 ┗ 📄README.md
```

## 🧠 What You'll Learn

- Defining parameter grids for `GridSearchCV` and `RandomizedSearchCV`
- Performing cross-validation
- Comparing models based on mean test scores
- Visualizing results using pandas DataFrames

## 📦 Requirements

Install dependencies using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
```

## 🚀 How to Run

1. Clone the repository or download the `.ipynb` file.
2. Launch Jupyter Notebook:

```bash
jupyter notebook gridsearchcv.ipynb
```

3. Run all cells sequentially.

## 🧪 Models Tuned

### ✅ Support Vector Machine (SVM)
Parameters tuned:
- `C`: [1, 10, 20]
- `kernel`: ['rbf', 'linear']
- `gamma`: ['auto']

### 🌲 Random Forest
Parameters tuned (example):
- `n_estimators`
- `max_depth`
- `criterion`

> Note: Parameters may be reduced for faster execution on local machines.

## 📊 Output

- Best parameters for each model
- Performance comparison using a DataFrame:
  - `param_C`, `param_kernel`, `mean_test_score`
- Visual representation of model performance (optional)
