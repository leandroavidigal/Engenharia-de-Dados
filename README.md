# Engenharia-de-Dados

MÓDULO 1: Fundamentos em arquitetura de dados e soluções em Nuvem
 
Capítulo 1 - Fundamentos em Arquitetura de Dados 
1.1 Por quê ir para a cloud? 
1.2 Well Architected Framework - O que define uma “boa” arquitetura? 
1.3 Pilar Excelência Operacional 
1.4 Pilar Segurança 
1.5 Pilar Confiabilidade 
1.6 Pilar Eficiência de Performance  
1.7 Pilar Otimização de custos  
 
Capítulo 2 - Modelos de Arquiteturas de Dados em Nuvem 
2.1. Databases gerenciados - Relacional  
2.2.  Databases gerenciados - Não relacional  
2.3.  Data Lake - Desenho da Arquitetura  
2.4.  Data Lake - Armazenamento  
2.5.  Data Lake - Ingestão de dados  
2.6.  Data Lake - Processamento de Big Data  
2.7.  Data Lake - Consumo de Dados - DW e Engines  
 
Capítulo 3 - Prática 
3.1.  Database em nuvem com AWS RDS  
3.2.  Data Lake com AWS S3  
3.3.  Extração de Dados com AWS DMS  
3.4.  Processamento de Big Data com AWS EMR  
3.5.  Processamento de Big Data com AWS Glue  
3.6.  Disponibilização de Dados com AWS Athena  
 
Capítulo 4 - IaC - Infraestrutura como código 
4.1.  Ferramentas de IaC  
4.2.  Terraform - Uso básico  
4.3.  Controle de versão de código com Github  
4.4.  Esteiras de deploy com Github  
 
Capítulo 5 - Use Cases - Prática 
5.1.  Data LakeHouse com Delta Lake e EMR  
5.2.  Streaming de Dados com AWS Kinesis  
5.3.  Orquestrando Pipelines com Airflow  
 
Capítulo 6 - Encerramento - Resumo, outras ferramentas e próximos passos
 

MÓDULO 2: Tecnologias de Big Data - Processamento de dados massivos
 
Capítulo 1. Introdução ao Spark e à Engenharia de Dados
1.1. Big Data e Engenharia de Dados
1.2. Engenharia de Dados + Ciência de Dados
1.3. Introdução ao Apache Spark
1.4. Estudos de Caso
1.5 Vantagens e Desvantagens do Spark
 
Capítulo 2 Conceitos Fundamentais do Spark
2.1. Instalando o Apache Spark
2.2. Nosso primeiro programa com Spark: Contando números
2.3. A arquitetura do Apache Spark
2.4. Transformações e ações no Apache Spark
2.5 Desempenho de Operações no Apache Spark
 
Capítulo 3 A API de Dataframes
3.1. Introdução aos Dataframes
3.2. Transformações sobre Dataframes
3.3. Estatística Descritiva com Dataframes
 
Capítulo 4 Spark SQL
4.1. A Linguagem SQL e Engenharia de Dados
4.2. Consultas com Spark SQL
4.3. Formatos de Dados
4.4. Fontes de Dados
4.5. Usando UDFs no Spark
 
Capítulo 5 Processamento de fluxos de dados contínuos
5.1. O que são streams?
5.2. Construindo aplicações com Spark Streaming
5.3. Um exemplo de aplicação
 
Capítulo 6  Outros módulos do Spark
6.1. Spark ML
6.2. Spark GraphX
 
Capítulo 7 O Spark na Nuvem
7.1. Vantagens de soluções em nuvem
7.2.   O Spark e os principais provedores de nuvem


MÓDULO 3: Desenho de arquiteturas de dados escaláveis
 
Capítulo 1. Arquitetura de Microsserviços 
1.1. Escalabilidade
1.2. Microsserviços
 
Capítulo 2.  Docker
2.1. Máquinas Virtuais vs Containers
2.2. Docker: principais conceitos
2.3. Instalando o Docker no Windows
2.4. Instalando o Docker no Linux
2.5. Docker: comandos básicos
2.6. Criando imagens
2.7 Repositórios remotos
 
Capítulo 3. Kubernetes: introdução e instalação
3.1. Kubernetes: conceitos e arquitetura
3.2.  Instalando o Minikube no Windows
3.3. Instalando o Minikube no Linux
3.4. Provisionando um cluster na GCP
3.5. Provisionando um cluster na AWS
 
Capítulo 4. Kubernetes: criando, expondo e escalando aplicações
4.1. Pods
4.2. Services
4.3. Secrets e ConfigMaps
4.4. ReplicaSets
 
Capítulo 5. Kubernetes: gerenciando aplicações e persistindo dados
5.1. Deployments
5.2. StorageClasses, PersistentVolumes e PersistentVolumeClaim
5.3. StatefulSets
5.4. Liveness e Readiness Probes
5.5 HorizontalPodAutoscaler
 
Capítulo 6. Helm Charts
6.1. Introdução
6.2. Deploy do Airflow Helm Chart
 
Capítulo 7. Operators
7.1. Introdução
7.2. Deploy do Spark Operator
 
Capítulo 8. Monitoramento
8.1. Coletando métricas com o Prometheus 
8.2. Criando Dashboards com Grafana 
 
 
MÓDULO 4: Processamento de Fluxos Contínuos de Dados
 
Capítulo 1 - Introdução a Event Stream, Stream Processing Applications, cases de sucesso
1.1 Event Stream 
1.2 Stream Processing 
1.3 Introdução ao Apache Kafka [Kafka Producer, Offsets, Brokers, Consumers] 
1.4 Stream processing [KsqlDB e Spark Streaming] 
 
Capítulo 2 - Arquitetura de Sistemas de Stream
2.1.  Arquiteturas orientadas a evento 
2.2.  Lambda Architecture 
2.3.  Kappa Architecture 
 
Capítulo 3 - Patterns Use cases 
3.1. Data Lake, Data Lakehouse e Evolução Histórica 
 
Capítulo 4 - Novos storages para armazenar dados em tempo real
4.1. Apache Druid - O que é? Para que serve? Como usar?  
4.2. Apache Pinot - O que é? Para que serve? Como usar? 
 
Capítulo 5 - Hands-on
5.1. Entendimento do projeto prático
         5.1.1. Explicação do Projeto e Configuração de Ambiente
5.2. Montando a infraestrutura na prática
          5.2.1. Deploy do EKS
          5.2.2. Deploy Cluster Kafka no Kubernetes [EKs]
5.3. Use cases - Prática
         5.3.1. Deploy do Kafka Connect e Criação do primeiro tópico no Kafka
        5.3.2. Configuração do Sink Connector e Deploy do KsqlDB
        5.3.3. Deploy do Apache Pinot
 

