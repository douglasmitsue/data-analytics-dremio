![arquitetura_dremio](https://github.com/douglasmitsue/data-analytics-dremio/blob/main/dremio.jpg)
## Automação de Pipeline de Dados
### Um pouco sobre o Dremio
O Dremio é uma plataforma de código aberto que ajuda Analistas e Cientistas de Dados a trabalhar juntos para descobrir, organizar e colaborar em diversos casos de uso analítico. Baseia-se  no  Apache  Arrow  para  acelerar  consultas  em  uma  variedade  de  fontes  de  dados  como Amazon S3, HDFS, bancos NoSQL e bancos de dados relacionais. Os dados podem ser analisados por meio de ferramentas de BI, incluindo Looker, Power BI, Python, Qlik, Spark, SQL  e  Tableau,  entre  outros.

Resolve  o  desafio  de  tornar  os  dados  rápidos  e  de  autoatendimento  para  os  consumidores de dados, eliminando o risco de criação, gerenciamento e governança associado a cópias de dados desnecessárias. Inclui recursos avançados para cargas de trabalho  corporativas,  incluindo  controles  de  segurança  abrangentes,  linhagem  de  dados,  recursos  de  aceleração  de  dados  avançados,  um  modelo  de  implantação  elástico  e  conectores  para fontes de dados populares.Também  faz  parte  da  plataforma a  Iniciativa  Gandiva  para  Apache  Arrow.  

## Apache  Arrow
Este  kernel de execução oferece eficiência até 100x maior em muitos tipos de consultas e operações. Essa eficiência aprimorada se traduz em custos operacionais mais baixos, melhor experiência do usuário e capacidade de suportar mais cargas de trabalho com o hardware existente.

#### A visão do Dremio é tornar os Engenheiros de Dados mais produtivos enquanto torna os consumidores de dados mais autossuficientes.

A imagem a seguir mostra o que o Dremio é capaz de fazer.

![arquitetura_dremio](https://github.com/douglasmitsue/data-analytics-dremio/blob/main/arquitetura-dremio.jpg)

#### Documentação com os passos iniciais: https://docs.dremio.com/cloud/test-drive/

### Projeto 1 - Self Service Data Analytics com a plataforma Dremio
Para este projeto o objetivo será construir um Pipeline de Dados a partir de um Data Lake com  Apache  Hadoop.  
Faremos  a  análise  de  planilhas  de  dados  diretamente  do  Data  Lake  com  poucos cliques, em alta velocidade e seguindo o conceito de Self-Service Analytics. 
Após a criação do Pipeline faremos a análise com o Microsoft Power BI.
Criaremos  Virtual  Datasets  e  Data  Reflections,  bem  como  trabalharemos  na  gestão  e  curadoria dos metadados.
Para o projeto faremos o Deploy do Dremio On-Premises com Docker e criaremos o Data Lake com Apache Hadoop HDFS.

### Arquitetura Projeto 1 

## Vamos começar.

### Criando um ambiente a partir do Zero:
[arquivo_configuracao_ambiente]()

### Implementando o Data Lake com Apache Hadoop HDFS
[arquivo_implementando_hdfs]()

### Implementando o Dremio
[arquivo_configuracao_dremio]()

