
# 📊 Análise Exploratória de Renda e Perfil de Clientes

Este é um projeto de estudo em análise de dados (realizado em meados de 2023) que tem como objetivo explorar e avaliar a composição de renda de uma base de clientes. Através de uma abordagem exploratória com Jupyter Notebooks, o estudo investiga a relação entre a renda, o estado civil e outros fatores demográficos, buscando insights sobre o perfil dos clientes.

-----

## 🎯 Objetivos do Estudo

O estudo é dividido em etapas, cada uma focada em uma análise específica:

  * **Análise Geral da Renda:** Explorar a distribuição e as principais características da renda presente no dataset.
  * **Perfil do Cliente por Estado Civil:** Analisar como o perfil dos clientes se distribui entre os diferentes estados civis.
  * **Métricas de Renda:** Calcular métricas estatísticas, como média e outras medidas de tendência central da renda, para diferentes grupos.
  * **Relação Renda vs. Estado Civil:** Fazer uma análise aprofundada da relação entre a renda e o estado civil, buscando padrões e variações.

-----

## 🛠️ Tecnologias Utilizadas

  * **Python:** Linguagem de programação principal.
  * **Jupyter Notebook:** Ambiente interativo utilizado para a análise e visualização dos dados.
  * **Pandas:** Biblioteca para manipulação e análise de dados.
  * **Outras bibliotecas (esperadas):** `matplotlib` ou `seaborn` para visualização de dados (gráficos), e `numpy` para operações numéricas.

-----

## 📁 Estrutura do Projeto

  * `Dataset.csv`: O arquivo de dados que serve como base para todas as análises.
  * `analise_renda.ipynb`: Notebook principal que contém a análise geral da renda.
  * `cliente_estado_civil.ipynb`: Notebook focado na análise demográfica dos clientes, com ênfase no estado civil.
  * `media.ipynb`: Notebook com a finalidade de calcular e apresentar métricas estatísticas, como a média de renda.
  * `renda_estado_civil.ipynb`: Notebook que aprofunda a análise da relação entre a renda e o estado civil.
  * `.venv/`: Ambiente virtual do Python, utilizado para isolar as dependências do projeto.

-----

## ▶️ Como Executar

Para rodar este projeto, é necessário ter o Python e o Jupyter instalados.

1.  Clone o repositório.
2.  Crie e ative um ambiente virtual.
3.  Instale as dependências:
    ```bash
    pip install pandas jupyter matplotlib seaborn
    ```
4.  Inicie o Jupyter Notebook na pasta do projeto:
    ```bash
    jupyter notebook
    ```
5.  Abra os notebooks (`.ipynb`) e execute as células para visualizar a análise.
