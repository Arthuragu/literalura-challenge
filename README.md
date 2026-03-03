# 📚 Literalura - Catálogo de Livros e Autores

Projeto desenvolvido em Java utilizando Spring Boot com o objetivo de criar um sistema para armazenar e consultar livros e autores em um banco de dados relacional.

---

## 🚀 Objetivo do Projeto

Criar uma aplicação que:

- Armazene livros e autores em um banco de dados
- Permita consultas com diferentes filtros
- Demonstre o uso de JPA, Hibernate e PostgreSQL
- Simule um cenário real de desenvolvimento Back-End

---

## 🗃 Modelagem do Banco de Dados

### 📘 Autor
- id
- nome
- dataNascimento
- dataFalecimento

### 📗 Livro
- id
- titulo
- idioma
- numeroDownloads
- autor_id (chave estrangeira)

### 🔗 Relacionamento

Um autor pode ter vários livros:


## 🛠 Tecnologias Utilizadas

- ☕ Java 17+
- 🌱 Spring Boot
- 🗄 Spring Data JPA
- 🐘 PostgreSQL
- 🔧 Maven
