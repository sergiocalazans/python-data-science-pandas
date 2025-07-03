# Python para Data Science - Pandas

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-blue.svg)

Este repositório contém um notebook Jupyter que serve como um curso introdutório de Python para Data Science, com um foco especial na biblioteca **Pandas**. O material aborda desde os fundamentos da linguagem Python, como tipos de dados e funções, até a manipulação e análise de dados tabulares com as principais ferramentas do Pandas.

## 📂 Estrutura do Projeto

```
.
├── data/
│   └── db.csv          # Dataset de veículos utilizado no notebook
├── Python_para_Data_Science_Pandas.ipynb  # Notebook principal com o curso
└── README.md           # Este arquivo
```

## 📖 Tabela de Conteúdos

1.  [**Introdução ao Python**](#1-introdução-ao-python)
    -   Ambiente de Desenvolvimento (Anaconda, Google Colab)
    -   Primeiro contato com dados usando Pandas (`.read_csv()`, `.info()`, `.describe()`)

2.  [**Trabalhando com Tuplas**](#2-trabalhando-com-tuplas)
    -   Criação, seleção e iteração
    -   Desempacotamento de tuplas
    -   Uso da função `zip()`

3.  [**Trabalhando com Dicionários**](#3-trabalhando-com-dicionários)
    -   Criação e operações básicas (acesso, inserção, remoção)
    -   Principais métodos (`.update()`, `.copy()`, `.pop()`, `.keys()`, `.values()`, `.items()`)
    -   Iteração em dicionários

4.  [**Funções e Pacotes**](#4-funções-e-pacotes)
    -   Funções *built-in*
    -   Definindo funções com e sem parâmetros
    -   Funções com retorno de um ou mais valores

5.  [**Pandas Básico**](#5-pandas-básico)
    -   **Estruturas de Dados**: `Series` e `DataFrames`
    -   **Seleções com DataFrames**:
        -   Seleção de colunas
        -   Seleção de linhas (slicing)
        -   Seleção por rótulos com `.loc`
        -   Seleção por posição com `.iloc`
    -   **Queries com DataFrames**:
        -   Filtros com indexação booleana
        -   Uso do método `.query()`
    -   **Iterando em DataFrames**:
        -   Criando novas colunas com base em dados existentes usando `.iterrows()`
    -   **Tratamento de Dados**:
        -   Identificando dados faltantes (`.isna()`)
        -   Removendo dados faltantes (`.dropna()`)
        -   Preenchendo dados faltantes (`.fillna()`)

---

## 🎯 Sobre o Notebook

O notebook `Python_para_Data_Science_Pandas.ipynb` é um guia prático e completo que cobre os seguintes tópicos:

### 1. Introdução ao Python
Uma breve visão geral da linguagem, como configurar seu ambiente e os primeiros passos na importação e exploração de um conjunto de dados real (`db.csv`) com o Pandas.

### 2. Trabalhando com Tuplas
Aprenda a criar e manipular tuplas, uma estrutura de dados imutável essencial em Python. Aborda desde a criação e seleção de elementos até técnicas mais avançadas como desempacotamento e o uso da função `zip()` para combinar coleções.

### 3. Trabalhando com Dicionários
Explore os dicionários, a estrutura de mapeamento chave-valor de Python. O notebook ensina a realizar operações CRUD (Criar, Ler, Atualizar, Deletar) e a iterar sobre chaves, valores e itens.

### 4. Funções e Pacotes
Entenda como criar suas próprias funções para modularizar e reutilizar código. Aprenda a definir funções com parâmetros e a retornar um ou múltiplos valores, um conceito fundamental para a programação eficiente.

### 5. Pandas Básico
O coração do notebook. Esta seção oferece uma imersão na biblioteca Pandas, cobrindo:
-   **Criação de `Series` e `DataFrames`** a partir de listas, dicionários e arquivos externos.
-   **Técnicas de seleção e fatiamento de dados** usando indexação, `.loc` e `.iloc`, permitindo que você acesse qualquer parte do seu DataFrame com precisão.
-   **Filtragem de dados** para encontrar informações específicas através de queries e máscaras booleanas.
-   **Cálculo de novas colunas**, como a `Km_media`, para enriquecer o dataset.
-   **Tratamento de valores ausentes (NaN)**, uma etapa crucial em qualquer projeto de análise de dados, ensinando a identificar, remover ou substituir esses valores.

## 🚀 Como Executar

Para executar este notebook em sua máquina local, siga os passos abaixo.

### Pré-requisitos
-   Python 3.7 ou superior
-   Jupyter Notebook ou JupyterLab (geralmente incluído em distribuições como Anaconda)

### Passos
1.  Clone o repositório:
    ```bash
    git clone https://github.com/sergiocalazans/Python_para_Data_Science_Pandas.git
    ```

2.  Navegue até o diretório clonado:
    ```bash
    cd Python_para_Data_Science_Pandas
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
5.  Abra o arquivo `Python_para_Data_Science_Pandas.ipynb` e execute as células.

Alternativamente, você pode abrir o notebook diretamente no **Google Colab** clicando no badge abaixo, sem necessidade de instalação local.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Gunga-16/Python_para_Data_Science_Pandas/blob/main/Python_para_Data_Science_Pandas.ipynb)
