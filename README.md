# SCSE3040 MLOps Practical 04

## From Notebook to Package

This practical converts the food delivery-time prediction workflow from a notebook into a reusable Python package.

### Objective

The objective is to organize machine learning code into separate Python modules and run the workflow from the command line without depending on a notebook.

### Package Structure

```text
work/
├── delivery/
│   ├── __init__.py
│   ├── data.py
│   ├── features.py
│   ├── model.py
│   └── validate.py
├── model.joblib
├── train.py
└── predict.py
