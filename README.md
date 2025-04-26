# DataScienceAnalytics

Este repositório contém uma coleção de mini projetos e estudos na área de **Data Science** e **Analytics**. Cada pasta dentro deste repositório representa um projeto distinto, focando em técnicas e abordagens variadas de análise de dados.

## Projetos

Aqui estão os mini projetos incluídos neste repositório:

### 1. **[Análise de Dados com Pandas](projeto_pandas)**
- **Descrição**: Este projeto utiliza a biblioteca **Pandas** para manipulação e análise de dados. Ele se foca em técnicas de limpeza, transformação e visualização de dados para análise exploratória.
- **Tecnologias utilizadas**: Python, Pandas, Matplotlib.
- **Instruções**: 
    - Clone o repositório e entre na pasta:
      ```bash
      git clone https://github.com/alan-csantos/DataScienceAnalytics.git
      cd projeto_pandas
      ```
    - Instale as dependências:
      ```bash
      pip install -r requirements.txt
      ```
    - Execute o script principal ou Jupyter notebook:
      ```bash
      python main.py
      # Ou execute o notebook diretamente no Jupyter:
      jupyter notebook analise_dados.ipynb
      ```

### 2. **[Modelo de Machine Learning para Classificação](projeto_classificacao)**
- **Descrição**: Este projeto explora o uso de **modelos de Machine Learning** para classificação de dados. Utiliza a biblioteca **Scikit-learn** para treinar e avaliar modelos de classificação.
- **Tecnologias utilizadas**: Python, Scikit-learn, Pandas, Matplotlib.
- **Instruções**:
    - Clone o repositório e entre na pasta:
      ```bash
      git clone https://github.com/alan-csantos/DataScienceAnalytics.git
      cd projeto_classificacao
      ```
    - Instale as dependências:
      ```bash
      pip install -r requirements.txt
      ```
    - Execute o script de treinamento e avaliação do modelo:
      ```bash
      python classificador.py
      ```

### 3. **[Análise de Séries Temporais](projeto_series_temporais)**
- **Descrição**: Neste projeto, são utilizadas técnicas de **análise de séries temporais** para prever tendências em dados temporais. O projeto pode usar modelos como **ARIMA** ou **Prophet**.
- **Tecnologias utilizadas**: Python, Pandas, Matplotlib, Statsmodels.
- **Instruções**:
    - Clone o repositório e entre na pasta:
      ```bash
      git clone https://github.com/alan-csantos/DataScienceAnalytics.git
      cd projeto_series_temporais
      ```
    - Instale as dependências:
      ```bash
      pip install -r requirements.txt
      ```
    - Execute o script de análise:
      ```bash
      python analise_temporal.py
      ```

### 4. **[Análise Exploratória de Dados (EDA)](projeto_eda)**
- **Descrição**: Este projeto realiza uma **análise exploratória de dados** (EDA) com o objetivo de entender a estrutura e as características dos dados antes de qualquer modelagem.
- **Tecnologias utilizadas**: Python, Pandas, Seaborn, Matplotlib.
- **Instruções**:
    - Clone o repositório e entre na pasta:
      ```bash
      git clone https://github.com/alan-csantos/DataScienceAnalytics.git
      cd projeto_eda
      ```
    - Instale as dependências:
      ```bash
      pip install -r requirements.txt
      ```
    - Execute o script de análise:
      ```bash
      python eda.py
      ```

### 5. **[Projeto de Análise de Dados com SQL](projeto_sql)**
- **Descrição**: Este projeto se concentra em análise de dados utilizando **SQL** para extrair e transformar dados de um banco de dados relacional.
- **Tecnologias utilizadas**: PostgreSQL, SQL, Python.
- **Instruções**:
    - Clone o repositório e entre na pasta:
      ```bash
      git clone https://github.com/alan-csantos/DataScienceAnalytics.git
      cd projeto_sql
      ```
    - Conecte-se ao banco de dados (certifique-se de configurar o PostgreSQL corretamente):
      ```bash
      psql -h localhost -U usuario -d nome_do_banco
      ```
    - Execute as queries conforme necessário para análise de dados.

## Como rodar os projetos

Para rodar qualquer um dos projetos, siga os passos abaixo:

1. Clone este repositório:
    ```bash
    git clone https://github.com/alan-csantos/DataScienceAnalytics.git
    ```

2. Entre na pasta do projeto desejado:
    ```bash
    cd DataScienceAnalytics/nome_da_pasta_do_projeto
    ```

3. Instale as dependências (se houver um arquivo `requirements.txt`):
    ```bash
    pip install -r requirements.txt
    ```

4. Execute o script principal ou notebook:
    - Para scripts Python:
        ```bash
        python nome_do_script.py
        ```
    - Para notebooks Jupyter:
        ```bash
        jupyter notebook nome_do_notebook.ipynb
        ```

## Estrutura do repositório

Aqui está a estrutura geral deste repositório:

