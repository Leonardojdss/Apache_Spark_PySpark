# Apache_Spark_PySpark

Fundamentos do Apache Spark
Este projeto tem como objetivo fornecer uma introdução prática ao Apache Spark utilizando PySpark para análise de dados da Receita Federal. O notebook inclui etapas para configuração do ambiente, leitura e processamento dos dados, manipulação de DataFrames, execução de consultas SQL e visualização de resultados. Abaixo está uma descrição detalhada das seções e operações realizadas no notebook.

Estrutura do Notebook
0 - Instanciando o Spark
Configuração do Ambiente:

Instalação do JDK JAVA e Spark.
Configuração das variáveis de ambiente SPARK_HOME e JAVA_HOME.
Inicialização do Spark:

Importação da biblioteca findspark para facilitar a configuração do PySpark no Python.
Criação de uma instância de SparkSession.
1 - Carregar Dados com Spark
Criação de um DataFrame:

Criação de um DataFrame simples a partir de uma lista de dados.
Carregamento de Dados CSV:

Leitura de arquivos CSV contendo dados de empresas, estabelecimentos e sócios.
Contagem do número de registros em cada arquivo.
2 - Manipulação
Tratamento Básico:

Renomeação de colunas dos DataFrames empresas, estabelecimentos e socios.
Análise dos schemas dos dados.
Conversão de Tipos de Dados:

Conversão de colunas de string para double e de string para date.
Comandos Essenciais:

Realização de consultas (SELECT).
Extração de informações dos dados.
Identificação e contagem de valores nulos.
Substituição de valores nulos em campos inteiros e strings.
Ordenação dos dados.
Criação de filtros.
Utilização do método LIKE.
Utilização do comando WHEN.
Sumarização de Dados:

Agrupamento e agregações.
Cálculo de contagem e média.
Estatísticas descritivas.
Joins:

Realização de diferentes tipos de joins (inner, left, right, outer).
Joins com os dados de empresas e estabelecimentos.
2.4 Utilizar SQL no SparkSQL
Consultas SQL:
Criação de views e execução de consultas SQL para filtrar, agrupar e calcular estatísticas.
2.5 Armazenamento
Saída CSV:

Exportação dos DataFrames para arquivos CSV.
Saída Parquet:

Exportação dos DataFrames para arquivos Parquet.
2.6 Particionamento
Particionamento de Arquivos:
Particionamento de arquivos CSV e Parquet.
3 - Conclusão
Conclusão sobre a utilidade do Spark para processar grandes volumes de dados em ambientes corporativos.
Como Executar
Configuração do Ambiente:

Siga as instruções para instalar o JDK JAVA e o Spark.
Configure as variáveis de ambiente SPARK_HOME e JAVA_HOME.
Execução do Notebook:

Utilize um ambiente Jupyter Notebook para executar o arquivo Fundamentos_Apache_Spark.ipynb.
Análise dos Resultados:

Siga as etapas descritas no notebook para carregar, manipular e analisar os dados.
Conclusão
Este notebook demonstra como utilizar PySpark para manipulação e análise de grandes volumes de dados, ilustrando o potencial do Apache Spark em aplicações de Big Data.

