# O que é um banco de dados?

## Conceito

Coleção organizada de informações ou dados estruturados armazenados em um sistema eletrônicos. Existem banco de dados não computadorizados como biblliotecas arquivos físicos, entre outros

## Tipo de Banco de Dados

* Relacionais/SQL
* Não Relacionais/NoSQL (Not OnlySQL)
* Orientado a Objetos
* Hierárquico

## O que é SGBD?

Um banco de dados não é auto gerenciável por isso existem sistemas de gerenciamento de banco deo dados chamados de SGBD. Fornecem conjunto de ferramentas e recursos para criar, manipular, consultar e adminstrar dados e segurança.

## Funcionalidades Básicas

```CRUD```
**C****reate
**R**ead
**U**pdate
**D**elete

## Estrutura básica de um BD Relacional

Composto por um BD onde será armazenado conjunto de tabelas que podem relacionar-se entre em si.

### Tabelas

Tabelas são compostas por colunas onde são armazenadas atributos de uma determinada entidade. Cada atributo deve ser armazenado em uma coluna diferente

### Registro

O registro ou linha ou tupla, são informações armazenadas em si, ou seja informações de uma entidade armazenadas em colunas são chamadas de registro.

### Relacionamentos

Dependem das chaves primárias que são identificadores únicos dos registros das tabelas e chaves estrangeiras que sinalizam que existe um relacionamento entre as tabelas

## Características Básicas do BD

* Relacionamento entre tabelas - informações são relacionadas entre si para compor informações mais relevantes
* Linguagem de consulta estruturada (SQL) permite o relacionamento
* Integridade referencial - relacionamento são referencias entre tabelas e o sistema garante a integridade desse relacionamento
* Normalização de dados - forma de estruturação de colunas 
* Segurança - gerenciamento seguro de acesso aos dados
* Flexibilidade e extensibilidade - alteração dos schemas
*Suporte e transações ACID - garantia da consistência da informação dentro do BD

### ACID
Conjunto de propriedade que garante confiabilidade e segurnça
**A**tomicidade - garante a execução bem sucedida de operaçãoes - erros em operaçãoe não são salvas.
**C**onsistência - a operação deve sair de um estado para outro onde ambas são consistentes
**I**solamento** - cada transação é executada de forma isolada sem interferir nas transações concorrentes para evitar acesso incorreto ou incosistencia de dados. Ex. Uma transação é feita após a outra e não ao mesmo tempo
**D**urabilidade - quando a transação é confirmada a informação não é revertida ao estado anterior.

[O que é um Banco de Dados Relacional?](https://www.oracle.com/br/database/what-is-a-relational-database/)
