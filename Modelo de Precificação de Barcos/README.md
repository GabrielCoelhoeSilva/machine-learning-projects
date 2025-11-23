# 🧠 Projeto de Previsão de Preços de Barcos com Machine Learning

Este projeto utiliza técnicas de **Ciência de Dados** e **Machine Learning** para prever o preço de barcos com base em suas características.  
O modelo foi treinado usando algoritmos de Regressão Linear e Random Forest Regressor, e comparado usando a métrica R².

---

## 📌 Objetivo

O projeto tem como objetivo:

- Analisar dados de barcos e suas características
- Identificar quais variáveis mais influenciam os preços
- Criar um modelo de previsão confiável
- Testar diferentes algoritmos e comparar seus resultados
- Utilizar o modelo treinado para prever preços de novos barcos

---

## 📂 Estrutura do Projeto

```plaintext
previsao_barcos/
│
├── data/
│   ├── barcos_ref.csv      # Base original usada no treino
│   └── novos_barcos.csv    # Novos dados para previsão
│
├── src/
│   └── modelo.py           # (opcional) script consolidado
│
│
└── README.md

| Tecnologia                  | Uso                   |
| --------------------------- | --------------------- |
| ![Python](https://www.python.org/static/community_logos/python-logo.png) Python 3.x | Linguagem principal |
| ![Pandas](https://pandas.pydata.org/static/img/pandas_mark.svg) Pandas | Manipulação dos dados |
| ![Seaborn](https://seaborn.pydata.org/_images/logo-mark-lightbg.svg) Seaborn / ![Matplotlib](https://matplotlib.org/_static/images/logo2.svg) Matplotlib | Visualizações |
| ![Scikit-learn](https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png) Scikit-learn | Modelagem e métricas |

```

## 📌 Melhorias Futuras

Embora o projeto já apresente resultados satisfatórios, algumas melhorias podem ser implementadas para aumentar sua eficiência, precisão e robustez. Entre elas:

### 🔧 Modelagem e Desempenho
- 🎯 **Ajuste de hiperparâmetros** via `GridSearchCV` ou `RandomizedSearchCV` para otimizar o modelo de Random Forest.
- 🔁 **Testar outros algoritmos de regressão**, como:
  - XGBoost
  - LightGBM
  - CatBoost (suporta dados categóricos sem necessidade de codificação)
- 📈 **Adicionar métricas complementares**, como:
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)
