<img loading="lazy" data-attachment-id="8654" data-permalink="https://fernandofranzini.wordpress.com/2015/01/12/treinamentos-java-2015/logo-java/" data-orig-file="https://fernandofranzini.files.wordpress.com/2015/01/logo-java.jpg" data-orig-size="3000,2121" data-comments-opened="0" data-image-meta="{&quot;aperture&quot;:&quot;0&quot;,&quot;credit&quot;:&quot;&quot;,&quot;camera&quot;:&quot;&quot;,&quot;caption&quot;:&quot;&quot;,&quot;created_timestamp&quot;:&quot;0&quot;,&quot;copyright&quot;:&quot;&quot;,&quot;focal_length&quot;:&quot;0&quot;,&quot;iso&quot;:&quot;0&quot;,&quot;shutter_speed&quot;:&quot;0&quot;,&quot;title&quot;:&quot;&quot;,&quot;orientation&quot;:&quot;0&quot;}" data-image-title="logo-java" data-image-description="" data-medium-file="https://fernandofranzini.files.wordpress.com/2015/01/logo-java.jpg?w=300" data-large-file="https://fernandofranzini.files.wordpress.com/2015/01/logo-java.jpg?w=705" class="aligncenter size-medium wp-image-8654" src="https://fernandofranzini.files.wordpress.com/2015/01/logo-java.jpg?w=300&amp;h=212" alt="logo-java" width="300" height="212" srcset="https://fernandofranzini.files.wordpress.com/2015/01/logo-java.jpg?w=300&amp;h=212 300w, https://fernandofranzini.files.wordpress.com/2015/01/logo-java.jpg?w=600&amp;h=424 600w, https://fernandofranzini.files.wordpress.com/2015/01/logo-java.jpg?w=150&amp;h=106 150w" sizes="(max-width: 300px) 100vw, 300px">

# Baseado no Livro Base de Automação de Teste - Backend API

>Esta é a API REST backend para o projeto de automação de teste do livro Base de Automação de Teste.

A aplicação tem caráter educativo. Ela foi desenvolvida em Spring Boot e possui um banco de dados em memória Derby.

<img class="lazy-load preload-me is-loaded" src="https://4infra.com.br/wp-content/uploads/2018/09/why-learn-java-750x375.jpg" width="750" height="375" title="java" alt="java" srcset="https://4infra.com.br/wp-content/uploads/2018/09/why-learn-java-750x375.jpg 750w">

## Como executar a aplicação

Primeiro você precisará executar o clone deste repositório. 
Após, siga os passos abaixo.

### Via linha de comando

>1.Instalar o Apache Maven e configurá-lo no seu PATH>
>2.Executar, no Terminal ou Prompt de Comando `mvn exec:java`>

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
