# Previsão de Salário com Regressão Linear

Este projeto utiliza regressão linear simples para prever o salário anual (em dólares) a partir dos anos de experiência de um profissional.

## Objetivo

Aplicar um modelo de regressão linear para entender a relação entre experiência e salário, e realizar previsões com base nesse histórico.

## Dataset

- **Fonte:** Salary_dataset.csv  
- **Variáveis:**  
  - `YearsExperience`: anos de experiência  
  - `Salary`: salário anual em dólares

## Etapas

1. Análise exploratória dos dados
2. Treinamento do modelo com scikit-learn
3. Avaliação do desempenho com métricas de erro
4. Visualização da reta de regressão

## Resultados

O modelo apresentou um desempenho compatível com sua simplicidade, com os seguintes resultados:

- **MAE (Erro Médio Absoluto):** aproximadamente \$6.286  
- **MSE (Erro Quadrático Médio):** cerca de 49.830.096  
- **RMSE (Raiz do Erro Quadrático Médio):** aproximadamente \$7.059  

Esses valores indicam que o modelo foi capaz de capturar a tendência geral dos dados, mas ainda possui margem de erro considerável por se basear em apenas uma variável.

## Tecnologias Utilizadas

- Python 3
- pandas, numpy, matplotlib
- scikit-learn
