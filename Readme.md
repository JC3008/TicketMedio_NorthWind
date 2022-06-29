# Este projeto apresenta a criação de um pipeline que carrega dados do Northwind para o AWS S3, bem como o tratamento dos dados dentro do datalake, processamento em cluster Spark usando o Glue, e modelagem de consulta e análise Athena/Power BI.

## Metodologia da solução:
Os arquivos disponibilizados foram carregados para o AWS S3, utilizando Python Boto3, e logo após foram carregados e catalogados utilizando o AWS GLUE, para que finalmente fossem disponibilizados para consulta via AWS ATHENA. 
Para modelagem da consulta, foi usada a ferramenta Power BI usando o Athena como fonte de dados. Todos os scripts utilizados e arquivo do Power BI serão disponibilizados em repositório Github informado 
# North_Wind_Case
