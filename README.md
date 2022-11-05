# airbyte-dbt-airflow-snowflake-metabase
Repositório para armazenar os artefatos do Pipeline utilizando Modern Data Stack com AirByte + DBT + Airflow + SnowFlake + Metabase


Tarefas:

Infraestrutura:

- Subir o Airbyte via docker X

- Subir o Airflow via docker X

- Subir o Metabase via docker X

- Criar o script de execução X

- Testar a Execução X

- Criar a Conta no Dbt Cloud X

- Criar a Conta no SnowFlake X

- Snowflake Data Warehouse:
    
    - Verificando a existência das tabelas X
    - Obtenção dos links de conexão e nome da conta X


Extração:

- No Airbyte:

    - Conectar com as origens baseadas nos Csvs X
    - Criar as entidades no snowflake através do script base da documentação    X
    - Conectar o destino no snowflake X
    - Criar as conexões do airbyte associando as origens ao destino X
    - Testar as conexões X


Preparação:

- No Airbyte:

    - Local Staging (Desenvolvimento)
    - Cloud Staging (Produção)


Transformação:

- No Dbt:

    - Criação da Conta
    - Conexão com o Github
    - Criação do Dbt Project
    - Criação do Profile de conexão com o snowflake
    - Criação do Schema
    - Criação dos Modelos Base
    - Criação do Modelo Relacionado
    - Visualização gráfica do modelo
    - Teste de execução
    - Commits, Branches, Pull Requests, Merges no Github
    - Obtenção do link de conexão com o Airbyte


Visualização:

- No Metabase:

    - Conectar Metabase com o Snowflake
    - Criar uma Question
    - Criar um Dashboard
    - Adicionar uma Question
    - Visualizar o Resultado


Orquestração:

- No Airflow:

    - Criar a dag

    - Criar as conexões com o Airbyte através do script

    - Testar a execução do pipeline