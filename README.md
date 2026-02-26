# 🌫️ Air Pollution Prediction using Linear Regression and MLP

Projeto de Machine Learning para previsão de níveis de poluição atmosférica utilizando dois modelos supervisionados:

- 📈 Regressão Linear
- 🧠 Multilayer Perceptron (MLP)

O objetivo é comparar desempenho, interpretabilidade e capacidade de generalização entre um modelo estatístico clássico e uma rede neural.

---

## 📊 Problema

A poluição do ar é um problema ambiental e de saúde pública crítico. Prever seus níveis permite:

- Planejamento urbano
- Alertas ambientais
- Políticas públicas
- Mitigação de riscos à saúde

Este projeto busca modelar a relação entre variáveis ambientais e o nível de poluição.

---

## 🗂️ Dataset

O dataset contém medições ambientais e meteorológicas utilizadas para prever a variável alvo de poluição.

Principais tipos de variáveis:

- Condições climáticas
- Concentração de poluentes
- Variáveis ambientais correlacionadas

---

## ⚙️ Pipeline do Projeto

1. Limpeza e preparação dos dados  
2. Análise exploratória (EDA)  
3. Tratamento de outliers  
4. Escalonamento das variáveis  
5. Treinamento dos modelos  
6. Avaliação e comparação  
7. Análise dos resultados  

---

## 🔍 Modelos Utilizados

### 📈 Regressão Linear

Modelo base, altamente interpretável e eficiente para relações lineares.

Vantagens:

- Simples e rápido
- Fácil interpretação dos coeficientes
- Baixo risco de overfitting

---

### 🧠 MLP Regressor (Rede Neural)

Modelo não linear capaz de capturar padrões complexos.

Características:

- Múltiplas camadas densas
- Funções de ativação não lineares
- Necessidade de normalização dos dados

---

## 📏 Métricas de Avaliação

Foram utilizadas métricas padrão para regressão:

- MAE — Mean Absolute Error
- RMSE — Root Mean Squared Error
- R² — Coeficiente de determinação
- R² Ajustado

---

## 📉 Experimento com Outliers

O projeto avaliou o impacto da remoção de outliers na variável alvo.

Observação importante:

➡️ A presença de outliers melhorou o R² do modelo  
➡️ Isso sugere que valores extremos fazem parte do fenômeno real  
➡️ Removê-los pode reduzir a capacidade preditiva  

---

## 📊 Visualizações

- Distribuição da variável alvo  
- Correlação entre variáveis  
- Gráfico Real vs Previsto  
- Análise de resíduos  

---

## 🏆 Resultados

O desempenho dos modelos mostrou que:

- A Regressão Linear apresentou forte capacidade preditiva
- O MLP capturou relações não lineares adicionais
- O dataset apresenta estrutura relativamente bem modelada por métodos lineares

---

## 🚀 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📌 Possíveis Melhorias Futuras

- Modelos ensemble (Random Forest, Gradient Boosting)
- Ajuste de hiperparâmetros
- Validação cruzada mais robusta
- Feature engineering avançado
- Modelagem de séries temporais

---

## 👨‍💻 Autor

Pedro Henrique  
Estudante de Data Science  

---

## ⭐ Objetivo do Projeto

Projeto desenvolvido para fins acadêmicos e construção de portfólio em Ciência de Dados e Machine Learning.
