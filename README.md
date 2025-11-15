# Previsão de doenças cardíacas usando redes neurais (IA - 2025/2, Professor Edjard, Trabalho 2)

### Membros
| Membro | Email |
| :--- | :--- |
| José Dercy V. da Silva Filho | <jose.dercy@icomp.ufam.edu.br> |
| Ronaldo Rodrigues Soares | <ronaldo.soares@icomp.ufam.edu.br> |
| Yan Fernandes da Silva | <yan.silva@icomp.ufam.edu.br> |
| Beatriz Emily Silva Aguiar | <beatriz.aguiar@icomp.ufam.edu.br> |
| Matheus Ricardo Oliveira Lima | <matheus.ricardo@icomp.ufam.edu.br> |

## Descrição
Este repositório aplica uma rede neural (Multi-Layer Perceptron / Keras) para prever a presença de doença coronariana usando o conjunto de dados "Heart Disease" do repositório UCI.
> É necessário para a execução do notebook importar o dataset **heart.csv** presente no link: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

## Problema
-   **Tipo:** problema de classificação binária (presença ou ausência de doença cardíaca).
-   **Motivação:** diagnóstico precoce e triagem com base em dados clínicos tabulares para apoiar decisões médicas e priorizar exames complementares.

## Dados (dataset)
-   **Origem:** UCI Machine Learning Repository - *Heart Disease* .
-   **Tamanho:** ~1025 instâncias e 14 atributos.
-   **Atributos típicos:** idade, sexo, pressão arterial em repouso, colesterol, máximo ritmo cardíaco, dor no peito, ECG, etc.

## Metodologia
-   **Pré-processamento:** limpeza, normalização e codificação de variáveis categóricas.
-   **Modelo:** rede neural densa (MLP) construída com Keras/TensorFlow.
-   **Treinamento:** divisão treino/teste, otimização via Adam, função de perda binária.
-   **Avaliação:** acurácia, matriz de confusão, precisão, recall e F1-score.

## Resultados
-   O notebook e reproduções semelhantes apresentam acurácia típica de mais de **90%**.
-   Os resultados finais podem variar conforme semente aleatória, pré-processamento e configuração do modelo.
-   Recomenda-se reexecutar o notebook para validar métricas exatas.

## Conclusão
O projeto demonstra de forma clara como aplicar uma rede neural em um problema médico clássico e alcança resultados consistentes com estudos similares. O notebook serve como bom ponto de partida para aprofundar o uso de modelos em dados clínicos e explorar técnicas de melhoria de desempenho e interpretabilidade.
