
![Captura da Web_1-9-2022_211055_www bing com](https://user-images.githubusercontent.com/101228590/188032774-db86a0ed-a91c-43b1-b290-c10055351e1a.jpeg)

# Framework
### 1- Algamoney

- ### [01 - API ](https://github.com/JoaoSchrock/Framework/tree/main/FRAMEWORK/src/)

---
## PARA ESCREVER NO - resources (application.properties)
```json
spring.jpa.database=MYSQL
spring.datasource.url=jdbc:mysql://localhost/demo?createDatabaseIfNotExist=true&useSSL=false
spring.datasource.username=root
spring.datasource.password=123456

spring.jpa.show-sql=true

spring.jackson.deserialization.fail-on-unknown-properties=true

```

## Criando Aluno - Resources - db.Migration
```Java
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
![Captura da Web_1-9-2022_20230_designer mocky io](https://user-images.githubusercontent.com/101228590/188026782-463f6138-7337-4dab-9047-a6b4cb2b18e7.jpeg)

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
## API

![API_Infografico4](https://user-images.githubusercontent.com/101228590/188027174-b4dbe4f1-d8ff-4df6-ae4b-d3535aa9290b.png)
 
![Captura da Web_1-9-2022_20818_www bing com](https://user-images.githubusercontent.com/101228590/188027337-566eaae5-60dd-4696-84f2-913384dfeeb1.jpeg)



## Web Service

![a](https://user-images.githubusercontent.com/101228590/188031922-74ac883a-3134-4948-bb06-391f3ac93c56.jpg)
![Captura da Web_1-9-2022_21327_www bing com](https://user-images.githubusercontent.com/101228590/188032099-7d756881-e3fe-4887-9d41-53d6da863dbb.jpeg)

```

Tendo em conta as operações disponíveis no Web service, a aplicação solicita uma dessas operações.
O Web service efetua o processamento e envia os dados para a aplicação que requereu a operação.

 A aplicação recebe os dados e faz a sua interpretação, convertendo-os para a sua linguagem própria.

```
<hr>

<div align="">

### ` Canais Para Estudo`
 <details><summary>🌐Canal</summary>
       </p>

- ### [Canal DevDojo](https://www.youtube.com/c/DevDojoBrasil/)

</details>

<hr>


### ` EBOOK`
 <details><summary>🌐Canal</summary>
       </p>
[101 RPA bots by ElectroNeek - volume 1(1).pdf](https://github.com/JoaoSchrock/Algamoney_api/files/9505966/101.RPA.bots.by.ElectroNeek.-.volume.1.1.pdf)


</details>

<hr>

[101 RPA bots by ElectroNeek - volume 1(1).pdf](https://github.com/JoaoSchrock/Algamoney_api/files/9505966/101.RPA.bots.by.ElectroNeek.-.volume.1.1.pdf)


## BR MODELO

```
A brModelo é uma ferramenta desktop voltada para o desenvolvimento de projeto de banco de dados
relacionais, incluindo as etapas conceitual, lógico e físico, com ampla utilização na área de computação
em todo o Brasil.

```


```
• = id_(nome da entidade)  "Identificador"
° = nome "Atributo"
```

## Diagrama de Entidade Conceitual
![Screenshot_1](https://user-images.githubusercontent.com/101228590/192066833-451aa09b-f08a-440d-9e26-a6de79c42716.png)

~~~mysql
create database senai;
use senai;
CREATE TABLE pessoas (pessoaid int, pessoaNome varchar(255), pessoaSobrenome varchar(255));
INSERT INTO pessoas (pessoaid, pessoaNome, pessoaSobrenome) values (1,"Joao","Schrock");
SELECT * FROM pessoas;
INSERT INTO pessoas (pessoaid, pessoaNome, pessoaSobrenome) values (2,"Gladson","Peres");
INSERT INTO pessoas (pessoaid, pessoaNome, pessoaSobrenome) values (3,"Juan","Gaspar");
INSERT INTO pessoas (pessoaid, pessoaNome, pessoaSobrenome) values (4,"puan","jaskar");
SELECT * FROM pessoas WHERE pessoaid = 2;

DELETE FROM pessoas WHERE pessoaid = 3;

~~~


~~~mysql
create database aeroporto;
use aeroporto;

CREATE TABLE companhia (companhiaid int, companhiaNome varchar(255));
CREATE TABLE aviao (aviaoid int, aviaoNome varchar(255));
CREATE TABLE piloto (pilotoid int, pilotoNome varchar(255));
INSERT INTO aviao (aviaoid, aviaoNome) values ('1', 'CavaloQueMorde');
INSERT INTO companhia (companhiaid, companhiaNome) values ('1', 'Aeroporto');
INSERT INTO piloto (pilotoid, pilotoNome) values ('1', 'Joao Schrock');
~~~

# Comandos MySQL

### Fazer Alterações quando Precisar
~~~mysql
ALTER TABLE pessoas add apelido varchar(255);
~~~

### Deleta apenas a tabela Apelido
~~~mysql
ALTER TABLE pessoas drop apelido;
~~~

### Insere um atributo na TABLE piloto
~~~mysql
INSERT INTO piloto (pilotoid, pilotoNome) values ('1', 'Joao Schrock');
~~~

### Deleta a pessoa que foi Selecionada(Pessoa 3)
~~~mysql
DELETE FROM pessoas WHERE pessoaid = 3;
~~~


