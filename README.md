# Projeto de Microservices com Spring Cloud e Spring Boot

Seja bem-vindo!

Este projeto demonstra o desenvolvimento de uma arquitetura completa de microservices utilizando Java, Spring Cloud e Spring Boot.

## Funcionalidades

- **Módulos Spring Cloud/Boot**: Utilização dos principais módulos do Spring Cloud e Spring Boot para construção de microservices.
- **Arquitetura de Microservices**: Entendimento e implementação de uma arquitetura completa de microservices.
- **Service Discovery**: Implementação de um mecanismo de descoberta de serviços.
- **API Gateway**: Configuração de um API Gateway para gerenciar as solicitações.
- **Balanceamento de Carga**: Implementação de balanceamento de carga para distribuir as solicitações entre os serviços.
- **Desenvolvimento de Microservices**: Criação de microservices individuais com responsabilidades específicas.
- **Comunicação Síncrona e Assíncrona**: Implementação de comunicação síncrona e assíncrona entre os microservices.
- **Serviço/Fila de Mensageria com RabbitMQ**: Configuração de RabbitMQ para gerenciamento de filas e mensagens.
- **Authorization Server com Keycloak**: Configuração de um servidor de autorização utilizando Keycloak.
- **Desenvolvimento de Imagens Docker**: Criação de imagens Docker customizadas para os microservices.
- **Containers Docker**: Criação e gerenciamento de containers Docker a partir das imagens.
- **Réplicas dos Microservices**: Configuração de réplicas para os microservices para garantir alta disponibilidade.

## Requisitos

- Conhecimento em Java e Orientação a Objetos
- Conhecimento básico em Spring Boot
- Noções de instalação de ferramentas
- Noções de REST APIs e Bancos de Dados

## Tecnologias Utilizadas

- Java
- Spring Boot
- Spring Cloud
- RabbitMQ
- Keycloak
- Docker

## Como Executar o Projeto

1. Clone o repositório:
    ```sh
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```

2. Compile e execute cada microservice:
    ```sh
    ./mvnw clean install
    ./mvnw spring-boot:run
    ```

3. Inicie o RabbitMQ e o Keycloak:
    ```sh
    docker-compose up -d
    ```

4. Crie as imagens Docker e inicie os containers:
    ```sh
    docker build -t nome-da-imagem .
    docker run -d --name nome-do-container nome-da-imagem
    ```

5. Acesse a aplicação via API Gateway:
    ```sh
    http://localhost:porta-gateway
    ```

## Links Úteis

- [Código Fonte das Aulas](https://github.com/seu-usuario/seu-repositorio)
- [Documentação Spring Cloud](https://spring.io/projects/spring-cloud)
- [Documentação Spring Boot](https://spring.io/projects/spring-boot)
- [RabbitMQ](https://www.rabbitmq.com/)
- [Keycloak](https://www.keycloak.org/)
- [Docker](https://www.docker.com/)

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

