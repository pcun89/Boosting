# Boosting
# Boosting in Python (scikit-learn)

This project demonstrates how to apply **Boosting algorithms** (Gradient Boosting and AdaBoost) using Python’s `scikit-learn`.  
It covers **regression** and **classification** tasks with end-to-end steps: data preparation, model training, evaluation, and hyperparameter tuning.

---

## Project Structure

- **boosting_examples.py** — main script containing both regression and classification examples
- **Functions include:**
  - `prepareRegressionData()` — generate and preprocess regression dataset
  - `prepareClassificationData()` — generate and preprocess classification dataset
  - `trainGradientBoostingRegressor()` — train and tune a Gradient Boosting model
  - `evaluateRegressor()` — evaluate regression model with MSE, MAE, R²
  - `trainAdaBoostClassifier()` — train and tune an AdaBoost classifier
  - `evaluateClassifier()` — evaluate classification model with accuracy, precision, recall, F1
  - `main()` — orchestrates the workflow and prints summary metrics

---

## Requirements

- Python 3.8+
- Libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `scipy`

Install dependencies:

```bash
pip install numpy pandas scikit-learn scipy
