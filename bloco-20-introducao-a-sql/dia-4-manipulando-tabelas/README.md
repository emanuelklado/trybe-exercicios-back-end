1. Backticks ou crase ( `` ) : São usadas para identificar nome de tabelas e colunas . São necessárias apenas quando o identificador for uma palavra reservada do MySQL , ou quando o nome da tabela ou coluna contiver espaços em branco.

2. Aspas simples ( '' ) : Devem ser usadas em valores do tipo string . Elas são aceitas na maioria dos SGBDs. Sendo assim, é mais preferível usar aspas simples em véz das aspas duplas.

- INSERT INTO - Serve para inserir dados em uma tabela:

```
INSERT INTO nome_da_tabela (coluna1, coluna2)
VALUES ('valor_coluna1', 'valor_coluna2');
```