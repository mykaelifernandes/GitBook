---
description: >-
  Ou base de Dados, É qualquer forma de armazenar dados que após processados
  geram informações para o usuário.
---

# Banco de Dados

Todo dado tem um tipo correspondente, se não conseguirmos determinar o tipo, poderemos ter problemas para obter as informações: perdê-las ou armazenar de forma errada.

| Tipo       | Conjunto            | Mais Usado |
| ---------- | ------------------- | ---------- |
| Texto      | char,varchar,text   | char       |
| Inteiro    | int,bigint,smallint | int        |
| Decimal    | decimal,float       | decimal    |
| Data/Hora  | date,time,datetime  | date       |
| Lógico     | boolean             | boolean    |
| Estrutural | blob,json           | json       |
| Binário    | blob                | blob       |

## Existem dois modelos de banco de Dados:

### 1. Relacionais

1.Organizado por tabelas e colunas.

2\. Relacionamento entre tabelas.

3.Linguagem SQL para manipulação de dados.

4.Suporte para transações isoladas ACID.

### 2. No SQL (Não relacional-ausência de estrutura)

1.Diferentes modelos de armazenamento.

2.Estrutura de dados flexíveis.

3.Alta performance com grande volume de dados.

{% hint style="info" %}
Pesquisar quais são os bancos desses modelos.
{% endhint %}

#### Linguagem SQL

Assim como Java é uma linguagem de programação, o próprio banco de dados possui a sua linguagem, que é a comunicação, que o desenvolvedor interage.

Linguagem de consulta estruturada - SQL através dela operamos na estrutura da base de dados,manipulação e seleção de registros, gerando informações de negócio.

* DQL - SELECT&#x20;
* DML - INSERT,UPDATE,DELETE (MANIPULAÇÃO DE REGISTRO)
* DDL - CREATE,ALTER,DROP (PARTE ESTRUTURAL: CÓDIGO,ENDEREÇO,NÚM,TEL)&#x20;
* DCL - GRANT,REVOKE }&#x20;
* DTL - BEGIN,COMMIT,ROLLBACK } GESTÃO DE UM BANCO DE DADOS



1. ESTRUTURAMOS DDL
2. INSERIMOS OS DADOS,ALTERAMOS OU EXCLUIMOS DML
3. OBTER OS DADOS DQL

{% hint style="info" %}
PROGRAMAÇÃO ORIENTADA A MANIPULAÇÃO DE DADOS.
{% endhint %}

QUESTIONAMENTOS PARA ADQUIRIR CAPACIDADE DE INTERPRETAÇÃO DE NEGÓCIO:&#x20;

&#x20;1.QUAIS SERIAM AS TABELAS DO SISTEMA?&#x20;

&#x20;2.QUAIS SERIAM OS CAMPOS EM CADA TABELA?

&#x20;3.QUAL TIPO DE DADO ADEQUADO PARA CADA CAMPO?
