# Projeto 2 — Ciclo Completo de Classificação de Risco de Crédito

---

## 📚 Explicação do Curso
Este projeto faz parte do curso de Cientista de Dados da EBAC e representa a conclusão do **ciclo completo de modelagem preditiva**. O objetivo é construir e avaliar modelos capazes de prever o **Score de Crédito** de clientes, abordando todas as fases do pipeline de Machine Learning: Pré-processamento, Balanceamento, Classificação Multi-Classe e Avaliação de Performance.

---

## 🎯 Objetivos
O principal objetivo deste projeto é a consolidação das habilidades de Machine Learning em problemas de classificação:

* **Pré-processamento de Dados:** Aplicar técnicas de limpeza, tratamento de dados faltantes e codificação de variáveis categóricas, preparando a base para a modelagem.
* **Balanceamento de Classes:** Implementar a técnica **SMOTE** para tratar o desbalanceamento inerente ao problema de risco de crédito.
* **Modelagem e Comparação:** Treinar e comparar a performance de dois algoritmos de Classificação Multi-Classe: **Naive Bayes** e **Árvore de Decisão**.
* **Avaliação de Modelos:** Avaliar a performance com métricas como Acurácia e, principalmente, **Recall (macro)**, crucial para garantir previsões confiáveis em todas as classes de score.

---

## 💻 Tecnologias Usadas
* **Linguagem:** Python
* **Bibliotecas Principais:** Pandas, NumPy, Scikit-learn, Matplotlib e Seaborn.
* **Ferramenta de Balanceamento:** `imbalanced-learn` (SMOTE).
* **Algoritmos:** Naive Bayes e Árvore de Decisão.
* **Ambiente:** Jupyter Notebook.

---

## 📈 Principais Análises Realizadas
O projeto abrangeu as seguintes etapas e análises técnicas:

* **Pré-processamento Inicial:** Tratamento da base de dados, incluindo a conversão da coluna 'Income' e o manuseio de dados faltantes (missing values) na variável 'Age'.
* **Engenharia de Features:** Aplicação do `One-Hot Encoding` em variáveis categóricas para adequá-las ao treinamento dos modelos.
* **Divisão e Balanceamento:** Separação da base em conjuntos de treino e teste e implementação do SMOTE para equalizar as classes de score.
* **Treinamento e Previsão:** Implementação e treinamento do Naive Bayes e da Árvore de Decisão na base balanceada.
* **Análise de Desempenho:** Cálculo de Acurácia e do *Classification Report*, detalhando o desempenho dos modelos em cada classe de score.

---

## ✨ Insights Chave (Valor de Negócio e Conclusão)

As conclusões extraídas desta modelagem são cruciais para a tomada de decisão no risco de crédito:

* **Validação Metodológica:** A implementação do **SMOTE** foi fundamental para evitar que o modelo ficasse enviesado pela classe majoritária, garantindo previsões justas e confiáveis.
* **Performance do Modelo:** A **Árvore de Decisão** foi validada como o algoritmo mais robusto e confiável para a classificação multi-classe do score de crédito neste contexto específico, apresentando maior eficácia após o balanceamento.
* **Decisão de Crédito:** Os resultados demonstram um modelo treinado com rigor, capaz de auxiliar instituições financeiras a tomar decisões mais informadas sobre a concessão de crédito, mitigando riscos de inadimplência.