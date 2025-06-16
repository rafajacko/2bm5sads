📋 Descrição do Projeto
Este é um projeto de API RESTful desenvolvido com Spring Boot, com autenticação via JWT (JSON Web Token) e controle de acesso baseado em roles (admin e user). O objetivo é fornecer uma aplicação web simples com cadastro de usuários, autenticação segura e controle de permissões por perfil.

---

✅ Cadastro de Usuários
Registro de novos usuários com:
Nome
E-mail
Senha (armazenada de forma segura com hash)
Role: user ou admin

✅ Autenticação com JWT
Login com validação de credenciais.
Geração de token JWT após login bem-sucedido.
Requisições aos endpoints protegidos devem conter o token JWT válido no cabeçalho Authorization.

---

🛠️ Tecnologias Utilizadas
Java 17
Spring Boot
Spring Security
JWT (JSON Web Token)
Spring Data JPA
MySQL (Banco de dados relacional)

---

Configuração do Banco de Dados (MySQL):
1. Crie um banco de dados:

CREATE DATABASE spring_jwt_demo;

2. Configure as credenciais no arquivo application.properties ou application.yml:
spring.datasource.url=jdbc:mysql://localhost:3306/spring_jwt_demo
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true


---

▶️ Como Executar o Projeto
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/seu-repositorio.git
Importe o projeto em sua IDE.

Execute a aplicação:

bash
Copiar
Editar
mvn spring-boot:run
A aplicação ficará disponível por padrão em:

arduino
Copiar
Editar
http://localhost:8080
