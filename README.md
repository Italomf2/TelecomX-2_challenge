# 📊 Challenge Telecom X – Parte 2: Predição de Churn

Este projeto tem como foco a construção de modelos de **machine learning** para prever a evasão de clientes (churn) da empresa fictícia **Telecom X**.

---

## 👤 Responsável
Italo Mendonça

---

## 🎯 Propósito
Desenvolver uma solução preditiva capaz de identificar quais clientes apresentam maior probabilidade de cancelar seus serviços, permitindo que a empresa adote ações preventivas de retenção.

---

## 🧩 Etapas Realizadas

### 1. Coleta e Preparação dos Dados
- Leitura de arquivo `.json` contendo dados estruturados em múltiplos níveis.  
- Conversão de strings em dicionários por meio de `ast.literal_eval`.  
- Expansão das seções `customer`, `phone`, `internet` e `account` utilizando `pd.json_normalize`.  
- Junção de todas as informações em um único **DataFrame**.  

### 2. Análise Exploratória
- Inspeção das primeiras e últimas linhas do dataset.  
- Revisão de tipos de variáveis e presença de valores ausentes.  
- Identificação de atributos com maior dispersão e variabilidade.  

### 3. Criação dos Modelos
- Teste de diferentes algoritmos:  
  - Regressão Logística  
  - K-Nearest Neighbors (KNN)  
  - Random Forest  
  - XGBoost  
- Avaliação do desempenho com métricas como **acurácia**, **F1-score** e **curva ROC**.  

### 4. Interpretação dos Resultados
- Estudo da **importância das variáveis** (feature importance).  
- Exploração de padrões com **gráficos de dispersão** e **boxplots**.  

---

## 🛠️ Ferramentas e Bibliotecas

- **Python 3.x**  
- **Pandas**, **NumPy**  
- **Seaborn**, **Matplotlib**  
- **Scikit-learn**  
- **XGBoost**  
- **Jupyter Notebook**  

---
