# Projeto: Classificação de Clientes - Churn Prediction

Este projeto utiliza aprendizado de máquina para prever quais clientes têm maior probabilidade de abandonar um serviço (churn), com foco em interpretar os melhores modelos de classificação.

---

## 🔍 Objetivo

Aplicar e comparar cinco modelos de machine learning:
- Random Forest
- LightGBM
- KNN
- Regressão Logística
- SVM Linear

Com uso de:
- Pipeline com pré-processamento
- Balanceamento com SMOTE
- GridSearchCV para otimização
- Avaliação com Acurácia, Relatório de Classificação e Curva ROC

---

## 📊 Análise Exploratória

Antes da modelagem, foi feita uma análise exploratória com foco em entender o comportamento de clientes que deram churn, analisando:
- Distribuição das classes
- Correlação entre variáveis
- Impacto de atributos como tempo de contrato, serviços adicionais, tipo de pagamento e valor mensal
- Identificação de desequilíbrio de classes, tratado com SMOTE

---

## ✅ Resultados

Todos os modelos foram avaliados com base na AUC-ROC com **0.86**, exceto para o KNN com **0.80**.  
O modelo **SVM Linear** apresentou a pior acurácia com **0.74**.  
O modelo **LightGBM** se destacou com AUC = **0.86** e acurácia = **0.82**, seguido pelo **Random Forest** com AUC = **0.86** e acurácia = **0.81**.

---

## 🛠️ Tecnologias

- Python
- scikit-learn
- imbalanced-learn
- matplotlib / seaborn
- VS Code

---

## 📁 Estrutura


