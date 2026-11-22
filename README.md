# Aplicação de ensembles em detecção de fraudes em cartões de crédito

Projeto que compara métodos de ensemble (Random Forest e XGBoost) com modelos individuais (Naive Bayes e árvore de decisão) na detecção de fraudes em transações de cartão de crédito, um problema de classificação binária com classes desbalanceadas.

O dataset é o [Credit Card Fraud Detection](https://www.kaggle.com/datasets/miadul/credit-card-fraud-detection-dataset), do Kaggle, com 10.000 transações simuladas.

## Estrutura

```
.
├── analysis.ipynb                  # Notebook com toda a análise
├── data/
│   └── credit_card_fraud_10k.csv   # Dataset
├── LICENSE
└── README.md
```

O notebook está dividido em sete seções: introdução, análise exploratória, validação estatística, pré-processamento, modelagem, resultados e conclusão.

## Como executar

O notebook usa um kernel R e uma série de pacotes. Abra-o a partir da raiz do repositório ou no Google Colab, que já traz o ambiente configurado.