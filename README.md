# Aplicação em Container
Este projeto contém uma aplicação feita em node.js através de um curso na plataforma Alura que apresenta uma estrutura onde existem 3 aplicações que conversam com o banco de dados através dos containers.

## Criando a imagem
Primeiro execute o comando: <br/>
```javascript
docker-compose build
```
Esse comando irá criar as imagens necessárias para criar os containers
<br/>
<br/>
Em seguida execute o comando: <br/>
```javascript
docker-compose up
```
O comando acima irá criar os containers e os inciará.

## Visualizando a aplicação
Digite a seguinte url no navegador:

>http://localhost:2080
>
>

Para visualizar os livros que são obtidos do banco de dados digite o seguinte: <br>
>http://localhost:2080/seed
>
>
E em seguida digite:
>http://localhost:2080
>
>