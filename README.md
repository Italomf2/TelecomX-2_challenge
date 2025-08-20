# 📊 Challenge Telecom X  Parte 2 – Prevendo Churn

Este projeto tem como objetivo desenvolver modelos de machine learning para prever a evasão de clientes (churn) da empresa fictícia Telecom X.

## 👤 Autor
Müller Pereira

## 🎯 Objetivo
Construir uma solução preditiva para identificar clientes com maior propensão a cancelar seus serviços, ajudando a empresa a agir proativamente para reter clientes.

---

## 🧩 Etapas do Projeto

### 1. Extração e Preparação dos Dados
- Leitura de um arquivo `.json` com dados aninhados.
- Conversão de strings para dicionários com `ast.literal_eval`.
- Expansão das colunas `customer`, `phone`, `internet` e `account` com `pd.json_normalize`.
- Consolidação em um único DataFrame.

### 2. Análise Exploratória
- Visualização das primeiras e últimas linhas dos dados.
- Informações sobre tipos de dados e valores nulos.
- Verificação de variáveis com maior variação.

### 3. Modelagem
- Aplicação de modelos como:
  - Regressão Logística
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - XGBoost
- Avaliação de desempenho usando métricas como acurácia, F1-score, curva ROC.

### 4. Interpretação dos Modelos
- Análise de importância de variáveis (feature importance).
- Visualização de padrões com gráficos de dispersão e boxplots.

---

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook

