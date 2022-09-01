# Framework
### 1- Algamoney

- ### [01 - API ](https://github.com/JoaoSchrock/Framework/tree/main/FRAMEWORK/src/)

---
## PARA ESCREVER NO - resources (application.properties)
```
spring.jpa.database=MYSQL
spring.datasource.url=jdbc:mysql://localhost/demo?createDatabaseIfNotExist=true&useSSL=false
spring.datasource.username=root
spring.datasource.password=123456

spring.jpa.show-sql=true

spring.jackson.deserialization.fail-on-unknown-properties=true

```

## Criando Aluno - Resources - db.Migration
```
CREATE TABLE aluno(
codigo BIGINT(20) PRIMARY KEY AUTO_INCREMENT,
nome VARCHAR(50) NOT NULL

)ENGINE=InnoDB DEFAULT CHARSET=utf8;

INSERT INTO aluno (nome) values ('João silva');
INSERT INTO aluno (nome) values ('João Pereira');
INSERT INTO aluno (nome) values ('Maria Silva');

}

```
## Site para Testar junto com o postman

```
Link do Site : https://designer.mocky.io/design

```
## ID

```
È um identificador

```








