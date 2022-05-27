
# Boas vindas ao repositório do projeto All For One

## Sumário

- [Introdução](#introdução)
- [Desenvolvimento](#desenvolvimento)
- [Instruções para restaurar o banco de dados Northwind](#instruções-para-restaurar-o-banco-de-dados-northwind)

---

## Introdução

Hoje você encontrará um projeto com o codinome *All For One* em que praticará todos os conceitos de SQL. Que utiliza um banco de dados diferente o `Northwind`.

---

## Desenvolvimento

Temos, nesse projeto, All For One, um banco de dados populado, permitindo a executação de queries com o intuito de encontrar as informações.

Para cada desafio, foi criado um arquivo SQL e sua solução nele, um arquivo na pasta raiz do projeto chamado desafioN.sql.

O arquivo contém apenas o código SQL do desafio resolvido.

Ex.:
```sql
SELECT * FROM northwind.orders;
```

---

## Instruções para restaurar o banco de dados `Northwind`

1. Faça o download do arquivo de backup [aqui](northwind.sql) clicando em "Raw", depois clicando com botão direito e selecionando "Salvar como" para salvar o arquivo em seu computador.
2. Abra o arquivo com algum editor de texto, e selecione todo o conteúdo do arquivo usando `CTRL-A`.
3. Abra o MySQL Workbench.
4. Abra uma nova janela de query e cole dentro dela todo o conteúdo do arquivo `northwind.sql`.
5. Selecione todo o código com o atalho `CTRL-A` e depois clique no icone de raio para executar a query.

    ![Restaurando o banco Northwind](images/restore_northwind.png)
6. Aguarde alguns segundos (espere em torno de 30 segundos antes de tentar fazer algo).
7. Clique no botão apontado na imagem a seguir para atualizar a listagem de banco de dados.

    ![Tabelas do banco Northwind](images/refresh_databases.png)
7. Verifique se o banco restaurado possui todas as seguintes tabelas:

    ![Tabelas do banco Northwind](images/northwind.png)
8. Clique com botão direito em cada tabela e selecione "Select Rows" e certifique-se que todas as tabelas possuem registros. Caso tenha alguma faltando, faça o passo a seguir. Caso contrário, pode ir para próxima seção.
9. Caso existam tabelas faltando, drope o banco de dados, clicando com o botão direito em cima do banco de dados northwind e selecionando "Drop Schema", e refaça os passos novamente, dessa vez aguardando um tempo maior quando executar o script de restauração.

    ![Drop Schema](images/drop_database.png)

---
