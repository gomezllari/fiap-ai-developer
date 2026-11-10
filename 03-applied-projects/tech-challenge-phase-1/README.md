# Machine Learning for Clinical Decision Support — FIAP Tech Challenge (Phase 1)

**FIAP Postgraduate Program: Artificial Intelligence for Developers**  
**Project type:** Collaborative academic group project

This project explores Machine Learning approaches for clinical decision support through two classification tasks:

- **Part A — Breast cancer diagnosis:** tabular data classification to distinguish malignant from benign cases. The team compared Logistic Regression, K-Nearest Neighbors, Support Vector Machine, Decision Tree and Random Forest, using recall, precision, F1-score, accuracy, ROC-AUC and a cost-sensitive decision threshold.
- **Part B — Pneumonia detection (extra):** chest X-ray image classification, comparing convolutional neural networks (CNNs) and a PCA + Random Forest baseline.

## Main results reported by the team

- **Breast cancer:** Logistic Regression with a 0.097 decision threshold achieved 0.98 recall (41 of 42 malignant cases), 0.95 accuracy and 0.996 ROC-AUC on the test set.
- **Pneumonia:** the selected CNN achieved 0.99 recall for pneumonia (385 of 390 cases), but only 0.41 recall for normal cases. This limitation is important and means the image model requires further improvement.

These are the results documented in the team's notebooks and technical report; they are not claims of clinical validation.

## Repository contents

- diagnostico_cancer_mama.ipynb — breast cancer classification notebook.
- diagnostico_pneumonia.ipynb — pneumonia image classification notebook (extra).
- data.csv — tabular dataset used in Part A.
- figuras/ — charts and model evaluation visualizations.
- relatorio_tecnico.pdf — technical report.
- requirements.txt and Dockerfile — environment and execution files.
- README_PT-BR.md — original Portuguese project documentation.

## How to explore

The notebooks can be opened in Jupyter or Google Colab. The pneumonia notebook downloads its image dataset separately; see the notebook and original Portuguese documentation for details. To reproduce the local environment, install the dependencies in requirements.txt or use the provided Dockerfile.

## Team

Developed collaboratively by the following FIAP postgraduate students:

- **Lucas Germano Farias**
- **Leandro Macedo Barros** — [GitHub @Macedole](https://github.com/Macedole)
- **Gabriel Rodrigues Belo** — [GitHub @gabrielrb](https://github.com/gabrielrb)
- **Larissa Silva Gomes** — [GitHub @gomezllari](https://github.com/gomezllari)

## Academic and medical-use disclaimer

This is an academic project developed for learning purposes. The models are experimental and must not be used to diagnose, rule out or guide treatment for any patient. They do not replace medical professionals or clinical validation.

## Original group repository

The project was originally developed and maintained collaboratively at [gabrielrb/tech-challenge-fase1](https://github.com/gabrielrb/tech-challenge-fase1). This portfolio copy preserves the group context and credits all contributors.
