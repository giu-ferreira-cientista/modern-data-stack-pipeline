# airbyte-dbt-airflow-snowflake-metabase
Repositório para armazenar os artefatos do Pipeline utilizando Modern Data Stack com AirByte + DBT + Airflow + SnowFlake + Metabase


Tarefas:

Infraestrutura:

- Subir o Airbyte via docker 

- Subir o Airflow via docker 

- Subir o Metabase via docker 

- Criar o script de execução 

- Testar a Execução 

- Criar a Conta no Dbt Cloud 

- Criar a Conta no SnowFlake 

- Snowflake Data Warehouse:
    
    - Verificando a existência das tabelas 
    - Obtenção dos links de conexão e nome da conta 


Extração:

- No Airbyte:

    - Conectar com as origens baseadas nos Csvs 
    - Criar as entidades no snowflake através do script base da documentação    
    - Conectar o destino no snowflake 
    - Criar as conexões do airbyte associando as origens ao destino 
    - Testar as conexões 


Preparação:

- No Airbyte (Destination Loading Method):

    - Local Staging (Ambiente de Desenvolvimento)
    - Cloud Staging (Ambiente de Produção)


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


Encerramento:

- Material de Apoio:

    - Links 

    - Códigos fonte

    - Apresentação
	