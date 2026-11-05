🇧🇷 Português | 🇺🇸 [English](README.en.md)

# Machine Learning A–Z: estudos e implementações

Notebooks em Python com os algoritmos clássicos de Machine Learning que estudei no curso **Machine Learning A–Z**. Cada técnica fica em uma pasta própria, com o notebook e o dataset usado.

## Conteúdo

| Área | Técnicas |
|---|---|
| **Regressão** | Pré-processamento de dados, regressão linear simples e múltipla, regressão polinomial, SVR, árvore de decisão, Random Forest |
| **Classificação** | Regressão logística, K-NN, SVM, Kernel SVM, Naive Bayes, árvore de decisão, Random Forest |
| **Clusterização** | K-Means, clusterização hierárquica |
| **Regras de associação** | Apriori, Eclat |
| **Aprendizado por reforço** | Upper Confidence Bound (UCB), Thompson Sampling |
| **Processamento de linguagem natural** | Bag of Words aplicado a avaliações de restaurantes |

## Estrutura

```
regression/                  # 7 notebooks
classification/              # 7 notebooks
clustering/
association-rule/
reinforcement-learning/
natural-language-processing/
requirements.txt
```

## Tecnologias

Python · pandas · NumPy · scikit-learn · Matplotlib · SciPy · apyori

## Como executar

```bash
git clone https://github.com/gusdiaso/learning_machine_learning.git
cd learning_machine_learning
pip install -r requirements.txt
pip install jupyter
jupyter notebook
```

## Próximos passos

Redução de dimensionalidade (PCA, LDA, Kernel PCA), seleção de modelos (validação cruzada, Grid Search, XGBoost) e redes neurais.

## Aplicação em projetos

Os fundamentos praticados aqui foram usados em projetos maiores, como a [previsão de criptomoedas com LSTM](https://github.com/gusdiaso/crypto_predict).

## Autor

Gustavo Dias de Oliveira · [LinkedIn](https://www.linkedin.com/in/gusdiaso/)

Licença MIT.
