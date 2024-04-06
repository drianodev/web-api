# Web API

Este é um projeto de demonstração utilizando o Spring Boot para criar uma API web documentada pelo Swagger.

## Requisitos

- Java 8 ou superior
- Maven

## Instalação e Execução

1. Clone este repositório:

    ```bash
    git clone https://github.com/seu-usuario/web-api.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd web-api
    ```

3. Compile o projeto:

    ```bash
    mvn clean package
    ```

4. Execute a aplicação:

    ```bash
    java -jar target/web-api-0.0.1-SNAPSHOT.jar
    ```

## Endpoints

Após executar a aplicação, você pode acessar a documentação dos endpoints usando o Swagger UI.

- Swagger UI: [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)

## Notas

- Este projeto utiliza o Spring Boot para configurar a aplicação web.
- A documentação dos endpoints é gerada automaticamente usando o Swagger.
