# Titanic Data Analysis

Este repositório contém uma análise detalhada dos dados do famoso desastre do RMS Titanic. Usando técnicas de Data Science e Machine Learning, exploramos os fatores que influenciaram as chances de sobrevivência dos passageir

### Objetivos
* Explorar os dados para obter insights importantes
* Visualizar as principais características que afetaram a sobrevivência
* Aplicar algoritmos de Machine Learning para prever sobrevivência com base nos dados dos passageiros

### Ferramentas utilizadas
* Python: Linguagem de programação principal
* Pandas: Para manipulação e análise de dados
* Seaborn & Matplotlib: Para visualizações de dados
* Scikit-learn: Para algoritmos de Machine Learning

### Análises realizadas

* Exploração de dados: Visualizações para entender as relações entre variáveis.
* Tratamento de dados faltantes: Lidando com valores ausentes.
* Engenharia de recursos: Criação de novas variáveis úteis.
* Modelagem: Teste de modelos preditivos como Regressão Logística, Random Forest e K-Nearest Neighbors.



### Organização de diretórios
```
.
├── data/              # Diretório contendo todos os arquivos de dados
│   ├── external/      # Arquivos de dados de fontes externas
│   ├── interim/       # Arquivos de dados intermediários
│   ├── processed/     # Arquivos de dados processados
│   └── raw/           # Arquivos de dados originais, imutáveis
├── docs/              # Documentação gerada através da biblioteca mkdocs
├── models/            # Modelos treinados e serializados, predições ou resumos de modelos
├── notebooks/         # Diretório contendo todos os notebooks utilizados nos passos
├── references/        # Dicionários de dados, manuais e todo o material exploratório
├── src/               # Código fonte utilizado nesse projeto
│   ├── data/          # Classes e funções utilizadas para download e processamento de dados
│   ├── deployment/    # Classes e funções utilizadas para implantação do modelo
│   └── model/         # Classes e funções utilizadas para modelagem
├── app.py             # Arquivo com o código da aplicação do streamlit
├── Procfile           # Arquivo de configuração do heroku
├── pyproject.toml     # Arquivo de dependências para reprodução do projeto
├── poetry.lock        # Arquivo com sub-dependências do projeto principal
├── README.md          # Informações gerais do projeto
└── tasks.py           # Arquivo com funções para criação de tarefas utilizadas pelo invoke

```
