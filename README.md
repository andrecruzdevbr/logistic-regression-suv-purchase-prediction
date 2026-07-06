# Logistic Regression SUV Purchase Prediction

Projeto de Machine Learning utilizando **Regressão Logística** para estimar a probabilidade de um usuário comprar uma SUV com base na idade e no salário estimado.

## Objetivo

Desenvolver um modelo de classificação binária capaz de prever a probabilidade de compra de uma SUV utilizando técnicas de Regressão Logística.

## Dataset

A base de dados contém informações de usuários com as seguintes variáveis:

- Age
- EstimatedSalary
- Purchased

A variável alvo é:

- **Purchased**
  - 0 = Não comprou
  - 1 = Comprou

## Etapas do Projeto

- Análise descritiva dos dados
- Construção do modelo de Regressão Logística
- Validação do modelo
- Matriz de Confusão
- Acurácia
- Relatório de Classificação
- Interpretação do Odds Ratio

## Resultados

O modelo apresentou:

- **Acurácia:** 84%
- **Pseudo R²:** 0.4816

As variáveis **Age** e **EstimatedSalary** foram estatisticamente significativas para explicar a probabilidade de compra da SUV.

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn

## Estrutura do Projeto

```
logistic-regression-suv-purchase-prediction/
│
├── README.md
├── data/
│   └── SUV_Network_Ads.csv
└── notebooks/
    └── Exercicio1_RegressaoLogistica_SUV_AndreDouglas_1665898.ipynb
```

## Autor

**André Douglas da Silva Cruz**

Pós-graduação em Inteligência Artificial e Aprendizado de Máquina – PUC Minas.