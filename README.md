# Explainable AI applications for Neurological Disorders classification and prediction models.

![Abstract Artwork](https://images.unsplash.com/photo-1590859808308-3d2d9c515b1a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1174&q=80
)

## Thesis Project, Newcastle University

This repository contains all the code and notes for my thesis project, which studies the use of explainable AI (XAI) tools within neurological disorders classification and prediction models. The aim of this project is to explore and identify the ways that neurological disorders diagnosis can be benefit from machine learning models that include explainability attributes, in order to explain visually or numerically the reasons behind classification or prediction decisions.

## Data

The datasets used in this project are the following:

- Alzheimer's Stage Classification: [Kaggle](https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images )
- Stroke Prediction: [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- Parkinson's Recognition Using Voice Frequencies: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Parkinson%27s+Disease+Classification#)
- Epileptic Seizure Classification: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Epileptic+Seizure+Recognition)

## Repository Structure

```
├── Interim Report Final.pdf
├── Parkinson_Classification_and_XAI.ipynb (Used in Final Study | Parkinson's Data Processing, Classifiers, LIME and EBM Explanations)
├── README.md
├── SeizuresPrediction_EBM.ipynb (Used in Final Study | Notebook for Epilepsy Prediction using EBM and InterpretML visualisations)
├── alzheimerVGG19_and_XAI.ipynb (VGG19 Model for Image Classification for Alzheimer's, including GRAD-CAM function)
├── alzheimercnn-and-xai.ipynb (Used in Final Study | CNN model for Alzheimer's Classification, including GRAD-CAM function)
└── strokeModels_and_XAI.ipynb (Used in Final Study | Stroke Data Analysis, Classifiers and SHAP, LIME, ELI5 Explanations)
```

All notebooks can be executed on Google Colab, or Kaggle to test visualisation on custom inputs from the datasets linked above. 


