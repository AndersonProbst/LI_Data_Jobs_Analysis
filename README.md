# LI_Data_Jobs_Analysis

# Análise dos skills mais requisitados nas vagas de Data Analyst, Data Scientis, Data Engineer

# Objetivo

A partir de um Dataset com vagas do linkedIn na área de dados, descobrir quais são os skills mais requisitados, e ver relações entre as diferentes áreas de análise, ciência, e engenharia de dados.

# Estrutura do repositório

- `Data\`
   Contém os arquivos de dados
   - `clean_jobs.csv` (dataset obtido do Kaggle com as vagas disponíveis)
   - `skills_por_cargo` (dataset criado após filtragem dos dados)

- `Notebook\`
   Contém o notebook usado no jupyter
   - `LinkedinDataset.ipynb` (Notebook usado para tratamento e análise dos dados)

- `Tableau\`
   Contém os dashboards e books usados no tableau para demonstração dos dados
   - `book1.twb` (book do tableau)
   - `book1.twbx` (book do tableau, versão pública)
   - `dashboard 1.png` (Dashboard com top 5 skills por cargo)
   - `dashboard 2.png` (Dashboard comparando os cargos e mostrando as skills mais relevantes em geral)

- `README.md`
  Arquivo com descrição do projeto.


# Metodologia
  - `Carregamento e pré-processamento` dos dados com Python e Pandas, focando nas colunas de título e descrição das vagas.
  - `Agrupamento de títulos similares` para padronizar cargos como "Data Analyst", "Data Scientist" e "Data Engineer".
  - `Extração e contagem das habilidades técnicas` mais mencionadas nas descrições das vagas, utilizando expressões regulares para identificar termos-chave (ex: Python, SQL, Power BI).
  - `Comparação das demandas de skills` entre os diferentes cargos.
  - `Visualização dos resultados com Tableau` para facilitar a interpretação e apresentação dos dados.

# Insights Principais:
  - `Python e SQL` são essenciais em todos os cargos.
  - Data Analysts demandam mais ferramentas de visualização `(Power BI, Tableau)`.
  - Data Scientists têm foco em `Machine Learning`.
  - Data Engineers priorizam `cloud (Azure/AWS)` e processamento distribuído `(Spark)`.
  - `Excel` tem baixa relevância para Data Scientists e Data Engineers, indicando foco em ferramentas mais avançadas. Ainda apresenta alguma demanda para Data Analysts

# Ferramnetas Utilizadas
  - `Python` com bibliotecas:
    - `pandas` para manipulação e análise de dados.
    - `re` para expressões regulares na extração de skills.
    - `collections.Counter` para contagem de palavras.
  - `Tableau` para criação de dashboards e visualizações interativas.
  - `Git e GitHub` para publicação do projeto.
  - `Jupyter` para desenvolvimento.


Fique à vontade para explorar o projeto, abrir issues ou sugerir melhorias!

Projeto desenvolvido por **`Anderson Probst`**
