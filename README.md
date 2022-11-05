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

    - Criação da Conta X
    - Conexão com o Github X
    - Criação do Dbt Project X
    - Criação do Profile de conexão com o snowflake X
    - Criação do Schema X
    - Criação dos Modelos Base X
    - Criação do Modelo Relacionado X
    - Visualização gráfica do modelo X 
    - Teste de execução X
    - Commits, Branches, Pull Requests, Merges no Github X 
    - Obtenção do link de conexão com o Airbyte X 


Visualização:

- No Metabase:

    - Conectar Metabase com o Snowflake X
    - Criar uma Question X 
    - Criar um Dashboard X
    - Adicionar uma Question X
    - Visualizar o Resultado X 


Orquestração:

- No Airflow:

    - Criar a dag X 

    - Criar as conexões com o Airbyte através do script X 

    - Testar a execução do pipeline  