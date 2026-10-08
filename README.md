\# InfoShop



Sistema de gestão para loja de informática — produtos, vendas, compras e locação.



\## Tecnologias



\- Java 21

\- Spring Boot

\- Spring Data JPA + Hibernate

\- PostgreSQL

\- Thymeleaf

\- Maven



\## Como rodar



\### 1. Pré-requisitos



\- Java 21+

\- PostgreSQL

\- Maven



\### 2. Criar o banco



```sql

CREATE DATABASE infoshop;

```



\### 3. Configurar o `.env`



Cria um arquivo `.env` na raiz do projeto:



```

DB\_URL=jdbc:postgresql://localhost:5432/infoshop

DB\_USERNAME=postgres

DB\_PASSWORD=sua\_senha

```



\### 4. Rodar



```bash

./mvnw spring-boot:run

```



Acesse: http://localhost:8080



\## Status



Em desenvolvimento 🚧

