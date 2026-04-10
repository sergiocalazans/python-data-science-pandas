# Python para Data Science - Pandas

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-blue.svg)

Este repositório contém um notebook Jupyter que serve como um portfólio de Python para Ciência de Dados, com um foco especial na biblioteca **Pandas**. O material aborda desde os fundamentos da linguagem Python, como tipos de dados e funções, até a manipulação e análise de dados tabulares com as principais ferramentas do Pandas.

## 📖 Tabela de Conteúdos

1.  [**Introdução ao Python**](#1-introdução-ao-python)
    - Ambiente de Desenvolvimento (Anaconda, Google Colab)
    - Primeiro contato com dados usando Pandas (`.read_csv()`, `.info()`, `.describe()`)

2.  [**Trabalhando com Tuplas**](#2-trabalhando-com-tuplas)
    - Criação, seleção e iteração
    - Desempacotamento de tuplas
    - Uso da função `zip()`

3.  [**Trabalhando com Dicionários**](#3-trabalhando-com-dicionários)
    - Criação e operações básicas (acesso, inserção, remoção)
    - Principais métodos (`.update()`, `.copy()`, `.pop()`, `.keys()`, `.values()`, `.items()`)
    - Iteração em dicionários

4.  [**Funções e Pacotes**](#4-funções-e-pacotes)
    - Funções _built-in_
    - Definindo funções com e sem parâmetros
    - Funções com retorno de um ou mais valores

5.  [**Pandas**](#5-pandas)
    - **Estruturas de Dados**: `Series` e `DataFrames`
    - **Seleções com DataFrames**:
      - Seleção de colunas
      - Seleção de linhas (slicing)
      - Seleção por rótulos com `.loc`
      - Seleção por posição com `.iloc`
    - **Queries com DataFrames**:
      - Filtros com indexação booleana
      - Uso do método `.query()`
    - **Iterando em DataFrames**:
      - Criando novas colunas com base em dados existentes usando `.iterrows()`
    - **Tratamento de Dados**:
      - Identificando dados faltantes (`.isna()`)
      - Removendo dados faltantes (`.dropna()`)
      - Preenchendo dados faltantes (`.fillna()`)

---

### 1. Introdução ao Python

Uma breve visão geral da linguagem, como configurar seu ambiente e os primeiros passos na importação e exploração de um conjunto de dados real (`.csv`) com o Pandas.

### 2. Trabalhando com Tuplas

Aprenda a criar e manipular tuplas, uma estrutura de dados imutável essencial em Python. Aborda desde a criação e seleção de elementos até técnicas mais avançadas como desempacotamento e o uso da função `zip()` para combinar coleções.

### 3. Trabalhando com Dicionários

Explore os dicionários, a estrutura de mapeamento chave-valor de Python. O notebook ensina a realizar operações CRUD (Criar, Ler, Atualizar, Deletar) e a iterar sobre chaves, valores e itens.

### 4. Funções e Pacotes

Entenda como criar suas próprias funções para modularizar e reutilizar código. Aprenda a definir funções com parâmetros e a retornar um ou múltiplos valores, um conceito fundamental para a programação eficiente.

### 5. Pandas

O coração do notebook. Esta seção oferece uma imersão na biblioteca Pandas, cobrindo:

- **Criação de `Series` e `DataFrames`** a partir de listas, dicionários e arquivos externos.

- **Técnicas de seleção e fatiamento de dados** usando indexação, `.loc` e `.iloc`, permitindo que você acesse qualquer parte do seu DataFrame com precisão.

- **Filtragem de dados** para encontrar informações específicas através de queries e máscaras booleanas.

- **Cálculo de novas colunas** para enriquecer o datasheet.

- **Tratamento de valores ausentes (NaN)**, uma etapa crucial em qualquer projeto de análise de dados, ensinando a identificar, remover ou substituir esses valores.

## 🚀 Como Executar

Para executar este notebook em sua máquina local, siga os passos abaixo.

### Pré-requisitos

- Python 3.7 ou superior
- Jupyter Notebook ou JupyterLab (geralmente incluído em distribuições como Anaconda)

### Passos

1.  Clone o repositório:

    ```bash
    git clone https://github.com/sergiocalazans/python-data-science-pandas.git
    ```

2.  Navegue até o diretório clonado:

    ```bash
    cd python-data-science-pandas
    ```

3.  Instale a biblioteca Pandas (se ainda não tiver):

    ```bash
    pip install pandas
    ```

4.  Inicie o Jupyter Notebook ou JupyterLab:
    ```bash
    jupyter notebook
    # ou
    jupyter lab
    ```

---
