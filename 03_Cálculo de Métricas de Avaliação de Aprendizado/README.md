# Cálculo de Métricas de Avaliação de Aprendizado

Este projeto tem como objetivo calcular manualmente as principais métricas utilizadas na avaliação de modelos de classificação binária. Ele foi desenvolvido com foco didático, para ajudar iniciantes a entenderem como essas métricas funcionam "por trás dos panos", sem o uso de bibliotecas externas.

## 📌 Objetivos

- Entender os conceitos de acurácia, precisão, sensibilidade (recall), especificidade e F-score.
- Implementar as fórmulas em Python puro.
- Utilizar uma matriz de confusão com valores simulados para calcular e interpretar as métricas.

## 📊 Matriz de Confusão Simulada

|                 | Previsto Positivo | Previsto Negativo |
|-----------------|-------------------|-------------------|
| **Real Positivo** | VP = 70            | FN = 10            |
| **Real Negativo** | FP = 5             | VN = 115           |

## 📐 Métricas Calculadas

- **Acurácia** = (VP + VN) / (VP + FP + FN + VN)
- **Precisão** = VP / (VP + FP)
- **Sensibilidade (Recall)** = VP / (VP + FN)
- **Especificidade** = VN / (VN + FP)
- **F-score** = 2 * (Precisão * Recall) / (Precisão + Recall)

## 💻 Tecnologias Utilizadas

- Python 3 (sem bibliotecas externas)
- Google Colab (recomendado)

## 📂 Estrutura do Projeto

O notebook está dividido em etapas:
1. Definição da matriz de confusão
2. Criação das funções para cálculo das métricas
3. Execução dos cálculos
4. Exibição dos resultados
5. Conclusão

## 📈 Resultados Esperados

Com os valores simulados, você verá as métricas impressas com duas casas decimais, permitindo interpretar o desempenho de um classificador com base em medidas fundamentais.

##

Este projeto é uma introdução prática e direta ao universo da avaliação de classificadores. Compreender essas métricas é essencial para interpretar corretamente os resultados de modelos de machine learning, especialmente em problemas de classificação binária.

---

> Feito com foco educacional, por quem está aprendendo e quer compartilhar conhecimento de forma simples e direta. 🙂

