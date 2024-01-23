# Banco de Dados

## SGBD
Sistema *gerenciador* de banco de dados
 
 **Banco de Dados**
 -É um sistema que vai armezenar dados e possiu feramentas para gerenciar dados.
 Banco de dados é um mine mundo.
 
 **Tabelas ou entidade**
 -Tabelas são as estruturas onde fica armazenados os dados.

 **Tipo de banco de dados**
 -Relacional ou não relacinal.

 **Coluna**
 -Campos ou atributos.

 **Linhas ou tupla**
 -Registro


# Trabalhando com uma SQL#

## Conectando : mysql -h localhost -u root
-h : host(computador que vc vai entrar)
-u : usuario
-p : senha

 show databases;  : ele mostra os bancos de dados do meu servidor.

 drop database :apaga banco de dados
 
 delete : apaga linha

 ; :sempre encerra o comando

use : qual banco de dados ira usar

create table : cria tabela

() : banco de dados

desc : mostra a estrutura da tabela

show tables : `exibe a estrutura da tabela`

## desc
mostra todas as tabelas

## show tables
exibe as tabelas que existe

\! cls :limpar tela

# comandos SQL
## DDL - DEFINIÇÃO DE DADOS
-`create database`

-`show databases`

-`create table`

-`show tables`

-`desc nome_da_tabela`

## DML - MANIPULAÇÃO DE DADOS
-`select * from nnome_da_tabela`

-`insert into nome_da_tabela(campo1, campo2 ...) values(valor1, valor2 ...)`

1. O que é um Sistema Gerenciador de Banco de Dados?
É um software projetado para gerenciar e facilitar o armazenamento, a organização, a recuperação e a manipulação eficientes de dados em um banco de dados. Os bancos de dados são estruturas que permitem armazenar grandes volumes de informações de forma organizada, para que possam ser facilmente acessadas, atualizadas e gerenciadas.
2. O que é um Banco de dados relacional?
é um tipo de banco de dados que organiza dados em tabelas relacionadas entre si.
Nesse modelo, os dados são organizados em tabelas bidimensionais chamadas relações, e as relações entre essas tabelas são estabelecidas com base em chaves.
3. O que é T-SQL?
é uma extensão da linguagem SQL (Structured Query Language) que é específica para os produtos da Microsoft, especialmente o Microsoft SQL Server. Desenvolvida pela Microsoft, o T-SQL inclui várias extensões e funcionalidades adicionais que não estão presentes no SQL padrão.
4. O que é PL/SQL?
é uma extensão procedural da linguagem SQL (Structured Query Language) desenvolvida pela Oracle Corporation. Assim como o T-SQL está associado ao Microsoft SQL Server, o PL/SQL é usado nos produtos de banco de dados Oracle, como o Oracle Database.
5. T-SQL e PL/SQL são iguais? Caso não sejam, cite 3 diferenças entre elas.

6. O Que é:
T-SQL (Transact-SQL) e PL/SQL (Procedural Language/Structured Query Language) tenham propósitos semelhantes e compartilhem algumas características por serem extensões de SQL
A. DML: MANIPULAÇÃO DE DADOS

B. DDL: DEFINIÇÃO DE DADOS

C. DCL : CONTOLE DE DADOS
