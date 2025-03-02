# Vegan Queen API

Teste a aplicação aqui: https://b-q-api.herokuapp.com/

## Índice

* [1. Apresentação](#1-apresentação)
* [2. End-Points](#2-end-points)
* [3. Fluxograma](#3-fluxograma)
* [4. Tecnologias Utilizadas](#4-tecnologias-utilizadas)
* [5. Melhorias Futuras](#5-melhorias-futuras)

## 1. Apresentação

Vegan Queen API é uma aplicação web desenvolvida para atender à necessidade sob demanda do restaurante sob mesmo nome, que já possui a interface front end desenvolvida e necessitava do back end em formato de API Rest e conexão com banco de dados. Este projeto foi proposto pela Laboratória, cujo objetivo é aprendizagem de programação back end, utilizando o restaurante fíctício Vegan Queen como exemplo, cuja interface este <a href="https://www.github.com/BiancaSherika/vegan-queen">repositório</a>.

As demandas do restaurante que o projeto atende são: criação e atualização de cadastro de funcionários, armazenar e visualizar produtos padrões, armazenar e visualizar comandas de pedidos e mudança de status dos pedidos conforme etapas de preparo.

## 2. End-Points

A aplicação possui os seguintes End-Points:

#### 2.1 `/users`

* `GET /users`
* `GET /users/:uid`
* `POST /users`
* `PUT /users/:uid`
* `DELETE /users/:uid`

#### 2.2 `/products`

* `GET /products`
* `GET /products/:productid`
* `POST /products`
* `PUT /products/:productid`
* `DELETE /products/:productid`

#### 2.3 `/orders`

* `GET /orders`
* `GET /orders/:orderId`
* `POST /orders`
* `PUT /orders/:orderId`
* `DELETE /orders/:orderId`

## 3. Fluxograma

A estruturação das tabelas e suas relações está exemplificado aqui: 

![](/server/img/fluxograma.png)

## 4. Tecnologias Utilizadas

- Node.js
- JavaScript
- Git e GitHub
- Express
- Sequelize
- Heroku
- PostgreSQL
- Insomnia
- Dbeaver
- Swagger UI
- VsCode 
 
## 5. Melhorias Futuras

Para as proximas refatorações serão implementados:

* End-Point `POST /auth`
* Middleware de autenticação
* Middleware de erros
* Documentação da API
* Testes unitários
* Testes _e2e_
* Docker
