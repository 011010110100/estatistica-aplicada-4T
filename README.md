# estatistica-aplicada-4T
Projeto de etatística aplicada para o 4 trimestre da PUCRS

# Análise Estatística de Dados de Jogadores da FIFA

Este repositório contém a análise estatística do banco de dados de jogadores de futebol registrados na FIFA.

## Descrição

O objetivo deste projeto é aplicar técnicas de Estatística Descritiva para sumarizar e analisar os dados do arquivo `Anexo_Projeto_fifa_world_national_teams_versão_oficial_20241.csv`.

## Conteúdo

* `Dados/Anexo_Projeto_fifa.../`: Arquivo contendo o banco de dados em formato CSV
* `Dados/Dicionario/`: Arquivo contendo explicações sobre os dados
* `analise_estatistica.ipynb`: Notebook Jupyter com a análise estatística dos dados, incluindo:
    * Identificação e listagem de variáveis qualitativas (nominal e ordinal) e quantitativas (discreta e contínua).
    * Tabelas de frequência para duas variáveis qualitativas.
    * Tabela com medidas de posição e variabilidade para cinco variáveis quantitativas.
    * Dois gráficos criativos para visualização dos resultados.
    * Histograma ou gráfico de barras para verificação de adequabilidade de um modelo probabilístico.

## Metodologia

A análise foi realizada utilizando a linguagem Python e as bibliotecas Pandas, NumPy, Matplotlib. O notebook `analise_estatistica.ipynb` contém o código e as explicações detalhadas de cada etapa da análise.

## Como Executar

-- Criar o ambiente virtual
    python -m venv venv

-- Ativar o ambiente virtual (Windows)
    venv\Scripts\activate

-- Ativar o ambiente virtual (Linux)
    source venv/bin/activate

--  Instalar dependências a partir do requirements.txt
    pip install -r requirements.txt

## Referências

* Banco de dados: [https://github.com/filipezabala/pucrs-tecnologo-bd](https://github.com/filipezabala/pucrs-tecnologo-bd)
* Modelo de relatório: [https://colab.research.google.com/drive/15xlP2Aonze12SAsBruHrHpcqOy-AeZYA?usp=sharing](https://colab.research.google.com/drive/15xlP2Aonze12SAsBruHrHpcqOy-AeZYA?usp=sharing)
* Automobile Data Set: [https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data](https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data)