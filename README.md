[![NPM](https://img.shields.io/npm/l/react)](https://github.com/lucarauj/testes-automatizados-com-Rest-Assured-Dio/blob/main/LICENSE)

<h1 align="center">
  TESTES AUTOMATIZADOS COM 
  <br/>
  <img align="center" alt="Lucarauj-RestAssured" height="130" width="400" src="https://github.com/lucarauj/assets/blob/main/RestAssured.jpeg">
</h1>

## Configurando dependências no projeto(`pom.xml`):

```xml
<dependency>
  <groupId>io.rest-assured</groupId>
	<artifactId>json-path</artifactId>
	<version>5.1.1</version>
	<scope>test</scope>
</dependency>
<dependency>
  <groupId>io.rest-assured</groupId>
  <artifactId>rest-assured</artifactId>
	<version>5.1.1</version>
	<scope>test</scope>
</dependency>
<dependency>
  <groupId>io.rest-assured</groupId>
	<artifactId>json-schema-validator</artifactId>
	<version>5.1.1</version>
	<scope>test</scope>
	</dependency>
<dependency>
  <groupId>org.junit.jupiter</groupId>
	<artifactId>junit-jupiter</artifactId>
	<version>5.9.0</version>
	<scope>test</scope>
</dependency>
<dependency>
  <groupId>com.github.javafaker</groupId>
	<artifactId>javafaker</artifactId>
	<version>1.0.2</version>
</dependency>
<dependency>
  <groupId>commons-logging</groupId>
  <artifactId>commons-logging</artifactId>
  <version>1.1.1</version>
</dependency>
```


## Algumas anotações utlizadas neste código:

- @TestMethodOrder(MethodOrderer.OrderAnnotation.class): executa os testes pela ordem da anotação @Order();
- @BeforeAll: executa o médoto antes de todos os testes;
- @Test: anotação básica para rodar os testes;
- @BeforeEach: executa o médoto antes de CADA teste;

## Algumas classes/métodos utilizados nos testes:

- Assertions.assertEquals(): verifica a igualdade entre parâmetros
- Assertions.assertNotNull(): verifica se a referência NÃO está nula

## Aluno

Lucas Araujo

<a href="https://www.linkedin.com/in/lucarauj"><img alt="lucarauj | LinkdeIN" width="40px" src="https://user-images.githubusercontent.com/43545812/144035037-0f415fc7-9f96-4517-a370-ccc6e78a714b.png" /></a>
