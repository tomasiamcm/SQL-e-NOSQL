<h1> O papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) </h1>

<h4>
Um Banco de Dados Relacional é tem como caracteristica principal armazenar os dados em formato de tabelas, onde as colunas são campos que epresentam as caracteristicas e as linhas representam os registros.



Normalmente, o banco de dados relacionais é utilizado para reduzir as anomolias e para proteger o seu banco de perda de integridade. 

Ele é baseado no modelo relacional, uma forma intuitiva e direta de representar os dados em tabelas, que também são chamados de relações. Em resumo: na horizontal, temos as linhas e na vertical as colunas. Cada coluna representa um campo diferente de dados e informações.

A maior característica desse modelo é a necessidade da estruturação de esquemas, projetando uma estrutura de relacionamento entre as linhas e colunas para, assim, poder adicionar algum dado.

No banco de dados não relacional (NoSQL), os esquemas não são necessários. Eles representam qualquer banco ligado à Big Data e não seguem o modelo relacional fornecido pelos sistemas tradicionais de gerenciamento de dados. São diversos tipos, como o key-value stores, graph stores, column stores, document stores, entre outros.

O banco de dados não relacional surgiu como uma alternativa para situações em que há uma quantidade exorbitante de dados para armazenar, onde a estruturação em tabelas se torna mais difícil.


Os bancos de dados relacionais armazenam dados de acordo com esquemas específicos. Por outro lado, os sistemas NoSQL permitem que os dados sejam armazenados usando qualquer estrutura necessária, mas fornece uma maneira de atualizar esses dados ao alterar essa estrutura.

A linguagem SQL (Structured Query Language) é usada para executar comandos em bancos de dados relacionais, que são os bancos baseados em tabelas.

Bancos de dados relacionais, como os do MySQL e PostgreSQL, armazenam dados usando um esquema explícito. Um esquema descreve como gravar dados no banco de dados, particularmente descrevendo a estrutura, tipos e estruturas de tabelas e registros.

Os termos ‘SQL’ e ‘NoSQL’ referem-se essencialmente a como esses esquemas são definidos. Em um banco de dados relacional, os usuários usam as instruções SELECT, INSERT e DELETE para adicionar ou atualizar dados.

O banco de dados NoSQL refere-se a um banco de dados não relacional.

Um banco de dados relacional é um formato de banco de dados rigidamente estruturado, baseado em tabelas, como – por exemplo- o MySQL ou o Oracle. Os bancos de dados NoSQL são documentados e permitem que você armazene e recupere dados em formatos diferentes das tabelas. Plataformas Populares NoSQL incluem MongoDB, ElasticSearch e Redis.

As aplicações modernas utilizam e geram tipos de dados complexos e em evolução. Os bancos de dados relacionais não foram projetados para lidar com esse tipo de armazenamento e recuperação de dados. Os bancos de dados NoSQL são mais flexíveis e escaláveis.

Em um Banco de Dados NoSQL, você pode adicionar novos dados sem ter que pré-definido no esquema do banco de dados, permitindo o processamento rápido de grandes volumes de dados não estruturados, semiestruturados e estruturados.

O esquema dinâmico dos bancos de dados NoSQL aceita prontamente o desenvolvimento ágil, o que requer iterações significativas e rápidas.

O termo NoSQL possui duas definições com origens diferentes, uma fazendo referência ao banco de dados RELACIONAL que não utilizava linguagem SQL para queries (consultas) criado por Carlo Strozzi e outra relacionada ao movimento NoSQL que define um co


SQL é uma linguagem padrão para trabalhar com bancos de dados relacionais. Ela é uma linguagem declarativa e que não necessita de profundos conhecimentos de programação para que alguém possa começar a escrever queries, as consultas e pedidps, que trazem resultados de acordo com o que você está buscando. SQL significa Standard Query Language, literalmente a linguagem padrão para realizar queries.

A linguagem SQL é utilizada de maneira relativamente parecida entre os principais bancos de dados relacionais do mercado: Oracle, MySQL, MariaDB, PostgreSQL, Microsoft SQL Server, entre muitos outros. Cada um tem suas características, sendo o MySQL e o PostgreSQL extremamente populares por possuírem versões gratuitas e de código aberto.


DML - Linguagem de Manipulação de Dados
O primeiro grupo é a DML (Data Manipulation Language - Linguagem de manipulação de dados). DML é um subconjunto da linguagem SQL que é utilizado para realizar inclusões, consultas, alterações e exclusões de dados presentes em registros. Estas tarefas podem ser executadas em vários registros de diversas tabelas ao mesmo tempo. Os comandos que realizam respectivamente as funções acima referidas são INSERT, UPDATE e DELETE.

DDL - Linguagem de Definição de Dados
O segundo grupo é a DDL (Data Definition Language - Linguagem de Definição de Dados). Uma DDL permite ao utilizador definir tabelas novas e elementos associados. A maioria dos bancos de dados de SQL comerciais tem extensões proprietárias no DDL.

DCL - Linguagem de Controle de Dados
O terceiro grupo é o DCL (Data Control Language - Linguagem de Controle de Dados). DCL controla os aspectos de autorização de dados e licenças de usuários para controlar quem tem acesso para ver ou manipular dados dentro do banco de dados.

DTL - Linguagem de Transação de Dados
BEGIN WORK - (ou BEGIN TRANSACTION, dependendo do dialeto SQL) - pode ser usado para marcar o começo de uma transação de banco de dados que pode ser completada ou não.
COMMIT - finaliza uma transação dentro de um sistema de gerenciamento de banco de dados.
ROLLBACK - faz com que as mudanças nos dados existentes desde o último COMMIT ou ROLLBACK sejam descartadas.
COMMIT e ROLLBACK interagem com áreas de controle como transação e locação. Ambos terminam qualquer transação aberta e liberam qualquer cadeado ligado a dados. Na ausência de um BEGIN WORK ou uma declaração semelhante, a semântica de SQL é dependente da implementação.

DQL - Linguagem de Consulta de Dados
Embora tenha apenas um comando, a DQL é a parte da SQL mais utilizada. O comando SELECT permite ao usuário especificar uma consulta ("query") como uma descrição do resultado desejado. Esse comando é composto de várias cláusulas e opções, possibilitando elaborar consultas das mais simples às mais elaboradas.

</h4>


xistem alguns tipos de banco de dados não relacionais que seria o banco de documentos (objetos JSON), e Chave-Valor (mais simples). 

Normalmente, o banco de dados não relacionais é utilizado para armazenar grandes quantidades de dados e para armazenar em nuvem. 