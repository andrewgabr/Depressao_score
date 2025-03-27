# **Projeto: Análise de Score de Depressão e Previsão de Risco**

## **Objetivo**
O objetivo deste projeto é analisar o histórico de pacientes e prever o risco de depressão com base em dados clínicos e psicológicos. O modelo será utilizado para avaliar a probabilidade de um paciente desenvolver sintomas graves de depressão, ajudando na decisão de intervenções e tratamentos adequados.

## **Tecnologias Utilizadas**
- **Linguagem**: Python  
- **Bibliotecas**: pandas, numpy, scikit-learn, Flask, matplotlib, seaborn  

## **Fases do Projeto**

### **1. Definição do Problema**
- Identificação dos fatores que influenciam o risco de depressão (idade, histórico familiar, sintomas clínicos, etc.)  
- Coleta de dados históricos de pacientes com diagnóstico de depressão  
- Formulação do problema como uma tarefa de classificação binária:  
  - **1**: Paciente com alto risco de depressão  
  - **0**: Paciente sem risco significativo de depressão  

### **2. Preparação dos Dados**
- Tratamento de valores ausentes (Missing Values)  
- Seleção de variáveis relevantes (Feature Selection)  
- Codificação de variáveis categóricas (ex.: gênero, histórico familiar)  
- Normalização/Escalonamento dos dados (se necessário)  

### **3. Criação do Modelo de Machine Learning (em andamento)**
- Uso de **Random Forest** para classificação do risco de depressão  
- Treinamento do modelo com validação cruzada  
- Avaliação das métricas de desempenho:
  - **Acurácia**  
  - **Precisão, Recall e F1-Score**  
  - **Matriz de Confusão**  
  - **Curva ROC-AUC**  

