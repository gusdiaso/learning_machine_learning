🇧🇷 [Português](README.md) | 🇺🇸 English

# Machine Learning A–Z: Study Notes and Implementations

Python notebooks with the classic Machine Learning algorithms I studied in the **Machine Learning A–Z** course. Each technique has its own folder, with the notebook and the dataset used.

## Contents

| Area | Techniques |
|---|---|
| **Regression** | Data preprocessing, simple and multiple linear regression, polynomial regression, SVR, decision tree, Random Forest |
| **Classification** | Logistic regression, K-NN, SVM, Kernel SVM, Naive Bayes, decision tree, Random Forest |
| **Clustering** | K-Means, hierarchical clustering |
| **Association rules** | Apriori, Eclat |
| **Reinforcement learning** | Upper Confidence Bound (UCB), Thompson Sampling |
| **Natural language processing** | Bag of Words applied to restaurant reviews |

## Structure

```
regression/                  # 7 notebooks
classification/              # 7 notebooks
clustering/
association-rule/
reinforcement-learning/
natural-language-processing/
requirements.txt
```

## Tech stack

Python · pandas · NumPy · scikit-learn · Matplotlib · SciPy · apyori

## How to run

```bash
git clone https://github.com/gusdiaso/learning_machine_learning.git
cd learning_machine_learning
pip install -r requirements.txt
pip install jupyter
jupyter notebook
```

## Next steps

Dimensionality reduction (PCA, LDA, Kernel PCA), model selection (cross-validation, Grid Search, XGBoost) and neural networks.

## Applied in larger projects

The fundamentals practiced here were used in larger projects, such as [cryptocurrency forecasting with LSTM](https://github.com/gusdiaso/crypto_predict).

## Author

Gustavo Dias de Oliveira · [LinkedIn](https://www.linkedin.com/in/gusdiaso/)

MIT License.
