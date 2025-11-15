# EthicalAI
Ethics

# Ethical AI: Fairness and Explainability on UCI Adult Income

## Overview
Logistic regression with scikit-learn, fairness evaluation with Fairlearn, and explanations with SHAP and LIME.

## Setup
- Python 3.10+
- `pip install -r requirements.txt`
  - fairlearn
  - shap
  - lime
  - scikit-learn
  - pandas
  - numpy
  - matplotlib

## How to run
1. Open `notebook.ipynb` (or Colab).
2. Run all cells to:
   - Load and clean the Adult dataset.
   - Train the model.
   - Print accuracy, confusion matrix, and classification report.
   - Compute fairness metrics with `MetricFrame`.
   - Render SHAP summary and sample local explanations.
   - Render LIME local explanation.

## Deliverables
- `notebook.ipynb` and exported `notebook.pdf`
- `report.pdf` (3 pages)
- `figures/` with saved plots (optional)

## Notes
- Sensitive feature: `sex`.
- Key fairness metrics: selection rate, FPR, TPR by group.
- Mitigations to try: remove `sex`, threshold tuning, Fairlearn constraints.
