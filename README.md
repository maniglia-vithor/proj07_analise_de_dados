# Análise de Dados com Python

Este projeto realiza uma **análise exploratória de dados (EDA)** utilizando a linguagem Python, com foco em dados de vendas comerciais. O objetivo é explorar, limpar, transformar, analisar e visualizar os dados de forma prática, gerando insights úteis para decisões de negócio.

##  Funcionalidades

- **Importação e visualização de dados** de planilhas Excel com `pandas`.
- **Limpeza de dados**:
  - Renomeação de colunas,
  - Preenchimento de valores nulos,
  - Conversão de tipos (float, datetime),
  - Remoção de duplicatas.
- **Análise exploratória**:
  - Total de vendas acumulado,
  - Categorias mais vendidas,
  - Relação entre prioridade de entrega e vendas por país,
  - Impacto dos descontos por subcategoria,
  - Cálculo do ticket médio por país.
- **Visualizações com gráficos**:
  - Barras, pizza e gráficos empilhados com `matplotlib` e `seaborn`.

##  Tecnologias Usadas

- **Python 3**
- **pandas**
- **matplotlib**
- **seaborn**

##  Estrutura Esperada

Para que o script funcione corretamente, é necessário:

- Um arquivo `.xlsx` com os dados de vendas, configurado no caminho correto dentro do código Python:
  ```python
  caminho_arquivo = '/content/drive/MyDrive/FATEC/04LinguagemProgramacao I Aulas/12 RP07 Análise de Dados com Python.xlsx'
