# Etapa 05 - Projeto final

## Apresentação Final do Projeto

Os slides podem ser visualizados em [slides](slides/MC356_Final.pdf).

## Motivação e Contexto

Devido a pandemia presente no ano de 2020, achamos relevante analisar dados referentes ao novo Coronavírus a fim de relacioná-los às características socioeconômicas de diversos países. Dessa forma, podemos utilizar dados referentes à saúde, educação e índices econômicos para determinar como tais fatores refletem na resposta de cada país perante a pandemia.

## Método

A metodologia do projeto seguirá o seguinte esquema:

![Metodologia](assets/Metodologia.png)

## Modelo Conceitual Inicial

![ModeloC](assets/Modelo-Conceitual.png)

## Modelos Lógicos Iniciais

![ModeloL](assets/Modelo-Logico.png)

## Tratamento dos dados

O conjunto de requests está em [WorldBank](notebooks/tratamento_dados_worldBank.ipynb) e [WorldBank](notebooks/insere_dados_worldBank_no_postgres.ipynb).

## Queries

O conjunto de queries está em [Queries](notebooks/WordBank_queries.ipynb).

## Bases de Dados

| Base   |  Link  |  Descrição |
|----------|:-------------:|------:|
| Covid-19 Dataset |  https://covid19api.com/ | Dados variados sobre COVID-19 de cada país, como, por exemplo, total de casos, total de mortes, etc. |
| World Development Dataset |    https://databank.worldbank.org/source/world-development-indicators   |  Dataset tabular contendo diversas informações e indicadores sobre a economia, saúde, aspectos da população em geral, entre outras áreas.  |
| World Education Dataset | https://databank.worldbank.org/source/education-statistics-%5e-all-indicators | Dataset contém informações variadas sobre a educação de diversos países. |


## Arquivos de Dados

nome do arquivo | link | breve descrição
----- | ----- | -----
`countries.csv` | [link](../stage04/data/countries.csv) | `Lista de países e seus códigos`
`fist_case.csv` | [link](../stage04/data/first_case.csv) | `Lista de países e seus primeiros casos de covid`
`summary.csv` | [link](../stage04/data/summary.csv) | `Lista de países e dados gerais sonbre a covid`
`world_development_indicators.csv` | [link](../stage04/data/world_development_indicators.csv) | `Lista de países e diversos indicatores agrupados nas tabelas do modelo lógico`
