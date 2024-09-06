# Análise de 24 Anos de Demanda Horária de Energia Elétrica no Brasil

## Overview

Este projeto analisa a demanda horária de energia elétrica no Brasil ao longo de 24 anos (2000-2024) utilizando um dataset do Operador Nacional do Sistema Elétrico (ONS). Exploramos padrões temporais, realizamos análises estatísticas e implementamos modelos de predição com Redes Neurais Recorrentes (RNN).

## Estrutura do Projeto

1. **Importação de Dependências**: Importação das bibliotecas necessárias para análise e modelagem.
2. **Download do Dataset**: Download e consolidação dos dados de demanda horária de energia elétrica no Brasil.
3. **Descrição do Dataset**: Descrição das colunas e exemplos de dados.
4. **Transformação dos Dados**: Agrupamento e extração de informações temporais.
5. **Visualização dos Dados**: Criação de gráficos interativos para visualização de padrões temporais.
6. **Análise Estatística**: Decomposição sazonal, análise de autocorrelação e identificação de outliers.
7. **Preparação dos Dados para Modelagem**: Normalização, divisão em treino e teste, e criação de sequências de dados.
8. **Modelagem com RNN**: Definição, treinamento e avaliação do modelo RNN.
9. **Visualização dos Resultados**: Comparação entre valores esperados e preditos.

## Dependências

- requests
- numpy
- pandas
- seaborn
- matplotlib
- keras
- sklearn
- statsmodels
- bokeh

## Como Executar

1. Clone o repositório.
2. Instale as dependências listadas acima.
3. Execute o notebook para realizar a análise e modelagem.