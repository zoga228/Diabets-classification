# Logistic Regression From Scratch — Learning Archive

An early NumPy/Python exercise implementing sigmoid prediction and gradient-descent updates for a diabetes-classification dataset.

`diabet.ipynb` expects a local `diabets/diabetes.csv` with eight features and a target. The data is not bundled. The notebook normalizes using all rows and computes accuracy on its training rows; its printed accuracy **is not a held-out generalization estimate**. This is a historical learning artifact, not a validated clinical model.

A proper follow-up needs a split before fitting preprocessing, a training-only imputer/scaler, validation-selected hyperparameters and an untouched test set. Recent implementations of reliable evaluation are in [Validation Stress Lab](https://github.com/zoga228/validation-stress-lab).
