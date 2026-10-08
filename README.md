# InfoShop

Sistema de gestão para loja de informática. Cadastro de produtos, vendas, compras e locação.

## Tecnologias

- Java 21
- Spring Boot
- Spring Data JPA / Hibernate
- PostgreSQL
- Thymeleaf
- Maven

## Como rodar

1. Cria o banco no PostgreSQL:
   CREATE DATABASE infoshop;

2. Cria um arquivo `.env` na raiz do projeto com:
   DB_URL=jdbc:postgresql://localhost:5432/infoshop
   DB_USERNAME=postgres
   DB_PASSWORD=sua_senha

3. Roda:
   ./mvnw spring-boot:run

4. Acessa: http://localhost:8080

## Status

Projeto em desenvolvimento.