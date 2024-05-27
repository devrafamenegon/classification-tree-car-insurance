# **Análise e Modelagem de Valores de Seguros de Carros 🚗**

---

## **1. Descrição da Aplicação e do Algoritmo (Árvore de Classificação) 🌳**

Este projeto tem como objetivo analisar e modelar os preços de seguros de carros com base em um conjunto de dados disponibilizados. A aplicação visa identificar as variáveis que exercem maior influência nos preços dos seguros, utilizando técnicas de análise exploratória de dados (EDA) e modelagem preditiva.

A principal técnica de modelagem utilizada neste projeto é a Árvore de Classificação. Uma árvore de decisão é um algoritmo de aprendizado de máquina supervisionado que é capaz de prever a variável alvo com base em várias características dos dados. A árvore é construída dividindo recursivamente os dados em subconjuntos homogêneos com base em um critério de divisão, como ganho de informação ou redução de impureza.

---

## **2. Tratamento dos Dados 🎲**

Os dados foram pré-processados para lidar com valores ausentes e transformar as variáveis categóricas em formato numérico. As etapas incluíram a remoção da coluna de identificação ('ID'), tratamento de valores ausentes (caso existissem) e mapeamento das variáveis categóricas para valores numéricos.

---

## **3. Características dos Dados e Análise Visual 👁‍🗨**

Os dados disponibilizados incluem as seguintes características:

- **MARCA**: Marca do veículo.
- **MODELO**: Modelo do veículo.
- **COR**: Cor do veículo.
- **IDADE**: Idade do condutor.
- **SEXO**: Sexo do condutor.
- **FATORSEGURO**: Fator de cálculo para o seguro.

A análise visual dos dados foi realizada utilizando histogramas, gráficos de barras, matrizes de dispersão e mapas de calor. Esses gráficos foram legendaods e acompanhados de uma explicação detalhada para facilitar a compreensão das características dos dados e identificar possíveis padrões ou correlações.

---

## **4. Implementação da Árvore de Classificação em Python 🐍**

A implementação da Árvore de Classificação foi realizada utilizando a biblioteca Scikit-learn em Python. Foram ajustados modelos de regressão linear e árvore de decisão aos dados e calculadas as pontuações de desempenho.

A árvore de decisão foi construída com base nas features selecionadas e um critério de "mse" (mean squared error) foi utilizado para avaliar o desempenho do modelo.

---

## **5. Documentação do Código 📃**

O código foi documentado de forma clara e organizada, incluindo comentários explicativos em cada etapa do processo. Isso facilita a compreensão do código e permite que outros desenvolvedores entendam e reproduzam os resultados.

---

## **6. Testes e Comentários dos Resultados ✨**

Foram realizados testes para avaliar o desempenho do modelo de Árvore de Classificação. Os resultados foram analisados e comentados, destacando os pontos fortes e as áreas de melhoria do modelo.

---
