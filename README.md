# Detecção de Fake News

## Descrição

Este projeto implementa um sistema de detecção de Fake News utilizando técnicas de Machine Learning e Processamento de Linguagem Natural (NLP). O objetivo é classificar notícias em duas categorias: `FAKE` (falsas) e `REAL` (verdadeiras), auxiliando no combate à desinformação.

O modelo utiliza o algoritmo Passive Aggressive Classifier, treinado com representações de texto geradas pelo método TF-IDF (Term Frequency-Inverse Document Frequency). O pipeline foi avaliado em termos de acurácia, precisão, revocação e matriz de confusão, apresentando resultados promissores com uma acurácia de 92.8%.

## Tecnologias Utilizadas

**Linguagem**: Python
**Bibliotecas**:
- `sklearn` (para algoritmos de aprendizado de máquina e métricas de avaliação)
- `pandas` (manipulação de dados)
- `numpy` (operações numéricas)
- `matplotlib` e `seaborn` (visualizações)
- `wordcloud` (visualização de palavras mais relevantes)

## Conclusão

O modelo apresenta um bom desempenho geral, com um número elevado de predições corretas para ambas as classes (FAKE e REAL). A acurácia geral de 92.8% reflete a capacidade do modelo de fazer classificações consistentes. Além disso:

- A classe `FAKE` teve 590 **predições corretas** e 43 **incorretas**, mostrando que o modelo é confiável na detecção de notícias falsas, mas ainda existem alguns casos de falsos negativos.

- A classe `REAL` teve 586 **predições corretas** e 48 **incorretas**, indicando que o modelo também é eficaz na identificação de notícias reais, embora algumas características das notícias reais possam ser confundidas.
