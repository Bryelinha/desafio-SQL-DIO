# desafio-SQL-DIO
 Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados
Modelo Relacional é a aplicação de determinadas regras sobre a tabela do banco de dados de forma a garantir o projeto adequado dessas tabelas.
Um conceito básico consiste na separação de dados referentes a elementos distintos em tabelas distintas, associadas através da utilização das chaves. Essas regras permitem um armazenamento consistente e um eficiente acesso aos dados, reduzindo redundâncias e diminuindo as chances dos dados se tornarem inconsistentes
A linguagem SQL é responsável por fazer a comunicação entre o SGBD e o BD.
A SQL se divide em DML (DataManipulation Language), DDL (Data Definition Language) a DCL (Data Control Language) e aDQL (Data Query Language)
DML São os comandos que irão manipular o conteúdo das tabelas estes comandos são: SELECT  UPDATE  DELETE  INSERT
DDL São os comandos que irão definir a criação do conteúdo das tabelas estes comandos são: CREATE  ALTER  DROP
DQL como SELECT 
os bancos de dados relacionais seguem o modelo ACID para preservar a integridade de uma transação.
Este conjunto de procedimentos é dividido em quatro propriedades, e são elas:
    Atomicidade: As ações que compõe a ação da transação devem ser concluídas com sucesso para ser efetivada. Se esta transação falhar, será feito o rollback.
    Consistência: Todas as regras e restrições descritas no banco de dados devem ser obedecidas garantindo que o banco de dados passe de uma forma consistente para outra forma consistente.
    Isolamento: Neste caso, a propriedade de isolamento garante que a transição não será interferida por nenhuma outra transação concorrente.
    Durabilidade: Os resultados salvos não são perdidos
Os principais problemas encontrados com a utilização do Modelo Relacional estão principalmente na dificuldade de conciliar o tipo de modelo com a demanda da escalabilidade que está cada vez mais frequente
temos quatro categorias do NoSQL que as diferenciam entre si:
    Chave-valor (key-value): Este modelo permite a sua visualização através de uma tabela de hash, no qual há uma chave única e um indicador de determinado dado, podendo ser uma String
ou um binário
Banco de Dados Orientado a Documento: este modelo armazena coleções e documentos
Orientado a Coluna (column family): mais complexo que o de chave-valor. Este tipo de banco de dados foi criado para armazenar e processar uma grande quantidade de dados distribuídos em diversas máquinas
Orientado a Grafos: este modelo possui três componentes básicos: nós (vértices dos grafos), os relacionamentos (arestas) e as propriedades (conhecidos também como atributos)
Resumindo: o conceito de modelo relacional (SQL) se baseia no fato de que todos os dados sejam guardados em tabelas. Ao modelo não-relacional (NoSQL) não se aplica o conceito de schema: uma chave de valor é que é utilizada para recuperar valores, conjunto de colunas ou documentos
O NoSQL tem muitas vantagens para ser utilizado, mas não devemos utilizá-lo em todas as situações. Em muitos sistemas, podemos usar o modelo relacional.
O NoSQL é mais indicado para aqueles sistemas que tenham necessidades maiores de armazenamento e desempenho.
O NoSQL não veio para substituir o SQL, mas sim para oferecer mais uma alternativa de um banco de dados mais flexível no suporte de dados.
Por isso, o mais comum em soluções escalares de sucesso é a utilização de uma arquitetura híbrida, aproveitando o melhor dois dois modelos.
