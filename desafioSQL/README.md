# Criar e consultar as três tabelas criadas

Usando o "SELECT" você consegue listar as tabelas e com o "JOIN" você consegue consultar as 3 tabelas Tendo alguma coisa que esteja iguais nelas.

SELECT PAIS.NOME, PAIS.SIGLA, ESTADO.NOME, ESTADO.SIGLA, CIDADE.NOME FROM PAIS JOIN ESTADO ON PAIS.ID = ESTADO.ID_PAIS JOIN CIDADE ON ESTADO.ID = CIDADE.ID_ESTADO;

![Captura de Tela 2022-08-23 às 18 38 05](https://user-images.githubusercontent.com/69183396/186271247-dda9f8d9-36aa-4aa6-8ae1-d8a47c55a214.png)

O "JOIN" Está linkando o PAIS com o ESTADO com o id Dos dois e a mesma coisa entre ESTADO E CIDADE.
