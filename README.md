# Customer Churn Prediction

A machine-learning notebook project built around the bundled `Churn_Modelling.csv` dataset.

## Repository contents

- `Customer_Churn_Prediction.ipynb` — the analysis and model-development notebook
- `Churn_Modelling.csv` — the dataset used by the notebook

Keeping the data beside the notebook makes the project easy to inspect and reproduce from a fresh checkout.

## Getting started

1. Clone the repository and enter the project directory.
2. Create a Python environment of your choice.
3. Open `Customer_Churn_Prediction.ipynb` in Jupyter Notebook, JupyterLab, VS Code, or another compatible notebook environment.
4. Install the Python packages imported by the notebook if they are not already available.
5. Run the notebook from top to bottom with `Churn_Modelling.csv` kept in the repository root.

## Reproducibility

The notebook is the source of truth for the current workflow and dependencies. When changing the analysis, rerun all cells in a clean kernel and confirm that the notebook can still read the bundled dataset from a fresh checkout.

## Validation guidance

For model or preprocessing changes, record the evaluation metric produced by the notebook and compare it with the previous result. Avoid putting performance numbers in project documentation unless they come from a reproducible run.

## Future improvements

Useful next steps include adding a pinned dependency file, automated dataset/schema checks, reusable training code, and regression tests as the notebook workflow is modularized.
