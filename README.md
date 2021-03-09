# Livro Base de Automação de Teste - Backend API

Esta é a API REST backend para o projeto de automação de teste do livro Base de Automação de Teste.

A aplicação tem caráter educativo. Ela foi desenvolvida em Spring Boot e possui um banco de dados em memória Derby.

## Como executar a aplicação

Primeiro você precisará executar o clone deste repositório. 
Após, siga os passos abaixo.

### Via linha de comando

1. Instalar o Apache Maven e configurá-lo no seu PATH
2. Executar, no Terminal ou Prompt de Comando `mvn exec:java`

Para saber que tudo ocorreu com sucesso as últimas linhas do terminal deve ser identicas a estas:

```text
Hibernate: values next value for hibernate_sequence
Hibernate: insert into pessoa (endereco, hobbies, nome, id) values (?, ?, ?, ?)
Hibernate: values next value for hibernate_sequence
Hibernate: insert into pessoa (endereco, hobbies, nome, id) values (?, ?, ?, ?)
```

Para parar a aplicação pressione `CTRL + C`

### Pela sua IDE favorita

1. Faça a importação do projeto como um projeto Maven
2. Execute a classe `BackendApplication.java` no pacote `com.otestadortecnico.backend`


## Documentação da API

Uma vez iniciada a API você pode acessar [http://localhost:8080/swagger-ui.htm](http://localhost:8080/swagger-ui.htm) 
para ver sua documentação.

Esta documentação só poderá ser acessada com a aplicação executando.

## Dúvidas

Insira uma _Issue_ neste projeto :-)

## 👨🏻‍🚀 Sobre mim
<a href="https://www.linkedin.com/in/mateus-macedo-937a32163/">
 <img style="border-radius:50%" width="100px; "src="https://avatars.githubusercontent.com/u/63172367?s=460&u=11fd26ea8a7f5663d7707d7ef254e4f8bfca1b05&v=4"/>
 <p>Mateus Macedo</p>
</a>
