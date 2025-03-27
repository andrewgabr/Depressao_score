# **Projeto: Análise de Score de Depressão e Previsão de Risco**

## **Objetivo**
O objetivo deste projeto é analisar o histórico de pacientes e prever o risco de depressão com base em dados clínicos e psicológicos. O modelo será utilizado para avaliar a probabilidade de um paciente desenvolver sintomas graves de depressão, ajudando na decisão de intervenções e tratamentos adequados.

## **Tecnologias Utilizadas**
- **Linguagem**: Python  
- **Bibliotecas**: pandas, numpy, scikit-learn, matplotlib, seaborn  

## **Fases do Projeto**

### **1. Definição do Problema**
- Identificação dos fatores que influenciam o risco de depressão (idade, histórico familiar, sintomas clínicos, etc.)  
- Coleta de dados históricos de pacientes com diagnóstico de depressão  

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



## **Questões de Pesquisa**

1. **Como a faixa etária e o gênero influenciam os níveis de ansiedade, depressão e estresse?**
   - Análise da correlação entre faixa etária/gênero e os índices de transtornos emocionais, identificando possíveis padrões em diferentes grupos etários e de gênero.

2. **Qual a relação entre horas de sono e os níveis de ansiedade e depressão?**
   - Investigar como a quantidade de horas de sono impacta os níveis de ansiedade e depressão, verificando se pessoas com menos horas de sono apresentam maiores índices de distúrbios emocionais.

3. **Como o histórico familiar de doenças mentais afeta os índices de ansiedade e depressão nos indivíduos?**
   - Avaliar se indivíduos com histórico familiar de doenças mentais têm maior probabilidade de desenvolver ansiedade e depressão.

4. **Terapia e meditação são estratégias eficazes para reduzir os níveis de ansiedade e depressão?**
   - Analisar a eficácia de terapias tradicionais e métodos alternativos, como meditação, para reduzir os níveis de ansiedade e depressão e verificar se há diferenças significativas entre os dois métodos.

5. **Como o nível de solidão está relacionado ao bem-estar geral e ao impacto na saúde mental dos indivíduos?**
   - Estudar a correlação entre solidão e saúde mental, verificando o impacto da solidão no bem-estar geral e como ela afeta os níveis de ansiedade e depressão.


