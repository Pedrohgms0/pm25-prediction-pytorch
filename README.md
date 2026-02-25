# 🌫️ Air Pollution Prediction — PM2.5

Este projeto realiza a análise e previsão da concentração de partículas finas no ar (PM2.5) a partir de dados meteorológicos e ambientais.

O notebook inclui todas as etapas do pipeline de Data Science: limpeza de dados, análise exploratória, preparação de features e treinamento de um modelo de regressão com rede neural.

---

## 📊 Objetivo

Prever os níveis de poluição do ar (PM2.5) com base em variáveis como:

- Temperatura
- Pressão atmosférica
- Umidade (Dew Point)
- Direção e velocidade do vento
- Gases poluentes (SO₂, NO₂, CO, O₃)
- Data e hora
- Estação de monitoramento

---

## 🧠 Metodologia

O projeto segue as etapas:

1. **Carregamento dos dados**
2. **Limpeza e tratamento de valores ausentes**
   - Preenchimento por média mensal (variáveis numéricas)
   - Preenchimento por moda (variáveis categóricas)
3. **Feature Engineering**
   - Criação de variável de data
   - Extração do dia da semana
4. **Análise Exploratória (EDA)**
   - Estatísticas descritivas
   - Boxplots
   - Gráficos de regressão
   - Matriz de correlação
5. **Codificação de variáveis categóricas**
6. **Normalização dos dados**
7. **Divisão treino/teste**
8. **Treinamento de modelo de regressão com PyTorch**
9. **Avaliação do modelo**

---

## 🤖 Modelo Utilizado

Rede neural totalmente conectada (MLP) para regressão:

- Camadas densas com ReLU
- Otimizador Adam
- Função de perda: MSE (Mean Squared Error)

---

## 📈 Métricas de Avaliação

O modelo é avaliado com:

- MAE (Erro Absoluto Médio)
- MSE (Erro Quadrático Médio)
- RMSE
- R² e R² ajustado

---

## 🛠️ Tecnologias Utilizadas

- Python
- PyTorch
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---
