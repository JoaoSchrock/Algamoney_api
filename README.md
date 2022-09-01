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

## JSON

```Java
Mesmo que se assemelhe à sintaxe literal do objeto JavaScript, ele pode ser usado independentemente
do JavaScript, e muitos ambientes de programação possuem a capacidade de ler (analisar) e gerar JSON
O JSON existe como uma string — útil quando você deseja transmitir dados por uma rede.


{
    "nome": "João Schrock",
    "idade": "17",
    "Estado Civil": "Solteiro"
}
```

## Spring Initializr

![Captura da Web_1-9-2022_195522_start spring io](https://user-images.githubusercontent.com/101228590/188026103-8f384712-89cd-4f7e-b0a3-bcf920e8bb66.jpeg)

```
SPRING INITIALIZR fornece uma interface web bem simples para o usuário. Podendo gerar 
seu projeto a partir de uma estrutura de configurações pré-moldadas. São configurações 
de versões do java/spring boot, grupo/nome do projeto, série de lista de dependências e etc.

```








