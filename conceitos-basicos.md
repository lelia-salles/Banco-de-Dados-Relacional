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

**A**tomicidade
**C**onsistência
**I**solamento**
**D**urabilidade
