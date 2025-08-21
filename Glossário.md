Glossário

01\) **S.G.B.D**: Sistema responsável pelo controle de usuários, distribuição e organização dos dados e seu

armazenamento, controlar o acesso aos dados conforme o perfil de cada usuário, Gera e controla log de atividades

02\) **Entidade**: Tabela no Banco de Dados (Arquivo) / Eu - Agrupamento de Dados representando uma ideia no DB

03\) **Atributo**: **Campo** em uma tabela de Banco de Dados

04\) **Tupla: Registro** (todos os atributos de um mesmo individuo)

05\) **Dado**: **Menor unidade** informacional (que sozinho não tem significado)

06\) **Informação**: Conjunto de **dados logicamente sequenciados**

07\) **Conhecimento**: Conjunto de **informações** organizadas **para** permitir **a tomada de decisões**

08\) **Relacional**: Relação entre entidades permitindo o **acesso** aos dados **para gerar informações**

09\) **D.B.A**: Data Base Administrator (cria bancos, usuários, tabelas, acessos)

10\) **A.D**.: Administrador de Dados (Modelar - Criar entidades e definir relacionamentos)

11\) **PK** - Primary Key: **Identificador único** - Ex: Um campo ou conjuntos de campos para identificar um registro de forma única

12\) **FK** - Foreign Key: **Identificador único de outra entidade** Chave Estrangeira (Atributo para associação entre entidades, sempre chamando uma PK)

13\) **Integridade Referencial**: Capacidade do SGBD garantir a **correta relação adequada entre as chaves**

14\) **Constraint**: É **Restrição** de operação para **garantir a integridade** **do banco** (ex.: Unique Constraint, Foreign Key Constraint)

15\) **Unique Constraint: Restrição** de chave primária (garantir unicidade do registro)

16\) **Transação**: Operação do BD que abre uma nova área de memória (ram) que pode ser finalizada de duas formas -> Rollback ou Commit

&nbsp;	17) **Rollback**: Desfaz as operações desde o início da última abertura de 'transação'

&nbsp;	18) **Commit**: Salvar, grava no BD operações desde a última abertura de 'transação'

19\) **Start Transaction**: Começa a transação

20\) **Schema**: Delimitação Lógica no BD para organização dos dados, podendo conter SubSchemas

21\) **M.E.R**. : Modelo de Entidades e Relacionamentos - Descrição gráfica de todas as tabelas e suas relações no sistema

22\) **Sequence**: Controle realizado pelo SGBD para garantir o incremento de geração de um atributo numérico (Sequencia) EX: PK - (Primary Key), ID

23\) **SQL**: Structed Query Language - Linguagem de consulta estruturada: Desenvolvida 1980, **permitindo consultas** em base de dados, **divida em DDL e DML**

&nbsp;	24) **DDL**: Data Definition Language - Linguagem de Definição de Dados - Criação de Tabelas, exclusão, altera-lás e etc.

&nbsp;	25) **DML**: Data Manipulation Language - Linguagem de Manipulação de Dados - 

26\) **Cardinalidade**: É um **relação numérica** entre entidades, podendo ser (**1:1, 1:n, n:1, n:n** nesse último é necessária uma entidade fraca)

27\) **Entidade Fraca:** - **AKA entidade de relacionamento**, Entidade que **depende de outras tabelas e** suas **FK** de outras para existir, também é **exclusiva de n:n**

28\) **Stored Procedure:** Função escrita em SQL que pode ser chamada várias vezes

29\) **Trigger:** É a configuração de um evento

&nbsp;	a) Before insert

&nbsp;	b) After insert

 	c) Before select

 	d) After select

&nbsp;	e) Before update

 	f) After update

 	g) Before delete

 	h) After delete

30\) **DW**

**31) Rollback:** Desfaz as operações





**Melhorias:**



Constraint essencialmente são FK



Dois tipos de exclusão: 

&nbsp;	Física: Delete, **PERMANENTE**

&nbsp;	Lógica: Delete, **DESATIVADO** para o sistema

