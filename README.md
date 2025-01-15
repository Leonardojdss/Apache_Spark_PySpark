# Apache_Spark_PySpark - Desenvolvidor por Leonardo José da Silva (Eu)

# Fundamentos do Apache Spark

Este projeto tem como objetivo fornecer uma introdução prática ao Apache Spark utilizando PySpark para análise de dados da Receita Federal. O notebook inclui etapas para configuração do ambiente, leitura e processamento dos dados, manipulação de DataFrames, execução de consultas SQL e visualização de resultados. Abaixo está uma descrição detalhada das seções e operações realizadas no notebook.

## Estrutura do Notebook

### 0 - Instanciando o Spark

1. **Configuração do Ambiente**:
   - Instalação do JDK JAVA e Spark.
   - Configuração das variáveis de ambiente `SPARK_HOME` e `JAVA_HOME`.

2. **Inicialização do Spark**:
   - Importação da biblioteca `findspark` para facilitar a configuração do PySpark no Python.
   - Criação de uma instância de `SparkSession`.

### 1 - Carregar Dados com Spark

1. **Criação de um DataFrame**:
   - Criação de um DataFrame simples a partir de uma lista de dados.

2. **Carregamento de Dados CSV**:
   - Leitura de arquivos CSV contendo dados de empresas, estabelecimentos e sócios.
   - Contagem do número de registros em cada arquivo.

### 2 - Manipulação

1. **Tratamento Básico**:
   - Renomeação de colunas dos DataFrames `empresas`, `estabelecimentos` e `socios`.
   - Análise dos schemas dos dados.

2. **Conversão de Tipos de Dados**:
   - Conversão de colunas de string para double e de string para date.

3. **Comandos Essenciais**:
   - Realização de consultas (`SELECT`).
   - Extração de informações dos dados.
   - Identificação e contagem de valores nulos.
   - Substituição de valores nulos em campos inteiros e strings.
   - Ordenação dos dados.
   - Criação de filtros.
   - Utilização do método `LIKE`.
   - Utilização do comando `WHEN`.

4. **Sumarização de Dados**:
   - Agrupamento e agregações.
   - Cálculo de contagem e média.
   - Estatísticas descritivas.

5. **Joins**:
   - Realização de diferentes tipos de joins (inner, left, right, outer).
   - Joins com os dados de empresas e estabelecimentos.

### 2.4 Utilizar SQL no SparkSQL

1. **Consultas SQL**:
   - Criação de views e execução de consultas SQL para filtrar, agrupar e calcular estatísticas.

### 2.5 Armazenamento

1. **Saída CSV**:
   - Exportação dos DataFrames para arquivos CSV.

2. **Saída Parquet**:
   - Exportação dos DataFrames para arquivos Parquet.

### 2.6 Particionamento

1. **Particionamento de Arquivos**:
   - Particionamento de arquivos CSV e Parquet.

### 3 - Conclusão

- Conclusão sobre a utilidade do Spark para processar grandes volumes de dados em ambientes corporativos.

## Como Executar

1. **Configuração do Ambiente**:
   - Siga as instruções para instalar o JDK JAVA e o Spark.
   - Configure as variáveis de ambiente `SPARK_HOME` e `JAVA_HOME`.

2. **Execução do Notebook**:
   - Utilize um ambiente Jupyter Notebook para executar o arquivo [`PySpark_essencial/Projeto_Dados_Receita_Federal/Fundamentos_Apache_Spark.ipynb`](PySpark_essencial/Projeto_Dados_Receita_Federal/Fundamentos_Apache_Spark.ipynb).

3. **Análise dos Resultados**:
   - Siga as etapas descritas no notebook para carregar, manipular e analisar os dados.

## Conclusão

Este notebook demonstra como utilizar PySpark para manipulação e análise de grandes volumes de dados, ilustrando o potencial do Apache Spark em aplicações de Big Data.
