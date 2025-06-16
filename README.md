# Projeto Java - Autenticação JWT com Spring Boot

Este é um projeto Java utilizando Spring Boot, com autenticação baseada em JWT (JSON Web Token) e controle de acesso por papéis (roles): `USER` e `ADMIN`.

## ✅ Funcionalidades

- Cadastro de usuários
- Login e geração de token JWT
- Segurança com Spring Security
- Controle de acesso baseado em roles
- Filtro de autenticação para proteger endpoints

## 🧰 Tecnologias utilizadas

- Java 17
- Spring Boot
- Spring Security
- JWT (jjwt)
- MySQL (configurável)
- Maven

## 🔧 Como rodar o projeto

1. Instale o JDK 17
2. Crie um banco de dados MySQL chamado `demo` (ou altere no `application.properties`)
3. Clone o projeto e abra no IntelliJ
4. Configure o `application.properties` com suas credenciais do MySQL:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/demo
spring.datasource.username=root
spring.datasource.password=senha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

5. Rode o projeto pelo método main da classe DemoApplication
