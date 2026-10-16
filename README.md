# Penguin Species Classifier

An interactive machine learning demo built with Streamlit and scikit-learn. Adjust a penguin's measurements and categorical features to explore a random forest prediction and class probabilities.

**Project type:** learning demo.

## What it demonstrates

- Loading and exploring a CSV dataset with pandas.
- Encoding categorical inputs consistently with the training data.
- Training a random forest classifier.
- Presenting predictions and probabilities in a small interactive interface.

## Run locally

From this repository's root, create a Python environment and run:

```bash
python -m pip install -r requirements.txt
streamlit run streamlit_app.py
```

The bundled dataset is `data/penguins_cleaned.csv`.

## Files

| Path | Purpose |
|---|---|
| `streamlit_app.py` | Data exploration, input controls, model training and predictions |
| `data/` | Penguin dataset |
| `requirements.txt` | Python dependencies |
| `environment.yml` | Environment configuration |

## Scope

The model is fitted during the app run. The app does not implement a held-out evaluation, calibrated confidence estimates, a persisted model or a production inference service. Prediction probabilities should be interpreted as model outputs, not validated accuracy.

Part of [Zohaib Jan's portfolio](https://github.com/zohaibjan).
